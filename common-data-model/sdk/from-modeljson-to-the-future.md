---
title: From model.json to the future | Microsoft Docs
description: Developer guide to using Common Data Model SDK with model.json metadata files.
author: miroslavplese
ms.service: common-data-model
ms.reviewer:
ms.topic: article
ms.date: 06/11/2020
ms.author: miplese
---

# From model.json to the future 

Common Data Model technology enables companies to infuse a deep understanding of the data managed by their services, beyond the simplistic structural representation of the entities and relationships. The rapid expansion of enterprise analytics systems, such as PowerBI, built on top of vast data estate being made readily available in data lakes from disparate sources, necessitated the development of a common system for representing the meaning of such data. Common Data Model helps to build a uniform representation of the semantics and provides tools and standards that simplify the solution integrations across data silos. 

Common Data Model language evolved from its original structure-only based form following the progress made in the interop space and growth of cloud-based solutions and analytics. Originally focusing on explaining the structure and relationships between entities, Common Data Model offered a simple metadata format called ["model.json"](../model-json.md). This format, however, was not able to convey the richness of semantics the source systems had on the data they would land in data lakes, leaving consumers with limited ability to understand it. In addition, the old format was tied too much to physical layout of the data and prevented people from building a higher-level understanding of the logical, conceptual form of the data. Re-thinking of this problem resulted in the creation of the next generation Common Data Model language and tooling, that we generally refer to as "manifest.cdm.json" format. More details about the format can be found in the technical paper [here](overview.md). 

With the new format providing many obvious benefits, the existing systems utilizing the old "model.json" format will want to add support for the newer format as well, while staying backward compatible. Fortunately, Common Data Model provides an Software Development Kit (SDK) that offers a uniform view of the two formats through its APIs. This drastically simplifies the process of adopting the "manifest.cdm.json" format for the service owners. 

In this article we will offer insights into how Common Data Model SDK enables services to use both formats and what is the guidance to migrate the services which rely on the older format to the new one. 

## Common Data Model SDK 

Before getting into the details of how "model.json" and "manifest.cdm.json" formats relate and how would one transition between them, it is good to introduce the reader to the Common Data Model Object Model and the SDK, and to explain why they exist. 

During the era when "model.json" was the persistence format of choice, the services joining Common Data Model ecosystem were encouraged to implement custom parsers that followed the specification of the format. This guidance was backed with several implementation samples that helped partners kick-start their development. This worked very well thanks to relative simplicity of the format. However, as explained above, this simplicity placed various limitations to how the data can be described. With the introduction of the "manifest.cdm.json" format, those restrictions were lifted, but with the added capabilities came complexity. 

To simplify the adoption process for services wanting to use the added power of the new format, the new Object Model and the SDK were built. The new Object Model introduces a programming interface that hides the complexity of the underlying schema, provides single implementation across multiple languages and a uniform view of the two formats, and supports advanced scenarios like converting logical schemas into different physical layouts. Services integrating the SDK can count on regular updates and new features being added to the APIs to cover an expanding number of applicable use cases and scenarios. 

Today, the SDK is available in four languages - C#, Java, Typescript and Python, with full parity of features and format support. For example, services integrating a C# version and emitting the data can be fully confident that readers written with Python SDK will see the data structure and semantics the same way. Common Data Model site provides [detailed information](../1.0om/api-reference/api-reference.md) about the APIs and there are accompanying [samples](../samples.md) to help service teams quickly ramp-up and start embedding the technology within their solutions. 

## Using the Common Data Model SDK with model.json files 

With the introductions out of the way, let's dive into a couple of examples that can demonstrate usage of the SDK to read, explore and write "model.json" format. 

> [!NOTE]
> This article includes only C#-based samples, but they apply to other languages as well. 

Generally, if you plan to build a service that will consume data described with Common Data Model metadata in a data lake, you will encounter “CDM folders”, which is a term we use to identify a well-structured composition of data partitions and Common Data Model metadata files which explain the schema of these partitions. The metadata files are your first artifact to read and process before ingesting the data, as they explain which entities are present, what is their structure and their relationship, and most importantly where the partition files are located. There is no restriction such that the partition files need to be present in the same folder - they can be many levels deep, depending on how the data writer decided to lay out their lake, so the location information found in the metadata file plays critical role. More information and examples of CDM folders can be found in its dedicated [documentation](../data-lake.md). 

Before we get started reading the schema, we want to let the SDK know where our files reside. This is achieved by instantiating the [corpus](fundamentals.md#the-corpus) object, the main collection of documents and definitions, and telling its [storage management layer](../1.0om/api-reference/storage/storage.md) which adapters to use to access file systems. The adapters are just an abstraction of underlying filesystems, supplying standardized read/write access for the SDK. We will set up two adapters, one pointing to the public store of CDM foundation files (consider them as bootstrap definitions) and the other pointing to an ADLSg2 container containing our CDM folder.

```csharp
    var cdmCorpus = new CdmCorpusDefinition(); 
    cdmCorpus.Storage.Mount("cdm", new CdmStandardsAdapter()); 
    cdmCorpus.Storage.Mount("adls", new ADLSAdapter("<ADDRESS>", "/<ROOT>", "<SHARED KEY>")); 
    cdmCorpus.Storage.DefaultNamespace = "adls"; 
```

Then, to load a "model.json" file at the root of the target location just one line will be enough: 

```csharp
    var manifest = await cdmCorpus.FetchObjectAsync<CdmManifestDefinition>("model.json"); 
```

Here, the manifest object represents Object Model's high-level _representation_ of a single "model.json" file, including all entities, attributes, partitions, and other information found in it. You will notice that this in-memory representation does not strictly match structure of the input JSON. This is because the API needs to provide uniform access to different persistence format to its clients, and thus performs implicit mapping of the "model.json" format structure to the higher-level form. 

Let's try to explore the list of entities declared in the schema. Following snippet demonstrates how this can be done. 

```csharp
    foreach (var entityDeclaration in manifest.Entities) 
    {
        var entityDefinition = await cdmCorpus.FetchObjectAsync<CdmEntityDefinition>(entityDeclaration.EntityPath, manifest); 

        Console.WriteLine($"Entity name: {entityDefinition.EntityName}"); 

        foreach (var attribute in entity.Attributes) 
        {
            Console.WriteLine($"\tAttribute name: {attribute.Name}");
        }
    }
```

> [!TIP]
> For additional examples of reading schema details please refer to the [read-manifest](https://github.com/microsoft/CDM/tree/master/samples/1-read-manifest) SDK sample.

The code above iterates over the entity declarations found in the manifest, loading the actual definition objects that hold information on attributes and other properties of the entity. Now, let's also list which partitions have been referenced by the "model.json" file.

```csharp
    foreach (var dataPartition in entityDeclaration.DataPartitions) 
    {
        Console.WriteLine(cdmCorpus.Storage.CorpusPathToAdapterPath(dataPartition.Location));
    }
```

You’ll notice here that there is a call made to `CorpusPathToAdapterPath` API. Before explaining its purpose, it is important to understand that all document and partition locations that the Object Model works with are bound to a “corpus”, the highest-level construct that groups all documents, storage settings, resolution options, etc. we work with. The corpus is not aware of implementation details of individual filesystems where the documents or partitions live – that knowledge is hidden in Object Model’s storage layer behind a simple `StorageAdapter` interface. This layer maps filesystem-specific paths into a uniform representation we call “corpus path”, which ensures that Object Model stays agnostic of specific peculiarities of different filesystems it reads from or writes to. Because of importance of this topic, taking a deeper look into [corpus and adapter documentation](fundamentals.md#the-corpus) will be helpful for the reader. With that cleared up, we can see that whenever there is a situation of a client needing the exact location of a document or a partition in their origin filesystems, the corpus-bound paths need to be converted with a call to Object Model's storage layer, function `CorpusPathToAdapterPath`. For the example snippet above, if the target filesystem was ADLSg2, the result of the function should be the actual URL of the data partition file. 

As an exercise for the reader, consider loading the newer "manifest.cdm.json" file. You should see that the only change required in such case is changing the input file name, and that the existing flow stays the same. Underneath, the SDK takes care of working with these different formats through the same API.

## Persisting the schema 

We've seen how we can load the older "model.json" format file and explore it, but what about writing the model out into files? Fortunately, persisting to a desired format is just a matter of selecting the right file name. The SDK detects the format based on the file name and activates the proper persistence logic. If you need to save the schema as a "model.json" file, you will make the following call:

```csharp
    await manifest.SaveAsAsync("model.json", true);
```

Or, if you want to save it to a newer format, the name needs to follow pattern "*.manifest.cdm.json", like this: 


```csharp
    await manifest.SaveAsAsync("mySchema.manifest.cdm.json", true); 
```

If the reader's intent is just to do a simple conversion from one format to the other, without fancy schema exploration, the client code will only require the following two lines: 

```csharp
    // Convert model.json to manifest.cdm.json
    var manifest = await cdmCorpus.FetchObjectAsync<CdmManifestDefinition>("model.json");
    await manifest.SaveAsAsync("mySchema.manifest.cdm.json", true);
```

Or, in the opposite direction:

```csharp
    // Convert manifest.cdm.json to model.json
    var manifest = await cdmCorpus.FetchObjectAsync<CdmManifestDefinition>("mySchema.manifest.cdm.json");
    await manifest.SaveAsAsync("model.json", true);
```

In more complicated scenarios, service owners may opt to adjust the content of the schema, attach more entities, and add new data partition references. Such use cases are out of scope of this article, but you can refer to [sample material](https://github.com/microsoft/CDM/tree/master/samples) available in the Common Data Model GitHub repo. In the end, persisting an updated schema to "model.json" or "manifest.cdm.json" formats is no different from what was described above.

## Things to keep in mind

With the two formats defining their own specific structures, and Object Model providing a single API view over them, some special constructs available in each format may not be clearly visible through these APIs and do require additional developer guidance. In this section, we will cover how client applications can reveal and work with these special structures. A separate article will be shared with further details about how these constructs look like in the schemas, how traits get preserved in the older format, how data types are mapped, and other information.

### Custom properties

Specification for "model.json" format recognizes two types of custom information pieces in its structure: [annotations](../model-json.md#annotations) and custom properties. They both enable services to include extra contextual information with the schema, which may be of value to consumers able to understand them. The Object Model recognizes and preserves these custom extensions and provides access to them.

From a programmatic usage perspective, the snippet below demonstrates how one would access the annotations on entity level:

```csharp
    var annotations = entity.ExhibitsTraits.Item("is.modelConversion.otherAnnotations")?.Arguments[0].Value;
    if (annotations != null)
    {
        foreach (Annotation annotation in annotations)
        {
            Console.WriteLine($"{annotation.Name}={annotation.Value}");
        }
    }
```

When talking about the second information type, the custom properties, they are made available in the Object Model as individual traits, following naming convention `"is.extension.<propertyname>"`. For example, if you want to get content of custom property "myapp:something", following code can retrieve you that:

```csharp
    var customPropValue = entity.ExhibitsTraits.Item("is.extension.myapp:something")?.Arguments[0].Value;
```

One more thing to note for services converting the "model.json" schema and writing it in "manifest.cdm.json" form is that custom properties that are not recognized by the Object Model will result in an additional document being saved next to the manifest file - "custom.extension.cdm.json". This document will hold definitions of `"is.extension"` traits that represent the custom properties discovered in the original "model.json" file. For recognized custom properties, such as those PowerBI uses, this additional document will not be written, as Object Model has internal knowledge of it. Which custom properties are recognized by Object Model can be found in the [extensions definitions folder](https://github.com/microsoft/CDM/tree/master/schemaDocuments/extensions).

### Model.json partition locations

By definition, partition locations in "model.json" metadata files [are absolute](../model-json.md#partitions). Since Object Model APIs operate through storage adapters, which is the abstraction layer over the underlying filesystem, these URIs get converted into a corpus path form via applicable adapter. The conversion is performed by the Object Model during loading of the metadata file automatically, _if the URI matches the actual location of the "model.json" file._ So, if we have configured an [ADLSAdapter](../1.0om/api-reference/storage/adlsadapter.md) as above to be mapped on namespace "adls", and partitions are under the same location or under any sub-folder, their paths will convert to corpus path that can look like this: "adls:/somepath/some-partition.csv". And, as shown in earlier section, clients can decode this corpus path back into original URI with this command:

```csharp
    var originalUri = cdmCorpus.Storage.CorpusPathToAdapterPath(dataPartition.Location)
```

In case the partition URIs do not match the location of the "model.json" file, a [RemoteAdapter](../1.0om/api-reference/storage/remoteadapter.md) must be pre-configured in the corpus prior to loading the metadata file. For example, if the URIs looks like "https://my.server.com:443/somepath", the RemoteAdapter should be configured as:

```csharp
    var hosts = new Dictionary<string, string>();
    hosts.Add("myserver", "https://my.server.com:443/somepath");
    cdmCorpus.Storage.Mount("remote", new RemoteAdapter(hosts));
```

As before, the original URI can then be retrieved by calling the `CorpusPathToAdapterPath` API.

### Model.json referenced models

[Reference models](../model-json.md#reference-models) are a concept in "model.json" spec that lets services re-use documents containing entity definitions. A "reference model" in a "model.json" file consists of an identifier and a location URI that points to the document containing the actual definition of the entity. An entity of type `ReferenceEntity` will use this identifier to declare that its actual definition can be found in a remote (referenced) document.

In Common Data Model API, this type of entity is represented through class [CdmReferenceEntityDeclarationDefinition](../1.0om/api-reference/cdm/referencedentitydeclaration.md) and its `EntityPath` property will contain a corpus path variant of the original document URI found in the "referenceModels" section of the "model.json" file. Passing this entity path value to `CorpusPathToAdapterPath` API will return the original referenced document URI. Like with partition location URIs mentioned above, if the referenced document URI is in a location different than where "model.json" file resides, a [RemoteAdapter](../1.0om/api-reference/storage/remoteadapter.md) needs to be pre-configured in the corpus to recognize such document URIs. 

Note that this concept in "model.json" spec has been rarely used in real-world solutions and has since been made obsolete with much more flexible import mechanism in "manifest.cdm.json" format. 

### Partition patterns 

The new "manifest.cdm.json" schema format introduced a new capability for data producers to define [partition patterns](manifest.md#data-partition-patterns) which removes the need to update metadata files whenever a new data partition is added. If a manifest has patterns defined, then before such schema is saved in "model.json" form using `SaveAsAsync` API, services must first make a call to `FileStatusCheckAsync` API on the manifest object: 

```csharp
    await manifest.FileStatusCheckAsync();
    await manifest.SaveAsAsync("model.json", true);
```

The `FileStatusCheckAsync` call will trigger file scanning logic in the Object Model, and will result in a number of new [CdmDataPartitionDefinition](../1.0om/api-reference/cdm/datapartition.md) objects being automatically created and added to entity declaration's partition collection for each partition file found in the target folder that matched the pattern.

> [!IMPORTANT]
> Partition _patterns_ are not preserved in the written "model.json" file. This requires writing the "manifest.cdm.json" files always in addition to "model.json", so it is the source of truth how the service originally arranged its data partitions. 

## Service migration guidance 

With the introduction of the new "manifest.cdm.json" metadata description format, a problem of coexistence of both old and new metadata formats appears. The transition between formats will take time, and service teams should adapt to this situation and assume that both formats may circulate in their environments. Thanks to the Object Model's native support for both formats via uniform API, this becomes easy to handle. 

For data producers, both "model.json" and "manifest.cdm.json" variant of their schema can be written together in the same CDM folder: 

```csharp
    await manifest.SaveAsAsync("model.json", true);
    await manifest.SaveAsAsync("mySchema.manifest.cdm.json", true);
```

This approach helps widen the set of consumers able to understand the outputted data, though for legacy consumers that support only the "model.json" format, this understanding will have lower fidelity due to format limitations.

For data consumers, the transition path is such that the service needs to become capable of selecting the "manifest.cdm.json" as default schema source if both old and new metadata format are present in the CDM folder, and only fall back to "model.json" in case the newer format file is not there. If that happens, the service needs to adjust its behavior because newer notions, such as traits, will not be available. Here's a simple example: 

```csharp
    var manifestFileName = MyFuncToFindManifestFileInTargetLake();
    var manifest = await cdmCorpus.FetchObjectAsync<CdmManifestDefinition>(manifestFileName ? manifestFileName : "model.json");

    // Do things, but expect that traits or other advanced features may not be available in the loaded schema
```

Following this guidance, data producers and consumers will be able to interop over multiple metadata formats, by leveraging the SDK to achieve this format “transparency”.

## Final words

In this article we have seen how Common Data Model evolved from basic representation of structure of the data to a more feature-rich semantics-based metadata language, and how a powerful programming interface was built to simplify interactions with the schemas written in this new language. We have seen how easy it is to use this interface to convert between old and new metadata format, and we've learned how to handle special constructs present in each format.

Service teams can use this guidance to get started preparing their services for the time when "model.json" format is no longer in use, and the new "manifest.cdm.json" is the metadata format of choice for cloud solutions built by Microsoft and leveraged by its partners. With the full backing and support available through open sourced tools, the service teams can expect to see a controlled metadata format transition in near future across relevant Microsoft product offerings.

Recommended further reading: 

* [Common Data Model official website](../index.md)
* [Technical paper on Common Data Model features](overview.md)
* [API reference](../1.0om/api-reference/api-reference.md)
* [GitHub repo with SDKs, schemas, and samples](https://github.com/Microsoft/CDM)
* [Introduction to SDK samples](../samples.md) 
* [Frequently asked questions on Common Data Model](../faq.md) 

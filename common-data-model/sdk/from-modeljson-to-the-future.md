---
title: From model.json to the future | Microsoft Docs
description: Developer guide to using Common Data Model SDK with model.json metadata files.
author: miroslavplese
ms.service: common-data-model
ms.reviewer:
ms.topic: article
ms.date: 06/23/2020
ms.author: miplese
---

# From model.json to the future 

Common Data Model technology enables companies to gain a deep understanding of the data managed by their services, beyond the simplistic structural representation of the entities and relationships.

The use of enterprise analytics systems, such as PowerBI, is rapidly expanding. This expansion is happening because of the vast amounts of data being made available in data lakes from disparate sources. A common system for representing the meaning of such data is needed. Common Data Model helps to build a uniform representation of the semantics and provides tools and standards that simplify the solution integrations across data silos. 

Common Data Model evolved from its original structure-only form following the progress made in the interop space and the growth of cloud-based solutions and analytics. Originally focusing on explaining the structure and relationships between entities, Common Data Model offered a simple metadata format called ["model.json"](../model-json.md). This format, however, was not able to convey the richness of semantics the source systems had on the data they would insert into data lakes, leaving consumers with limited ability to understand it. In addition, the old format was heavily tied to the physical layout of the data, preventing people from building a higher level understanding of the logical and conceptual form of the data. The next generation of Common Data Model, generally referred to as ["manifest.cdm.json"](overview.md) format, was created to address these issues.

With the new format providing many obvious benefits, existing systems utilizing the "model.json" format can add support for the newer format as well, while staying backward compatible. Common Data Model provides a Software Development Kit (SDK) that offers a uniform view of the two formats through its APIs. This SDK simplifies the process of adopting the "manifest.cdm.json" format. 

In this article we offer insights into how the Common Data Model SDK enables services to use both formats and give guidance for migrating services that rely on the older format to the new format. 

## Common Data Model SDK 

Before we discuss the relationship between the "model.json" and the "manifest.cdm.json" formats and how to transition between them, we introduce the Common Data Model object model and the SDK, and explain why they exist.

When "model.json" was the recommended format, the services that joined the Common Data Model ecosystem were encouraged to implement custom parsers that followed the format's specification. This guidance was backed with several implementation samples that helped partners start their development. This worked very well due to the relative simplicity of the format. However, as explained earlier, this simplicity placed various limitations to how the data can be described. With the introduction of the "manifest.cdm.json" format, those restrictions were lifted and brought additional capabilities.

 The new object model and the SDK are built to simplify the adoption process for services that want to adopt the new format. The new object model introduces a programming interface that hides the complexity of the underlying schema, provides a single implementation across multiple languages and a uniform view of both formats, and supports advanced scenarios like converting logical schemas into different physical layouts. Services that integrate the SDK can expect regular updates and new features to be added to the APIs to cover an expanding number of applicable use cases and scenarios. 

Today, the SDK is available in C#, Java, Typescript, and Python, with full parity of features and format support. For example, services integrating a C# version and emitting the data can be fully confident that readers written with the Python SDK will see the data structure and semantics the same way. The Common Data Model site provides [detailed information](../1.0om/api-reference/api-reference.md) about the APIs and their accompanying [samples](../samples.md) to help service teams quickly onboard and start embedding the technology within their solutions. 

## Using the Common Data Model SDK with model.json files 

Here are some examples that demonstrate how you can use the the Common Data Model SDK to read, explore, and write the "model.json" format. 

>[!NOTE]
>This article includes C#-based samples, however, they apply to other languages as well. 

If you plan to build a service that will consume data that's described with Common Data Model metadata in a data lake, you will encounter [**CDM folders**](../data-lake.md). CDM folders are well-structured compositions of data partitions and Common Data Model metadata files which explain the schema of these partitions. The metadata files are the first artifacts to read and process before ingesting the data because they explain which entities are present, their structure and relationship, and most importantly, the location of the partition files. The partition files do not need to be present in the same folder. They can be many levels deep, depending on how the data writer lays out their lake. Therefore, the location information in the metadata file plays critical role. 

Before you can read the schema, you must let the SDK know where the files reside. You do this by instantiating the [corpus](fundamentals.md#the-corpus) object, the main collection of documents and definitions, and telling its [storage management layer](../1.0om/api-reference/storage/storage.md) which adapters to use to access file systems. The adapters are just an abstraction of underlying filesystems, supplying standardized read/write access for the SDK. We will set up two adapters, one pointing to the public store that contains the Common Data Model foundation files (think of them as bootstrap definitions) and the other pointing to an ADLSg2 container containing our CDM folder.

```csharp
    var cdmCorpus = new CdmCorpusDefinition(); 
    cdmCorpus.Storage.Mount("cdm", new CdmStandardsAdapter()); 
    cdmCorpus.Storage.Mount("adls", new ADLSAdapter("<ADDRESS>", "/<ROOT>", "<SHARED KEY>")); 
    cdmCorpus.Storage.DefaultNamespace = "adls"; 
```

Then, to load a "model.json" file at the root of the target location: 

```csharp
    var manifest = await cdmCorpus.FetchObjectAsync<CdmManifestDefinition>("model.json"); 
```

Here, the manifest object represents the object model's high-level _representation_ of a single "model.json" file, including all entities, attributes, partitions, and other information found in it. This in-memory representation doesn't strictly match the structure of the input JSON. This is because the API needs to provide uniform access to different persistence formats to its clients, and thus performs implicit mapping of the "model.json" format structure to the higher level form. 

Let's explore the list of entities declared in the schema. The following snippet demonstrates how this can be done. 

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

>[!TIP]
>For additional examples of how to read schema details, refer to the [read-manifest](https://github.com/microsoft/CDM/tree/master/samples/1-read-manifest) SDK sample.

The code previously shown iterates over the entity declarations that are in the manifest, loading the actual definition objects that hold information on attributes and other properties of the entity. Now, let's also list the partitions that have been referenced by the "model.json" file.

```csharp
    foreach (var dataPartition in entityDeclaration.DataPartitions) 
    {
        Console.WriteLine(cdmCorpus.Storage.CorpusPathToAdapterPath(dataPartition.Location));
    }
```

You’ll notice that there is a call made to the `CorpusPathToAdapterPath` API. Before explaining its purpose, it is important to understand that all document and partition locations that the object model works with are bound to a “corpus”, the highest-level construct that groups all documents, storage settings, resolution options, etc. with which we work. The corpus is not aware of the implementation details of the individual filesystems where the documents or partitions live. That knowledge is hidden in object model’s storage layer behind a simple `StorageAdapterBase` contract. This layer maps filesystem-specific paths into a uniform representation we call “corpus path”, which ensures that the object model is agnostic of specific details of the different filesystems from which it reads or writes. You can take a deeper look into the [corpus and adapter documentation](fundamentals.md#the-corpus) to learn more. 

We can see that whenever a client needs the location of a document or a partition in their filesystems, the corpus-bound paths need to be converted with a call to the object model's storage layer function, `CorpusPathToAdapterPath`. In the code snippet earlier, if the target filesystem was ADLSg2, the result of the function should be the actual URL of the data partition file. 

If you load the newer "manifest.cdm.json" file. You should see that the only change that's required is a change to the input file name. The existing flow stays the same. Underneath, the SDK takes care of working with these different formats through the same API.

## Persisting the schema 

So far, you've seen how to load the older "model.json" format file and explore it, but what about writing the model out into files? Fortunately, persisting to a desired format can be done by just selecting the right file name. The SDK detects the format based on the file name, and then activates the proper persistence logic. If you need to save the schema as a "model.json" file, you will make the following call:

```csharp
    await manifest.SaveAsAsync("model.json", true);
```

Or, if you want to save it to the newer format, the name needs to follow the "*.manifest.cdm.json" pattern, like this: 

```csharp
    await manifest.SaveAsAsync("mySchema.manifest.cdm.json", true); 
```

If the intent is just to do a simple conversion from one format to the other, without additional schema exploration, the client code is just the following two lines: 

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

In more complicated scenarios, service owners may opt to adjust the content of the schema, attach more entities, and add new data partition references. Such use cases are out of scope of this article, but you can refer to the [sample material](https://github.com/microsoft/CDM/tree/master/samples) available in the Common Data Model GitHub repo. Persisting an updated schema to the "model.json" or the "manifest.cdm.json" format is the same as discussed earlier in this article.

## Things to keep in mind

Each format has its own structures and the object model provides a single API to manage them. Some of the constructs available in each format may not be clearly visible through the API and do require additional developer guidance. This section covers how client applications can reveal and work with these special structures.

### Custom properties

The specification for the "model.json" format defines two types of custom information pieces in its structure, [annotations](../model-json.md#annotations) and custom properties. Both information pieces enable services to include extra contextual information with the schema, which may be of value to some consumers. The object model recognizes and preserves these custom extensions and provides access to them.

The following snippet demonstrates how one can access the annotations on the entity level:

```csharp
    var annotations = entity.ExhibitsTraits.Item("is.modelConversion.otherAnnotations")?.Arguments[0].Value;
    if (annotations != null)
    {
        foreach (NameValuePair annotation in annotations)
        {
            Console.WriteLine($"{annotation.Name}={annotation.Value}");
        }
    }
```

The custom properties are made available in the object model as individual traits with following naming convention `"is.extension.<propertyname>"`. For example, if you want to get the content from custom property "myapp:something", the following code can retrieve it:

```csharp
    var customPropValue = entity.ExhibitsTraits.Item("is.extension.myapp:something")?.Arguments[0].Value;
```

For services in which you convert the "model.json" schema to the "manifest.cdm.json" format, the custom properties that are _not recognized_ by the object model will result in an additional document being saved next to the manifest file. This document is named "custom.extension.cdm.json". This document will hold the definitions of `"is.extension"` traits that represent the custom properties discovered in the original "model.json" file. For _recognized_ custom properties, such as those PowerBI uses, this additional document will not be written since the object model has internal knowledge of it. Find more information about which custom properties are recognized by the object model in the [extensions definitions folder](https://github.com/microsoft/CDM/tree/master/schemaDocuments/extensions).

### Model.json partition locations

By definition, partition locations in the "model.json" metadata files [are absolute](../model-json.md#partitions). Since the object model APIs operate through storage adapters, which is the abstraction layer over the underlying filesystem, these URIs are converted into a corpus path via the applicable adapter. The conversion is automatically performed by the object model when the metadata file loads, _if the URI matches the actual location of the "model.json" file._ So, if you've configured an [ADLSAdapter](../1.0om/api-reference/storage/adlsadapter.md) to be mapped on the "adls" namespace, and the partitions are under the same location, or under any sub-folder, their paths will convert to a corpus path that can look like this: "adls:/somepath/some-partition.csv". And, as shown earlier, clients can decode this corpus path back into the original URI with the following command:

```csharp
    var originalUri = cdmCorpus.Storage.CorpusPathToAdapterPath(dataPartition.Location)
```

If the partition URIs do not match the location of the "model.json" file, a [RemoteAdapter](../1.0om/api-reference/storage/remoteadapter.md) must be pre-configured in the corpus prior to loading the metadata file. For example, if the URIs look like "https://my.server.com:443/somepath", the RemoteAdapter must be configured as follows:

```csharp
    var hosts = new Dictionary<string, string>();
    hosts.Add("myserver", "https://my.server.com:443/somepath");
    cdmCorpus.Storage.Mount("remote", new RemoteAdapter(hosts));
```

As noted earlier in this article, the original URI can then be retrieved by calling the `CorpusPathToAdapterPath` API.

### Model.json referenced models

[Reference models](../model-json.md#reference-models) are a concept in the "model.json" specification that defines how services re-use documents that contain entity definitions. A "reference model" in a "model.json" file consists of an identifier and a location URI that points to the document that contains the actual definition of the entity. An entity of type `ReferenceEntity` uses this identifier to declare that its actual definition can be found in a remote (referenced) document.

In Common Data Model, this type of entity is represented through the [CdmReferenceEntityDeclarationDefinition](../1.0om/api-reference/cdm/referencedentitydeclaration.md) class. Its `EntityPath` property will contain a corpus path variant of the original document URI found in the "referenceModels" section of the "model.json" file. Passing this entity path value to the `CorpusPathToAdapterPath` API will return the original referenced document URI. Similar to the partition location URIs mentioned earlier, if the referenced document URI is in a location that's different from where the "model.json" file resides, a [RemoteAdapter](../1.0om/api-reference/storage/remoteadapter.md) needs to be pre-configured in the corpus to recognize such document URIs. 

Note that this concept in "model.json" specification is rarely used in real-world solutions and has since been made obsolete since there are more flexible import mechanisms in the "manifest.cdm.json" format. 

### Partition patterns 

The new "manifest.cdm.json" schema format introduces a new capability for data producers to define [partition patterns](manifest.md#data-partition-patterns), removing the need to update metadata files whenever a new data partition is added. If a manifest has patterns defined, before such schema is saved in the "model.json" form using the `SaveAsAsync` API, the services must first make a call to the `FileStatusCheckAsync` API on the manifest object like this: 

```csharp
    await manifest.FileStatusCheckAsync();
    await manifest.SaveAsAsync("model.json", true);
```

The `FileStatusCheckAsync` call triggers the file scanning logic in the object model, and results in a number of new [CdmDataPartitionDefinition](../1.0om/api-reference/cdm/datapartition.md) objects being automatically created and added to the entity declaration's partition collection for each partition file that matches the pattern in the target folder.

>[!IMPORTANT]
>Partition _patterns_ are not preserved in the written "model.json" file. To avoid loss of information, services should write the "manifest.cdm.json" file next to the "model.json" file, so that "manifest.cdm.json" is the source of truth regarding how the patterns were originally defined.

## Service migration guidance 

With the introduction of the "manifest.cdm.json" metadata description format, a problem of coexistence of both old and new metadata formats appears. The transition between formats takes time, and service teams should adapt to this situation and assume that both formats may circulate in their environments. Thanks to the object model's native support for both formats via a uniform API, this becomes easy to handle. 

For data producers, both "model.json" and "manifest.cdm.json" variants of their schema can be written together in the same CDM folder: 

```csharp
    await manifest.SaveAsAsync("model.json", true);
    await manifest.SaveAsAsync("mySchema.manifest.cdm.json", true);
```

This approach increases the number of consumers who can understand the data output, though for legacy services that support only the "model.json" format, this understanding will be less, due to format limitations.

For data consumers, the transition path is such that the service needs to become capable of selecting the "manifest.cdm.json" as the default schema source if both old and new metadata formats are present in the CDM folder, and only fall back to "model.json" in case the newer format file is not there. If that happens, the service needs to adjust its behavior because newer concepts, such as traits, will not be available. Here's a simple example: 

```csharp
    var manifestFileName = MyFuncToFindManifestFileInTargetLake();
    var manifest = await cdmCorpus.FetchObjectAsync<CdmManifestDefinition>(manifestFileName ? manifestFileName : "model.json");

    // Do things, but expect that traits or other advanced features may not be available in the loaded schema
```

Following this guidance, data producers and consumers will be able to interop over multiple metadata formats by leveraging the SDK to achieve this format “transparency”.

## Conclusion

In this article we have seen how Common Data Model evolved from a basic representation of the structure of the data to a more feature-rich, semantics-based, metadata language, and how a powerful programming interface was built to simplify interactions with the schemas written in this new language. We have seen how easy it is to use this interface to convert between old and new metadata format, and we've learned how to handle the constructs present in each format.

Service teams can use this guide to get started preparing their services for the time when the "model.json" format is no longer in use, and the new "manifest.cdm.json" is the metadata format of choice for cloud solutions built by Microsoft and leveraged by its partners. With the full backing and support available through open sourced tools, the service teams can expect to see a controlled metadata format transition in near future across relevant Microsoft product offerings.

Recommended further reading: 

* [Common Data Model official website](../index.md)
* [Technical paper on Common Data Model features](overview.md)
* [API reference](../1.0om/api-reference/api-reference.md)
* [GitHub repo with SDKs, schemas, and samples](https://github.com/Microsoft/CDM)
* [Introduction to SDK samples](../samples.md) 
* [Frequently asked questions on Common Data Model](../faq.md) 

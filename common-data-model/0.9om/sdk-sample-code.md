---
title: SDK Sample Code - Common Data Model | Microsoft Docs
description: This contains SDK's sample code.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 6/18/2019
ms.author: nebanfic
---

# SDK Sample Code

### Sample Location and Structure

Sample code that demonstrate concepts and their use  are available for C# implementation is available <a href  = "https://commondatamodel.visualstudio.com/CDM/_git/CDM.Tools.Public?path=%2FSDK-examples&version=GBfeatures%2Fcdm0.9">here</a>.

On this path you will find multiple VS sample projects organized is separate folders. Next to them, you can find the example-public-standards folder which contains local copy of CDM Standard Entities and is referenced by the sample projects.

Within each project, files are organized in following manner:

- code-cs - VS solution
- Set of JSON files with CDM entity definitions
- Set of folders for each entity containing empty sample data partition file (CSV)


### Every Sample Prerequisite

Every time we interact with CDM we interact with some persistent form of CDM and we need to provide storage adapter(s).
 
Sample code which sets up a config to use the local storage system where we need to provide paths to the schema documents on a local file system (some commonly used schema documents can be provided by using CDN/GitHub storage adapters):

```
 ICdmCorpusDef cdmCorpus = new CorpusImpl();

// Path to the example root.
string pathFromExeToExampleRoot = "../../../../../";
JObject localConfig = new JObject(
new JProperty("adapter", "LocalAdapter"),
new JProperty("root", pathFromExeToExampleRoot));

// Register it as the 'local' device.
IStorageAdapter localAdapter = cdmCorpus.CreateStorageAdapter(localConfig);

cdmCorpus.RegisterStorageAdapter("local", localAdapter);
cdmCorpus.DefaultNamespace = "local"; // local is our default. so any paths that start out navigating without a device tag will assume local

// Fake CDM, normally use the GitHub adapter.
JObject cdmConfig = new JObject(
new JProperty("adapter", "LocalAdapter"),
new JProperty("root", pathFromExeToExampleRoot + "example-public-standards"));

// Register it as the 'cdm' device, not the default so must use "cdm:/folder" to get there.
IStorageAdapter cdmAdapter = cdmCorpus.CreateStorageAdapter(cdmConfig);
cdmCorpus.RegisterStorageAdapter("cdm", cdmAdapter);
```

### Explanation of C# sample code in files for the new OM

#### Read Folio (1-read-folio)

In this sample, you learn how to read the CDM Folio with all entity definitions, examine an entity, its attributes and partitions.
- Open read-folio.sln in code-cs directory.
- Run the project. You should see a console with the list of entities and corresponding schema locations.
- Type a number for a chosen entity and see the list of attributes and traits.

How it works:
The OM reads the content of **default.folio.cdm.json** file located at the root of the project directory. The relative path points at it from the location of the exe. For example, the location of the read folio executable is *E:\cdm_sdk_test\CDM SDK 0.9\1-read-folio\code-cs\read-folio\bin\Debug\netcoreapp2.1*, the way the path to the folder with entities is specified.

How it works:

The OM reads the content of default.folio.cdm.json file located at the root of the project directory. The relative path points at it from the location of the exe. For example, the location of the read folio executable is *E:\cdm_sdk_test\CDM SDK 0.9\1-read-folio\code-cs\read-folio\bin\Debug\netcoreapp2.1*, the way the path to the folder with entities is specified.

```
string pathFromExeToExampleRoot = "../../../../../../";
```

Once it lists entities, it can be pointed at a specific entity and will parse JSON for that specific entity to get the entity attributes and traits.
Follow comments in the Program.cs for each specific fragment.

#### Create Folio (2-create-folio)

In this example, you learn how to create a folio with select number of entities as well as corresponding partitions.

- Open create-folio.sln in code-cs directory.
- Examine the root directory for the project. The zip file contains files and folders that have already been created. To fully test the code, you will need to delete certain files and folder.

This is what you get in the zip file:

![Read Folio Picture 1](0.9om/readfolio1.png)

Delete all items except for code-cs (you can also keep code-ts for consistency). This is what you should have been left with:

![Read Folio Picture 2](0.9om/readfolio2.png)


- Run the project. Monitor messages in the console as they are informative to what is going on. Look into your directory, it should have all  files and folders generated again. 
- There are few code fragments here. After configuring adapters, same as in the first sample, we create temp folio object, add specific entities of your choice. Note that you need to point at definitions for those entities.

```
// Add each declaration, this example is about medical appointments and care plans
ICdmLocalEntityDeclarationDef entDec = cdmCorpus.MakeObject<ICdmLocalEntityDeclarationDef>(CdmObjectType.LocalEntityDeclarationDef, "Account");
 entDec.EntitySchema ="cdm:/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Account.cdm.json/Account";
folioAbstract.Entities.Add(entDec);
```

The following fragment implements Resolving entities (basically creating instances of specific entities using their abstract definitions as well as foundation definitions). After that, each entity is saved to the directory in corresponding JSON file along with the eponymous folder with empty CSV partition file.
Follow comments in the Program.cs for each specific fragment.

#### Customize Entities (3-customize-entities)

Steps to do:
- Open 3-customize-entities and inside code-cs open 3-customize-entities.sln.
- Run the project.
This sample will load an existing folio and to it a new entity that is a customized version of a standard.

We will add the CareTeam entity, but first we will add the 'currentCity' attribute and give the new entity a new name 'MobileCareTeam'. This new definition becomes a local abstract description of an entity that is resolved and flattened before being added to the folio.

```
// This method turns relative corpus paths into absolute ones in case we are in some sub-folders and don't know it.

string folioPath = cdmCorpus.MakeAbsoluteCorpusPath("default.folio.cdm.json");
ICdmFolioDef folio = await cdmCorpus.CreateRootFolio(folioPath);

// First we will make a new document right in the same folder as the folio.
ICdmDocumentDef docAbs = cdmCorpus.MakeObject< ICdmDocumentDef>(CdmObjectType.DocumentDef, "MobileCareTeam.cdm.json");
```

Import the CDM description of the original so the symbols will resolve.

```
docAbs.AddImport("cdm:/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CareTeam.cdm.json", null);

// We will make a new trait to identify things that are known to be temporary, used later. In theory this would be defined somewhere central so it can be shared.
ICdmTraitDef traitTemp = docAbs.AddDefinition<ICdmTraitDef>(CdmObjectType.TraitDef, "means.temporary");

traitTemp.ExtendsTrait = cdmCorpus.MakeObject<ICdmTraitRef>(CdmObjectType.TraitRef, "means", true); // extends the standard 'means' base trait

// Has a parameter for the expected duration in days.
ICdmParameterDef param = cdmCorpus.MakeObject<ICdmParameterDef>(CdmObjectType.ParameterDef, "estimatedDays");

// By not using "true" on the last arg, this becomes a real reference object in the JSON. Go look at the difference from "means" when this is done.
param.DataTypeRef = cdmCorpus.MakeObject<ICdmDataTypeRef>(CdmObjectType.DataTypeRef, "integer"); param.DefaultValue = "30";

traitTemp.HasParameterDefs.Add(param);
// Make an entity definition and add it to the list of definitions in the document.

ICdmEntityDef entAbs = docAbs.AddDefinition<ICdmEntityDef>(CdmObjectType.EntityDef, "MobileCareTeam");

// This entity extends the standard.
// This function with 'true' will make a simple reference to the base.
entAbs.ExtendsEntity = cdmCorpus.MakeObject<ICdmEntityRef>(CdmObjectType.EntityRef, "CareTeam", true);

// And we will add an attribute.
ICdmTypeAttributeDef attNew = cdmCorpus.MakeObject<ICdmTypeAttributeDef>(CdmObjectType.TypeAttributeDef, "currentCity");

// The attribute is a type is 'City" this is one of the predefined semantic types in meanings.cdm.json
attNew.DataType = cdmCorpus.MakeObject<ICdmDataTypeRef>(CdmObjectType.DataTypeRef, "city", true);

attNew.Description = "The current city where the mobile care team is working";

// Also apply our fancy new 'temporary' trait. They stay in a city for 90 days on average.
ICdmTraitRef tr = cdmCorpus.MakeObject<ICdmTraitRef>(CdmObjectType.TraitRef, "means.temporary");

tr.AddArgument("estimatedDays", "90");

attNew.AppliedTraits.Add(tr);

// Add attribute to the entity.
entAbs.AddAttributeDef(attNew);
```

The entity abstract definition is done, add the document to the corpus in the root folder and then save the doc.

```
cdmCorpus.GetRootFolder("local").AddDocument("MobileCareTeam.cdm.json", docAbs);

```

The next step is to remove all of the guesswork out of decoding the entity shape by 'resolving' it to a relational by reference shape.

```
var resOpt = new ResolveOptions

{

WrtDoc = docAbs, // This value is important, it sets a point of view for resolving symbolic references, usually you want to use 'this' document.

Directives = new AttributeResolutionDirectiveSet(new HashSet<string> { "normalized", "referenceOnly" }) // These direct the OM to avoid one to many relationship nesting and to use foreign keys for many to one refs.

};

// Now resolve it.
ICdmEntityDef entFlat = await entAbs.CreateResolvedEntity(resOpt, "LocalMobileCareTeam"); // made the entity and document have a different name to avoid conflicts in this folder

// Now just add the pointer into our folio.
ICdmLocalEntityDeclarationDef localEDef = cdmCorpus.MakeObject<ICdmLocalEntityDeclarationDef>(CdmObjectType.LocalEntityDeclarationDef, "LocalMobileCareTeam");
localEDef.EntitySchema = "/LocalMobileCareTeam.cdm.json/LocalMobileCareTeam";
folio.Entities.Add(localEDef);
```

Update all of the file status times in the folio.

```
await folio.RefreshFileStatus();

```

And save the folio along with linked definition files.

```
await folio.SaveAs($"default.folio.cdm.json", new CopyOptions(), true);
```


#### Read Model.Json (0.1 OM library) or read 0.9 OM library and work with 0.9 OM library (4-validate-folio)

Steps to do:
- Open 4-validate-folio and inside code-cs open 4-validate-folio.sln project
- Run the project.
This sample reads the content of a model document, converts it to folio and lists the attributes it knows about for a given entity, the sample will get the schema definition document and you should get the list of all the attributes and then the traits of each.
 
Code with explanation:

```
// This method turns relative corpus paths into absolute ones in case we are in some sub-folders and don't know it.

// We could also list here a file with '.folio.cdm.json' extension.
string folioPath = cdmCorpus.MakeAbsoluteCorpusPath("model.json");

// Internally calls persistence layer to turn 0.1 OM model into 0.9 OM Folio and work with 0.9 OM.
var folio = await cdmCorpus.CreateRootFolio(folioPath);

foreach (ICdmEntityDeclarationDef entDec in folio.Entities)
{
        // Check for the type of the entity, if local - proceed, if not, stop!
        if (entDec is ICdmLocalEntityDeclarationDef)
        {

          ICdmLocalEntityDeclarationDef localDec = entDec as ICdmLocalEntityDeclarationDef;
         
          // Fetch the entity object from the doc.
          ICdmEntityDef entSelected = await cdmCorpus.GetObjectFromCorpusPath(localDec.EntitySchema) as ICdmEntityDef;

          // This way of getting the attributes only works well for 'resolved' entities that have been flattened out.
          // An abstract entity can be resolved by calling createResolvedEntity on it

          if (entSelected is ICdmEntityDef)
          {
            foreach (ICdmTypeAttributeDef att in entSelected.HasAttributes)
            {
              // Do something with the attribute.
              // List all traits.
              foreach (ICdmTraitRef tr in att.AppliedTraits)
              {
                // Do something with the trait.
              }
             }
                  // Stop the loop since we executed a local entity.
                  break;
           }

          iEnt++;
        }
}
```

### Explanation of in-documentation sample code

#### Read 0.9 OM file(s) and work with 0.1 OM library

The following sample reads default.folio.cdm.json file and corresponding entities in the definitions array and converts it to the 0.1 OM file. It executes some logic by using the old 0.1 OM library and in the end it saves the model as both folio (0.9 OM) and model (0.1 OM).

```
// Read folio and all the referenced files from folio and convert it to a model.(internally calls model.json persistence).
var model = await Model.ImportFromFolio(GetLocalCorpus(), "default.folio.cdm.json");

// Do some changes to the model.
model.Description = "This is a different description";
 
var entity = new LocalEntity { Name = "Some entity name" };
 
var oldCount = model.Entities.Count;
 
model.Entities.Add(entity);
 
// Export it back to folio.
var newFolio = Model.ExportToFolio(model, this.GetLocalCorpus());
 
// Save it back to a file with saving the referenced files as well.
await newFolio.SaveAs("folioFromModel.folio.cdm.json", null, true);

 // Save it back to a model.json (OM 0.1) file just by changing the extension.
await newFolio.SaveAs("model..json", null, true);
```

#### Representation of 0.1 OM extensions in 0.9 OM Folio

0.1 OM has a support for extensions which can give partners different and additional set of properties they may want to use. 0.9 OM will continue to support extensions by creating a trait reference (see ICdmTraitRef) with the is.extension prefix. Example of the extensions in 0.1OM vs 0.9OM:

0.1 OM:

```
"pbi:mashup": {

  "fastCombine": true,

  "document": "sample document query",

  "queriesMetadata": {

    "Orders": {

    "queryId": "88bc570c-047d-460f-8eed-c0ef17649afd",

    "queryName": "Orders",

    "loadEnabled": true

    }

  }

}
```

0.9 OM:

```
{

"traitReference": "is.extension.pbi:mashup",

"arguments": [

  {

  "name": "fastCombine",

  "value": "True"

  },

  {

  "name": "document",

  "value": "sample document query"

  },

  {

  "name": "queriesMetadata",

  "value": {

  "Orders": {

  "queryId": "88bc570c-047d-460f-8eed-c0ef17649afd",

  "queryName": "Orders",

  "loadEnabled": true

    }

   }

  }  

]

}
```
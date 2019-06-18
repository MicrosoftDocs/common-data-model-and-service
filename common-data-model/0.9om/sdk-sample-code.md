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
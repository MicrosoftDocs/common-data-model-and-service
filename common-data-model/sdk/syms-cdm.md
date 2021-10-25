---
title: Working with Synapse metadata store | Microsoft Docs
description: This article provides guidance to developers for using Common Data Model SDK with Synapse workspaces and their metadata stores.
author: supawa
ms.service: common-data-model
ms.topic: article
ms.date: 09/01/2021
ms.author: supawa
---

# SyMS Adapter Overview

The SyMS adapter is the storage adapter that's used to interact with data in Sapse workspace. It provides the Common Data Model view of [Synapse](/azure/synapse-analytics/overview-what-is) workspace.

**__Note:__** : SyMS adapter is in preview stage and few functionality might change in future.

## SyMS object hierarchy representation in Common Data Model

Common Data Model maps SyMS metadata into a folder structure as shown below:

 
 ![cdmsymsmapping](../media/cdm-syms-mapping.png) 


|File Name|SyMS Mapping|
|---|---|
|databases.manifest.cdm.json| Stores list of databases in SyMS as sub-manifest.
|[databaseName].manifest.cdm.json| Stores entities (SyMS tables) declaration such as data location information.
|[entityName].cdm.json| Stores entity (SyMS table) definition like attributes (SyMS column) and traits.

## Reading metadata from SyMS

1. Create and mount SyMS adapter to corpus.Please consult [this page](../1.0om/api-reference/storage/symsadapter.md) for more information about adapter’s API.
    ```csharp
    SymsAdapter adapter = new SymsAdapter("<symsworkspaceName>.dev.azuresynapse-dogfood.net","<tenantid>","<clientId>","<Secret>");

    corpus.Storage.Mount("syms", adapter);
    ```
2. Optional: Create and mount all ADLS storage accounts as ADLS adapters which are attached to the SyMS workspace.

    ```csharp
    corpus.Storage.Mount("adls1",
                new ADLSAdapter(
                "/<FILESYSTEM-NAME>",
                "<CLIENT-ID>",
                "<CLIENT-SECRET>"
                ));
    
            
    corpus.Storage.Mount("adls2",
                new ADLSAdapter(
                "/<FILESYSTEM-NAME>",
                "<CLIENT-ID>",
                "<CLIENT-SECRET>"
                ));
    ```
   **__Note:__** If the ADLS adapters are not added, CDM will create and mount respective adapters that correspond to the discovered data locations.

    ```csharp
    corpus.Storage.NamespaceAdapters
    ```
3.	Read the list of databases from SyMS workspace
 
    Databases are stored as submanifests in databases.manifest.cdm.json. So read databases.manifest.cdm.json first.

    ```csharp
    CdmManifestDefinition manifest = await corpus.FetchObjectAsync<CdmManifestDefinition>("syms:/databases.manifest.cdm.json");
    ```
4.	Read SyMS database 
 
    Read the submanifest definition to get databases as manifests.
    ```csharp
    CdmManifestDefinition manifestdb = await corpus.FetchObjectAsync<CdmManifestDefinition>($"syms:/<databaseName>/<databaseName>.manifest.cdm.json" null, true);
    ```
    or
    ```csharp
    CdmManifestDefinition manifestdb = await corpus.FetchObjectAsync<CdmManifestDefinition>(manifest.SubManifests[0].Definition, null, true);
    ```
5.	Read SyMS tables
 
    Tables are stored as entities in CDM. Read CdmEntityDefinition object to read SyMS table.

    ```csharp
    var entity = await corpus.FetchObjectAsync<CdmEntityDefinition>(manifestdb.Entities[0].EntityPath, manifestdb); 
    ```

6.	Read SyMS table as CDM document.
    ```csharp
    var doc = await corpus.FetchObjectAsync<CdmDocumentDefinition>($"syms:/{manifestdb.ManifestName}/<tableName>.cdm.json");
    ```

   **__Note:__** Database name will be in the form of "manifestdb.ManifestName".

7. Data locations are represented in the form of data partition patterns. Use the following API to resolve the pattern to individual data partition objects.
    ```csharp
    manifestdb.FileStatusCheckAsync();
    ```


## Creating a database and a table in SyMS

1. Create and mount SyMS adapter to corpus. Please consult [this page](../1.0om/api-reference/storage/symsadapter.md) for more information about adapter’s API.
    ```csharp
    SymsAdapter adapter = new SymsAdapter("<symsWorkSpaceName>.dev.azuresynapse-dogfood.net","<tenantId>","<clientId>","<secret>");

    corpus.Storage.Mount("syms", adapter);
    ```
2. Create and mount all ADLS storage accounts attached to the SyMS workspace as SDK's ADLS adapters.

    ```csharp
    corpus.Storage.Mount("adls1",
                new ADLSAdapter(
                "/<FILESYSTEM-NAME>",
                "<CLIENT-ID>",
                "<CLIENT-SECRET>"
                ));
    
            
    corpus.Storage.Mount("adls2",
                new ADLSAdapter(
                "/<FILESYSTEM-NAME>",
                "<CLIENT-ID>",
                "<CLIENT-SECRET>"
                ));
    ``` 

3. Create manifest object or load from  *.manifest.cdm.json document.
     ```csharp
    var manifest = await corpus.FetchObjectAsync<CdmManifestDefinition>("local:/<manifestFileName>.manifest.cdm.json");
    ```
    Make sure manifest has following content
    1. [is.storagesource](list-of-traits.md#isstoragesource) is a mandatory trait that must be defined in the manifest, and should contain location of the default lake linked to SyMS.
    2. Manifest name is SyMS database name.
    3. Providing data partition for an entity (SyMS table) is mandatory in SyMS. If ADLS adapter's namespace is provided, then the corresponding ADLS adapter path will be converted to the absolute path of the partition. Otherwise, the location will be calculated relative to the location value found in "is.storagesource" trait. In the example below, it is "adls1:/" which is default for the Address entity.

    Example :
    ```json
    {
        "manifestName": "SymsTestDatabase",
        "explanation": "SymsTestDatabase syms database",
        "exhibitsTraits": [
            {
            "traitReference": "is.storagesource",
            "arguments": [
                {
                "name": "namespace",
                "value": "adls1:/"
                }
            ]
            }
        ],
        "entities": [
            {
            "type": "LocalEntity",
            "entityName": "Account",
            "entityPath": "Account.cdm.json/Account",
            "dataPartitions": [
                {
                "location": "adls2:/Account/partition-data.csv",
                "exhibitsTraits": [
                    {
                    "traitReference": "is.partition.format.CSV",
                    "arguments": [
                        {
                        "name": "columnHeaders",
                        "value": "true"
                        },
                        {
                        "name": "delimiter",
                        "value": ","
                        }
                    ]
                    }
                ],
                "lastFileStatusCheckTime": "2021-08-17T00:50:29.016Z",
                "lastFileModifiedTime": "2020-02-24T00:00:00.000Z"
                }
            ],
            "lastFileStatusCheckTime": "2021-08-17T00:50:29.017Z",
            "lastFileModifiedTime": "2021-08-17T00:11:06.991Z",
            "lastChildFileModifiedTime": "2021-08-17T00:11:06.991Z"
            },
            {
            "type": "LocalEntity",
            "entityName": "Address",
            "entityPath": "Address.cdm.json/Address",
            "dataPartitions": [
                {
                "location": "Address/partition-data.csv",
                "exhibitsTraits": [
                    {
                    "traitReference": "is.partition.format.CSV",
                    "arguments": [
                        {
                        "name": "columnHeaders",
                        "value": "true"
                        },
                        {
                        "name": "delimiter",
                        "value": ","
                        }
                    ]
                    }
                ],
                "lastFileStatusCheckTime": "2021-08-17T00:50:30.992Z",
                "lastFileModifiedTime": "2020-02-24T00:00:00.000Z"
                }
            ],
            "lastFileStatusCheckTime": "2021-08-17T00:50:30.992Z",
            "lastFileModifiedTime": "2021-06-25T00:54:16.717Z",
            "lastChildFileModifiedTime": "2021-06-25T00:54:16.717Z"
            }
        ],
        "lastFileStatusCheckTime": "2021-08-17T00:50:29.010Z",
        "lastFileModifiedTime": "2021-08-17T00:47:05.987Z",
        "lastChildFileModifiedTime": "2021-08-17T00:11:06.991Z",
        "relationships": [
            {
            "name": "Account_Account_relationship",
            "fromEntity": "Account.cdm.json/Account",
            "fromEntityAttribute": "parentAccountId",
            "toEntity": "Account.cdm.json/Account",
            "toEntityAttribute": "accountId"
            },
            {
            "name": "Address_Address_relationship",
            "fromEntity": "Address.cdm.json/Address",
            "fromEntityAttribute": "masterId",
            "toEntity": "Address.cdm.json/Address",
            "toEntityAttribute": "accountId"
            }
        ],
        "jsonSchemaSemanticVersion": "1.0.0",
        "imports": [
            {
            "corpusPath": "cdm:/foundations.cdm.json"
            }
        ]
    }
    ```
4. Save manifest

    Create database and resepective tables in SyMS.
    
    ```csharp
    var ret = await manifest.SaveAsAsync($"syms:/{manifest.ManifestName}/{manifest.ManifestName}.manifest.cdm.json")
    ```

## Writing deltas into SyMS
1. Create a new table in existing SyMS database.
    1. Read SyMS database.
     ```csharp
    CdmManifestDefinition manifestdb = await corpus.FetchObjectAsync<CdmManifestDefinition>("syms:/<databaseName>/<databaseName>.manifest.cdm.json");
    ```
    2. Create table definition i.e. [tableName].cdm.json document.
    3. Add [tableName] under entity declaration in [databaseName].manifest.cdm.json.
    4. Save manifest.
    ```csharp
    var ret = await manifest.SaveAsAsync($"syms:/{manifest.ManifestName}/{manifest.ManifestName}.manifest.cdm.json")
    ```
2. Delete a table from SyMS.
    1. Read SyMS database.
    2. Remove [tableName] under entity declaration from [databaseName].manifest.cdm.json.
    4. Save manifest.

3. Modify existing table.
    1. Read SyMS database.
    2. Read [tableName].cdm.json
        ```csharp
        var doc = await corpus.FetchObjectAsync<CdmDocumentDefinition>($"syms:/{manifestdb.ManifestName}/<tableName>.cdm.json");
        ```
    3. Add/Modify column in [tableName].cdm.json
    4. Save document
        ```csharp
        var ret = await doc.SaveAsAsync($"syms:/{manifestdb.ManifestName}/<tableName>.cdm.json")
        ```
    5. Change entity declaration object in manifest.
    6. Update LastFileModifiedTime to current time.
        ```csharp
        manifestModified.Entities[0].LastFileModifiedTime = DateTimeOffset.UtcNow;
        ```
    7. Save manifest.
    

## SymsAdapter Class
Please refer to [this](../1.0om/api-reference/storage/symsadapter.md) section.

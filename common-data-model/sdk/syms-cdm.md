---
title: SyMS Adapter Overview | Microsoft Docs
description: Overview of SymsAdapter.
author: supawa
ms.service: common-data-model
ms.topic: article
ms.date: 09/01/2021
ms.author: supawa
---

# SyMS Adapter Overview

The SyMS adapter is the storage adapter that's used to interact with data in synapse workspace. It provides the Common Data Model view of synpase workspace.

</br>

## SyMS View in Common Data Model

Common Data Model maps SyMS metadata into a folder structure as shown below:

 
 ![cdmsymsmapping](../media/cdm-syms-mapping.png) 


|File Name|SyMS Mapping|
|---|---|
|databases.manifest.cdm.json| It stores list of databases in SyMS as sub-manifest.
|[databaseName].manifest.cdm.json| It stores entities (SyMS tables) declaration such as data location information.
|[entityName].cdm.json| It stores entity (SyMS table) definition like attributes (SyMS column) and traits.

</br>

## How to read from SyMS?


1. Create and mount SyMS adapter to cropus.
    ```csharp
    SymsAdapter adapter = new SymsAdapter("<symsworkspaceName>.dev.azuresynapse-dogfood.net","<tenantid>","<clientId>","<Secret>");

    corpus.Storage.Mount("syms", adapter);
    ```
2. Optional: Create and mount all ADLS storage account as ADLS adapter which are attached to the SyMS workspace.

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
    Note : If you don’t create it , CDM internally create the respective ADLS adapters corresponding to location of data and mount it which can be later on found in mounted adapter list.

    ```csharp
    corpus.Storage.NamespaceAdapters
    ```
3.	Read the list of Database from SyMS workspace
 
    Databases are stored as submanifest in databases.manifest.cdm.json. So read databases.manifest.cdm.json first.

    ```csharp
    CdmManifestDefinition manifest = await corpus.FetchObjectAsync<CdmManifestDefinition>("syms:/databases.manifest.cdm.json");
    ```
4.	Read SyMS database 
 
    Read the submanifest definiton to get database as manifest.

    ```csharp
    CdmManifestDefinition manifestdb = await corpus.FetchObjectAsync<CdmManifestDefinition>(manifest.SubManifests[0].Definition, null, true);
    ```
    or 

    ```csharp
    CdmManifestDefinition manifestdb = await corpus.FetchObjectAsync<CdmManifestDefinition>($"syms:/<databaseName>/<databaseName>.manifest.cdm.json" null, true);
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
    Note: Database Name is manifestdb.ManifestName.

7. Data locations are stored in form of data partition pattern. Use following api to resolve it to datapartition objects. 
    ```csharp
    manifestdb.FileStatusCheckAsync();
    ```

</br>

## How to Create database and table in SyMS?

</br>

1. Create and mount SyMS adapter to cropus.
    ```csharp
    SymsAdapter adapter = new SymsAdapter("<symsworkspaceName>.dev.azuresynapse-dogfood.net","<tenantid>","<clientId>","<Secret>");

    corpus.Storage.Mount("syms", adapter);
    ```
2. Create and mount all ADLS storage account as ADLS adapter which are attached to the SyMS workspace.

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
    Make sure manifest have following content
    1. [is.storagesource](list-of-traits.md#isstoragesource) trait must be defined in manifest. This store location of default lake linked to SyMS. This is mandatory trait.
    2. Manifest Name is SyMS database name.
    3. Data partition for entity(SyMS table) is mandatory in SyMS. If ADLS adapter's namespace is provided, then corresponding ADLS adapter path will be converted to absolute path otherwise location would be calculated relative to location value of is.storagesource trait. In example below, it is adls1:/ which is default for address entity.

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
</br>

## How to Push Deltas into SyMS Database
1. Create a new table in existing SyMS database.
    1. Read Syms database.
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
    2. Read [tabeName].cdm.json
        ```csharp
        var doc = await corpus.FetchObjectAsync<CdmDocumentDefinition>($"syms:/{manifestdb.ManifestName}/<tableName>.cdm.json");
        ```
    3. Add/Modify column in [tabeName].cdm.json
    4. Save document
        ```csharp
        var ret = await doc.SaveAsAsync($"syms:/{manifestdb.ManifestName}/<tableName>.cdm.json")
        ```
    5. Change entity decalration object in manifest.
    6. Update LastFileModifiedTime to currernt time.
        ```csharp
        manifestModified.Entities[0].LastFileModifiedTime = DateTimeOffset.UtcNow;
        ```
    7. Save manifest.
    
    </br>
## Error Handling and Troubleshooting 

Register [event callback](../1.0om/api-reference/utilities/callback.md) to capture the error/warning logs and code.
Please refer [log code](../troubleshooting/log-code.md) and [troubleshooting](../troubleshooting/eventlist-usage.md) section for more details.

</br>

## SymsAdapter Class
Refere [this](../1.0om/api-reference/storage/symsadapter.md) section.

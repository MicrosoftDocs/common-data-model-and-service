---
title: Storage | Microsoft Docs
description: API reference for Storage.
author: jinichu

ms.reviewer: deonhe 
ms.topic: reference 
ms.date: 08/24/2020
ms.author: jibyun
---

# Storage

## Overview

The Storage classes provide a way to interact with Common Data Model files. The role of a [storage adapter](storageadapter.md) is to provide an abstraction of the underlying file system where Common Data Model files are stored. Whether data is stored locally or remotely, such as on Azure Data Lake Storage Gen 2, storage adapters can be used to simplify the reading and writing of documents without the [object model](../cdm/cdm.md) having to understand the underlying mechanism of interacting with different file systems. There are various existing storage adapter implementation classes to help interact with different types of file systems. Users can also implement their own adapters by extending the storage adapter interface. The [storage manager's](storagemanager.md) role is to be the "storage" for the [corpus](../cdm/corpus.md), by allowing and managing interactions with the storage adapters.

The C# code can be found [here](https://github.com/microsoft/CDM/tree/master/objectModel/CSharp/Microsoft.CommonDataModel.ObjectModel/Storage).

>[!NOTE]
>While storage adapters accept all paths, including paths that contain colons, the underlying file systems that back them may not. Keep this in mind if you need cross-platform support.

## Classes
|Name|Description|
|---|---|
|[ADLS Adapter](adlsadapter.md)|Used to interact with data on Azure Data Lake Storage Gen2.|
|[Common Data Model Standards Adapter](cdmstandardsadapter.md)|Points to the Common Data Model public standards schema documents.|
|[Github Adapter](githubadapter.md)|Points to the Common Data Model public standards schema documents on [Github](https://github.com/microsoft/CDM/tree/master/schemaDocuments).|
|[Local Adapter](localadapter.md)|Used to interact with data on the local file system.|
|[Network Adapter](networkadapter.md)|Contains logic for adapters that deal with data across a network.|
|[Remote Adapter](remoteadapter.md)|Used to interact with data on a remote file system.|
|[Storage Adapter Base](storageadapterbase.md)|The base class for an adapter object that can read and write documents to and from a data source. It allows a user to interact with data from multiple data sources without having to manually copy data to the location where the [object model](../cdm/cdm.md) is running. By deriving from this class, users are able to create their own adapter if needed.|
|[Storage Adapter](storageadapter.md)|The base interface for an adapter object that can read and write documents to and from a data source. It allows a user to interact with data from multiple data sources without having to manually copy data to the location where the [object model](../cdm/cdm.md) is running. This interface also allows users to create their own adapter, if needed.
**Note**: This class is on the deprecation path. Use [StorageAdapterBase] instead|
|[Storage Manager](storagemanager.md)|Acts like a storage for the [corpus](../cdm/corpus.md) and is used to interact with [storage adapters](storageadapterbase.md).|

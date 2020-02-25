---
title: Storage | Microsoft Docs
description: API reference for Storage.
author: jinichu
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: jibyun
---

# Storage

## Overview

The Storage classes provide a way to interact with Common Data Model files. The role of a [storage adapter](storageadapter.md) is to provide an abstraction of the underlying file system where Common Data Model files are stored. Whether data is stored locally or remotely, such as on Azure Data Lake Storage Gen 2, storage adapters can be used to simplify the reading and writing of documents without the [object model](../cdm/cdm.md) having to understand the underlying mechanism of interacting with different file systems. There are various existing storage adapter implementation classes to help interact with different types of file systems. Users can also implement their own adapters by extending the storage adapter interface. The [storage manager's](storagemanager.md) role is to be the "storage" for the [corpus](../cdm/corpus.md), by allowing and managing interactions with the storage adapters.

The C# code can be found [here](https://github.com/microsoft/CDM/tree/master/objectModel/CSharp/Microsoft.CommonDataModel.ObjectModel/Storage).

## Classes
|Name|Description|
|---|---|
|[ADLSAdapter](adlsadapter.md)|Used to interact with data on Azure Data Lake Storage Gen2.|
|[GithubAdapter](githubadapter.md)|Points to the Common Data Model public standards schema documents on [Github](https://github.com/microsoft/CDM/tree/master/schemaDocuments).|
|[LocalAdapter](localadapter.md)|Used to interact with data on the local file system.|
|[NetworkAdapter](networkadapter.md)|Contains logic for adapters that deal with data across a network.|
|[RemoteAdapter](remoteadapter.md)|Used to interact with data on a remote file system.|
|[Storage Adapter](storageadapter.md)|The base interface for an adapter object that can read and write documents to and from a data source. It allows a user to interact with data from multiple data sources without having to manually copy data to the location where the [object model](../cdm/cdm.md) is running. This interface also allows users to create their own adapter, if needed.|
|[Storage Manager](storagemanager.md)|Acts like a storage for the [corpus](../cdm/corpus.md) and is used to interact with [storage adapters](storageadapter.md).|

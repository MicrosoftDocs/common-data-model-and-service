---
title: Storage - Common Data Model | Microsoft Docs
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
TODO: Description

## Classes
|Name|Description|
|---|---|
|[Storage Manager](storagemanager.md)|Acts like a storage for the [corpus](../cdm/corpus.md) and is used to interact with [storage adapters](storageadapter.md).|
|[ADLSAdapter](adlsadapter.md)|Used to interact with data on Azure Data Lake Storage Gen2.|
|[GithubAdapter](githubadapter.md)|Points to the CDM public standards schema documents on Github.|
|[LocalAdapter](localadapter.md)|Used to interact with data on the local file system.|
|[NetworkAdapter](networkadapter.md)|Contains logic for adapters that deal with data across a network.|
|[RemoteAdapter](remoteadapter.md)|Used to interact with data on a remote file system.|

## Interfaces
|Name|Description|
|---|---|
|[Storage Adapter](storageadapter.md)|The base for an adapter object that can read and write documents to and from a data source. It allows a user to interact with data from multiple data sources without having to manually copy data to the location where the CDM object model is running. This interface also allows users to create their own adapter, if needed.|
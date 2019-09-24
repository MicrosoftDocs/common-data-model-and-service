---
title: Owner - Common Data Model | Microsoft Docs
description: Group of undeleted system users and undeleted teams. Owners can be used to control access to specific objects.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Owner

Group of undeleted system users and undeleted teams. Owners can be used to control access to specific objects.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Owner.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /Owner  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[versionNumber](#versionNumber)||<a href="Owner.md" target="_blank">applicationCommon/Owner</a>|
|[ownerId](#ownerId)|Unique identifier for the Owner: systemuserid or teamid.|<a href="Owner.md" target="_blank">applicationCommon/Owner</a>|
|[name](#name)|Name of the Owner.|<a href="Owner.md" target="_blank">applicationCommon/Owner</a>|
|[ownerIdType](#ownerIdType)||<a href="Owner.md" target="_blank">applicationCommon/Owner</a>|
|[yomiName](#yomiName)|Pronunciation of the name of the owner, written in phonetic hiragana or katakana characters.|<a href="Owner.md" target="_blank">applicationCommon/Owner</a>|

### <a href=#versionNumber name="versionNumber">versionNumber</a>

First included in: applicationCommon/Owner (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Unique identifier for the Owner: systemuserid or teamid.  
First included in: applicationCommon/Owner (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Unique identifier for the Owner: systemuserid or teamid.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#name name="name">name</a>

Name of the Owner.  
First included in: applicationCommon/Owner (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Name</td></tr><tr><td>description</td><td>Name of the Owner.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

First included in: applicationCommon/Owner (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#yomiName name="yomiName">yomiName</a>

Pronunciation of the name of the owner, written in phonetic hiragana or katakana characters.  
First included in: applicationCommon/Owner (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Name</td></tr><tr><td>description</td><td>Pronunciation of the name of the owner, written in phonetic hiragana or katakana characters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yominame</td></tr></table>

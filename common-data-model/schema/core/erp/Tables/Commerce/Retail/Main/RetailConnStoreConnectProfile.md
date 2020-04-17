---
title: RetailConnStoreConnectProfile - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailConnStoreConnectProfile

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Main/RetailConnStoreConnectProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnStoreConnectProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailConnStoreConnectProfile.md" target="_blank">Main/RetailConnStoreConnectProfile</a>|
|[Name](#Name)||<a href="RetailConnStoreConnectProfile.md" target="_blank">Main/RetailConnStoreConnectProfile</a>|
|[NoIPSec](#NoIPSec)||<a href="RetailConnStoreConnectProfile.md" target="_blank">Main/RetailConnStoreConnectProfile</a>|
|[Port](#Port)||<a href="RetailConnStoreConnectProfile.md" target="_blank">Main/RetailConnStoreConnectProfile</a>|
|[PreferIPV6](#PreferIPV6)||<a href="RetailConnStoreConnectProfile.md" target="_blank">Main/RetailConnStoreConnectProfile</a>|
|[SCUploadOptionsRecId](#SCUploadOptionsRecId)||<a href="RetailConnStoreConnectProfile.md" target="_blank">Main/RetailConnStoreConnectProfile</a>|
|[Server](#Server)||<a href="RetailConnStoreConnectProfile.md" target="_blank">Main/RetailConnStoreConnectProfile</a>|
|[Timeout](#Timeout)||<a href="RetailConnStoreConnectProfile.md" target="_blank">Main/RetailConnStoreConnectProfile</a>|
|[TransactionServiceProfileRecId](#TransactionServiceProfileRecId)||<a href="RetailConnStoreConnectProfile.md" target="_blank">Main/RetailConnStoreConnectProfile</a>|
|[Relationship_StoreConnectConfigRelationRelationshipId](#Relationship_StoreConnectConfigRelationRelationshipId)||<a href="RetailConnStoreConnectProfile.md" target="_blank">Main/RetailConnStoreConnectProfile</a>|
|[Relationship_TransactionServiceRelationRelationshipId](#Relationship_TransactionServiceRelationRelationshipId)||<a href="RetailConnStoreConnectProfile.md" target="_blank">Main/RetailConnStoreConnectProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/RetailConnStoreConnectProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnStoreConnectProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/RetailConnStoreConnectProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NoIPSec name="NoIPSec">NoIPSec</a>

First included in: Main/RetailConnStoreConnectProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NoIPSec attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Port name="Port">Port</a>

First included in: Main/RetailConnStoreConnectProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Port attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PreferIPV6 name="PreferIPV6">PreferIPV6</a>

First included in: Main/RetailConnStoreConnectProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreferIPV6 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SCUploadOptionsRecId name="SCUploadOptionsRecId">SCUploadOptionsRecId</a>

First included in: Main/RetailConnStoreConnectProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SCUploadOptionsRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Server name="Server">Server</a>

First included in: Main/RetailConnStoreConnectProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Server attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Timeout name="Timeout">Timeout</a>

First included in: Main/RetailConnStoreConnectProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Timeout attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransactionServiceProfileRecId name="TransactionServiceProfileRecId">TransactionServiceProfileRecId</a>

First included in: Main/RetailConnStoreConnectProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionServiceProfileRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_StoreConnectConfigRelationRelationshipId name="Relationship_StoreConnectConfigRelationRelationshipId">Relationship_StoreConnectConfigRelationRelationshipId</a>

First included in: Main/RetailConnStoreConnectProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StoreConnectConfigRelationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/RetailConnStoreConnectUploadOptions.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailConnStoreConnectUploadOptions.cdm.json/RetailConnStoreConnectUploadOptions</a></td><td><a href="../Parameter/RetailConnStoreConnectUploadOptions.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransactionServiceRelationRelationshipId name="Relationship_TransactionServiceRelationRelationshipId">Relationship_TransactionServiceRelationRelationshipId</a>

First included in: Main/RetailConnStoreConnectProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransactionServiceRelationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/RetailTransactionServiceProfile.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailTransactionServiceProfile.cdm.json/RetailTransactionServiceProfile</a></td><td><a href="../Parameter/RetailTransactionServiceProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

---
title: SIGSignatureLog - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# SIGSignatureLog

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Transaction/SIGSignatureLog.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SIGSignatureLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[AuditLogRef](#AuditLogRef)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[Comment](#Comment)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[DocumentClassId](#DocumentClassId)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[LoginId](#LoginId)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[ReasonCode](#ReasonCode)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[RefRecId](#RefRecId)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[RefTableId](#RefTableId)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[SerializedDocument](#SerializedDocument)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[SignatureDateTime](#SignatureDateTime)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[SigneeId](#SigneeId)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[SigningCertificate](#SigningCertificate)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[SigningProvider](#SigningProvider)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[DataAreaId](#DataAreaId)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[Relationship_SIGReasonCodeRelationshipId](#Relationship_SIGReasonCodeRelationshipId)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[Relationship_SysDataBaseLogRelationshipId](#Relationship_SysDataBaseLogRelationshipId)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="SIGSignatureLog.md" target="_blank">Transaction/SIGSignatureLog</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SIGSignatureLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AuditLogRef name="AuditLogRef">AuditLogRef</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuditLogRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentClassId name="DocumentClassId">DocumentClassId</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentClassId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoginId name="LoginId">LoginId</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoginId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonCode name="ReasonCode">ReasonCode</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SerializedDocument name="SerializedDocument">SerializedDocument</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerializedDocument attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureDateTime name="SignatureDateTime">SignatureDateTime</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SigneeId name="SigneeId">SigneeId</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SigneeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SigningCertificate name="SigningCertificate">SigningCertificate</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SigningCertificate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SigningProvider name="SigningProvider">SigningProvider</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SigningProvider attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SIGReasonCodeRelationshipId name="Relationship_SIGReasonCodeRelationshipId">Relationship_SIGReasonCodeRelationshipId</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SIGReasonCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SIGReasonCode.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Transaction/SIGReasonCode.cdm.json/SIGReasonCode</a></td><td><a href="SIGReasonCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysDataBaseLogRelationshipId name="Relationship_SysDataBaseLogRelationshipId">Relationship_SysDataBaseLogRelationshipId</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysDataBaseLogRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SysDataBaseLog.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Transaction/SysDataBaseLog.cdm.json/SysDataBaseLog</a></td><td><a href="SysDataBaseLog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/SIGSignatureLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

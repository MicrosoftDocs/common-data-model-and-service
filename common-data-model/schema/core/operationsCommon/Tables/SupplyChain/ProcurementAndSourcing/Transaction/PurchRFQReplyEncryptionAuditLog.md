---
title: PurchRFQReplyEncryptionAuditLog in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Request for quotation reply encryption activity in Transaction

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/PurchRFQReplyEncryptionAuditLog.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQReplyEncryptionAuditLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request for quotation reply encryption activity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[PurchRFQReplyTable](#PurchRFQReplyTable)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[RFQId](#RFQId)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[Action](#Action)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[ActionCaller](#ActionCaller)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[EncryptionActivity](#EncryptionActivity)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[UserId](#UserId)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[UserSid](#UserSid)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[UserObjectId](#UserObjectId)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[UserNetworkAlias](#UserNetworkAlias)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[UserNetworkDomain](#UserNetworkDomain)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[UserIdentityProvider](#UserIdentityProvider)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[EncryptionKeyName](#EncryptionKeyName)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[EncryptionKeyVaultUrl](#EncryptionKeyVaultUrl)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[EncryptionKeyIdentifier](#EncryptionKeyIdentifier)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[Relationship_PurchRFQReplyTableRelationshipId](#Relationship_PurchRFQReplyTableRelationshipId)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchRFQReplyEncryptionAuditLog.md" target="_blank">Transaction/PurchRFQReplyEncryptionAuditLog</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQReplyEncryptionAuditLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchRFQReplyTable name="PurchRFQReplyTable">PurchRFQReplyTable</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchRFQReplyTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RFQId name="RFQId">RFQId</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Action name="Action">Action</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Action attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ActionCaller name="ActionCaller">ActionCaller</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionCaller attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EncryptionActivity name="EncryptionActivity">EncryptionActivity</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EncryptionActivity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#UserId name="UserId">UserId</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserSid name="UserSid">UserSid</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserSid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserObjectId name="UserObjectId">UserObjectId</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserObjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.readOnly**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserNetworkAlias name="UserNetworkAlias">UserNetworkAlias</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserNetworkAlias attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserNetworkDomain name="UserNetworkDomain">UserNetworkDomain</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserNetworkDomain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserIdentityProvider name="UserIdentityProvider">UserIdentityProvider</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserIdentityProvider attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EncryptionKeyName name="EncryptionKeyName">EncryptionKeyName</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EncryptionKeyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EncryptionKeyVaultUrl name="EncryptionKeyVaultUrl">EncryptionKeyVaultUrl</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EncryptionKeyVaultUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EncryptionKeyIdentifier name="EncryptionKeyIdentifier">EncryptionKeyIdentifier</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EncryptionKeyIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

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

### <a href=#Relationship_PurchRFQReplyTableRelationshipId name="Relationship_PurchRFQReplyTableRelationshipId">Relationship_PurchRFQReplyTableRelationshipId</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRFQReplyTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PurchRFQReplyTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQReplyTable.cdm.json/PurchRFQReplyTable</a></td><td><a href="../WorksheetHeader/PurchRFQReplyTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/PurchRFQReplyEncryptionAuditLog (this entity)  

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

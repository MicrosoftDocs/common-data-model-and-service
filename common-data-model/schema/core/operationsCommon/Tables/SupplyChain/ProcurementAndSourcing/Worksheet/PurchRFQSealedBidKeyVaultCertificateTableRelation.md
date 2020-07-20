---
title: PurchRFQSealedBidKeyVaultCertificateTableRelation in Worksheet - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Link between the request for quotation reply and Key vault secret in Worksheet(PurchRFQSealedBidKeyVaultCertificateTableRelation)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQSealedBidKeyVaultCertificateTableRelation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Link between the request for quotation reply and Key vault secret</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchRFQSealedBidKeyVaultCertificateTableRelation.md" target="_blank">Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation</a>|
|[PurchRFQReplyTable](#PurchRFQReplyTable)||<a href="PurchRFQSealedBidKeyVaultCertificateTableRelation.md" target="_blank">Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation</a>|
|[KeyVaultCertificateTable](#KeyVaultCertificateTable)||<a href="PurchRFQSealedBidKeyVaultCertificateTableRelation.md" target="_blank">Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchRFQSealedBidKeyVaultCertificateTableRelation.md" target="_blank">Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation</a>|
|[Relationship_PurchRFQReplyTableRelationshipId](#Relationship_PurchRFQReplyTableRelationshipId)||<a href="PurchRFQSealedBidKeyVaultCertificateTableRelation.md" target="_blank">Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation</a>|
|[Relationship_KeyVaultCertificateTableRelationshipId](#Relationship_KeyVaultCertificateTableRelationshipId)||<a href="PurchRFQSealedBidKeyVaultCertificateTableRelation.md" target="_blank">Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchRFQSealedBidKeyVaultCertificateTableRelation.md" target="_blank">Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQSealedBidKeyVaultCertificateTableRelation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchRFQReplyTable name="PurchRFQReplyTable">PurchRFQReplyTable</a>

First included in: Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation (this entity)  

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

### <a href=#KeyVaultCertificateTable name="KeyVaultCertificateTable">KeyVaultCertificateTable</a>

First included in: Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyVaultCertificateTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation (this entity)  

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

First included in: Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation (this entity)  

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

### <a href=#Relationship_KeyVaultCertificateTableRelationshipId name="Relationship_KeyVaultCertificateTableRelationshipId">Relationship_KeyVaultCertificateTableRelationshipId</a>

First included in: Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_KeyVaultCertificateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.cdm.json/KeyVaultCertificateTable</a></td><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Worksheet/PurchRFQSealedBidKeyVaultCertificateTableRelation (this entity)  

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

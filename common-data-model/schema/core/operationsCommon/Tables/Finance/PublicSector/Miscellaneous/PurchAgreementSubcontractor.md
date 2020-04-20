---
title: PurchAgreementSubcontractor - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# PurchAgreementSubcontractor

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/PublicSector/Miscellaneous/PurchAgreementSubcontractor.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchAgreementSubcontractor/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[Description](#Description)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[EndDate](#EndDate)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[MaximumAmount_PSN](#MaximumAmount_PSN)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[PercentParticipation](#PercentParticipation)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[PurchAgreementHeader](#PurchAgreementHeader)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[PurchAgreementVendorType_PSN](#PurchAgreementVendorType_PSN)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[StartDate](#StartDate)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[SubcontractorID](#SubcontractorID)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[VendAccount_PSN](#VendAccount_PSN)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[VendBankAccountDataAreaID_PSN](#VendBankAccountDataAreaID_PSN)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[VendBankAccountID_PSN](#VendBankAccountID_PSN)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[VendTable](#VendTable)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[Relationship_PurchAgreementHeaderRelationshipId](#Relationship_PurchAgreementHeaderRelationshipId)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[Relationship_SubContractorRelationshipId](#Relationship_SubContractorRelationshipId)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[Relationship_VendBankAccountRelationshipId](#Relationship_VendBankAccountRelationshipId)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="PurchAgreementSubcontractor.md" target="_blank">Miscellaneous/PurchAgreementSubcontractor</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchAgreementSubcontractor/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#MaximumAmount_PSN name="MaximumAmount_PSN">MaximumAmount_PSN</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAmount_PSN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PercentParticipation name="PercentParticipation">PercentParticipation</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentParticipation attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchAgreementHeader name="PurchAgreementHeader">PurchAgreementHeader</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchAgreementHeader attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchAgreementVendorType_PSN name="PurchAgreementVendorType_PSN">PurchAgreementVendorType_PSN</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchAgreementVendorType_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SubcontractorID name="SubcontractorID">SubcontractorID</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubcontractorID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendAccount_PSN name="VendAccount_PSN">VendAccount_PSN</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendBankAccountDataAreaID_PSN name="VendBankAccountDataAreaID_PSN">VendBankAccountDataAreaID_PSN</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendBankAccountDataAreaID_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendBankAccountID_PSN name="VendBankAccountID_PSN">VendBankAccountID_PSN</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendBankAccountID_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendTable name="VendTable">VendTable</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchAgreementHeaderRelationshipId name="Relationship_PurchAgreementHeaderRelationshipId">Relationship_PurchAgreementHeaderRelationshipId</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchAgreementHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchAgreementHeader.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchAgreementHeader.cdm.json/PurchAgreementHeader</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchAgreementHeader.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SubContractorRelationshipId name="Relationship_SubContractorRelationshipId">Relationship_SubContractorRelationshipId</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SubContractorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendBankAccountRelationshipId name="Relationship_VendBankAccountRelationshipId">Relationship_VendBankAccountRelationshipId</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendBankAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendBankAccount.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendBankAccount.cdm.json/VendBankAccount</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendBankAccount.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Miscellaneous/PurchAgreementSubcontractor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

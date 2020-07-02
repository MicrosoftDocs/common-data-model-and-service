---
title: PurchaseRequisitionHeaderV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Purchase requisitions V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase requisitions V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RequisitionNumber](#RequisitionNumber)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[RequisitionName](#RequisitionName)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[PreparerRecId](#PreparerRecId)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[PreparerPersonnelNumber](#PreparerPersonnelNumber)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[RequisitionStatus](#RequisitionStatus)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[RequisitionPurpose](#RequisitionPurpose)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[DefaultRequestedDate](#DefaultRequestedDate)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[DefaultAccountingDate](#DefaultAccountingDate)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[DefaultBusinessJustificationRecId](#DefaultBusinessJustificationRecId)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[DefaultBusinessJustificationCode](#DefaultBusinessJustificationCode)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[DefaultBusinessJustificationDetails](#DefaultBusinessJustificationDetails)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[ProjectBuyingLegalEntityRecId](#ProjectBuyingLegalEntityRecId)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[ProjectBuyingLegalEntityId](#ProjectBuyingLegalEntityId)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[DefaultProjectId](#DefaultProjectId)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[IsPurchaseRequisitionOnHold](#IsPurchaseRequisitionOnHold)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[OnHoldExplanation](#OnHoldExplanation)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|
|[BackingTable_PurchReqTableRelationshipId](#BackingTable_PurchReqTableRelationshipId)||<a href="PurchaseRequisitionHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity</a>|

### <a href=#RequisitionNumber name="RequisitionNumber">RequisitionNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequisitionName name="RequisitionName">RequisitionName</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreparerRecId name="PreparerRecId">PreparerRecId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreparerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreparerPersonnelNumber name="PreparerPersonnelNumber">PreparerPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preparer</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreparerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Preparer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequisitionStatus name="RequisitionStatus">RequisitionStatus</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequisitionPurpose name="RequisitionPurpose">RequisitionPurpose</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRequestedDate name="DefaultRequestedDate">DefaultRequestedDate</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRequestedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultAccountingDate name="DefaultAccountingDate">DefaultAccountingDate</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultAccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBusinessJustificationRecId name="DefaultBusinessJustificationRecId">DefaultBusinessJustificationRecId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBusinessJustificationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBusinessJustificationCode name="DefaultBusinessJustificationCode">DefaultBusinessJustificationCode</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBusinessJustificationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBusinessJustificationDetails name="DefaultBusinessJustificationDetails">DefaultBusinessJustificationDetails</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBusinessJustificationDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectBuyingLegalEntityRecId name="ProjectBuyingLegalEntityRecId">ProjectBuyingLegalEntityRecId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectBuyingLegalEntityRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectBuyingLegalEntityId name="ProjectBuyingLegalEntityId">ProjectBuyingLegalEntityId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Buying legal entity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectBuyingLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Buying legal entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProjectId name="DefaultProjectId">DefaultProjectId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchaseRequisitionOnHold name="IsPurchaseRequisitionOnHold">IsPurchaseRequisitionOnHold</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchaseRequisitionOnHold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnHoldExplanation name="OnHoldExplanation">OnHoldExplanation</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHoldExplanation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchReqTableRelationshipId name="BackingTable_PurchReqTableRelationshipId">BackingTable_PurchReqTableRelationshipId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchReqTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchReqTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchReqTable.cdm.json/PurchReqTable</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchReqTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

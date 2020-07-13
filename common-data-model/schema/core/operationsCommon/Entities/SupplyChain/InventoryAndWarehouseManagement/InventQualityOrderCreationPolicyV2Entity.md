---
title: InventQualityOrderCreationPolicyV2Entity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Quality order creation policies V2 in InventoryAndWarehouseManagement(InventQualityOrderCreationPolicyV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quality order creation policies V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AcceptableQualityLevelPercentage](#AcceptableQualityLevelPercentage)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[AccountCode](#AccountCode)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[AccountRelation](#AccountRelation)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[BlockedDocumentationProcess](#BlockedDocumentationProcess)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[QualityOrderCreationDocumentationEvent](#QualityOrderCreationDocumentationEvent)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[OperationalSiteId](#OperationalSiteId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[ItemCode](#ItemCode)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[ItemRelation](#ItemRelation)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[ItemSamplingId](#ItemSamplingId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[QualityOrderCreationPolicyType](#QualityOrderCreationPolicyType)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[IsQualityOrderFailureCreatingQuantineOrder](#IsQualityOrderFailureCreatingQuantineOrder)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[IsQualityOrderCreationDisplayingMessage](#IsQualityOrderCreationDisplayingMessage)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[QualityOrderCreationDocumentationEventStage](#QualityOrderCreationDocumentationEventStage)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[QualityTestGroupId](#QualityTestGroupId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[EffectiveDateTime](#EffectiveDateTime)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[ExpirationDateTime](#ExpirationDateTime)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[WrkCtrCode](#WrkCtrCode)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[WrkCtrRelation](#WrkCtrRelation)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[VendorGroupId](#VendorGroupId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[CustomerGroupId](#CustomerGroupId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[QualityGroupId](#QualityGroupId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[OperationsResourceGroupId](#OperationsResourceGroupId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[OperationsResourceId](#OperationsResourceId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[RouteOperationId](#RouteOperationId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[RouteGroupId](#RouteGroupId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[AssociationCreationSequenceNumber](#AssociationCreationSequenceNumber)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[BackingTable_InventTestAssociationTableRelationshipId](#BackingTable_InventTestAssociationTableRelationshipId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventQualityOrderCreationPolicyV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity</a>|

### <a href=#AcceptableQualityLevelPercentage name="AcceptableQualityLevelPercentage">AcceptableQualityLevelPercentage</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptableQualityLevelPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCode name="AccountCode">AccountCode</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountRelation name="AccountRelation">AccountRelation</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BlockedDocumentationProcess name="BlockedDocumentationProcess">BlockedDocumentationProcess</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockedDocumentationProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityOrderCreationDocumentationEvent name="QualityOrderCreationDocumentationEvent">QualityOrderCreationDocumentationEvent</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityOrderCreationDocumentationEvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationalSiteId name="OperationalSiteId">OperationalSiteId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRelation name="ItemRelation">ItemRelation</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSamplingId name="ItemSamplingId">ItemSamplingId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSamplingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityOrderCreationPolicyType name="QualityOrderCreationPolicyType">QualityOrderCreationPolicyType</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityOrderCreationPolicyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQualityOrderFailureCreatingQuantineOrder name="IsQualityOrderFailureCreatingQuantineOrder">IsQualityOrderFailureCreatingQuantineOrder</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQualityOrderFailureCreatingQuantineOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQualityOrderCreationDisplayingMessage name="IsQualityOrderCreationDisplayingMessage">IsQualityOrderCreationDisplayingMessage</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQualityOrderCreationDisplayingMessage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityOrderCreationDocumentationEventStage name="QualityOrderCreationDocumentationEventStage">QualityOrderCreationDocumentationEventStage</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityOrderCreationDocumentationEventStage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestGroupId name="QualityTestGroupId">QualityTestGroupId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveDateTime name="EffectiveDateTime">EffectiveDateTime</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpirationDateTime name="ExpirationDateTime">ExpirationDateTime</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WrkCtrCode name="WrkCtrCode">WrkCtrCode</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WrkCtrCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WrkCtrRelation name="WrkCtrRelation">WrkCtrRelation</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WrkCtrRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorGroupId name="VendorGroupId">VendorGroupId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerGroupId name="CustomerGroupId">CustomerGroupId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityGroupId name="QualityGroupId">QualityGroupId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationsResourceGroupId name="OperationsResourceGroupId">OperationsResourceGroupId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsResourceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationsResourceId name="OperationsResourceId">OperationsResourceId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationId name="RouteOperationId">RouteOperationId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteGroupId name="RouteGroupId">RouteGroupId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssociationCreationSequenceNumber name="AssociationCreationSequenceNumber">AssociationCreationSequenceNumber</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociationCreationSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventTestAssociationTableRelationshipId name="BackingTable_InventTestAssociationTableRelationshipId">BackingTable_InventTestAssociationTableRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventTestAssociationTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventTestAssociationTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventTestAssociationTable.cdm.json/InventTestAssociationTable</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventTestAssociationTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderCreationPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

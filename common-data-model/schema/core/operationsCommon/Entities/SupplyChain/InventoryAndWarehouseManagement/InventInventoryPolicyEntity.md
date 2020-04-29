---
title: InventInventoryPolicyEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Item model group inventory policies

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventInventoryPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item model group inventory policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PolicyId](#PolicyId)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[IsNegativePhysicalInventoryAllowed](#IsNegativePhysicalInventoryAllowed)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[IsNegativeFinancialInventoryAllowed](#IsNegativeFinancialInventoryAllowed)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[AreQuarantineManagementProcessesEnabled](#AreQuarantineManagementProcessesEnabled)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[IsRegistrationRequired](#IsRegistrationRequired)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[IsReceivingRequired](#IsReceivingRequired)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[IsPickingRequired](#IsPickingRequired)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[IsDeductionRequired](#IsDeductionRequired)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[WillInventoryReservationUseFIFOReservation](#WillInventoryReservationUseFIFOReservation)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[ShouldFIFODateReserveBackwards](#ShouldFIFODateReserveBackwards)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[DefaultSalesReservationMode](#DefaultSalesReservationMode)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[WillInventoryReservationReserveSameBatch](#WillInventoryReservationReserveSameBatch)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[ShouldConsolidateSameBatchReservations](#ShouldConsolidateSameBatchReservations)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[WillInventoryReservationUseFEFOReservation](#WillInventoryReservationUseFEFOReservation)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[FEFODateControlledInventoryReservationCriteria](#FEFODateControlledInventoryReservationCriteria)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[BatchDispositionCode](#BatchDispositionCode)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[WillRegistrationProvideVendorBatchDetails](#WillRegistrationProvideVendorBatchDetails)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[ApprovedVendorCheckMethod](#ApprovedVendorCheckMethod)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[Relationship_CostFlowAssumptionPolicyRelationshipId](#Relationship_CostFlowAssumptionPolicyRelationshipId)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[BackingTable_InventModelGroupRelationshipId](#BackingTable_InventModelGroupRelationshipId)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventInventoryPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryPolicyEntity</a>|

### <a href=#PolicyId name="PolicyId">PolicyId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsNegativePhysicalInventoryAllowed name="IsNegativePhysicalInventoryAllowed">IsNegativePhysicalInventoryAllowed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNegativePhysicalInventoryAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsNegativeFinancialInventoryAllowed name="IsNegativeFinancialInventoryAllowed">IsNegativeFinancialInventoryAllowed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNegativeFinancialInventoryAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreQuarantineManagementProcessesEnabled name="AreQuarantineManagementProcessesEnabled">AreQuarantineManagementProcessesEnabled</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreQuarantineManagementProcessesEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRegistrationRequired name="IsRegistrationRequired">IsRegistrationRequired</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRegistrationRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReceivingRequired name="IsReceivingRequired">IsReceivingRequired</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReceivingRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingRequired name="IsPickingRequired">IsPickingRequired</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeductionRequired name="IsDeductionRequired">IsDeductionRequired</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeductionRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInventoryReservationUseFIFOReservation name="WillInventoryReservationUseFIFOReservation">WillInventoryReservationUseFIFOReservation</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInventoryReservationUseFIFOReservation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShouldFIFODateReserveBackwards name="ShouldFIFODateReserveBackwards">ShouldFIFODateReserveBackwards</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShouldFIFODateReserveBackwards attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesReservationMode name="DefaultSalesReservationMode">DefaultSalesReservationMode</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesReservationMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInventoryReservationReserveSameBatch name="WillInventoryReservationReserveSameBatch">WillInventoryReservationReserveSameBatch</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInventoryReservationReserveSameBatch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShouldConsolidateSameBatchReservations name="ShouldConsolidateSameBatchReservations">ShouldConsolidateSameBatchReservations</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShouldConsolidateSameBatchReservations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInventoryReservationUseFEFOReservation name="WillInventoryReservationUseFEFOReservation">WillInventoryReservationUseFEFOReservation</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInventoryReservationUseFEFOReservation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FEFODateControlledInventoryReservationCriteria name="FEFODateControlledInventoryReservationCriteria">FEFODateControlledInventoryReservationCriteria</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEFODateControlledInventoryReservationCriteria attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchDispositionCode name="BatchDispositionCode">BatchDispositionCode</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchDispositionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRegistrationProvideVendorBatchDetails name="WillRegistrationProvideVendorBatchDetails">WillRegistrationProvideVendorBatchDetails</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRegistrationProvideVendorBatchDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApprovedVendorCheckMethod name="ApprovedVendorCheckMethod">ApprovedVendorCheckMethod</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovedVendorCheckMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CostFlowAssumptionPolicyRelationshipId name="Relationship_CostFlowAssumptionPolicyRelationshipId">Relationship_CostFlowAssumptionPolicyRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CostFlowAssumptionPolicyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventModelGroupRelationshipId name="BackingTable_InventModelGroupRelationshipId">BackingTable_InventModelGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventModelGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventModelGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventModelGroup.cdm.json/InventModelGroup</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventModelGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryPolicyEntity (this entity)  

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

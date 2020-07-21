---
title: PurchProcurementDocumentEntryPolicyEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Procurement type document entry policies in ProcurementAndSourcing(PurchProcurementDocumentEntryPolicyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement type document entry policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AreFactBoxesAutomaticallyRecalculated](#AreFactBoxesAutomaticallyRecalculated)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges](#WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[WillDocumentEntryAutomaticallyAllocateLineLevelCharges](#WillDocumentEntryAutomaticallyAllocateLineLevelCharges)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[WillDocumentEntryRecordPriceDetails](#WillDocumentEntryRecordPriceDetails)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[WillDocumentEntryDisplayPriceMarginAlerts](#WillDocumentEntryDisplayPriceMarginAlerts)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[ArePurchaseCyclesActivated](#ArePurchaseCyclesActivated)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[InvoicedPurchaseOrderMaintenanceRule](#InvoicedPurchaseOrderMaintenanceRule)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[IsChangeManagementActivated](#IsChangeManagementActivated)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[IsChangeManagementActivationOverridable](#IsChangeManagementActivationOverridable)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[IsIntercompanyPurchaseOrderLineAgreementLineMatched](#IsIntercompanyPurchaseOrderLineAgreementLineMatched)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[IsSentRFQLocked](#IsSentRFQLocked)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[IsVendorInformationTransferBeingPrompted](#IsVendorInformationTransferBeingPrompted)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[LineLevelDiscountCalculationRule](#LineLevelDiscountCalculationRule)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[PriceMarginThresholdRule](#PriceMarginThresholdRule)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[TradeAgreementSearchDateType](#TradeAgreementSearchDateType)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[BackingTable_PurchParametersRelationshipId](#BackingTable_PurchParametersRelationshipId)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchProcurementDocumentEntryPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity</a>|

### <a href=#AreFactBoxesAutomaticallyRecalculated name="AreFactBoxesAutomaticallyRecalculated">AreFactBoxesAutomaticallyRecalculated</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreFactBoxesAutomaticallyRecalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges name="WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges">WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDocumentEntryAutomaticallyAllocateLineLevelCharges name="WillDocumentEntryAutomaticallyAllocateLineLevelCharges">WillDocumentEntryAutomaticallyAllocateLineLevelCharges</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDocumentEntryAutomaticallyAllocateLineLevelCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDocumentEntryRecordPriceDetails name="WillDocumentEntryRecordPriceDetails">WillDocumentEntryRecordPriceDetails</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDocumentEntryRecordPriceDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDocumentEntryDisplayPriceMarginAlerts name="WillDocumentEntryDisplayPriceMarginAlerts">WillDocumentEntryDisplayPriceMarginAlerts</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDocumentEntryDisplayPriceMarginAlerts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePurchaseCyclesActivated name="ArePurchaseCyclesActivated">ArePurchaseCyclesActivated</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseCyclesActivated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicedPurchaseOrderMaintenanceRule name="InvoicedPurchaseOrderMaintenanceRule">InvoicedPurchaseOrderMaintenanceRule</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicedPurchaseOrderMaintenanceRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsChangeManagementActivated name="IsChangeManagementActivated">IsChangeManagementActivated</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsChangeManagementActivated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsChangeManagementActivationOverridable name="IsChangeManagementActivationOverridable">IsChangeManagementActivationOverridable</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsChangeManagementActivationOverridable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseOrderLineAgreementLineMatched name="IsIntercompanyPurchaseOrderLineAgreementLineMatched">IsIntercompanyPurchaseOrderLineAgreementLineMatched</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseOrderLineAgreementLineMatched attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSentRFQLocked name="IsSentRFQLocked">IsSentRFQLocked</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSentRFQLocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVendorInformationTransferBeingPrompted name="IsVendorInformationTransferBeingPrompted">IsVendorInformationTransferBeingPrompted</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVendorInformationTransferBeingPrompted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineLevelDiscountCalculationRule name="LineLevelDiscountCalculationRule">LineLevelDiscountCalculationRule</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineLevelDiscountCalculationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceMarginThresholdRule name="PriceMarginThresholdRule">PriceMarginThresholdRule</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceMarginThresholdRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAgreementSearchDateType name="TradeAgreementSearchDateType">TradeAgreementSearchDateType</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAgreementSearchDateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchParametersRelationshipId name="BackingTable_PurchParametersRelationshipId">BackingTable_PurchParametersRelationshipId</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchParameters.cdm.json/PurchParameters</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentEntryPolicyEntity (this entity)  

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

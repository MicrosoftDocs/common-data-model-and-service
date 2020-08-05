---
title: TMSTransportationManagementParametersEntity in Transportation - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Transportation management parameters in Transportation(TMSTransportationManagementParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSTransportationManagementParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transportation management parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WillPurchaseOrderEntryAutomaticallyCreateLoad](#WillPurchaseOrderEntryAutomaticallyCreateLoad)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[WillSalesOrderEntryAutomaticallyCreateLoad](#WillSalesOrderEntryAutomaticallyCreateLoad)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[WillTransferOrderEntryAutomaticallyCreateLoad](#WillTransferOrderEntryAutomaticallyCreateLoad)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[BOLCarrierRoleRecId](#BOLCarrierRoleRecId)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[DefaultCarrierAppointmentDurationMinutes](#DefaultCarrierAppointmentDurationMinutes)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[DefaultVendorInvoiceReconciliationAttachmentName](#DefaultVendorInvoiceReconciliationAttachmentName)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[DefaultVendorInvoiceReconciliationAttachmentTypeCode](#DefaultVendorInvoiceReconciliationAttachmentTypeCode)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[WillLoadRatingApplyDirectDeliverySalesCharge](#WillLoadRatingApplyDirectDeliverySalesCharge)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[DriverCheckoutIntervalMinutes](#DriverCheckoutIntervalMinutes)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[IsVendorInvoiceWorkflowEnabled](#IsVendorInvoiceWorkflowEnabled)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[FreightBillTransactionText](#FreightBillTransactionText)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[IsDynamicRoutePlanningEnabled](#IsDynamicRoutePlanningEnabled)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[LoadAttachmentTypeCode](#LoadAttachmentTypeCode)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[WillVendorInvoiceReceiptAutomaticallyReconcileFreightBill](#WillVendorInvoiceReceiptAutomaticallyReconcileFreightBill)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[FreightBillReconciliationIntervalSeconds](#FreightBillReconciliationIntervalSeconds)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[WillLoadPlanningShipmentConfirmationPromptForShipmentDate](#WillLoadPlanningShipmentConfirmationPromptForShipmentDate)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[ParametersKey](#ParametersKey)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[WillShipmentsCreateLoads](#WillShipmentsCreateLoads)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[PortTransportationHubTypeId](#PortTransportationHubTypeId)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[WillVendorInvoiceApprovalAutomaticallyPostVendorInvoiceJournal](#WillVendorInvoiceApprovalAutomaticallyPostVendorInvoiceJournal)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[VendorInvoiceJournalName](#VendorInvoiceJournalName)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[VendorInvoiceWorkflowUserId](#VendorInvoiceWorkflowUserId)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[IsFreightBillReconciliationEnabled](#IsFreightBillReconciliationEnabled)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[AreFreightBillsCreated](#AreFreightBillsCreated)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[IsMasterBillOfLadingCreatedForMultipleShipmentLoads](#IsMasterBillOfLadingCreatedForMultipleShipmentLoads)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[WillLoadPlanningSeparatelyPostTransferOrderShipmentConfirmations](#WillLoadPlanningSeparatelyPostTransferOrderShipmentConfirmations)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[BillOfLadingThirdPartyShippingCarrierLogisticsLocationRolePurpose](#BillOfLadingThirdPartyShippingCarrierLogisticsLocationRolePurpose)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[BackingTable_TMSParametersRelationshipId](#BackingTable_TMSParametersRelationshipId)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSTransportationManagementParametersEntity.md" target="_blank">Transportation/TMSTransportationManagementParametersEntity</a>|

### <a href=#WillPurchaseOrderEntryAutomaticallyCreateLoad name="WillPurchaseOrderEntryAutomaticallyCreateLoad">WillPurchaseOrderEntryAutomaticallyCreateLoad</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchaseOrderEntryAutomaticallyCreateLoad attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesOrderEntryAutomaticallyCreateLoad name="WillSalesOrderEntryAutomaticallyCreateLoad">WillSalesOrderEntryAutomaticallyCreateLoad</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesOrderEntryAutomaticallyCreateLoad attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTransferOrderEntryAutomaticallyCreateLoad name="WillTransferOrderEntryAutomaticallyCreateLoad">WillTransferOrderEntryAutomaticallyCreateLoad</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTransferOrderEntryAutomaticallyCreateLoad attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLCarrierRoleRecId name="BOLCarrierRoleRecId">BOLCarrierRoleRecId</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLCarrierRoleRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCarrierAppointmentDurationMinutes name="DefaultCarrierAppointmentDurationMinutes">DefaultCarrierAppointmentDurationMinutes</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCarrierAppointmentDurationMinutes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVendorInvoiceReconciliationAttachmentName name="DefaultVendorInvoiceReconciliationAttachmentName">DefaultVendorInvoiceReconciliationAttachmentName</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVendorInvoiceReconciliationAttachmentName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVendorInvoiceReconciliationAttachmentTypeCode name="DefaultVendorInvoiceReconciliationAttachmentTypeCode">DefaultVendorInvoiceReconciliationAttachmentTypeCode</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVendorInvoiceReconciliationAttachmentTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillLoadRatingApplyDirectDeliverySalesCharge name="WillLoadRatingApplyDirectDeliverySalesCharge">WillLoadRatingApplyDirectDeliverySalesCharge</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillLoadRatingApplyDirectDeliverySalesCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DriverCheckoutIntervalMinutes name="DriverCheckoutIntervalMinutes">DriverCheckoutIntervalMinutes</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DriverCheckoutIntervalMinutes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVendorInvoiceWorkflowEnabled name="IsVendorInvoiceWorkflowEnabled">IsVendorInvoiceWorkflowEnabled</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVendorInvoiceWorkflowEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightBillTransactionText name="FreightBillTransactionText">FreightBillTransactionText</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightBillTransactionText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDynamicRoutePlanningEnabled name="IsDynamicRoutePlanningEnabled">IsDynamicRoutePlanningEnabled</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDynamicRoutePlanningEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadAttachmentTypeCode name="LoadAttachmentTypeCode">LoadAttachmentTypeCode</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadAttachmentTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillVendorInvoiceReceiptAutomaticallyReconcileFreightBill name="WillVendorInvoiceReceiptAutomaticallyReconcileFreightBill">WillVendorInvoiceReceiptAutomaticallyReconcileFreightBill</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillVendorInvoiceReceiptAutomaticallyReconcileFreightBill attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightBillReconciliationIntervalSeconds name="FreightBillReconciliationIntervalSeconds">FreightBillReconciliationIntervalSeconds</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightBillReconciliationIntervalSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillLoadPlanningShipmentConfirmationPromptForShipmentDate name="WillLoadPlanningShipmentConfirmationPromptForShipmentDate">WillLoadPlanningShipmentConfirmationPromptForShipmentDate</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillLoadPlanningShipmentConfirmationPromptForShipmentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParametersKey name="ParametersKey">ParametersKey</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParametersKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillShipmentsCreateLoads name="WillShipmentsCreateLoads">WillShipmentsCreateLoads</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillShipmentsCreateLoads attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PortTransportationHubTypeId name="PortTransportationHubTypeId">PortTransportationHubTypeId</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PortTransportationHubTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillVendorInvoiceApprovalAutomaticallyPostVendorInvoiceJournal name="WillVendorInvoiceApprovalAutomaticallyPostVendorInvoiceJournal">WillVendorInvoiceApprovalAutomaticallyPostVendorInvoiceJournal</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillVendorInvoiceApprovalAutomaticallyPostVendorInvoiceJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceJournalName name="VendorInvoiceJournalName">VendorInvoiceJournalName</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceWorkflowUserId name="VendorInvoiceWorkflowUserId">VendorInvoiceWorkflowUserId</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceWorkflowUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFreightBillReconciliationEnabled name="IsFreightBillReconciliationEnabled">IsFreightBillReconciliationEnabled</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFreightBillReconciliationEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreFreightBillsCreated name="AreFreightBillsCreated">AreFreightBillsCreated</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreFreightBillsCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMasterBillOfLadingCreatedForMultipleShipmentLoads name="IsMasterBillOfLadingCreatedForMultipleShipmentLoads">IsMasterBillOfLadingCreatedForMultipleShipmentLoads</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMasterBillOfLadingCreatedForMultipleShipmentLoads attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillLoadPlanningSeparatelyPostTransferOrderShipmentConfirmations name="WillLoadPlanningSeparatelyPostTransferOrderShipmentConfirmations">WillLoadPlanningSeparatelyPostTransferOrderShipmentConfirmations</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillLoadPlanningSeparatelyPostTransferOrderShipmentConfirmations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillOfLadingThirdPartyShippingCarrierLogisticsLocationRolePurpose name="BillOfLadingThirdPartyShippingCarrierLogisticsLocationRolePurpose">BillOfLadingThirdPartyShippingCarrierLogisticsLocationRolePurpose</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfLadingThirdPartyShippingCarrierLogisticsLocationRolePurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TMSParametersRelationshipId name="BackingTable_TMSParametersRelationshipId">BackingTable_TMSParametersRelationshipId</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Parameter/TMSParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Parameter/TMSParameters.cdm.json/TMSParameters</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Parameter/TMSParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSTransportationManagementParametersEntity (this entity)  

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

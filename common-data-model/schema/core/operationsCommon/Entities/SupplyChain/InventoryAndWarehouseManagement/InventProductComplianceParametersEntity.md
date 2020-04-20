---
title: InventProductComplianceParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# InventProductComplianceParametersEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventProductComplianceParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductComplianceAdministratorUserId](#ProductComplianceAdministratorUserId)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[DefaultProductDataSheetValidityDays](#DefaultProductDataSheetValidityDays)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[DefaultExpiryAdviceDays](#DefaultExpiryAdviceDays)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[AnnualCalculationBasisStartDate](#AnnualCalculationBasisStartDate)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[AnnualCalculationBasisEndDate](#AnnualCalculationBasisEndDate)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[WillSalesOrderEntryIssueRegulationWarning](#WillSalesOrderEntryIssueRegulationWarning)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[WillPurchaseOrderEntryIssueRegulationWarning](#WillPurchaseOrderEntryIssueRegulationWarning)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[WillSalesPackingSlipPostingIssueRegulationWarning](#WillSalesPackingSlipPostingIssueRegulationWarning)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[WillSalesPackingSlipPrintingIncludeProductSafetyDataSheet](#WillSalesPackingSlipPrintingIncludeProductSafetyDataSheet)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[WillExpiredProductSafetyDataSheetPreventSalesPackingSlipProcessing](#WillExpiredProductSafetyDataSheetPreventSalesPackingSlipProcessing)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[EffectiveDayBasisType](#EffectiveDayBasisType)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[WillProductSafetyDataSheetModificationRequireReasonEntry](#WillProductSafetyDataSheetModificationRequireReasonEntry)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[WillSalesProcessesCreateExpiredProductSafetyDataSheetAlerts](#WillSalesProcessesCreateExpiredProductSafetyDataSheetAlerts)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[WillSalesProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts](#WillSalesProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[WillPurchaseProcessesCreateExpiredProductSafetyDataSheetAlerts](#WillPurchaseProcessesCreateExpiredProductSafetyDataSheetAlerts)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[WillPurchaseProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts](#WillPurchaseProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[BackingTable_PdsMRCParametersRelationshipId](#BackingTable_PdsMRCParametersRelationshipId)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventProductComplianceParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductComplianceParametersEntity</a>|

### <a href=#ProductComplianceAdministratorUserId name="ProductComplianceAdministratorUserId">ProductComplianceAdministratorUserId</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductComplianceAdministratorUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProductDataSheetValidityDays name="DefaultProductDataSheetValidityDays">DefaultProductDataSheetValidityDays</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductDataSheetValidityDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultExpiryAdviceDays name="DefaultExpiryAdviceDays">DefaultExpiryAdviceDays</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultExpiryAdviceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnnualCalculationBasisStartDate name="AnnualCalculationBasisStartDate">AnnualCalculationBasisStartDate</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnnualCalculationBasisStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnnualCalculationBasisEndDate name="AnnualCalculationBasisEndDate">AnnualCalculationBasisEndDate</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnnualCalculationBasisEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesOrderEntryIssueRegulationWarning name="WillSalesOrderEntryIssueRegulationWarning">WillSalesOrderEntryIssueRegulationWarning</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesOrderEntryIssueRegulationWarning attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchaseOrderEntryIssueRegulationWarning name="WillPurchaseOrderEntryIssueRegulationWarning">WillPurchaseOrderEntryIssueRegulationWarning</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchaseOrderEntryIssueRegulationWarning attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesPackingSlipPostingIssueRegulationWarning name="WillSalesPackingSlipPostingIssueRegulationWarning">WillSalesPackingSlipPostingIssueRegulationWarning</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesPackingSlipPostingIssueRegulationWarning attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesPackingSlipPrintingIncludeProductSafetyDataSheet name="WillSalesPackingSlipPrintingIncludeProductSafetyDataSheet">WillSalesPackingSlipPrintingIncludeProductSafetyDataSheet</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesPackingSlipPrintingIncludeProductSafetyDataSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillExpiredProductSafetyDataSheetPreventSalesPackingSlipProcessing name="WillExpiredProductSafetyDataSheetPreventSalesPackingSlipProcessing">WillExpiredProductSafetyDataSheetPreventSalesPackingSlipProcessing</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillExpiredProductSafetyDataSheetPreventSalesPackingSlipProcessing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveDayBasisType name="EffectiveDayBasisType">EffectiveDayBasisType</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveDayBasisType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductSafetyDataSheetModificationRequireReasonEntry name="WillProductSafetyDataSheetModificationRequireReasonEntry">WillProductSafetyDataSheetModificationRequireReasonEntry</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductSafetyDataSheetModificationRequireReasonEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesProcessesCreateExpiredProductSafetyDataSheetAlerts name="WillSalesProcessesCreateExpiredProductSafetyDataSheetAlerts">WillSalesProcessesCreateExpiredProductSafetyDataSheetAlerts</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesProcessesCreateExpiredProductSafetyDataSheetAlerts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts name="WillSalesProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts">WillSalesProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchaseProcessesCreateExpiredProductSafetyDataSheetAlerts name="WillPurchaseProcessesCreateExpiredProductSafetyDataSheetAlerts">WillPurchaseProcessesCreateExpiredProductSafetyDataSheetAlerts</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchaseProcessesCreateExpiredProductSafetyDataSheetAlerts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchaseProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts name="WillPurchaseProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts">WillPurchaseProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchaseProcessesCreateExpiryAdvicePeriodProductSafetyDataSheetAlerts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PdsMRCParametersRelationshipId name="BackingTable_PdsMRCParametersRelationshipId">BackingTable_PdsMRCParametersRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PdsMRCParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Parameter/PdsMRCParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Parameter/PdsMRCParameters.cdm.json/PdsMRCParameters</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Parameter/PdsMRCParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductComplianceParametersEntity (this entity)  

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

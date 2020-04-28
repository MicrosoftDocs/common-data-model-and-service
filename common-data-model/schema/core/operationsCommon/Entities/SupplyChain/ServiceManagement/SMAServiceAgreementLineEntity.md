---
title: SMAServiceAgreementLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Service agreement lines

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ServiceManagement/SMAServiceAgreementLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Service agreement lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[IsLineSuspended](#IsLineSuspended)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ItemSetup](#ItemSetup)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ItemUnitSymbol](#ItemUnitSymbol)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[LineDescription](#LineDescription)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[LineNote](#LineNote)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[PeriodEndDate](#PeriodEndDate)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[PeriodStartDate](#PeriodStartDate)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProjectActivityNumber](#ProjectActivityNumber)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProjectCustomerAccountNumber](#ProjectCustomerAccountNumber)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProjectSalesCurrencyCode](#ProjectSalesCurrencyCode)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProjectId](#ProjectId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProjectLinePropertyId](#ProjectLinePropertyId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProjectTaxGroupCode](#ProjectTaxGroupCode)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProjectTaxItemGroupCode](#ProjectTaxItemGroupCode)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProjectDescription](#ProjectDescription)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceAgreementId](#ServiceAgreementId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceIntervalId](#ServiceIntervalId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceObjectId](#ServiceObjectId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceObjectRelationId](#ServiceObjectRelationId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceTaskId](#ServiceTaskId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceEndBeforeTime](#ServiceEndBeforeTime)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceStartAfterTime](#ServiceStartAfterTime)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceTimeWindowId](#ServiceTimeWindowId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceTransactionType](#ServiceTransactionType)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[WorkerPersonnelNumber](#WorkerPersonnelNumber)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceInventoryAgreementSiteId](#ServiceInventoryAgreementSiteId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceInventoryAgreementWarehouseId](#ServiceInventoryAgreementWarehouseId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ServiceInventoryAgreementWarehouseLocationId](#ServiceInventoryAgreementWarehouseLocationId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[Hours](#Hours)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ItemQuantity](#ItemQuantity)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[ExpenseQuantity](#ExpenseQuantity)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[Relationship_ServiceAgreementHeaderRelationshipId](#Relationship_ServiceAgreementHeaderRelationshipId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[Relationship_ProjectRelationshipId](#Relationship_ProjectRelationshipId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[Relationship_ReleasedProductV2RelationshipId](#Relationship_ReleasedProductV2RelationshipId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[Relationship_UnitRelationshipId](#Relationship_UnitRelationshipId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[Relationship_ServiceInventoryAgreementSiteRelationshipId](#Relationship_ServiceInventoryAgreementSiteRelationshipId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[Relationship_ServiceInventoryAgreementWarehouseRelationshipId](#Relationship_ServiceInventoryAgreementWarehouseRelationshipId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[BackingTable_SMAAgreementLineRelationshipId](#BackingTable_SMAAgreementLineRelationshipId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SMAServiceAgreementLineEntity.md" target="_blank">ServiceManagement/SMAServiceAgreementLineEntity</a>|

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLineSuspended name="IsLineSuspended">IsLineSuspended</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLineSuspended attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSetup name="ItemSetup">ItemSetup</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSetup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemUnitSymbol name="ItemUnitSymbol">ItemUnitSymbol</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDescription name="LineDescription">LineDescription</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line description</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNote name="LineNote">LineNote</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line text</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line text</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodEndDate name="PeriodEndDate">PeriodEndDate</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period end date</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Period end date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodStartDate name="PeriodStartDate">PeriodStartDate</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period start date</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Period start date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectActivityNumber name="ProjectActivityNumber">ProjectActivityNumber</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCustomerAccountNumber name="ProjectCustomerAccountNumber">ProjectCustomerAccountNumber</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project customer acccount</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project customer acccount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCategoryId name="ProjectCategoryId">ProjectCategoryId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectSalesCurrencyCode name="ProjectSalesCurrencyCode">ProjectSalesCurrencyCode</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectSalesCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectLinePropertyId name="ProjectLinePropertyId">ProjectLinePropertyId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectLinePropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectTaxGroupCode name="ProjectTaxGroupCode">ProjectTaxGroupCode</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectTaxItemGroupCode name="ProjectTaxItemGroupCode">ProjectTaxItemGroupCode</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectDescription name="ProjectDescription">ProjectDescription</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project description</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceAgreementId name="ServiceAgreementId">ServiceAgreementId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceIntervalId name="ServiceIntervalId">ServiceIntervalId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceIntervalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceObjectId name="ServiceObjectId">ServiceObjectId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceObjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceObjectRelationId name="ServiceObjectRelationId">ServiceObjectRelationId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceObjectRelationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTaskId name="ServiceTaskId">ServiceTaskId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaskId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceEndBeforeTime name="ServiceEndBeforeTime">ServiceEndBeforeTime</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service end before time</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceEndBeforeTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Service end before time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceStartAfterTime name="ServiceStartAfterTime">ServiceStartAfterTime</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service start after time</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceStartAfterTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Service start after time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTimeWindowId name="ServiceTimeWindowId">ServiceTimeWindowId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTimeWindowId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTransactionType name="ServiceTransactionType">ServiceTransactionType</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerPersonnelNumber name="WorkerPersonnelNumber">WorkerPersonnelNumber</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceInventoryAgreementSiteId name="ServiceInventoryAgreementSiteId">ServiceInventoryAgreementSiteId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceInventoryAgreementSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceInventoryAgreementWarehouseId name="ServiceInventoryAgreementWarehouseId">ServiceInventoryAgreementWarehouseId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceInventoryAgreementWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceInventoryAgreementWarehouseLocationId name="ServiceInventoryAgreementWarehouseLocationId">ServiceInventoryAgreementWarehouseLocationId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceInventoryAgreementWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Hours name="Hours">Hours</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hours</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Hours</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemQuantity name="ItemQuantity">ItemQuantity</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseQuantity name="ExpenseQuantity">ExpenseQuantity</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expense quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ServiceAgreementHeaderRelationshipId name="Relationship_ServiceAgreementHeaderRelationshipId">Relationship_ServiceAgreementHeaderRelationshipId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ServiceAgreementHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WorkerRelationshipId name="Relationship_WorkerRelationshipId">Relationship_WorkerRelationshipId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProjectRelationshipId name="Relationship_ProjectRelationshipId">Relationship_ProjectRelationshipId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReleasedProductV2RelationshipId name="Relationship_ReleasedProductV2RelationshipId">Relationship_ReleasedProductV2RelationshipId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReleasedProductV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnitRelationshipId name="Relationship_UnitRelationshipId">Relationship_UnitRelationshipId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnitRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ServiceInventoryAgreementSiteRelationshipId name="Relationship_ServiceInventoryAgreementSiteRelationshipId">Relationship_ServiceInventoryAgreementSiteRelationshipId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ServiceInventoryAgreementSiteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ServiceInventoryAgreementWarehouseRelationshipId name="Relationship_ServiceInventoryAgreementWarehouseRelationshipId">Relationship_ServiceInventoryAgreementWarehouseRelationshipId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ServiceInventoryAgreementWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_SMAAgreementLineRelationshipId name="BackingTable_SMAAgreementLineRelationshipId">BackingTable_SMAAgreementLineRelationshipId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SMAAgreementLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ServiceManagement/WorksheetLine/SMAAgreementLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ServiceManagement/WorksheetLine/SMAAgreementLine.cdm.json/SMAAgreementLine</a></td><td><a href="../../../Tables/SupplyChain/ServiceManagement/WorksheetLine/SMAAgreementLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ServiceManagement/SMAServiceAgreementLineEntity (this entity)  

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

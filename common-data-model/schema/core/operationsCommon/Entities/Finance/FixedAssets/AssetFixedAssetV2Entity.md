---
title: AssetFixedAssetV2Entity in FixedAssets - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Fixed assets V2 entity in FixedAssets(AssetFixedAssetV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FixedAssets/AssetFixedAssetV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed assets V2 entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Agent](#Agent)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[AssetActivityCode](#AssetActivityCode)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ActivityCode](#ActivityCode)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[AssetConditionId](#AssetConditionId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[BarCode](#BarCode)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Comments](#Comments)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Contact](#Contact)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ContactPersonnelNumber](#ContactPersonnelNumber)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Department](#Department)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[DepartmentOperatingUnitNumber](#DepartmentOperatingUnitNumber)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[DepartmentSearchName](#DepartmentSearchName)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[DisposalRestrictions](#DisposalRestrictions)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[DocumentLocation](#DocumentLocation)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[FixedAssetGroupId](#FixedAssetGroupId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[FixedAssetNumber](#FixedAssetNumber)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[GISReferenceNumber](#GISReferenceNumber)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[GuaranteeDate](#GuaranteeDate)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Information1](#Information1)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Information2](#Information2)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Information3](#Information3)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[InsuranceDate1](#InsuranceDate1)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[InsuranceDate2](#InsuranceDate2)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[InsuranceVendor](#InsuranceVendor)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[InsuredAtFairMarketValue](#InsuredAtFairMarketValue)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[InsuredValue](#InsuredValue)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[LastPeriodicValueCostUpdate](#LastPeriodicValueCostUpdate)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[LastMaintenance](#LastMaintenance)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[LeaseNote](#LeaseNote)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[AssetLocationId](#AssetLocationId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[LocationMemo](#LocationMemo)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[MajorTypeId](#MajorTypeId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Make](#Make)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[MissingAsset](#MissingAsset)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Model](#Model)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ModelYear](#ModelYear)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Name](#Name)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[NextMaintenance](#NextMaintenance)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ParcelID](#ParcelID)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[PhysicalInventory](#PhysicalInventory)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[PolicyAmount](#PolicyAmount)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[PolicyExpirationDate](#PolicyExpirationDate)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[PolicyNumber](#PolicyNumber)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[PropertyGroupId](#PropertyGroupId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[PropertyType](#PropertyType)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Quantity](#Quantity)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Reference](#Reference)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ReplacementCost](#ReplacementCost)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Responsible](#Responsible)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ResponsiblePersonnelNumber](#ResponsiblePersonnelNumber)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[RoomNumber](#RoomNumber)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[SearchName](#SearchName)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[SerialNumber](#SerialNumber)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[SortField1Id](#SortField1Id)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[SortField2Id](#SortField2Id)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[SortField3Id](#SortField3Id)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[TechnicalInformation1](#TechnicalInformation1)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[TechnicalInformation2](#TechnicalInformation2)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[TechnicalInformation3](#TechnicalInformation3)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Titleholder](#Titleholder)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Type](#Type)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[UnitCost](#UnitCost)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[UnitOfMeasure](#UnitOfMeasure)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[AcceleratedDepGroup](#AcceleratedDepGroup)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[AcceleratedDepreciationFixedAssetEquipmentGroupId](#AcceleratedDepreciationFixedAssetEquipmentGroupId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[AssetClassification](#AssetClassification)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ExceptionTaxationCode](#ExceptionTaxationCode)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[DeferredType](#DeferredType)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ExceptionTaxationRateDenominator](#ExceptionTaxationRateDenominator)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ExceptionTaxationRate](#ExceptionTaxationRate)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[IsSecondHand](#IsSecondHand)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[NameOfTheLender](#NameOfTheLender)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[IsRented](#IsRented)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Resource](#Resource)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[PhysicalAssetNumber](#PhysicalAssetNumber)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[LongTermReceivableTax](#LongTermReceivableTax)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[OutgoingICMS](#OutgoingICMS)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ICMSCreditInstallments](#ICMSCreditInstallments)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[TransferredFromInventory](#TransferredFromInventory)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[TaxationCodeForCOFINS](#TaxationCodeForCOFINS)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[AppropriationMethod](#AppropriationMethod)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[FixedAssetCreditGroup](#FixedAssetCreditGroup)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[TaxCreditsInstallments](#TaxCreditsInstallments)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[TaxCreditPurpose](#TaxCreditPurpose)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[TaxationCodeForPIS](#TaxationCodeForPIS)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[FiscalEstablishment_BR](#FiscalEstablishment_BR)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[AssetSourceType_CN](#AssetSourceType_CN)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[SourceTypeId](#SourceTypeId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[MainAssetId](#MainAssetId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[AcquisitionDate](#AcquisitionDate)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[AcquisitionPrice](#AcquisitionPrice)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[AssetTypeOfMajorType](#AssetTypeOfMajorType)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ContactName](#ContactName)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[ResponsibleName](#ResponsibleName)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Relationship_AssetFixedAssetV2AssetGroupRelationshipId](#Relationship_AssetFixedAssetV2AssetGroupRelationshipId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Relationship_AssetFixedAssetV2AssetLocationRelationshipId](#Relationship_AssetFixedAssetV2AssetLocationRelationshipId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Relationship_AsseFixeAssetV2AssetWorkerResponsibleRelationshipId](#Relationship_AsseFixeAssetV2AssetWorkerResponsibleRelationshipId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[BackingTable_AssetTableRelationshipId](#BackingTable_AssetTableRelationshipId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AssetFixedAssetV2Entity.md" target="_blank">FixedAssets/AssetFixedAssetV2Entity</a>|

### <a href=#Agent name="Agent">Agent</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Agent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetActivityCode name="AssetActivityCode">AssetActivityCode</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetActivityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityCode name="ActivityCode">ActivityCode</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetConditionId name="AssetConditionId">AssetConditionId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCode name="BarCode">BarCode</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Comments name="Comments">Comments</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Contact name="Contact">Contact</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Contact attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonnelNumber name="ContactPersonnelNumber">ContactPersonnelNumber</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Department name="Department">Department</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Department attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepartmentOperatingUnitNumber name="DepartmentOperatingUnitNumber">DepartmentOperatingUnitNumber</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepartmentOperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepartmentSearchName name="DepartmentSearchName">DepartmentSearchName</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepartmentSearchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisposalRestrictions name="DisposalRestrictions">DisposalRestrictions</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposalRestrictions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentLocation name="DocumentLocation">DocumentLocation</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetGroupId name="FixedAssetGroupId">FixedAssetGroupId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetNumber name="FixedAssetNumber">FixedAssetNumber</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GISReferenceNumber name="GISReferenceNumber">GISReferenceNumber</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GISReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GuaranteeDate name="GuaranteeDate">GuaranteeDate</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuaranteeDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Information1 name="Information1">Information1</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Information1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Information2 name="Information2">Information2</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Information2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Information3 name="Information3">Information3</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Information3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuranceDate1 name="InsuranceDate1">InsuranceDate1</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceDate1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuranceDate2 name="InsuranceDate2">InsuranceDate2</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceDate2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuranceVendor name="InsuranceVendor">InsuranceVendor</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceVendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuredAtFairMarketValue name="InsuredAtFairMarketValue">InsuredAtFairMarketValue</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuredAtFairMarketValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuredValue name="InsuredValue">InsuredValue</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuredValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastPeriodicValueCostUpdate name="LastPeriodicValueCostUpdate">LastPeriodicValueCostUpdate</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastPeriodicValueCostUpdate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastMaintenance name="LastMaintenance">LastMaintenance</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastMaintenance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeaseNote name="LeaseNote">LeaseNote</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeaseNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetLocationId name="AssetLocationId">AssetLocationId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationMemo name="LocationMemo">LocationMemo</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationMemo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MajorTypeId name="MajorTypeId">MajorTypeId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MajorTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Make name="Make">Make</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Make attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MissingAsset name="MissingAsset">MissingAsset</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MissingAsset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Model name="Model">Model</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Model attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModelYear name="ModelYear">ModelYear</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModelYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NextMaintenance name="NextMaintenance">NextMaintenance</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextMaintenance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParcelID name="ParcelID">ParcelID</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParcelID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalInventory name="PhysicalInventory">PhysicalInventory</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalInventory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyAmount name="PolicyAmount">PolicyAmount</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyExpirationDate name="PolicyExpirationDate">PolicyExpirationDate</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyNumber name="PolicyNumber">PolicyNumber</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PropertyGroupId name="PropertyGroupId">PropertyGroupId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PropertyType name="PropertyType">PropertyType</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reference name="Reference">Reference</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplacementCost name="ReplacementCost">ReplacementCost</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplacementCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Responsible name="Responsible">Responsible</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Responsible attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponsiblePersonnelNumber name="ResponsiblePersonnelNumber">ResponsiblePersonnelNumber</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsiblePersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoomNumber name="RoomNumber">RoomNumber</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoomNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SearchName name="SearchName">SearchName</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SerialNumber name="SerialNumber">SerialNumber</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortField1Id name="SortField1Id">SortField1Id</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField1Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortField2Id name="SortField2Id">SortField2Id</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField2Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortField3Id name="SortField3Id">SortField3Id</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField3Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalInformation1 name="TechnicalInformation1">TechnicalInformation1</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechnicalInformation1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalInformation2 name="TechnicalInformation2">TechnicalInformation2</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechnicalInformation2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalInformation3 name="TechnicalInformation3">TechnicalInformation3</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechnicalInformation3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Titleholder name="Titleholder">Titleholder</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Titleholder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCost name="UnitCost">UnitCost</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitOfMeasure name="UnitOfMeasure">UnitOfMeasure</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceleratedDepGroup name="AcceleratedDepGroup">AcceleratedDepGroup</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceleratedDepreciationFixedAssetEquipmentGroupId name="AcceleratedDepreciationFixedAssetEquipmentGroupId">AcceleratedDepreciationFixedAssetEquipmentGroupId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepreciationFixedAssetEquipmentGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetClassification name="AssetClassification">AssetClassification</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetClassification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExceptionTaxationCode name="ExceptionTaxationCode">ExceptionTaxationCode</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceptionTaxationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferredType name="DeferredType">DeferredType</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExceptionTaxationRateDenominator name="ExceptionTaxationRateDenominator">ExceptionTaxationRateDenominator</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exception rate (denominator)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceptionTaxationRateDenominator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exception rate (denominator)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExceptionTaxationRate name="ExceptionTaxationRate">ExceptionTaxationRate</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exception rate (numerator)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceptionTaxationRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exception rate (numerator)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSecondHand name="IsSecondHand">IsSecondHand</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSecondHand attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NameOfTheLender name="NameOfTheLender">NameOfTheLender</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameOfTheLender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRented name="IsRented">IsRented</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRented attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Resource name="Resource">Resource</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Resource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalAssetNumber name="PhysicalAssetNumber">PhysicalAssetNumber</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalAssetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LongTermReceivableTax name="LongTermReceivableTax">LongTermReceivableTax</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LongTermReceivableTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutgoingICMS name="OutgoingICMS">OutgoingICMS</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutgoingICMS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ICMSCreditInstallments name="ICMSCreditInstallments">ICMSCreditInstallments</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSCreditInstallments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferredFromInventory name="TransferredFromInventory">TransferredFromInventory</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferredFromInventory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxationCodeForCOFINS name="TaxationCodeForCOFINS">TaxationCodeForCOFINS</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationCodeForCOFINS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AppropriationMethod name="AppropriationMethod">AppropriationMethod</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AppropriationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetCreditGroup name="FixedAssetCreditGroup">FixedAssetCreditGroup</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetCreditGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCreditsInstallments name="TaxCreditsInstallments">TaxCreditsInstallments</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCreditsInstallments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCreditPurpose name="TaxCreditPurpose">TaxCreditPurpose</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCreditPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxationCodeForPIS name="TaxationCodeForPIS">TaxationCodeForPIS</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationCodeForPIS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishment_BR name="FiscalEstablishment_BR">FiscalEstablishment_BR</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishment_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetSourceType_CN name="AssetSourceType_CN">AssetSourceType_CN</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetSourceType_CN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceTypeId name="SourceTypeId">SourceTypeId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAssetId name="MainAssetId">MainAssetId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcquisitionDate name="AcquisitionDate">AcquisitionDate</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcquisitionPrice name="AcquisitionPrice">AcquisitionPrice</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetTypeOfMajorType name="AssetTypeOfMajorType">AssetTypeOfMajorType</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetTypeOfMajorType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactName name="ContactName">ContactName</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contact</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponsibleName name="ResponsibleName">ResponsibleName</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Responsible</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsibleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Responsible</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetFixedAssetV2AssetGroupRelationshipId name="Relationship_AssetFixedAssetV2AssetGroupRelationshipId">Relationship_AssetFixedAssetV2AssetGroupRelationshipId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetFixedAssetV2AssetGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetFixedAssetV2AssetLocationRelationshipId name="Relationship_AssetFixedAssetV2AssetLocationRelationshipId">Relationship_AssetFixedAssetV2AssetLocationRelationshipId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetFixedAssetV2AssetLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AsseFixeAssetV2AssetWorkerResponsibleRelationshipId name="Relationship_AsseFixeAssetV2AssetWorkerResponsibleRelationshipId">Relationship_AsseFixeAssetV2AssetWorkerResponsibleRelationshipId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AsseFixeAssetV2AssetWorkerResponsibleRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_AssetTableRelationshipId name="BackingTable_AssetTableRelationshipId">BackingTable_AssetTableRelationshipId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AssetTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FixedAssets/Main/AssetTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetTable.cdm.json/AssetTable</a></td><td><a href="../../../Tables/Finance/FixedAssets/Main/AssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: FixedAssets/AssetFixedAssetV2Entity (this entity)  

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

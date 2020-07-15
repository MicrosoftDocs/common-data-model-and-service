---
title: AssetFixedAssetEntity in FixedAssets - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Fixed assets in FixedAssets(AssetFixedAssetEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FixedAssets/AssetFixedAssetEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed assets</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Agent](#Agent)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AssetActivityCode](#AssetActivityCode)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ActivityCode](#ActivityCode)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ActivityCodeDescription](#ActivityCodeDescription)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AssetConditionId](#AssetConditionId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AssetConditionDescription](#AssetConditionDescription)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[BarCode](#BarCode)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Comments](#Comments)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Contact](#Contact)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ContactName](#ContactName)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ContactPersonnelNumber](#ContactPersonnelNumber)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Department](#Department)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[DepartmentOperatingUnitNumber](#DepartmentOperatingUnitNumber)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[DepartmentSearchName](#DepartmentSearchName)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[DisposalRestrictions](#DisposalRestrictions)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[DocumentLocation](#DocumentLocation)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[FixedAssetGroupId](#FixedAssetGroupId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[FixedAssetNumber](#FixedAssetNumber)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[GISReferenceNumber](#GISReferenceNumber)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[GuaranteeDate](#GuaranteeDate)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Information1](#Information1)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Information2](#Information2)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Information3](#Information3)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[InsuranceDate1](#InsuranceDate1)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[InsuranceDate2](#InsuranceDate2)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[InsuranceVendor](#InsuranceVendor)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[InsuredAtFairMarketValue](#InsuredAtFairMarketValue)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[InsuredValue](#InsuredValue)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[LastPeriodicValueCostUpdate](#LastPeriodicValueCostUpdate)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[LastMaintenance](#LastMaintenance)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[LeaseNote](#LeaseNote)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AssetLocationId](#AssetLocationId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AssetLocationName](#AssetLocationName)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[LocationId](#LocationId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[LocationMemo](#LocationMemo)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[MajorTypeId](#MajorTypeId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[MajorTypeDescription](#MajorTypeDescription)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Make](#Make)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[MissingAsset](#MissingAsset)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Model](#Model)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ModelYear](#ModelYear)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Name](#Name)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[NextMaintenance](#NextMaintenance)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ParcelID](#ParcelID)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[PhysicalInventory](#PhysicalInventory)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[PolicyAmount](#PolicyAmount)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[PolicyExpirationDate](#PolicyExpirationDate)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[PolicyNumber](#PolicyNumber)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[PropertyGroup](#PropertyGroup)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[PropertyGroupId](#PropertyGroupId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[PropertyGroupDescription](#PropertyGroupDescription)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[PropertyType](#PropertyType)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Quantity](#Quantity)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Reference](#Reference)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ReplacementCost](#ReplacementCost)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Responsible](#Responsible)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ResponsibleName](#ResponsibleName)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ResponsiblePersonnelNumber](#ResponsiblePersonnelNumber)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[RoomNumber](#RoomNumber)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SearchName](#SearchName)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SerialNumber](#SerialNumber)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SortField1Id](#SortField1Id)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SortField1Sorting](#SortField1Sorting)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SortField1Description](#SortField1Description)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SortField2Id](#SortField2Id)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SortField2Sorting](#SortField2Sorting)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SortField2Description](#SortField2Description)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SortField3Id](#SortField3Id)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SortField3Sorting](#SortField3Sorting)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SortField3Description](#SortField3Description)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[TechnicalInformation1](#TechnicalInformation1)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[TechnicalInformation2](#TechnicalInformation2)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[TechnicalInformation3](#TechnicalInformation3)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Titleholder](#Titleholder)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Type](#Type)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[UnitCost](#UnitCost)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[UnitOfMeasure](#UnitOfMeasure)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AcceleratedDepGroup](#AcceleratedDepGroup)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AcceleratedDepreciationFixedAssetEquipmentGroupId](#AcceleratedDepreciationFixedAssetEquipmentGroupId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AssetClassification](#AssetClassification)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ExceptionTaxationCode](#ExceptionTaxationCode)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[DeferredType](#DeferredType)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ExceptionTaxationRateDenominator](#ExceptionTaxationRateDenominator)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ExceptionTaxationRate](#ExceptionTaxationRate)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[IsSecondHand](#IsSecondHand)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AssetTypeOfMajorType](#AssetTypeOfMajorType)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[NameOfTheLender](#NameOfTheLender)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[IsRented](#IsRented)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Resource](#Resource)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[PhysicalAssetNumber](#PhysicalAssetNumber)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[LongTermReceivableTax](#LongTermReceivableTax)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[OutgoingICMS](#OutgoingICMS)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[ICMSCreditInstallments](#ICMSCreditInstallments)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[TransferredFromInventory](#TransferredFromInventory)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[TaxationCodeForCOFINS](#TaxationCodeForCOFINS)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AppropriationMethod](#AppropriationMethod)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[FixedAssetCreditGroup](#FixedAssetCreditGroup)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[TaxCreditsInstallments](#TaxCreditsInstallments)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[TaxCreditPurpose](#TaxCreditPurpose)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[TaxationCodeForPIS](#TaxationCodeForPIS)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[FiscalEstablishment_BR](#FiscalEstablishment_BR)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AssetSourceType_CN](#AssetSourceType_CN)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[SourceTypeId](#SourceTypeId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[MainAssetId](#MainAssetId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AcquisitionDate](#AcquisitionDate)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[AcquisitionPrice](#AcquisitionPrice)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Relationship_AssetGroupRelationshipId](#Relationship_AssetGroupRelationshipId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Relationship_AssetLocationRelationshipId](#Relationship_AssetLocationRelationshipId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Relationship_WorkerResponsibleRelationshipId](#Relationship_WorkerResponsibleRelationshipId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[BackingTable_AssetTableRelationshipId](#BackingTable_AssetTableRelationshipId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AssetFixedAssetEntity.md" target="_blank">FixedAssets/AssetFixedAssetEntity</a>|

### <a href=#Agent name="Agent">Agent</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#ActivityCodeDescription name="ActivityCodeDescription">ActivityCodeDescription</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetConditionId name="AssetConditionId">AssetConditionId</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#AssetConditionDescription name="AssetConditionDescription">AssetConditionDescription</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetConditionDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCode name="BarCode">BarCode</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#ContactName name="ContactName">ContactName</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#ContactPersonnelNumber name="ContactPersonnelNumber">ContactPersonnelNumber</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#AssetLocationName name="AssetLocationName">AssetLocationName</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetLocationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationId name="LocationId">LocationId</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationMemo name="LocationMemo">LocationMemo</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#MajorTypeDescription name="MajorTypeDescription">MajorTypeDescription</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MajorTypeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Make name="Make">Make</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#PropertyGroup name="PropertyGroup">PropertyGroup</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PropertyGroupId name="PropertyGroupId">PropertyGroupId</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#PropertyGroupDescription name="PropertyGroupDescription">PropertyGroupDescription</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyGroupDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PropertyType name="PropertyType">PropertyType</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#ResponsibleName name="ResponsibleName">ResponsibleName</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#ResponsiblePersonnelNumber name="ResponsiblePersonnelNumber">ResponsiblePersonnelNumber</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#SortField1Sorting name="SortField1Sorting">SortField1Sorting</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField1Sorting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortField1Description name="SortField1Description">SortField1Description</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField1Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortField2Id name="SortField2Id">SortField2Id</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#SortField2Sorting name="SortField2Sorting">SortField2Sorting</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField2Sorting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortField2Description name="SortField2Description">SortField2Description</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField2Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortField3Id name="SortField3Id">SortField3Id</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#SortField3Sorting name="SortField3Sorting">SortField3Sorting</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField3Sorting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortField3Description name="SortField3Description">SortField3Description</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField3Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalInformation1 name="TechnicalInformation1">TechnicalInformation1</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#AssetTypeOfMajorType name="AssetTypeOfMajorType">AssetTypeOfMajorType</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#NameOfTheLender name="NameOfTheLender">NameOfTheLender</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

### <a href=#Relationship_AssetGroupRelationshipId name="Relationship_AssetGroupRelationshipId">Relationship_AssetGroupRelationshipId</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetLocationRelationshipId name="Relationship_AssetLocationRelationshipId">Relationship_AssetLocationRelationshipId</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WorkerResponsibleRelationshipId name="Relationship_WorkerResponsibleRelationshipId">Relationship_WorkerResponsibleRelationshipId</a>

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkerResponsibleRelationshipId attribute are listed below.</summary>

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

First included in: FixedAssets/AssetFixedAssetEntity (this entity)  

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

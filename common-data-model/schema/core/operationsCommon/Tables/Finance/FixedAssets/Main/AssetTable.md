---
title: AssetTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# AssetTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AcquisitionDate_W](#AcquisitionDate_W)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AcquisitionPrice_W](#AcquisitionPrice_W)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AcquisitionValueNO](#AcquisitionValueNO)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AllowSale_PL](#AllowSale_PL)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssessmentNO](#AssessmentNO)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssessmentTaxNO](#AssessmentTaxNO)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetActivityCode](#AssetActivityCode)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetClassification_JP](#AssetClassification_JP)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetDeferredType_JP](#AssetDeferredType_JP)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetGroup](#AssetGroup)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetId](#AssetId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetProductionYear_PL](#AssetProductionYear_PL)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetPropertyGroup](#AssetPropertyGroup)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetReplaceCost](#AssetReplaceCost)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetSourceType_CN](#AssetSourceType_CN)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetType](#AssetType)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Barcode](#Barcode)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[CategoryId_LV](#CategoryId_LV)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Condition](#Condition)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[DefaultDimension](#DefaultDimension)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Department](#Department)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[DisposalRestriction](#DisposalRestriction)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Documents](#Documents)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[ExceptionTaxationCode_JP](#ExceptionTaxationCode_JP)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[ExceptionTaxationRate_JP](#ExceptionTaxationRate_JP)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[ExceptionTaxationRateDenominator_JP](#ExceptionTaxationRateDenominator_JP)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[FiscalEstablishment_BR](#FiscalEstablishment_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[GISReferenceNumber](#GISReferenceNumber)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[GuaranteeDate](#GuaranteeDate)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[ICMSCreditInstallments_BR](#ICMSCreditInstallments_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[InsuranceAgent](#InsuranceAgent)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[InsuranceDate1](#InsuranceDate1)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[InsuranceDate2](#InsuranceDate2)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[InsurancePolicyNum](#InsurancePolicyNum)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[InsuranceVendor](#InsuranceVendor)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[InsuredAtMarketValue](#InsuredAtMarketValue)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[InsuredValue](#InsuredValue)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[IsMissing](#IsMissing)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[IsRented_JP](#IsRented_JP)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[IsSecondHand_JP](#IsSecondHand_JP)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[LastFactorUpdateDate](#LastFactorUpdateDate)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[LastMaintenance](#LastMaintenance)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Lease](#Lease)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[LenderName_JP](#LenderName_JP)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Location](#Location)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[LocationMemo](#LocationMemo)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[MainAssetId](#MainAssetId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[MaintenanceInfo1](#MaintenanceInfo1)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[MaintenanceInfo2](#MaintenanceInfo2)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[MaintenanceInfo3](#MaintenanceInfo3)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[MajorType](#MajorType)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Make](#Make)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Model](#Model)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[ModelYear](#ModelYear)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Name](#Name)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[NameAlias](#NameAlias)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[NextMaintenance](#NextMaintenance)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Notes](#Notes)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[ParcelId](#ParcelId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PhysicalAssetNumber_BR](#PhysicalAssetNumber_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PhysicalInventory](#PhysicalInventory)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PISCOFINSReceivableLongTerm_BR](#PISCOFINSReceivableLongTerm_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PolicyAmount](#PolicyAmount)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PolicyExpiration](#PolicyExpiration)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PropertyType](#PropertyType)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PurchLineRecId](#PurchLineRecId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Quantity](#Quantity)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Reference](#Reference)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[ReturnOnInvestmentsNO](#ReturnOnInvestmentsNO)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[RoomNumber](#RoomNumber)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[SerialNum](#SerialNum)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[SortingId](#SortingId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[SortingId2](#SortingId2)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[SortingId3](#SortingId3)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[SubventionNO](#SubventionNO)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[SubventionTaxFreeNO](#SubventionTaxFreeNO)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TaxCountyNO](#TaxCountyNO)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TaxICMSOutgoing_BR](#TaxICMSOutgoing_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TechInfo1](#TechInfo1)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TechInfo2](#TechInfo2)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TechInfo3](#TechInfo3)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TitleHolder](#TitleHolder)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TransferredFromInventory_BR](#TransferredFromInventory_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[UnitCost](#UnitCost)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[UnitOfMeasure](#UnitOfMeasure)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[ValueAt19840101NO](#ValueAt19840101NO)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[WorkerContactName](#WorkerContactName)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[WorkerResponsible](#WorkerResponsible)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[WrkCtrId_JP](#WrkCtrId_JP)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AcceleratedDepGroup_JP](#AcceleratedDepGroup_JP)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[COFINSTaxationCode_BR](#COFINSTaxationCode_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PISCOFINSAppropriationMethod_BR](#PISCOFINSAppropriationMethod_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PISCOFINSCreditGroup_BR](#PISCOFINSCreditGroup_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PISCOFINSCreditInstallments_BR](#PISCOFINSCreditInstallments_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PISCOFINSCreditPurpose_BR](#PISCOFINSCreditPurpose_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PISTaxationCode_BR](#PISTaxationCode_BR)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TransportTaxCode_RU](#TransportTaxCode_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[ClothRiggingId_RU](#ClothRiggingId_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssessedTaxType_RU](#AssessedTaxType_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetBelonged_RU](#AssetBelonged_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[AssetUse_RU](#AssetUse_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[BuildingStartDate_RU](#BuildingStartDate_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[DenominatorShare_RU](#DenominatorShare_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[NumeratorShare_RU](#NumeratorShare_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[LandCadastralNum_RU](#LandCadastralNum_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[LandTaxCode_RU](#LandTaxCode_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[LandType_RU](#LandType_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[LogisticsPostalAddress_RU](#LogisticsPostalAddress_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[PassportNum_RU](#PassportNum_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[RegisterRemovalDate_RU](#RegisterRemovalDate_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[ReleaseYear_RU](#ReleaseYear_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[QuotaTypesRecId_RU](#QuotaTypesRecId_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TaxAllowanceRecId_RU](#TaxAllowanceRecId_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[VehicleType_RU](#VehicleType_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TaxBase_RU](#TaxBase_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TaxBaseUnitId_RU](#TaxBaseUnitId_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[TaxCode_RU](#TaxCode_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[VatRefundingStartDate_RU](#VatRefundingStartDate_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[VehicleEcoClass_RU](#VehicleEcoClass_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[VehicleModel_RU](#VehicleModel_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[VehiclePlateDate_RU](#VehiclePlateDate_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[VehiclePlateNum_RU](#VehiclePlateNum_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[RoomCadastralNum_RU](#RoomCadastralNum_RU)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_AssetActivityCodeRelationshipId](#Relationship_AssetActivityCodeRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_AssetConditionRelationshipId](#Relationship_AssetConditionRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_AssetGroup_AssetGroupRelationshipId](#Relationship_AssetGroup_AssetGroupRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_AssetLocationRelationshipId](#Relationship_AssetLocationRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_AssetMajorTypeRelationshipId](#Relationship_AssetMajorTypeRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_AssetPropertyGroupRelationshipId](#Relationship_AssetPropertyGroupRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_AssetSortingRelationshipId](#Relationship_AssetSortingRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_AssetSorting_SortingId2RelationshipId](#Relationship_AssetSorting_SortingId2RelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_AssetSorting_SortingId3RelationshipId](#Relationship_AssetSorting_SortingId3RelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_AssetSourceType_CNRelationshipId](#Relationship_AssetSourceType_CNRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_CategoryId_LVRelationshipId](#Relationship_CategoryId_LVRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_FiscalEstablishment_BRRelationshipId](#Relationship_FiscalEstablishment_BRRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_OMOperatingUnitRelationshipId](#Relationship_OMOperatingUnitRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_PurchLineRelationshipId](#Relationship_PurchLineRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_WrkCtrTable_JPRelationshipId](#Relationship_WrkCtrTable_JPRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_AssetAcceleratedDepGroup_JPRelationshipId](#Relationship_AssetAcceleratedDepGroup_JPRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_LogisticsPostalAddress_FKRelationshipId](#Relationship_LogisticsPostalAddress_FKRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_RAssetInventIssueQuotaTypesRelationshipId](#Relationship_RAssetInventIssueQuotaTypesRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_RAssetTaxAllowanceRelationshipId](#Relationship_RAssetTaxAllowanceRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_RAssetTaxAllowanceDecreaseBaseRelationshipId](#Relationship_RAssetTaxAllowanceDecreaseBaseRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetTable.md" target="_blank">Main/AssetTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcquisitionDate_W name="AcquisitionDate_W">AcquisitionDate_W</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionDate_W attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#AcquisitionPrice_W name="AcquisitionPrice_W">AcquisitionPrice_W</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionPrice_W attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AcquisitionValueNO name="AcquisitionValueNO">AcquisitionValueNO</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionValueNO attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AllowSale_PL name="AllowSale_PL">AllowSale_PL</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSale_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssessmentNO name="AssessmentNO">AssessmentNO</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessmentNO attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AssessmentTaxNO name="AssessmentTaxNO">AssessmentTaxNO</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessmentTaxNO attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AssetActivityCode name="AssetActivityCode">AssetActivityCode</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetActivityCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetClassification_JP name="AssetClassification_JP">AssetClassification_JP</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetClassification_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssetDeferredType_JP name="AssetDeferredType_JP">AssetDeferredType_JP</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetDeferredType_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssetGroup name="AssetGroup">AssetGroup</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetId name="AssetId">AssetId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetProductionYear_PL name="AssetProductionYear_PL">AssetProductionYear_PL</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetProductionYear_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetPropertyGroup name="AssetPropertyGroup">AssetPropertyGroup</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetPropertyGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetReplaceCost name="AssetReplaceCost">AssetReplaceCost</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetReplaceCost attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AssetSourceType_CN name="AssetSourceType_CN">AssetSourceType_CN</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetSourceType_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetType name="AssetType">AssetType</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Barcode name="Barcode">Barcode</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Barcode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryId_LV name="CategoryId_LV">CategoryId_LV</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryId_LV attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Condition name="Condition">Condition</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Condition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Department name="Department">Department</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Department attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DisposalRestriction name="DisposalRestriction">DisposalRestriction</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposalRestriction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Documents name="Documents">Documents</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Documents attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExceptionTaxationCode_JP name="ExceptionTaxationCode_JP">ExceptionTaxationCode_JP</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceptionTaxationCode_JP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExceptionTaxationRate_JP name="ExceptionTaxationRate_JP">ExceptionTaxationRate_JP</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceptionTaxationRate_JP attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExceptionTaxationRateDenominator_JP name="ExceptionTaxationRateDenominator_JP">ExceptionTaxationRateDenominator_JP</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceptionTaxationRateDenominator_JP attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FiscalEstablishment_BR name="FiscalEstablishment_BR">FiscalEstablishment_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishment_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GISReferenceNumber name="GISReferenceNumber">GISReferenceNumber</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GISReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GuaranteeDate name="GuaranteeDate">GuaranteeDate</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuaranteeDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ICMSCreditInstallments_BR name="ICMSCreditInstallments_BR">ICMSCreditInstallments_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSCreditInstallments_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InsuranceAgent name="InsuranceAgent">InsuranceAgent</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceAgent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuranceDate1 name="InsuranceDate1">InsuranceDate1</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceDate1 attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#InsuranceDate2 name="InsuranceDate2">InsuranceDate2</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceDate2 attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#InsurancePolicyNum name="InsurancePolicyNum">InsurancePolicyNum</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsurancePolicyNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuranceVendor name="InsuranceVendor">InsuranceVendor</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceVendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuredAtMarketValue name="InsuredAtMarketValue">InsuredAtMarketValue</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuredAtMarketValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InsuredValue name="InsuredValue">InsuredValue</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuredValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IsMissing name="IsMissing">IsMissing</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMissing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsRented_JP name="IsRented_JP">IsRented_JP</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRented_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsSecondHand_JP name="IsSecondHand_JP">IsSecondHand_JP</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSecondHand_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LastFactorUpdateDate name="LastFactorUpdateDate">LastFactorUpdateDate</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastFactorUpdateDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#LastMaintenance name="LastMaintenance">LastMaintenance</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastMaintenance attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Lease name="Lease">Lease</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Lease attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LenderName_JP name="LenderName_JP">LenderName_JP</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LenderName_JP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Location name="Location">Location</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Location attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationMemo name="LocationMemo">LocationMemo</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationMemo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAssetId name="MainAssetId">MainAssetId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaintenanceInfo1 name="MaintenanceInfo1">MaintenanceInfo1</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaintenanceInfo1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaintenanceInfo2 name="MaintenanceInfo2">MaintenanceInfo2</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaintenanceInfo2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaintenanceInfo3 name="MaintenanceInfo3">MaintenanceInfo3</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaintenanceInfo3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MajorType name="MajorType">MajorType</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MajorType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Make name="Make">Make</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Make attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Model name="Model">Model</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Model attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModelYear name="ModelYear">ModelYear</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModelYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NameAlias name="NameAlias">NameAlias</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameAlias attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NextMaintenance name="NextMaintenance">NextMaintenance</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextMaintenance attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Notes name="Notes">Notes</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Notes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParcelId name="ParcelId">ParcelId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParcelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalAssetNumber_BR name="PhysicalAssetNumber_BR">PhysicalAssetNumber_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalAssetNumber_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalInventory name="PhysicalInventory">PhysicalInventory</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalInventory attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PISCOFINSReceivableLongTerm_BR name="PISCOFINSReceivableLongTerm_BR">PISCOFINSReceivableLongTerm_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PISCOFINSReceivableLongTerm_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PolicyAmount name="PolicyAmount">PolicyAmount</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PolicyExpiration name="PolicyExpiration">PolicyExpiration</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyExpiration attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PropertyType name="PropertyType">PropertyType</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PurchLineRecId name="PurchLineRecId">PurchLineRecId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchLineRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Reference name="Reference">Reference</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnOnInvestmentsNO name="ReturnOnInvestmentsNO">ReturnOnInvestmentsNO</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnOnInvestmentsNO attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RoomNumber name="RoomNumber">RoomNumber</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoomNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SerialNum name="SerialNum">SerialNum</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerialNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortingId name="SortingId">SortingId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortingId2 name="SortingId2">SortingId2</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingId2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortingId3 name="SortingId3">SortingId3</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortingId3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubventionNO name="SubventionNO">SubventionNO</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubventionNO attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SubventionTaxFreeNO name="SubventionTaxFreeNO">SubventionTaxFreeNO</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubventionTaxFreeNO attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxCountyNO name="TaxCountyNO">TaxCountyNO</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCountyNO attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxICMSOutgoing_BR name="TaxICMSOutgoing_BR">TaxICMSOutgoing_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxICMSOutgoing_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TechInfo1 name="TechInfo1">TechInfo1</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechInfo1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechInfo2 name="TechInfo2">TechInfo2</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechInfo2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechInfo3 name="TechInfo3">TechInfo3</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechInfo3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TitleHolder name="TitleHolder">TitleHolder</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TitleHolder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferredFromInventory_BR name="TransferredFromInventory_BR">TransferredFromInventory_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferredFromInventory_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UnitCost name="UnitCost">UnitCost</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCost attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UnitOfMeasure name="UnitOfMeasure">UnitOfMeasure</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValueAt19840101NO name="ValueAt19840101NO">ValueAt19840101NO</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueAt19840101NO attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WorkerContactName name="WorkerContactName">WorkerContactName</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerContactName attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkerResponsible name="WorkerResponsible">WorkerResponsible</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerResponsible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WrkCtrId_JP name="WrkCtrId_JP">WrkCtrId_JP</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WrkCtrId_JP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceleratedDepGroup_JP name="AcceleratedDepGroup_JP">AcceleratedDepGroup_JP</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepGroup_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#COFINSTaxationCode_BR name="COFINSTaxationCode_BR">COFINSTaxationCode_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the COFINSTaxationCode_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PISCOFINSAppropriationMethod_BR name="PISCOFINSAppropriationMethod_BR">PISCOFINSAppropriationMethod_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PISCOFINSAppropriationMethod_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PISCOFINSCreditGroup_BR name="PISCOFINSCreditGroup_BR">PISCOFINSCreditGroup_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PISCOFINSCreditGroup_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PISCOFINSCreditInstallments_BR name="PISCOFINSCreditInstallments_BR">PISCOFINSCreditInstallments_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PISCOFINSCreditInstallments_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PISCOFINSCreditPurpose_BR name="PISCOFINSCreditPurpose_BR">PISCOFINSCreditPurpose_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PISCOFINSCreditPurpose_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PISTaxationCode_BR name="PISTaxationCode_BR">PISTaxationCode_BR</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PISTaxationCode_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportTaxCode_RU name="TransportTaxCode_RU">TransportTaxCode_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportTaxCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClothRiggingId_RU name="ClothRiggingId_RU">ClothRiggingId_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClothRiggingId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssessedTaxType_RU name="AssessedTaxType_RU">AssessedTaxType_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessedTaxType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssetBelonged_RU name="AssetBelonged_RU">AssetBelonged_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetBelonged_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssetUse_RU name="AssetUse_RU">AssetUse_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetUse_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BuildingStartDate_RU name="BuildingStartDate_RU">BuildingStartDate_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuildingStartDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DenominatorShare_RU name="DenominatorShare_RU">DenominatorShare_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DenominatorShare_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NumeratorShare_RU name="NumeratorShare_RU">NumeratorShare_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumeratorShare_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LandCadastralNum_RU name="LandCadastralNum_RU">LandCadastralNum_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LandCadastralNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LandTaxCode_RU name="LandTaxCode_RU">LandTaxCode_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LandTaxCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LandType_RU name="LandType_RU">LandType_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LandType_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalAddress_RU name="LogisticsPostalAddress_RU">LogisticsPostalAddress_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalAddress_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNum_RU name="PassportNum_RU">PassportNum_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegisterRemovalDate_RU name="RegisterRemovalDate_RU">RegisterRemovalDate_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegisterRemovalDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ReleaseYear_RU name="ReleaseYear_RU">ReleaseYear_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleaseYear_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#QuotaTypesRecId_RU name="QuotaTypesRecId_RU">QuotaTypesRecId_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotaTypesRecId_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAllowanceRecId_RU name="TaxAllowanceRecId_RU">TaxAllowanceRecId_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAllowanceRecId_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VehicleType_RU name="VehicleType_RU">VehicleType_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleType_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxBase_RU name="TaxBase_RU">TaxBase_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBase_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseUnitId_RU name="TaxBaseUnitId_RU">TaxBaseUnitId_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseUnitId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCode_RU name="TaxCode_RU">TaxCode_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VatRefundingStartDate_RU name="VatRefundingStartDate_RU">VatRefundingStartDate_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VatRefundingStartDate_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VehicleEcoClass_RU name="VehicleEcoClass_RU">VehicleEcoClass_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleEcoClass_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VehicleModel_RU name="VehicleModel_RU">VehicleModel_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleModel_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VehiclePlateDate_RU name="VehiclePlateDate_RU">VehiclePlateDate_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehiclePlateDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#VehiclePlateNum_RU name="VehiclePlateNum_RU">VehiclePlateNum_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehiclePlateNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoomCadastralNum_RU name="RoomCadastralNum_RU">RoomCadastralNum_RU</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoomCadastralNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetActivityCodeRelationshipId name="Relationship_AssetActivityCodeRelationshipId">Relationship_AssetActivityCodeRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetActivityCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AssetActivityCode.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetActivityCode.cdm.json/AssetActivityCode</a></td><td><a href="../Group/AssetActivityCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetConditionRelationshipId name="Relationship_AssetConditionRelationshipId">Relationship_AssetConditionRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetConditionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetCondition.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetCondition.cdm.json/AssetCondition</a></td><td><a href="AssetCondition.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetGroup_AssetGroupRelationshipId name="Relationship_AssetGroup_AssetGroupRelationshipId">Relationship_AssetGroup_AssetGroupRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetGroup_AssetGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AssetGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetGroup.cdm.json/AssetGroup</a></td><td><a href="../Group/AssetGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetLocationRelationshipId name="Relationship_AssetLocationRelationshipId">Relationship_AssetLocationRelationshipId</a>

First included in: Main/AssetTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AssetLocation.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetLocation.cdm.json/AssetLocation</a></td><td><a href="../Group/AssetLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetMajorTypeRelationshipId name="Relationship_AssetMajorTypeRelationshipId">Relationship_AssetMajorTypeRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetMajorTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetMajorType.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetMajorType.cdm.json/AssetMajorType</a></td><td><a href="AssetMajorType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetPropertyGroupRelationshipId name="Relationship_AssetPropertyGroupRelationshipId">Relationship_AssetPropertyGroupRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetPropertyGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AssetPropertyGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetPropertyGroup.cdm.json/AssetPropertyGroup</a></td><td><a href="../Group/AssetPropertyGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetSortingRelationshipId name="Relationship_AssetSortingRelationshipId">Relationship_AssetSortingRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetSortingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetSorting.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetSorting.cdm.json/AssetSorting</a></td><td><a href="../Parameter/AssetSorting.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetSorting_SortingId2RelationshipId name="Relationship_AssetSorting_SortingId2RelationshipId">Relationship_AssetSorting_SortingId2RelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetSorting_SortingId2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetSorting.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetSorting.cdm.json/AssetSorting</a></td><td><a href="../Parameter/AssetSorting.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetSorting_SortingId3RelationshipId name="Relationship_AssetSorting_SortingId3RelationshipId">Relationship_AssetSorting_SortingId3RelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetSorting_SortingId3RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetSorting.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetSorting.cdm.json/AssetSorting</a></td><td><a href="../Parameter/AssetSorting.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetSourceType_CNRelationshipId name="Relationship_AssetSourceType_CNRelationshipId">Relationship_AssetSourceType_CNRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetSourceType_CNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetSourceType_CN.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetSourceType_CN.cdm.json/AssetSourceType_CN</a></td><td><a href="AssetSourceType_CN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CategoryId_LVRelationshipId name="Relationship_CategoryId_LVRelationshipId">Relationship_CategoryId_LVRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CategoryId_LVRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetBookTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetBookTable.cdm.json/AssetBookTable</a></td><td><a href="AssetBookTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalEstablishment_BRRelationshipId name="Relationship_FiscalEstablishment_BRRelationshipId">Relationship_FiscalEstablishment_BRRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalEstablishment_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FiscalBooksBrazil/Main/FiscalEstablishment_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FiscalEstablishment_BR.cdm.json/FiscalEstablishment_BR</a></td><td><a href="../../FiscalBooksBrazil/Main/FiscalEstablishment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OMOperatingUnitRelationshipId name="Relationship_OMOperatingUnitRelationshipId">Relationship_OMOperatingUnitRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OMOperatingUnitRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/OMOperatingUnit.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/OMOperatingUnit.cdm.json/OMOperatingUnit</a></td><td><a href="../../../Common/GAB/Main/OMOperatingUnit.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchLineRelationshipId name="Relationship_PurchLineRelationshipId">Relationship_PurchLineRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.cdm.json/PurchLine</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Main/AssetTable (this entity)  

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

### <a href=#Relationship_WrkCtrTable_JPRelationshipId name="Relationship_WrkCtrTable_JPRelationshipId">Relationship_WrkCtrTable_JPRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WrkCtrTable_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Main/WrkCtrTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/WrkCtrTable.cdm.json/WrkCtrTable</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Main/WrkCtrTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetAcceleratedDepGroup_JPRelationshipId name="Relationship_AssetAcceleratedDepGroup_JPRelationshipId">Relationship_AssetAcceleratedDepGroup_JPRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetAcceleratedDepGroup_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AssetAcceleratedDepGroup_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetAcceleratedDepGroup_JP.cdm.json/AssetAcceleratedDepGroup_JP</a></td><td><a href="../Group/AssetAcceleratedDepGroup_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsPostalAddress_FKRelationshipId name="Relationship_LogisticsPostalAddress_FKRelationshipId">Relationship_LogisticsPostalAddress_FKRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsPostalAddress_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RAssetInventIssueQuotaTypesRelationshipId name="Relationship_RAssetInventIssueQuotaTypesRelationshipId">Relationship_RAssetInventIssueQuotaTypesRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RAssetInventIssueQuotaTypesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RAsset/Main/RAssetInventIssueQuotaTypes.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Main/RAssetInventIssueQuotaTypes.cdm.json/RAssetInventIssueQuotaTypes</a></td><td><a href="../../RAsset/Main/RAssetInventIssueQuotaTypes.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RAssetTaxAllowanceRelationshipId name="Relationship_RAssetTaxAllowanceRelationshipId">Relationship_RAssetTaxAllowanceRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RAssetTaxAllowanceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RAsset/Main/RAssetTaxAllowance.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Main/RAssetTaxAllowance.cdm.json/RAssetTaxAllowance</a></td><td><a href="../../RAsset/Main/RAssetTaxAllowance.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RAssetTaxAllowanceDecreaseBaseRelationshipId name="Relationship_RAssetTaxAllowanceDecreaseBaseRelationshipId">Relationship_RAssetTaxAllowanceDecreaseBaseRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RAssetTaxAllowanceDecreaseBaseRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RAsset/Main/RAssetTaxAllowance.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Main/RAssetTaxAllowance.cdm.json/RAssetTaxAllowance</a></td><td><a href="../../RAsset/Main/RAssetTaxAllowance.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/AssetTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

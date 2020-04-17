---
title: RetailPubRetailStoreTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailPubRetailStoreTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailPubRetailStoreTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPubRetailStoreTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[CategoryHierarchy](#CategoryHierarchy)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[ChannelType](#ChannelType)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Currency](#Currency)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[DefaultCustAccount](#DefaultCustAccount)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[DefaultCustDataAreaId](#DefaultCustDataAreaId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[DefaultDimension](#DefaultDimension)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[InternalOrganization](#InternalOrganization)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[inventLocation](#inventLocation)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[inventLocationDataAreaId](#inventLocationDataAreaId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[OMOperatingUnitID](#OMOperatingUnitID)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[OriginId](#OriginId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[OriginInstanceRelationType](#OriginInstanceRelationType)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[OriginRecVersion](#OriginRecVersion)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[PriceIncludesSalesTax](#PriceIncludesSalesTax)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[TransactionServiceProfile](#TransactionServiceProfile)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_DimensionAttributeValueSetRelationshipId](#Relationship_DimensionAttributeValueSetRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_EcoResCategoryHierarchyRelationshipId](#Relationship_EcoResCategoryHierarchyRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_InternalOrganizationRelationshipId](#Relationship_InternalOrganizationRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_InventLocationRelationshipId](#Relationship_InventLocationRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_OMOperatingUnitRelationshipId](#Relationship_OMOperatingUnitRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_RetailChannelTableRelationshipId](#Relationship_RetailChannelTableRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_RetailTransactionServiceProfileRelationshipId](#Relationship_RetailTransactionServiceProfileRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[closingMethod](#closingMethod)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[createLabelsForZeroPrice](#createLabelsForZeroPrice)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[cultureName](#cultureName)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[DatabaseName](#DatabaseName)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[functionalityProfile](#functionalityProfile)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[generatesItemLabels](#generatesItemLabels)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[generatesShelfLabels](#generatesShelfLabels)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[hideTrainingMode](#hideTrainingMode)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[InventLocationIdForCustomerOrder](#InventLocationIdForCustomerOrder)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[inventoryLookup](#inventoryLookup)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[itemIdOnReceipt](#itemIdOnReceipt)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[layoutId](#layoutId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[maximumPostingDifference](#maximumPostingDifference)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[maximumTextLengthOnReceipt](#maximumTextLengthOnReceipt)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[maxRoundingAmount](#maxRoundingAmount)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[maxRoundingTaxAmount](#maxRoundingTaxAmount)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[maxShiftDifferenceAmount](#maxShiftDifferenceAmount)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[maxTransactionDifferenceAmount](#maxTransactionDifferenceAmount)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[numberOfTopOrBottomLines](#numberOfTopOrBottomLines)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[OfflineProfile](#OfflineProfile)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[oneStatementPerDay](#oneStatementPerDay)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[openFrom](#openFrom)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[openTo](#openTo)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[PackedExtensions](#PackedExtensions)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Password](#Password)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[phone](#phone)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[poItemFilter](#poItemFilter)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[removeAddTender](#removeAddTender)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[replicationCounter](#replicationCounter)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[RetailReqPlanIdSched](#RetailReqPlanIdSched)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[RoundingAccountLedgerDimension](#RoundingAccountLedgerDimension)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[roundingTaxAccount](#roundingTaxAccount)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[separateStmtPerStaffTerminal](#separateStmtPerStaffTerminal)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[serviceChargePct](#serviceChargePct)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[serviceChargePrompt](#serviceChargePrompt)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[SQLServerName](#SQLServerName)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[statementMethod](#statementMethod)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[stmtCalcBatchEndTime](#stmtCalcBatchEndTime)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[StoreOriginId](#StoreOriginId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[StoreOriginRecVersion](#StoreOriginRecVersion)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[taxGroup](#taxGroup)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[TaxGroupDataAreaId](#TaxGroupDataAreaId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[TaxIdentificationNumber](#TaxIdentificationNumber)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[TaxOverrideGroup](#TaxOverrideGroup)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[tenderDeclarationCalculation](#tenderDeclarationCalculation)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[UseCustomerBasedTax](#UseCustomerBasedTax)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[UseDefaultCustAccount](#UseDefaultCustAccount)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[UseDestinationBasedTax](#UseDestinationBasedTax)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[UserName](#UserName)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[bankDropCalculation](#bankDropCalculation)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[startAmountCalculation](#startAmountCalculation)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_DimensionAttributeValueCombinationRelationshipId](#Relationship_DimensionAttributeValueCombinationRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_InventLocationForCustomerOrderRelationshipId](#Relationship_InventLocationForCustomerOrderRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_LanguageTableRelationshipId](#Relationship_LanguageTableRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_OfflineProfileRelationshipId](#Relationship_OfflineProfileRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_ReqPlanSchedRelationshipId](#Relationship_ReqPlanSchedRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_RetailFunctionalityProfileRelationshipId](#Relationship_RetailFunctionalityProfileRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_RetailSalesTaxOverrideGroupRelationshipId](#Relationship_RetailSalesTaxOverrideGroupRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_RetailStoreTableRelationshipId](#Relationship_RetailStoreTableRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_RetailTenderTypeTableRelationshipId](#Relationship_RetailTenderTypeTableRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_RetailTillLayoutRelationshipId](#Relationship_RetailTillLayoutRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|
|[Relationship_TaxGroupHeadingRelationshipId](#Relationship_TaxGroupHeadingRelationshipId)||<a href="RetailPubRetailStoreTable.md" target="_blank">Miscellaneous/RetailPubRetailStoreTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPubRetailStoreTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CategoryHierarchy name="CategoryHierarchy">CategoryHierarchy</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ChannelType name="ChannelType">ChannelType</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustAccount name="DefaultCustAccount">DefaultCustAccount</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustDataAreaId name="DefaultCustDataAreaId">DefaultCustDataAreaId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

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

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InternalOrganization name="InternalOrganization">InternalOrganization</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalOrganization attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#inventLocation name="inventLocation">inventLocation</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the inventLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#inventLocationDataAreaId name="inventLocationDataAreaId">inventLocationDataAreaId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the inventLocationDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMOperatingUnitID name="OMOperatingUnitID">OMOperatingUnitID</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OriginId name="OriginId">OriginId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OriginInstanceRelationType name="OriginInstanceRelationType">OriginInstanceRelationType</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginInstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OriginRecVersion name="OriginRecVersion">OriginRecVersion</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginRecVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PriceIncludesSalesTax name="PriceIncludesSalesTax">PriceIncludesSalesTax</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceIncludesSalesTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransactionServiceProfile name="TransactionServiceProfile">TransactionServiceProfile</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionServiceProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/erp/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeValueSetRelationshipId name="Relationship_DimensionAttributeValueSetRelationshipId">Relationship_DimensionAttributeValueSetRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResCategoryHierarchyRelationshipId name="Relationship_EcoResCategoryHierarchyRelationshipId">Relationship_EcoResCategoryHierarchyRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResCategoryHierarchyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchy.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchy.cdm.json/EcoResCategoryHierarchy</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InternalOrganizationRelationshipId name="Relationship_InternalOrganizationRelationshipId">Relationship_InternalOrganizationRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InternalOrganizationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailInternalOrganization.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailInternalOrganization.cdm.json/RetailInternalOrganization</a></td><td><a href="../Main/RetailInternalOrganization.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventLocationRelationshipId name="Relationship_InventLocationRelationshipId">Relationship_InventLocationRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OMOperatingUnitRelationshipId name="Relationship_OMOperatingUnitRelationshipId">Relationship_OMOperatingUnitRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/OMOperatingUnit.md" target="_blank">/core/erp/Tables/Common/GAB/Main/OMOperatingUnit.cdm.json/OMOperatingUnit</a></td><td><a href="../../../Common/GAB/Main/OMOperatingUnit.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailChannelTableRelationshipId name="Relationship_RetailChannelTableRelationshipId">Relationship_RetailChannelTableRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailChannelTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailChannelTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailChannelTable.cdm.json/RetailChannelTable</a></td><td><a href="../Main/RetailChannelTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionServiceProfileRelationshipId name="Relationship_RetailTransactionServiceProfileRelationshipId">Relationship_RetailTransactionServiceProfileRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionServiceProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/RetailTransactionServiceProfile.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailTransactionServiceProfile.cdm.json/RetailTransactionServiceProfile</a></td><td><a href="../Parameter/RetailTransactionServiceProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#closingMethod name="closingMethod">closingMethod</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the closingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#createLabelsForZeroPrice name="createLabelsForZeroPrice">createLabelsForZeroPrice</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createLabelsForZeroPrice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#cultureName name="cultureName">cultureName</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cultureName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DatabaseName name="DatabaseName">DatabaseName</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DatabaseName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#functionalityProfile name="functionalityProfile">functionalityProfile</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the functionalityProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#generatesItemLabels name="generatesItemLabels">generatesItemLabels</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the generatesItemLabels attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#generatesShelfLabels name="generatesShelfLabels">generatesShelfLabels</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the generatesShelfLabels attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#hideTrainingMode name="hideTrainingMode">hideTrainingMode</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the hideTrainingMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventLocationIdForCustomerOrder name="InventLocationIdForCustomerOrder">InventLocationIdForCustomerOrder</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationIdForCustomerOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#inventoryLookup name="inventoryLookup">inventoryLookup</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the inventoryLookup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#itemIdOnReceipt name="itemIdOnReceipt">itemIdOnReceipt</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the itemIdOnReceipt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#layoutId name="layoutId">layoutId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the layoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#maximumPostingDifference name="maximumPostingDifference">maximumPostingDifference</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumPostingDifference attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maximumTextLengthOnReceipt name="maximumTextLengthOnReceipt">maximumTextLengthOnReceipt</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumTextLengthOnReceipt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#maxRoundingAmount name="maxRoundingAmount">maxRoundingAmount</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxRoundingAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maxRoundingTaxAmount name="maxRoundingTaxAmount">maxRoundingTaxAmount</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxRoundingTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maxShiftDifferenceAmount name="maxShiftDifferenceAmount">maxShiftDifferenceAmount</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxShiftDifferenceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maxTransactionDifferenceAmount name="maxTransactionDifferenceAmount">maxTransactionDifferenceAmount</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxTransactionDifferenceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#numberOfTopOrBottomLines name="numberOfTopOrBottomLines">numberOfTopOrBottomLines</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberOfTopOrBottomLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OfflineProfile name="OfflineProfile">OfflineProfile</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfflineProfile attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#oneStatementPerDay name="oneStatementPerDay">oneStatementPerDay</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the oneStatementPerDay attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#openFrom name="openFrom">openFrom</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the openFrom attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#openTo name="openTo">openTo</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the openTo attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#PackedExtensions name="PackedExtensions">PackedExtensions</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedExtensions attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#Password name="Password">Password</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Password attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#phone name="phone">phone</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the phone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#poItemFilter name="poItemFilter">poItemFilter</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the poItemFilter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#removeAddTender name="removeAddTender">removeAddTender</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the removeAddTender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#replicationCounter name="replicationCounter">replicationCounter</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the replicationCounter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailReqPlanIdSched name="RetailReqPlanIdSched">RetailReqPlanIdSched</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailReqPlanIdSched attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingAccountLedgerDimension name="RoundingAccountLedgerDimension">RoundingAccountLedgerDimension</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingAccountLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#roundingTaxAccount name="roundingTaxAccount">roundingTaxAccount</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the roundingTaxAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#separateStmtPerStaffTerminal name="separateStmtPerStaffTerminal">separateStmtPerStaffTerminal</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the separateStmtPerStaffTerminal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#serviceChargePct name="serviceChargePct">serviceChargePct</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the serviceChargePct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#serviceChargePrompt name="serviceChargePrompt">serviceChargePrompt</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the serviceChargePrompt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SQLServerName name="SQLServerName">SQLServerName</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SQLServerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#statementMethod name="statementMethod">statementMethod</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statementMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#stmtCalcBatchEndTime name="stmtCalcBatchEndTime">stmtCalcBatchEndTime</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stmtCalcBatchEndTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreOriginId name="StoreOriginId">StoreOriginId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreOriginId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#StoreOriginRecVersion name="StoreOriginRecVersion">StoreOriginRecVersion</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreOriginRecVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#taxGroup name="taxGroup">taxGroup</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the taxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroupDataAreaId name="TaxGroupDataAreaId">TaxGroupDataAreaId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroupDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIdentificationNumber name="TaxIdentificationNumber">TaxIdentificationNumber</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIdentificationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOverrideGroup name="TaxOverrideGroup">TaxOverrideGroup</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOverrideGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#tenderDeclarationCalculation name="tenderDeclarationCalculation">tenderDeclarationCalculation</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the tenderDeclarationCalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseCustomerBasedTax name="UseCustomerBasedTax">UseCustomerBasedTax</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseCustomerBasedTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseDefaultCustAccount name="UseDefaultCustAccount">UseDefaultCustAccount</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseDefaultCustAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseDestinationBasedTax name="UseDestinationBasedTax">UseDestinationBasedTax</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseDestinationBasedTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UserName name="UserName">UserName</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#bankDropCalculation name="bankDropCalculation">bankDropCalculation</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the bankDropCalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#startAmountCalculation name="startAmountCalculation">startAmountCalculation</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the startAmountCalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_DimensionAttributeValueCombinationRelationshipId name="Relationship_DimensionAttributeValueCombinationRelationshipId">Relationship_DimensionAttributeValueCombinationRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventLocationForCustomerOrderRelationshipId name="Relationship_InventLocationForCustomerOrderRelationshipId">Relationship_InventLocationForCustomerOrderRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLocationForCustomerOrderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LanguageTableRelationshipId name="Relationship_LanguageTableRelationshipId">Relationship_LanguageTableRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LanguageTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Group/LanguageTable.cdm.json/LanguageTable</a></td><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OfflineProfileRelationshipId name="Relationship_OfflineProfileRelationshipId">Relationship_OfflineProfileRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OfflineProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailOfflineProfile.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailOfflineProfile.cdm.json/RetailOfflineProfile</a></td><td><a href="RetailOfflineProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqPlanSchedRelationshipId name="Relationship_ReqPlanSchedRelationshipId">Relationship_ReqPlanSchedRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqPlanSchedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/MasterPlanning/Group/ReqPlanSched.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/Group/ReqPlanSched.cdm.json/ReqPlanSched</a></td><td><a href="../../../SupplyChain/MasterPlanning/Group/ReqPlanSched.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailFunctionalityProfileRelationshipId name="Relationship_RetailFunctionalityProfileRelationshipId">Relationship_RetailFunctionalityProfileRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailFunctionalityProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/RetailFunctionalityProfile.md" target="_blank">/core/erp/Tables/Commerce/Retail/Group/RetailFunctionalityProfile.cdm.json/RetailFunctionalityProfile</a></td><td><a href="../Group/RetailFunctionalityProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailSalesTaxOverrideGroupRelationshipId name="Relationship_RetailSalesTaxOverrideGroupRelationshipId">Relationship_RetailSalesTaxOverrideGroupRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailSalesTaxOverrideGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/RetailSalesTaxOverrideGroup.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailSalesTaxOverrideGroup.cdm.json/RetailSalesTaxOverrideGroup</a></td><td><a href="../Parameter/RetailSalesTaxOverrideGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreTableRelationshipId name="Relationship_RetailStoreTableRelationshipId">Relationship_RetailStoreTableRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailStoreTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailStoreTable.cdm.json/RetailStoreTable</a></td><td><a href="../Main/RetailStoreTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTenderTypeTableRelationshipId name="Relationship_RetailTenderTypeTableRelationshipId">Relationship_RetailTenderTypeTableRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTenderTypeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailTenderTypeTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailTenderTypeTable.cdm.json/RetailTenderTypeTable</a></td><td><a href="../Main/RetailTenderTypeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTillLayoutRelationshipId name="Relationship_RetailTillLayoutRelationshipId">Relationship_RetailTillLayoutRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTillLayoutRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/RetailTillLayout.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailTillLayout.cdm.json/RetailTillLayout</a></td><td><a href="../Parameter/RetailTillLayout.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxGroupHeadingRelationshipId name="Relationship_TaxGroupHeadingRelationshipId">Relationship_TaxGroupHeadingRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailStoreTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

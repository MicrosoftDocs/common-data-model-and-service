---
title: RetailChannelEntity in ChannelManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Retail channel in ChannelManagement(RetailChannelEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/RetailChannelEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail channel</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RetailChannelId](#RetailChannelId)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[ChannelTimeZone](#ChannelTimeZone)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[ChannelTimeZoneInfoId](#ChannelTimeZoneInfoId)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[DefaultCustomerAccount](#DefaultCustomerAccount)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[DefaultCustomerLegalEntity](#DefaultCustomerLegalEntity)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[TaxGroupCode](#TaxGroupCode)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[TaxGroupLegalEntity](#TaxGroupLegalEntity)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[ChannelType](#ChannelType)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[Currency](#Currency)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[EventNotificationProfileId](#EventNotificationProfileId)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[InventLocation](#InventLocation)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[InventLocationDataAreaId](#InventLocationDataAreaId)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[OMOperatingUnitID](#OMOperatingUnitID)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[Payment](#Payment)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[PaymMode](#PaymMode)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[PriceIncludesSalesTax](#PriceIncludesSalesTax)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[StoreArea](#StoreArea)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[TransactionServiceProfile](#TransactionServiceProfile)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[DisplayTaxPerTaxComponent](#DisplayTaxPerTaxComponent)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[CategoryHierarchyName](#CategoryHierarchyName)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[MCRCustomerCreditRetailInfocodeId](#MCRCustomerCreditRetailInfocodeId)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[MCREnableDirectedSelling](#MCREnableDirectedSelling)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[MCREnableOrderCompletion](#MCREnableOrderCompletion)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[MCREnableOrderPriceControl](#MCREnableOrderPriceControl)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[MCRPriceOverrideRetailInfocodeId](#MCRPriceOverrideRetailInfocodeId)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[MCRReasonCodeRetailInfocodeId](#MCRReasonCodeRetailInfocodeId)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[OnlineCatalogName](#OnlineCatalogName)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[closingMethod](#closingMethod)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[createLabelsForZeroPrice](#createLabelsForZeroPrice)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[cultureName](#cultureName)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[DatabaseName](#DatabaseName)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[EFTStoreNumber](#EFTStoreNumber)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[functionalityProfile](#functionalityProfile)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[generatesItemLabels](#generatesItemLabels)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[generatesShelfLabels](#generatesShelfLabels)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[hideTrainingMode](#hideTrainingMode)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[InventLocationIdForCustomerOrder](#InventLocationIdForCustomerOrder)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[inventoryLookup](#inventoryLookup)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[itemIdOnReceipt](#itemIdOnReceipt)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[maximumPostingDifference](#maximumPostingDifference)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[maximumTextLengthOnReceipt](#maximumTextLengthOnReceipt)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[maxRoundingAmount](#maxRoundingAmount)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[maxRoundingTaxAmount](#maxRoundingTaxAmount)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[maxShiftDifferenceAmount](#maxShiftDifferenceAmount)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[maxTransactionDifferenceAmount](#maxTransactionDifferenceAmount)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[numberOfTopOrBottomLines](#numberOfTopOrBottomLines)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[OfflineProfile](#OfflineProfile)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[oneStatementPerDay](#oneStatementPerDay)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[openFrom](#openFrom)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[openTo](#openTo)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[phone](#phone)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[poItemFilter](#poItemFilter)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[removeAddTender](#removeAddTender)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[RetailReqPlanIdSched](#RetailReqPlanIdSched)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[ReturnTaxGroup_W](#ReturnTaxGroup_W)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[RoundingAccountLedgerDimension](#RoundingAccountLedgerDimension)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[roundingTaxAccount](#roundingTaxAccount)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[separateStmtPerStaffTerminal](#separateStmtPerStaffTerminal)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[serviceChargePct](#serviceChargePct)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[serviceChargePrompt](#serviceChargePrompt)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[SQLServerName](#SQLServerName)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[statementMethod](#statementMethod)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[stmtCalcBatchEndTime](#stmtCalcBatchEndTime)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[stmtPostAsBusinessDay](#stmtPostAsBusinessDay)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[TaxIdentificationNumber](#TaxIdentificationNumber)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[TaxOverrideGroup](#TaxOverrideGroup)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[tenderDeclarationCalculation](#tenderDeclarationCalculation)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[UseCustomerBasedTax](#UseCustomerBasedTax)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[UseDefaultCustAccount](#UseDefaultCustAccount)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[UseDestinationBasedTax](#UseDestinationBasedTax)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[UserName](#UserName)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[OfflineProfileName](#OfflineProfileName)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[RoundingAccountLedgerDimensionDisplayValue](#RoundingAccountLedgerDimensionDisplayValue)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[CategoryHierarchy](#CategoryHierarchy)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[ChannelProfileName](#ChannelProfileName)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[LiveDatabaseConnectionProfileName](#LiveDatabaseConnectionProfileName)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[OperatingUnitPartyNumber](#OperatingUnitPartyNumber)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[Name](#Name)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[TaxOverrideGroupCode](#TaxOverrideGroupCode)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[ManualAccept](#ManualAccept)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[UseCustomerBasedTaxExemption](#UseCustomerBasedTaxExemption)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[RetailReturnPolicyChannel](#RetailReturnPolicyChannel)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[CalcExemptTaxesForPriceInclusive](#CalcExemptTaxesForPriceInclusive)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[BackingTable_RetailChannelTableRelationshipId](#BackingTable_RetailChannelTableRelationshipId)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailChannelEntity.md" target="_blank">ChannelManagement/RetailChannelEntity</a>|

### <a href=#RetailChannelId name="RetailChannelId">RetailChannelId</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChannelTimeZone name="ChannelTimeZone">ChannelTimeZone</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChannelTimeZoneInfoId name="ChannelTimeZoneInfoId">ChannelTimeZoneInfoId</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelTimeZoneInfoId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustomerAccount name="DefaultCustomerAccount">DefaultCustomerAccount</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default customer</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default customer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustomerLegalEntity name="DefaultCustomerLegalEntity">DefaultCustomerLegalEntity</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustomerLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroupCode name="TaxGroupCode">TaxGroupCode</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroupLegalEntity name="TaxGroupLegalEntity">TaxGroupLegalEntity</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroupLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChannelType name="ChannelType">ChannelType</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EventNotificationProfileId name="EventNotificationProfileId">EventNotificationProfileId</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventNotificationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocation name="InventLocation">InventLocation</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationDataAreaId name="InventLocationDataAreaId">InventLocationDataAreaId</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Legal entity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Legal entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMOperatingUnitID name="OMOperatingUnitID">OMOperatingUnitID</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Payment name="Payment">Payment</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Payment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymMode name="PaymMode">PaymMode</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceIncludesSalesTax name="PriceIncludesSalesTax">PriceIncludesSalesTax</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prices include sales tax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceIncludesSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prices include sales tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreArea name="StoreArea">StoreArea</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionServiceProfile name="TransactionServiceProfile">TransactionServiceProfile</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionServiceProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayTaxPerTaxComponent name="DisplayTaxPerTaxComponent">DisplayTaxPerTaxComponent</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayTaxPerTaxComponent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryHierarchyName name="CategoryHierarchyName">CategoryHierarchyName</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCustomerCreditRetailInfocodeId name="MCRCustomerCreditRetailInfocodeId">MCRCustomerCreditRetailInfocodeId</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCustomerCreditRetailInfocodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCREnableDirectedSelling name="MCREnableDirectedSelling">MCREnableDirectedSelling</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCREnableDirectedSelling attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCREnableOrderCompletion name="MCREnableOrderCompletion">MCREnableOrderCompletion</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCREnableOrderCompletion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCREnableOrderPriceControl name="MCREnableOrderPriceControl">MCREnableOrderPriceControl</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCREnableOrderPriceControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRPriceOverrideRetailInfocodeId name="MCRPriceOverrideRetailInfocodeId">MCRPriceOverrideRetailInfocodeId</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRPriceOverrideRetailInfocodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRReasonCodeRetailInfocodeId name="MCRReasonCodeRetailInfocodeId">MCRReasonCodeRetailInfocodeId</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRReasonCodeRetailInfocodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnlineCatalogName name="OnlineCatalogName">OnlineCatalogName</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnlineCatalogName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#closingMethod name="closingMethod">closingMethod</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the closingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#createLabelsForZeroPrice name="createLabelsForZeroPrice">createLabelsForZeroPrice</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createLabelsForZeroPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#cultureName name="cultureName">cultureName</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cultureName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DatabaseName name="DatabaseName">DatabaseName</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DatabaseName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFTStoreNumber name="EFTStoreNumber">EFTStoreNumber</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFTStoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#functionalityProfile name="functionalityProfile">functionalityProfile</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the functionalityProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#generatesItemLabels name="generatesItemLabels">generatesItemLabels</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the generatesItemLabels attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#generatesShelfLabels name="generatesShelfLabels">generatesShelfLabels</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the generatesShelfLabels attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#hideTrainingMode name="hideTrainingMode">hideTrainingMode</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the hideTrainingMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationIdForCustomerOrder name="InventLocationIdForCustomerOrder">InventLocationIdForCustomerOrder</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationIdForCustomerOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#inventoryLookup name="inventoryLookup">inventoryLookup</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the inventoryLookup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#itemIdOnReceipt name="itemIdOnReceipt">itemIdOnReceipt</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the itemIdOnReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#maximumPostingDifference name="maximumPostingDifference">maximumPostingDifference</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumPostingDifference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#maximumTextLengthOnReceipt name="maximumTextLengthOnReceipt">maximumTextLengthOnReceipt</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumTextLengthOnReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#maxRoundingAmount name="maxRoundingAmount">maxRoundingAmount</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxRoundingAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#maxRoundingTaxAmount name="maxRoundingTaxAmount">maxRoundingTaxAmount</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxRoundingTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#maxShiftDifferenceAmount name="maxShiftDifferenceAmount">maxShiftDifferenceAmount</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxShiftDifferenceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#maxTransactionDifferenceAmount name="maxTransactionDifferenceAmount">maxTransactionDifferenceAmount</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxTransactionDifferenceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#numberOfTopOrBottomLines name="numberOfTopOrBottomLines">numberOfTopOrBottomLines</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberOfTopOrBottomLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OfflineProfile name="OfflineProfile">OfflineProfile</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfflineProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#oneStatementPerDay name="oneStatementPerDay">oneStatementPerDay</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the oneStatementPerDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#openFrom name="openFrom">openFrom</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the openFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#openTo name="openTo">openTo</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the openTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#phone name="phone">phone</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the phone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#poItemFilter name="poItemFilter">poItemFilter</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the poItemFilter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#removeAddTender name="removeAddTender">removeAddTender</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the removeAddTender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailReqPlanIdSched name="RetailReqPlanIdSched">RetailReqPlanIdSched</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailReqPlanIdSched attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnTaxGroup_W name="ReturnTaxGroup_W">ReturnTaxGroup_W</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnTaxGroup_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingAccountLedgerDimension name="RoundingAccountLedgerDimension">RoundingAccountLedgerDimension</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingAccountLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#roundingTaxAccount name="roundingTaxAccount">roundingTaxAccount</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the roundingTaxAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#separateStmtPerStaffTerminal name="separateStmtPerStaffTerminal">separateStmtPerStaffTerminal</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the separateStmtPerStaffTerminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#serviceChargePct name="serviceChargePct">serviceChargePct</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the serviceChargePct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#serviceChargePrompt name="serviceChargePrompt">serviceChargePrompt</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the serviceChargePrompt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SQLServerName name="SQLServerName">SQLServerName</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SQLServerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#statementMethod name="statementMethod">statementMethod</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statementMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#stmtCalcBatchEndTime name="stmtCalcBatchEndTime">stmtCalcBatchEndTime</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stmtCalcBatchEndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#stmtPostAsBusinessDay name="stmtPostAsBusinessDay">stmtPostAsBusinessDay</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stmtPostAsBusinessDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIdentificationNumber name="TaxIdentificationNumber">TaxIdentificationNumber</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIdentificationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOverrideGroup name="TaxOverrideGroup">TaxOverrideGroup</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOverrideGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#tenderDeclarationCalculation name="tenderDeclarationCalculation">tenderDeclarationCalculation</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the tenderDeclarationCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseCustomerBasedTax name="UseCustomerBasedTax">UseCustomerBasedTax</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseCustomerBasedTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseDefaultCustAccount name="UseDefaultCustAccount">UseDefaultCustAccount</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseDefaultCustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseDestinationBasedTax name="UseDestinationBasedTax">UseDestinationBasedTax</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseDestinationBasedTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserName name="UserName">UserName</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OfflineProfileName name="OfflineProfileName">OfflineProfileName</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfflineProfileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingAccountLedgerDimensionDisplayValue name="RoundingAccountLedgerDimensionDisplayValue">RoundingAccountLedgerDimensionDisplayValue</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingAccountLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryHierarchy name="CategoryHierarchy">CategoryHierarchy</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChannelProfileName name="ChannelProfileName">ChannelProfileName</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Channel profile name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelProfileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Channel profile name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LiveDatabaseConnectionProfileName name="LiveDatabaseConnectionProfileName">LiveDatabaseConnectionProfileName</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Live Database Connection Profile Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LiveDatabaseConnectionProfileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Live Database Connection Profile Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitPartyNumber name="OperatingUnitPartyNumber">OperatingUnitPartyNumber</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

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

### <a href=#TaxOverrideGroupCode name="TaxOverrideGroupCode">TaxOverrideGroupCode</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOverrideGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualAccept name="ManualAccept">ManualAccept</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual accept</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualAccept attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manual accept</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseCustomerBasedTaxExemption name="UseCustomerBasedTaxExemption">UseCustomerBasedTaxExemption</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseCustomerBasedTaxExemption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailReturnPolicyChannel name="RetailReturnPolicyChannel">RetailReturnPolicyChannel</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailReturnPolicyChannel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalcExemptTaxesForPriceInclusive name="CalcExemptTaxesForPriceInclusive">CalcExemptTaxesForPriceInclusive</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcExemptTaxesForPriceInclusive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

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

### <a href=#BackingTable_RetailChannelTableRelationshipId name="BackingTable_RetailChannelTableRelationshipId">BackingTable_RetailChannelTableRelationshipId</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailChannelTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/ChannelManagement/Main/RetailChannelTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/Main/RetailChannelTable.cdm.json/RetailChannelTable</a></td><td><a href="../../../Tables/Commerce/ChannelManagement/Main/RetailChannelTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ChannelManagement/RetailChannelEntity (this entity)  

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

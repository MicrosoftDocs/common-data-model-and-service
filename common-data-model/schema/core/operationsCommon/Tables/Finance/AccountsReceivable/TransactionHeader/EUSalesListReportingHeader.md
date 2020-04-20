---
title: EUSalesListReportingHeader - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# EUSalesListReportingHeader

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsReceivable/TransactionHeader/EUSalesListReportingHeader.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EUSalesListReportingHeader/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[AmountCount](#AmountCount)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[AuthorizedByRole_CZ](#AuthorizedByRole_CZ)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[ChangeInPeriodicity_ES](#ChangeInPeriodicity_ES)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[ChangeInPeriodicity_HU](#ChangeInPeriodicity_HU)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[CompanyBuildNum_HU](#CompanyBuildNum_HU)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[CompanyCountryName_CZ](#CompanyCountryName_CZ)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[CompanyDoorNum_HU](#CompanyDoorNum_HU)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[CompanyFloorNum_HU](#CompanyFloorNum_HU)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[CompanyNameAppendix_CZ](#CompanyNameAppendix_CZ)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[CompanyStairwayNum_HU](#CompanyStairwayNum_HU)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[ContactInfo_LT](#ContactInfo_LT)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[ContactPersonId](#ContactPersonId)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[ControlRef_BE](#ControlRef_BE)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[Correction](#Correction)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[CustomerInformation_AT](#CustomerInformation_AT)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[EUSalesListCorrectedDeclaration_ES](#EUSalesListCorrectedDeclaration_ES)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[EUSalesListCorrectionType_ES](#EUSalesListCorrectionType_ES)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[EUSalesListDocumentNumber_ES](#EUSalesListDocumentNumber_ES)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[EUSalesListNotificationType_DE](#EUSalesListNotificationType_DE)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[EUSalesListPresentationType_ES](#EUSalesListPresentationType_ES)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[EUSalesListRegistrationId_DE](#EUSalesListRegistrationId_DE)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[EUSalesListTaxCode](#EUSalesListTaxCode)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[EUSalesListTransferPurchases](#EUSalesListTransferPurchases)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[FilingDate](#FilingDate)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[FilledByFirstName_CZ](#FilledByFirstName_CZ)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[FilledByLastName_CZ](#FilledByLastName_CZ)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[FromDate](#FromDate)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[HcmWorkerRecId](#HcmWorkerRecId)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[LegalEntity](#LegalEntity)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[LineCount](#LineCount)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[LineCountCorrections_ES](#LineCountCorrections_ES)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[LogisticsPostalAddressAlternate](#LogisticsPostalAddressAlternate)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[OfficialDeclaration_BE](#OfficialDeclaration_BE)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[ParticipantNumber_DE](#ParticipantNumber_DE)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[PersonTitle](#PersonTitle)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[Phone](#Phone)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[ReplacementDeclarationRef](#ReplacementDeclarationRef)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[ReportingPeriodType](#ReportingPeriodType)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[ReportType_LT](#ReportType_LT)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[StrippedVATNum](#StrippedVATNum)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TaxAuthority](#TaxAuthority)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TaxIntraCommTable_NL](#TaxIntraCommTable_NL)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[ToDate](#ToDate)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TotalAmountCorrections_ES](#TotalAmountCorrections_ES)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TotalAmountItems](#TotalAmountItems)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TotalAmountPropertyMoving_CZ](#TotalAmountPropertyMoving_CZ)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TotalAmountPurchasedOnBehalf_LV](#TotalAmountPurchasedOnBehalf_LV)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TotalAmountServices](#TotalAmountServices)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TotalAmountTriangular](#TotalAmountTriangular)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TotalAmountTriangularIntermediate_HU](#TotalAmountTriangularIntermediate_HU)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TotalCancelledAmountItems](#TotalCancelledAmountItems)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TotalCancelledAmountPropertyMoving_CZ](#TotalCancelledAmountPropertyMoving_CZ)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TotalCancelledAmountServices](#TotalCancelledAmountServices)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[TotalCancelledAmountTriangular](#TotalCancelledAmountTriangular)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[UserId_LT](#UserId_LT)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[CompanyCoRegNum](#CompanyCoRegNum)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[CompanyVATNum](#CompanyVATNum)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[DataAreaId](#DataAreaId)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[Relationship_ContactPersonRelationshipId](#Relationship_ContactPersonRelationshipId)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[Relationship_LegalEntityRelationshipId](#Relationship_LegalEntityRelationshipId)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[Relationship_LogisticsPostalAddressAlternateRelationshipId](#Relationship_LogisticsPostalAddressAlternateRelationshipId)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[Relationship_TaxAuthorityRelationshipId](#Relationship_TaxAuthorityRelationshipId)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[Relationship_TaxIntraCommTable_NLRelationshipId](#Relationship_TaxIntraCommTable_NLRelationshipId)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EUSalesListReportingHeader.md" target="_blank">TransactionHeader/EUSalesListReportingHeader</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EUSalesListReportingHeader/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountCount name="AmountCount">AmountCount</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AuthorizedByRole_CZ name="AuthorizedByRole_CZ">AuthorizedByRole_CZ</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuthorizedByRole_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangeInPeriodicity_ES name="ChangeInPeriodicity_ES">ChangeInPeriodicity_ES</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeInPeriodicity_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ChangeInPeriodicity_HU name="ChangeInPeriodicity_HU">ChangeInPeriodicity_HU</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeInPeriodicity_HU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CompanyBuildNum_HU name="CompanyBuildNum_HU">CompanyBuildNum_HU</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyBuildNum_HU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCountryName_CZ name="CompanyCountryName_CZ">CompanyCountryName_CZ</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCountryName_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyDoorNum_HU name="CompanyDoorNum_HU">CompanyDoorNum_HU</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyDoorNum_HU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyFloorNum_HU name="CompanyFloorNum_HU">CompanyFloorNum_HU</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyFloorNum_HU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyNameAppendix_CZ name="CompanyNameAppendix_CZ">CompanyNameAppendix_CZ</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyNameAppendix_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyStairwayNum_HU name="CompanyStairwayNum_HU">CompanyStairwayNum_HU</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyStairwayNum_HU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactInfo_LT name="ContactInfo_LT">ContactInfo_LT</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactInfo_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ControlRef_BE name="ControlRef_BE">ControlRef_BE</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ControlRef_BE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Correction name="Correction">Correction</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Correction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomerInformation_AT name="CustomerInformation_AT">CustomerInformation_AT</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerInformation_AT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EUSalesListCorrectedDeclaration_ES name="EUSalesListCorrectedDeclaration_ES">EUSalesListCorrectedDeclaration_ES</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListCorrectedDeclaration_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EUSalesListCorrectionType_ES name="EUSalesListCorrectionType_ES">EUSalesListCorrectionType_ES</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListCorrectionType_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EUSalesListDocumentNumber_ES name="EUSalesListDocumentNumber_ES">EUSalesListDocumentNumber_ES</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListDocumentNumber_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EUSalesListNotificationType_DE name="EUSalesListNotificationType_DE">EUSalesListNotificationType_DE</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListNotificationType_DE attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EUSalesListPresentationType_ES name="EUSalesListPresentationType_ES">EUSalesListPresentationType_ES</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListPresentationType_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EUSalesListRegistrationId_DE name="EUSalesListRegistrationId_DE">EUSalesListRegistrationId_DE</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListRegistrationId_DE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EUSalesListTaxCode name="EUSalesListTaxCode">EUSalesListTaxCode</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListTaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EUSalesListTransferPurchases name="EUSalesListTransferPurchases">EUSalesListTransferPurchases</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListTransferPurchases attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FilingDate name="FilingDate">FilingDate</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilingDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FilledByFirstName_CZ name="FilledByFirstName_CZ">FilledByFirstName_CZ</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilledByFirstName_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FilledByLastName_CZ name="FilledByLastName_CZ">FilledByLastName_CZ</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilledByLastName_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#HcmWorkerRecId name="HcmWorkerRecId">HcmWorkerRecId</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HcmWorkerRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineCount name="LineCount">LineCount</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineCountCorrections_ES name="LineCountCorrections_ES">LineCountCorrections_ES</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineCountCorrections_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LogisticsPostalAddressAlternate name="LogisticsPostalAddressAlternate">LogisticsPostalAddressAlternate</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalAddressAlternate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OfficialDeclaration_BE name="OfficialDeclaration_BE">OfficialDeclaration_BE</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfficialDeclaration_BE attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ParticipantNumber_DE name="ParticipantNumber_DE">ParticipantNumber_DE</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParticipantNumber_DE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonTitle name="PersonTitle">PersonTitle</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Phone name="Phone">Phone</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Phone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplacementDeclarationRef name="ReplacementDeclarationRef">ReplacementDeclarationRef</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplacementDeclarationRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingPeriodType name="ReportingPeriodType">ReportingPeriodType</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingPeriodType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReportType_LT name="ReportType_LT">ReportType_LT</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportType_LT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StrippedVATNum name="StrippedVATNum">StrippedVATNum</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StrippedVATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAuthority name="TaxAuthority">TaxAuthority</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAuthority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIntraCommTable_NL name="TaxIntraCommTable_NL">TaxIntraCommTable_NL</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIntraCommTable_NL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TotalAmountCorrections_ES name="TotalAmountCorrections_ES">TotalAmountCorrections_ES</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmountCorrections_ES attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalAmountItems name="TotalAmountItems">TotalAmountItems</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmountItems attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalAmountPropertyMoving_CZ name="TotalAmountPropertyMoving_CZ">TotalAmountPropertyMoving_CZ</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmountPropertyMoving_CZ attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalAmountPurchasedOnBehalf_LV name="TotalAmountPurchasedOnBehalf_LV">TotalAmountPurchasedOnBehalf_LV</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmountPurchasedOnBehalf_LV attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalAmountServices name="TotalAmountServices">TotalAmountServices</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmountServices attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalAmountTriangular name="TotalAmountTriangular">TotalAmountTriangular</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmountTriangular attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalAmountTriangularIntermediate_HU name="TotalAmountTriangularIntermediate_HU">TotalAmountTriangularIntermediate_HU</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmountTriangularIntermediate_HU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalCancelledAmountItems name="TotalCancelledAmountItems">TotalCancelledAmountItems</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalCancelledAmountItems attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalCancelledAmountPropertyMoving_CZ name="TotalCancelledAmountPropertyMoving_CZ">TotalCancelledAmountPropertyMoving_CZ</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalCancelledAmountPropertyMoving_CZ attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalCancelledAmountServices name="TotalCancelledAmountServices">TotalCancelledAmountServices</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalCancelledAmountServices attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalCancelledAmountTriangular name="TotalCancelledAmountTriangular">TotalCancelledAmountTriangular</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalCancelledAmountTriangular attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UserId_LT name="UserId_LT">UserId_LT</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserId_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCoRegNum name="CompanyCoRegNum">CompanyCoRegNum</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCoRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyVATNum name="CompanyVATNum">CompanyVATNum</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyVATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

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

### <a href=#Relationship_ContactPersonRelationshipId name="Relationship_ContactPersonRelationshipId">Relationship_ContactPersonRelationshipId</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ContactPersonRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Main/ContactPerson.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/ContactPerson.cdm.json/ContactPerson</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Main/ContactPerson.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LegalEntityRelationshipId name="Relationship_LegalEntityRelationshipId">Relationship_LegalEntityRelationshipId</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LegalEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LogisticsPostalAddressAlternateRelationshipId name="Relationship_LogisticsPostalAddressAlternateRelationshipId">Relationship_LogisticsPostalAddressAlternateRelationshipId</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsPostalAddressAlternateRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxAuthorityRelationshipId name="Relationship_TaxAuthorityRelationshipId">Relationship_TaxAuthorityRelationshipId</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAuthorityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxAuthorityAddress.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxAuthorityAddress.cdm.json/TaxAuthorityAddress</a></td><td><a href="../../Tax/Group/TaxAuthorityAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxIntraCommTable_NLRelationshipId name="Relationship_TaxIntraCommTable_NLRelationshipId">Relationship_TaxIntraCommTable_NLRelationshipId</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIntraCommTable_NLRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Transaction/TaxIntraCommTable_NL.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxIntraCommTable_NL.cdm.json/TaxIntraCommTable_NL</a></td><td><a href="../../Tax/Transaction/TaxIntraCommTable_NL.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionHeader/EUSalesListReportingHeader (this entity)  

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

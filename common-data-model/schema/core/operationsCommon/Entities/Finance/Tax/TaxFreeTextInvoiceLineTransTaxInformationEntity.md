---
title: TaxFreeTextInvoiceLineTransTaxInformationEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Free text invoice line transaction tax information in Tax(TaxFreeTextInvoiceLineTransTaxInformationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Free text invoice line transaction tax information</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ParentRecId](#ParentRecId)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[LineNumber](#LineNumber)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[BankLocation](#BankLocation)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[BankTaxInformation](#BankTaxInformation)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[CompanyLocation](#CompanyLocation)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[CompanyTaxInformation](#CompanyTaxInformation)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[CSTSchedule](#CSTSchedule)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[CustomerLocation](#CustomerLocation)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[CustomerTaxInformation](#CustomerTaxInformation)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[CustomsIECRegistrationNumber](#CustomsIECRegistrationNumber)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[CustomsTariffCode](#CustomsTariffCode)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[CustomsTariffDirection](#CustomsTariffDirection)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[Direction](#Direction)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ExciseCENVATCreditAvailed](#ExciseCENVATCreditAvailed)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ExciseConsignment](#ExciseConsignment)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ExciseDirectSettlement](#ExciseDirectSettlement)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ExciseDisposalType](#ExciseDisposalType)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ExciseDSA](#ExciseDSA)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ExciseECCRegistrationNumber](#ExciseECCRegistrationNumber)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ExciseIsScrap](#ExciseIsScrap)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ExciseRecordType](#ExciseRecordType)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ExciseTariffCodes](#ExciseTariffCodes)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ExciseType](#ExciseType)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[Exempt](#Exempt)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[GSTINRegistrationNumber](#GSTINRegistrationNumber)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[HSNCode](#HSNCode)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[InclTax](#InclTax)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ITCCategory](#ITCCategory)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[NonBusinessUsagePercentage](#NonBusinessUsagePercentage)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[SalesTaxFormTypes](#SalesTaxFormTypes)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[SalesTaxRegistrationNumber](#SalesTaxRegistrationNumber)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ServiceAccountingCode](#ServiceAccountingCode)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ServiceCategory](#ServiceCategory)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ServiceCode](#ServiceCode)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ServiceTaxConsignmentNoteNum](#ServiceTaxConsignmentNoteNum)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ServiceTaxGTAServiceCategory](#ServiceTaxGTAServiceCategory)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ServiceTaxIsRecoverable](#ServiceTaxIsRecoverable)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[ServiceTaxRegistrationNumber](#ServiceTaxRegistrationNumber)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[TANRegistrationNumber](#TANRegistrationNumber)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[TaxID](#TaxID)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[TaxInventVATItemId](#TaxInventVATItemId)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[TaxWithholdAcknowledgementNumber](#TaxWithholdAcknowledgementNumber)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[TaxWithholdCountryRegionToRemittance](#TaxWithholdCountryRegionToRemittance)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[TaxWithholdNatureOfAssessee](#TaxWithholdNatureOfAssessee)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[TaxWithholdNatureOfRemittance](#TaxWithholdNatureOfRemittance)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[TaxWithholdSoftwareDeclReceived](#TaxWithholdSoftwareDeclReceived)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[Type](#Type)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[VATCommodityCode](#VATCommodityCode)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[VATGoodsType](#VATGoodsType)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[VATNonRecoverablePercent](#VATNonRecoverablePercent)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[VATSchedule](#VATSchedule)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[VATTINRegistrationNumber](#VATTINRegistrationNumber)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[VendorLocation](#VendorLocation)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[VendorTaxInformation](#VendorTaxInformation)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[BackingTable_TransTaxInformationEntityRelationshipId](#BackingTable_TransTaxInformationEntityRelationshipId)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TaxFreeTextInvoiceLineTransTaxInformationEntity.md" target="_blank">Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity</a>|

### <a href=#ParentRecId name="ParentRecId">ParentRecId</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

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

### <a href=#BankLocation name="BankLocation">BankLocation</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankTaxInformation name="BankTaxInformation">BankTaxInformation</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankTaxInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyLocation name="CompanyLocation">CompanyLocation</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyTaxInformation name="CompanyTaxInformation">CompanyTaxInformation</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyTaxInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CSTSchedule name="CSTSchedule">CSTSchedule</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CSTSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerLocation name="CustomerLocation">CustomerLocation</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerTaxInformation name="CustomerTaxInformation">CustomerTaxInformation</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTaxInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsIECRegistrationNumber name="CustomsIECRegistrationNumber">CustomsIECRegistrationNumber</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsIECRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsTariffCode name="CustomsTariffCode">CustomsTariffCode</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsTariffCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsTariffDirection name="CustomsTariffDirection">CustomsTariffDirection</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsTariffDirection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Direction name="Direction">Direction</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Direction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseCENVATCreditAvailed name="ExciseCENVATCreditAvailed">ExciseCENVATCreditAvailed</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseCENVATCreditAvailed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseConsignment name="ExciseConsignment">ExciseConsignment</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseConsignment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseDirectSettlement name="ExciseDirectSettlement">ExciseDirectSettlement</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseDirectSettlement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseDisposalType name="ExciseDisposalType">ExciseDisposalType</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseDisposalType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseDSA name="ExciseDSA">ExciseDSA</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseDSA attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseECCRegistrationNumber name="ExciseECCRegistrationNumber">ExciseECCRegistrationNumber</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseECCRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseIsScrap name="ExciseIsScrap">ExciseIsScrap</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseIsScrap attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseRecordType name="ExciseRecordType">ExciseRecordType</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseRecordType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseTariffCodes name="ExciseTariffCodes">ExciseTariffCodes</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseTariffCodes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseType name="ExciseType">ExciseType</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Exempt name="Exempt">Exempt</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Exempt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTINRegistrationNumber name="GSTINRegistrationNumber">GSTINRegistrationNumber</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTINRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HSNCode name="HSNCode">HSNCode</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HSNCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InclTax name="InclTax">InclTax</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ITCCategory name="ITCCategory">ITCCategory</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ITCCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NonBusinessUsagePercentage name="NonBusinessUsagePercentage">NonBusinessUsagePercentage</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonBusinessUsagePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxFormTypes name="SalesTaxFormTypes">SalesTaxFormTypes</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxFormTypes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxRegistrationNumber name="SalesTaxRegistrationNumber">SalesTaxRegistrationNumber</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceAccountingCode name="ServiceAccountingCode">ServiceAccountingCode</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAccountingCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceCategory name="ServiceCategory">ServiceCategory</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceCode name="ServiceCode">ServiceCode</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTaxConsignmentNoteNum name="ServiceTaxConsignmentNoteNum">ServiceTaxConsignmentNoteNum</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxConsignmentNoteNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTaxGTAServiceCategory name="ServiceTaxGTAServiceCategory">ServiceTaxGTAServiceCategory</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxGTAServiceCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTaxIsRecoverable name="ServiceTaxIsRecoverable">ServiceTaxIsRecoverable</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxIsRecoverable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTaxRegistrationNumber name="ServiceTaxRegistrationNumber">ServiceTaxRegistrationNumber</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TANRegistrationNumber name="TANRegistrationNumber">TANRegistrationNumber</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TANRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxID name="TaxID">TaxID</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxInventVATItemId name="TaxInventVATItemId">TaxInventVATItemId</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInventVATItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdAcknowledgementNumber name="TaxWithholdAcknowledgementNumber">TaxWithholdAcknowledgementNumber</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdAcknowledgementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdCountryRegionToRemittance name="TaxWithholdCountryRegionToRemittance">TaxWithholdCountryRegionToRemittance</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCountryRegionToRemittance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdNatureOfAssessee name="TaxWithholdNatureOfAssessee">TaxWithholdNatureOfAssessee</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdNatureOfAssessee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdNatureOfRemittance name="TaxWithholdNatureOfRemittance">TaxWithholdNatureOfRemittance</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdNatureOfRemittance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdSoftwareDeclReceived name="TaxWithholdSoftwareDeclReceived">TaxWithholdSoftwareDeclReceived</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdSoftwareDeclReceived attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

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

### <a href=#VATCommodityCode name="VATCommodityCode">VATCommodityCode</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATCommodityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATGoodsType name="VATGoodsType">VATGoodsType</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATGoodsType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATNonRecoverablePercent name="VATNonRecoverablePercent">VATNonRecoverablePercent</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATNonRecoverablePercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATSchedule name="VATSchedule">VATSchedule</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATTINRegistrationNumber name="VATTINRegistrationNumber">VATTINRegistrationNumber</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATTINRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorLocation name="VendorLocation">VendorLocation</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorTaxInformation name="VendorTaxInformation">VendorTaxInformation</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorTaxInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TransTaxInformationEntityRelationshipId name="BackingTable_TransTaxInformationEntityRelationshipId">BackingTable_TransTaxInformationEntityRelationshipId</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TransTaxInformationEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Tax/TaxFreeTextInvoiceLineTransTaxInformationEntity (this entity)  

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

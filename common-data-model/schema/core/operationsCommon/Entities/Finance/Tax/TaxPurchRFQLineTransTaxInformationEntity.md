---
title: TaxPurchRFQLineTransTaxInformationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Purch RFQ line transaction tax information

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxPurchRFQLineTransTaxInformationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purch RFQ line transaction tax information</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[VendorTaxInformation](#VendorTaxInformation)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[BankLocation](#BankLocation)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[BankTaxInformation](#BankTaxInformation)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[CompanyLocation](#CompanyLocation)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[CompanyTaxInformation](#CompanyTaxInformation)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[CSTSchedule](#CSTSchedule)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[CustomerLocation](#CustomerLocation)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[CustomerTaxInformation](#CustomerTaxInformation)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[CustomsIECRegistrationNumber](#CustomsIECRegistrationNumber)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[CustomsTariffCode](#CustomsTariffCode)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[CustomsTariffDirection](#CustomsTariffDirection)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[Direction](#Direction)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ExciseCENVATCreditAvailed](#ExciseCENVATCreditAvailed)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ExciseConsignment](#ExciseConsignment)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ExciseDirectSettlement](#ExciseDirectSettlement)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ExciseDisposalType](#ExciseDisposalType)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ExciseDSA](#ExciseDSA)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ExciseECCRegistrationNumber](#ExciseECCRegistrationNumber)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ExciseIsScrap](#ExciseIsScrap)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ExciseRecordType](#ExciseRecordType)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ExciseTariffCodes](#ExciseTariffCodes)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ExciseType](#ExciseType)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[Exempt](#Exempt)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[GSTINRegistrationNumber](#GSTINRegistrationNumber)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[HSNCode](#HSNCode)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[InclTax](#InclTax)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ITCCategory](#ITCCategory)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[NonBusinessUsagePercentage](#NonBusinessUsagePercentage)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[SalesTaxFormTypes](#SalesTaxFormTypes)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[SalesTaxRegistrationNumber](#SalesTaxRegistrationNumber)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ServiceAccountingCode](#ServiceAccountingCode)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ServiceCategory](#ServiceCategory)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ServiceCode](#ServiceCode)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ServiceTaxConsignmentNoteNum](#ServiceTaxConsignmentNoteNum)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ServiceTaxGTAServiceCategory](#ServiceTaxGTAServiceCategory)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ServiceTaxIsRecoverable](#ServiceTaxIsRecoverable)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[ServiceTaxRegistrationNumber](#ServiceTaxRegistrationNumber)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[TANRegistrationNumber](#TANRegistrationNumber)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[TaxID](#TaxID)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[TaxInventVATItemId](#TaxInventVATItemId)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[TaxWithholdAcknowledgementNumber](#TaxWithholdAcknowledgementNumber)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[TaxWithholdCountryRegionToRemittance](#TaxWithholdCountryRegionToRemittance)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[TaxWithholdNatureOfAssessee](#TaxWithholdNatureOfAssessee)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[TaxWithholdNatureOfRemittance](#TaxWithholdNatureOfRemittance)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[TaxWithholdSoftwareDeclReceived](#TaxWithholdSoftwareDeclReceived)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[Type](#Type)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[VATCommodityCode](#VATCommodityCode)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[VATGoodsType](#VATGoodsType)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[VATNonRecoverablePercent](#VATNonRecoverablePercent)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[VATSchedule](#VATSchedule)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[VATTINRegistrationNumber](#VATTINRegistrationNumber)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[VendorLocation](#VendorLocation)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[RFQId](#RFQId)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[LineNum](#LineNum)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[BackingTable_TransTaxInformationEntityRelationshipId](#BackingTable_TransTaxInformationEntityRelationshipId)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TaxPurchRFQLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchRFQLineTransTaxInformationEntity</a>|

### <a href=#VendorTaxInformation name="VendorTaxInformation">VendorTaxInformation</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorTaxInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankLocation name="BankLocation">BankLocation</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankTaxInformation name="BankTaxInformation">BankTaxInformation</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankTaxInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyLocation name="CompanyLocation">CompanyLocation</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyTaxInformation name="CompanyTaxInformation">CompanyTaxInformation</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyTaxInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CSTSchedule name="CSTSchedule">CSTSchedule</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CSTSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerLocation name="CustomerLocation">CustomerLocation</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerTaxInformation name="CustomerTaxInformation">CustomerTaxInformation</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTaxInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsIECRegistrationNumber name="CustomsIECRegistrationNumber">CustomsIECRegistrationNumber</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsIECRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsTariffCode name="CustomsTariffCode">CustomsTariffCode</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsTariffCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsTariffDirection name="CustomsTariffDirection">CustomsTariffDirection</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsTariffDirection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Direction name="Direction">Direction</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Direction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseCENVATCreditAvailed name="ExciseCENVATCreditAvailed">ExciseCENVATCreditAvailed</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseCENVATCreditAvailed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseConsignment name="ExciseConsignment">ExciseConsignment</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseConsignment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseDirectSettlement name="ExciseDirectSettlement">ExciseDirectSettlement</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseDirectSettlement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseDisposalType name="ExciseDisposalType">ExciseDisposalType</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseDisposalType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseDSA name="ExciseDSA">ExciseDSA</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseDSA attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseECCRegistrationNumber name="ExciseECCRegistrationNumber">ExciseECCRegistrationNumber</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseECCRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseIsScrap name="ExciseIsScrap">ExciseIsScrap</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseIsScrap attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseRecordType name="ExciseRecordType">ExciseRecordType</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseRecordType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseTariffCodes name="ExciseTariffCodes">ExciseTariffCodes</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseTariffCodes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseType name="ExciseType">ExciseType</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Exempt name="Exempt">Exempt</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Exempt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTINRegistrationNumber name="GSTINRegistrationNumber">GSTINRegistrationNumber</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTINRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HSNCode name="HSNCode">HSNCode</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HSNCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InclTax name="InclTax">InclTax</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ITCCategory name="ITCCategory">ITCCategory</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ITCCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NonBusinessUsagePercentage name="NonBusinessUsagePercentage">NonBusinessUsagePercentage</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonBusinessUsagePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxFormTypes name="SalesTaxFormTypes">SalesTaxFormTypes</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxFormTypes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxRegistrationNumber name="SalesTaxRegistrationNumber">SalesTaxRegistrationNumber</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceAccountingCode name="ServiceAccountingCode">ServiceAccountingCode</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAccountingCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceCategory name="ServiceCategory">ServiceCategory</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceCode name="ServiceCode">ServiceCode</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTaxConsignmentNoteNum name="ServiceTaxConsignmentNoteNum">ServiceTaxConsignmentNoteNum</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxConsignmentNoteNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTaxGTAServiceCategory name="ServiceTaxGTAServiceCategory">ServiceTaxGTAServiceCategory</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxGTAServiceCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTaxIsRecoverable name="ServiceTaxIsRecoverable">ServiceTaxIsRecoverable</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxIsRecoverable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTaxRegistrationNumber name="ServiceTaxRegistrationNumber">ServiceTaxRegistrationNumber</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TANRegistrationNumber name="TANRegistrationNumber">TANRegistrationNumber</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TANRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxID name="TaxID">TaxID</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxInventVATItemId name="TaxInventVATItemId">TaxInventVATItemId</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInventVATItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdAcknowledgementNumber name="TaxWithholdAcknowledgementNumber">TaxWithholdAcknowledgementNumber</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdAcknowledgementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdCountryRegionToRemittance name="TaxWithholdCountryRegionToRemittance">TaxWithholdCountryRegionToRemittance</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCountryRegionToRemittance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdNatureOfAssessee name="TaxWithholdNatureOfAssessee">TaxWithholdNatureOfAssessee</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdNatureOfAssessee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdNatureOfRemittance name="TaxWithholdNatureOfRemittance">TaxWithholdNatureOfRemittance</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdNatureOfRemittance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdSoftwareDeclReceived name="TaxWithholdSoftwareDeclReceived">TaxWithholdSoftwareDeclReceived</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdSoftwareDeclReceived attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATCommodityCode name="VATCommodityCode">VATCommodityCode</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATCommodityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATGoodsType name="VATGoodsType">VATGoodsType</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATGoodsType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATNonRecoverablePercent name="VATNonRecoverablePercent">VATNonRecoverablePercent</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATNonRecoverablePercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATSchedule name="VATSchedule">VATSchedule</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATTINRegistrationNumber name="VATTINRegistrationNumber">VATTINRegistrationNumber</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATTINRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorLocation name="VendorLocation">VendorLocation</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQId name="RFQId">RFQId</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TransTaxInformationEntityRelationshipId name="BackingTable_TransTaxInformationEntityRelationshipId">BackingTable_TransTaxInformationEntityRelationshipId</a>

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchRFQLineTransTaxInformationEntity (this entity)  

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

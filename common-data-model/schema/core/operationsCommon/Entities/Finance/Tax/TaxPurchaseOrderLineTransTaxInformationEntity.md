---
title: TaxPurchaseOrderLineTransTaxInformationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# TaxPurchaseOrderLineTransTaxInformationEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxPurchaseOrderLineTransTaxInformationEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[BankLocation](#BankLocation)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[BankTaxInformation](#BankTaxInformation)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[CompanyLocation](#CompanyLocation)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[CompanyTaxInformation](#CompanyTaxInformation)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[CSTSchedule](#CSTSchedule)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[CustomerLocation](#CustomerLocation)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[CustomerTaxInformation](#CustomerTaxInformation)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[CustomsIECRegistrationNumber](#CustomsIECRegistrationNumber)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[CustomsTariffCode](#CustomsTariffCode)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[CustomsTariffDirection](#CustomsTariffDirection)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[Direction](#Direction)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ExciseCENVATCreditAvailed](#ExciseCENVATCreditAvailed)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ExciseConsignment](#ExciseConsignment)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ExciseDirectSettlement](#ExciseDirectSettlement)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ExciseDisposalType](#ExciseDisposalType)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ExciseDSA](#ExciseDSA)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ExciseECCRegistrationNumber](#ExciseECCRegistrationNumber)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ExciseIsScrap](#ExciseIsScrap)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ExciseRecordType](#ExciseRecordType)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ExciseTariffCodes](#ExciseTariffCodes)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ExciseType](#ExciseType)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[Exempt](#Exempt)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[GSTINRegistrationNumber](#GSTINRegistrationNumber)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[HSNCode](#HSNCode)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[InclTax](#InclTax)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ITCCategory](#ITCCategory)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[NonBusinessUsagePercentage](#NonBusinessUsagePercentage)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[SalesTaxFormTypes](#SalesTaxFormTypes)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[SalesTaxRegistrationNumber](#SalesTaxRegistrationNumber)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ServiceAccountingCode](#ServiceAccountingCode)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ServiceCategory](#ServiceCategory)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ServiceCode](#ServiceCode)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ServiceTaxConsignmentNoteNum](#ServiceTaxConsignmentNoteNum)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ServiceTaxGTAServiceCategory](#ServiceTaxGTAServiceCategory)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ServiceTaxIsRecoverable](#ServiceTaxIsRecoverable)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[ServiceTaxRegistrationNumber](#ServiceTaxRegistrationNumber)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[TANRegistrationNumber](#TANRegistrationNumber)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[TaxID](#TaxID)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[TaxInventVATItemId](#TaxInventVATItemId)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[TaxWithholdAcknowledgementNumber](#TaxWithholdAcknowledgementNumber)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[TaxWithholdCountryRegionToRemittance](#TaxWithholdCountryRegionToRemittance)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[TaxWithholdNatureOfAssessee](#TaxWithholdNatureOfAssessee)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[TaxWithholdNatureOfRemittance](#TaxWithholdNatureOfRemittance)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[TaxWithholdSoftwareDeclReceived](#TaxWithholdSoftwareDeclReceived)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[Type](#Type)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[VATCommodityCode](#VATCommodityCode)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[VATGoodsType](#VATGoodsType)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[VATNonRecoverablePercent](#VATNonRecoverablePercent)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[VATSchedule](#VATSchedule)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[VATTINRegistrationNumber](#VATTINRegistrationNumber)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[VendorLocation](#VendorLocation)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[VendorTaxInformation](#VendorTaxInformation)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[PurchaseOrderLineNumber](#PurchaseOrderLineNumber)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[PurchaseOrderNumber](#PurchaseOrderNumber)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[BackingTable_TransTaxInformationEntityRelationshipId](#BackingTable_TransTaxInformationEntityRelationshipId)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TaxPurchaseOrderLineTransTaxInformationEntity.md" target="_blank">Tax/TaxPurchaseOrderLineTransTaxInformationEntity</a>|

### <a href=#BankLocation name="BankLocation">BankLocation</a>

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

### <a href=#VendorTaxInformation name="VendorTaxInformation">VendorTaxInformation</a>

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

### <a href=#PurchaseOrderLineNumber name="PurchaseOrderLineNumber">PurchaseOrderLineNumber</a>

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderNumber name="PurchaseOrderNumber">PurchaseOrderNumber</a>

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TransTaxInformationEntityRelationshipId name="BackingTable_TransTaxInformationEntityRelationshipId">BackingTable_TransTaxInformationEntityRelationshipId</a>

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

First included in: Tax/TaxPurchaseOrderLineTransTaxInformationEntity (this entity)  

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

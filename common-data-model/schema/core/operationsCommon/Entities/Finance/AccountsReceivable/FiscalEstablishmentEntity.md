---
title: FiscalEstablishmentEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Fiscal establishment in AccountsReceivable(FiscalEstablishmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/FiscalEstablishmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal establishment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Accountant](#Accountant)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[CCM](#CCM)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[CNPJ](#CNPJ)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[Address](#Address)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[NFeAuthority](#NFeAuthority)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[PrintDanfeWhenAproved](#PrintDanfeWhenAproved)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[BlockPostingNotValidatedNfeXml](#BlockPostingNotValidatedNfeXml)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[NFeDigitalCertificate](#NFeDigitalCertificate)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[EmailTemplateApprovedNFe](#EmailTemplateApprovedNFe)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[EmailTemplateCanceledNFe](#EmailTemplateCanceledNFe)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[EmailTemplateCorrectionLetterNFe](#EmailTemplateCorrectionLetterNFe)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[NFeEnvironment](#NFeEnvironment)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[PreprintedSecurityForm](#PreprintedSecurityForm)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[SendDanfePdfInEmail](#SendDanfePdfInEmail)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[ValidateXmlSchema](#ValidateXmlSchema)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[NFeVersion](#NFeVersion)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[FciToIntrastateEnabled](#FciToIntrastateEnabled)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[FiscalEstablishmentGroup](#FiscalEstablishmentGroup)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[SalesIssuer](#SalesIssuer)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[FiscalOrganization](#FiscalOrganization)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[IE](#IE)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[ClosedWarehouse](#ClosedWarehouse)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[Name](#Name)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[NextFiscalPrinterDailyReportNumber](#NextFiscalPrinterDailyReportNumber)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[NIRE](#NIRE)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[SPEDContribReportingType](#SPEDContribReportingType)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[MatchNfeXmlOnPosting](#MatchNfeXmlOnPosting)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[NFCeAuthority](#NFCeAuthority)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[CSC](#CSC)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[CSCToken](#CSCToken)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[NFCeEmailApproved](#NFCeEmailApproved)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[NFCeEnvironment](#NFCeEnvironment)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[NFCeSendPdfInEmail](#NFCeSendPdfInEmail)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[NFCeVersion](#NFCeVersion)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[AccountantCPF](#AccountantCPF)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[AccountantCRC](#AccountantCRC)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[AddressLocation](#AddressLocation)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[AddressParty](#AddressParty)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[PartyNumber](#PartyNumber)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[AddressName](#AddressName)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[FiscalEstablishmentGroupId](#FiscalEstablishmentGroupId)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[FiscalEstablishmentSalesIssuerId](#FiscalEstablishmentSalesIssuerId)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[EFDocNFe402018005v110](#EFDocNFe402018005v110)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[EFDocNFeTechNotes](#EFDocNFeTechNotes)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[BackingTable_FiscalEstablishment_BRRelationshipId](#BackingTable_FiscalEstablishment_BRRelationshipId)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="FiscalEstablishmentEntity.md" target="_blank">AccountsReceivable/FiscalEstablishmentEntity</a>|

### <a href=#Accountant name="Accountant">Accountant</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Accountant attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CCM name="CCM">CCM</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CCM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CNPJ name="CNPJ">CNPJ</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CNPJ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Address name="Address">Address</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Address attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NFeAuthority name="NFeAuthority">NFeAuthority</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NFeAuthority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintDanfeWhenAproved name="PrintDanfeWhenAproved">PrintDanfeWhenAproved</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintDanfeWhenAproved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BlockPostingNotValidatedNfeXml name="BlockPostingNotValidatedNfeXml">BlockPostingNotValidatedNfeXml</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockPostingNotValidatedNfeXml attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NFeDigitalCertificate name="NFeDigitalCertificate">NFeDigitalCertificate</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NFeDigitalCertificate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailTemplateApprovedNFe name="EmailTemplateApprovedNFe">EmailTemplateApprovedNFe</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailTemplateApprovedNFe attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailTemplateCanceledNFe name="EmailTemplateCanceledNFe">EmailTemplateCanceledNFe</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailTemplateCanceledNFe attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailTemplateCorrectionLetterNFe name="EmailTemplateCorrectionLetterNFe">EmailTemplateCorrectionLetterNFe</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailTemplateCorrectionLetterNFe attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NFeEnvironment name="NFeEnvironment">NFeEnvironment</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NFeEnvironment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreprintedSecurityForm name="PreprintedSecurityForm">PreprintedSecurityForm</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreprintedSecurityForm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SendDanfePdfInEmail name="SendDanfePdfInEmail">SendDanfePdfInEmail</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SendDanfePdfInEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateXmlSchema name="ValidateXmlSchema">ValidateXmlSchema</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateXmlSchema attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NFeVersion name="NFeVersion">NFeVersion</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NFeVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FciToIntrastateEnabled name="FciToIntrastateEnabled">FciToIntrastateEnabled</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FciToIntrastateEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentGroup name="FiscalEstablishmentGroup">FiscalEstablishmentGroup</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

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

### <a href=#SalesIssuer name="SalesIssuer">SalesIssuer</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesIssuer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalOrganization name="FiscalOrganization">FiscalOrganization</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOrganization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IE name="IE">IE</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedWarehouse name="ClosedWarehouse">ClosedWarehouse</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

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

### <a href=#NextFiscalPrinterDailyReportNumber name="NextFiscalPrinterDailyReportNumber">NextFiscalPrinterDailyReportNumber</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextFiscalPrinterDailyReportNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NIRE name="NIRE">NIRE</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NIRE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SPEDContribReportingType name="SPEDContribReportingType">SPEDContribReportingType</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDContribReportingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MatchNfeXmlOnPosting name="MatchNfeXmlOnPosting">MatchNfeXmlOnPosting</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchNfeXmlOnPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NFCeAuthority name="NFCeAuthority">NFCeAuthority</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NFCeAuthority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CSC name="CSC">CSC</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CSC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CSCToken name="CSCToken">CSCToken</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CSCToken attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NFCeEmailApproved name="NFCeEmailApproved">NFCeEmailApproved</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NFCeEmailApproved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NFCeEnvironment name="NFCeEnvironment">NFCeEnvironment</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NFCeEnvironment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NFCeSendPdfInEmail name="NFCeSendPdfInEmail">NFCeSendPdfInEmail</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NFCeSendPdfInEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NFCeVersion name="NFCeVersion">NFCeVersion</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NFCeVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountantCPF name="AccountantCPF">AccountantCPF</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountantCRC name="AccountantCRC">AccountantCRC</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantCRC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocation name="AddressLocation">AddressLocation</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressParty name="AddressParty">AddressParty</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressName name="AddressName">AddressName</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentGroupId name="FiscalEstablishmentGroupId">FiscalEstablishmentGroupId</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentSalesIssuerId name="FiscalEstablishmentSalesIssuerId">FiscalEstablishmentSalesIssuerId</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentSalesIssuerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFDocNFe402018005v110 name="EFDocNFe402018005v110">EFDocNFe402018005v110</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocNFe402018005v110 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFDocNFeTechNotes name="EFDocNFeTechNotes">EFDocNFeTechNotes</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocNFeTechNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_FiscalEstablishment_BRRelationshipId name="BackingTable_FiscalEstablishment_BRRelationshipId">BackingTable_FiscalEstablishment_BRRelationshipId</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FiscalEstablishment_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Main/FiscalEstablishment_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FiscalEstablishment_BR.cdm.json/FiscalEstablishment_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Main/FiscalEstablishment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/FiscalEstablishmentEntity (this entity)  

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

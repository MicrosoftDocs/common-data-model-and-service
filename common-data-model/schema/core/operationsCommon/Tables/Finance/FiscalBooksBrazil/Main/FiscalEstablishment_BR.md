---
title: FiscalEstablishment_BR in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Fiscal establishment in Main(FiscalEstablishment_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FiscalEstablishment_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FiscalEstablishment_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

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
|[RecId](#RecId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Accountant_BR](#Accountant_BR)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[CCMNum_BR](#CCMNum_BR)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[CNPJCPFNum_BR](#CNPJCPFNum_BR)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[DirPartyLocation](#DirPartyLocation)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocAuthority](#EFDocAuthority)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocAutomaticPrinting](#EFDocAutomaticPrinting)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocBlockPostingNotValidatedXml](#EFDocBlockPostingNotValidatedXml)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocDigitalCertificateSubject](#EFDocDigitalCertificateSubject)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocEmailApproved](#EFDocEmailApproved)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocEmailCanceled](#EFDocEmailCanceled)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocEmailEvent](#EFDocEmailEvent)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocEnvironment](#EFDocEnvironment)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocPrePrintedSecurityForm](#EFDocPrePrintedSecurityForm)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocSendPdfInEmail](#EFDocSendPdfInEmail)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocValidateSchemaOnPosting](#EFDocValidateSchemaOnPosting)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocVersion](#EFDocVersion)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[FciToIntrastateEnabled](#FciToIntrastateEnabled)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[FiscalEstablishmentGroup_BR](#FiscalEstablishmentGroup_BR)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[FiscalEstablishmentSalesIssuer](#FiscalEstablishmentSalesIssuer)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[FiscalOrganization_BR](#FiscalOrganization_BR)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[IENum_BR](#IENum_BR)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[IsClosedWarehouse](#IsClosedWarehouse)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Name](#Name)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[NextFiscalPrinterDailyReportNumber](#NextFiscalPrinterDailyReportNumber)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[NIRE](#NIRE)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[SPEDContribReportingType](#SPEDContribReportingType)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocMatchNfeXmlOnPosting](#EFDocMatchNfeXmlOnPosting)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[ConsumerEFDocAuthority](#ConsumerEFDocAuthority)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[ConsumerEFDocCsc](#ConsumerEFDocCsc)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[ConsumerEFDocCscToken](#ConsumerEFDocCscToken)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[ConsumerEFDocEmailApproved](#ConsumerEFDocEmailApproved)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[ConsumerEFDocEnvironment](#ConsumerEFDocEnvironment)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[ConsumerEFDocSendPdfInEmail](#ConsumerEFDocSendPdfInEmail)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[ConsumerEFDocVersion](#ConsumerEFDocVersion)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocNFe402018005v110](#EFDocNFe402018005v110)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocNFeTechNotes](#EFDocNFeTechNotes)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[TechnicalResponsibleCNPJ](#TechnicalResponsibleCNPJ)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[TechnicalResponsibleContactName](#TechnicalResponsibleContactName)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[TechnicalResponsibleEmail](#TechnicalResponsibleEmail)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[TechnicalResponsiblePhone](#TechnicalResponsiblePhone)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[TechnicalResponsibleIdCSRT](#TechnicalResponsibleIdCSRT)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[TechnicalResponsibleCSRT](#TechnicalResponsibleCSRT)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[SPEDContribReportingTypeNFe](#SPEDContribReportingTypeNFe)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[SPEDContribReportingTypeNFCe](#SPEDContribReportingTypeNFCe)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[EFDocKeyVaultCertificateRef](#EFDocKeyVaultCertificateRef)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_AccountantRelationshipId](#Relationship_AccountantRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_DirPartyLocationRelationshipId](#Relationship_DirPartyLocationRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_EFDocApprovedEmailTemplateRelationshipId](#Relationship_EFDocApprovedEmailTemplateRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_EFDocAuthorityRelationshipId](#Relationship_EFDocAuthorityRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_EFDocCanceledEmailTemplateRelationshipId](#Relationship_EFDocCanceledEmailTemplateRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_EFDocEventEmailTemplateRelationshipId](#Relationship_EFDocEventEmailTemplateRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_EFDocWebServicesRelationshipId](#Relationship_EFDocWebServicesRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_FiscalEstablishmentGroupRelationshipId](#Relationship_FiscalEstablishmentGroupRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_FiscalOrganizationRelationshipId](#Relationship_FiscalOrganizationRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_ConsumerEFDocApprovedEmailTemplateRelationshipId](#Relationship_ConsumerEFDocApprovedEmailTemplateRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_ConsumerEFDocAuthorityRelationshipId](#Relationship_ConsumerEFDocAuthorityRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_ConsumerEFDocWebServicesRelationshipId](#Relationship_ConsumerEFDocWebServicesRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_EFDocKeyVaultCertificateTableRelationshipId](#Relationship_EFDocKeyVaultCertificateTableRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="FiscalEstablishment_BR.md" target="_blank">Main/FiscalEstablishment_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FiscalEstablishment_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Accountant_BR name="Accountant_BR">Accountant_BR</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Accountant_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CCMNum_BR name="CCMNum_BR">CCMNum_BR</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CCMNum_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CNPJCPFNum_BR name="CNPJCPFNum_BR">CNPJCPFNum_BR</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CNPJ</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CNPJCPFNum_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CNPJ</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirPartyLocation name="DirPartyLocation">DirPartyLocation</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirPartyLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EFDocAuthority name="EFDocAuthority">EFDocAuthority</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocAuthority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFDocAutomaticPrinting name="EFDocAutomaticPrinting">EFDocAutomaticPrinting</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocAutomaticPrinting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EFDocBlockPostingNotValidatedXml name="EFDocBlockPostingNotValidatedXml">EFDocBlockPostingNotValidatedXml</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post only NF-e that have valid access keys</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocBlockPostingNotValidatedXml attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Post only NF-e that have valid access keys</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EFDocDigitalCertificateSubject name="EFDocDigitalCertificateSubject">EFDocDigitalCertificateSubject</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocDigitalCertificateSubject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFDocEmailApproved name="EFDocEmailApproved">EFDocEmailApproved</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Approved NF-e</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocEmailApproved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Approved NF-e</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFDocEmailCanceled name="EFDocEmailCanceled">EFDocEmailCanceled</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Canceled NF-e</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocEmailCanceled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Canceled NF-e</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFDocEmailEvent name="EFDocEmailEvent">EFDocEmailEvent</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Correction letter</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocEmailEvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Correction letter</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFDocEnvironment name="EFDocEnvironment">EFDocEnvironment</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocEnvironment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EFDocPrePrintedSecurityForm name="EFDocPrePrintedSecurityForm">EFDocPrePrintedSecurityForm</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preprinted security form</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocPrePrintedSecurityForm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Preprinted security form</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EFDocSendPdfInEmail name="EFDocSendPdfInEmail">EFDocSendPdfInEmail</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attach the DANFE as PDF file to  email</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocSendPdfInEmail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attach the DANFE as PDF file to  email</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EFDocValidateSchemaOnPosting name="EFDocValidateSchemaOnPosting">EFDocValidateSchemaOnPosting</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocValidateSchemaOnPosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EFDocVersion name="EFDocVersion">EFDocVersion</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FciToIntrastateEnabled name="FciToIntrastateEnabled">FciToIntrastateEnabled</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>FCI applies to intrastate operations</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FciToIntrastateEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>FCI applies to intrastate operations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FiscalEstablishmentGroup_BR name="FiscalEstablishmentGroup_BR">FiscalEstablishmentGroup_BR</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentGroup_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentSalesIssuer name="FiscalEstablishmentSalesIssuer">FiscalEstablishmentSalesIssuer</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales issuer</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentSalesIssuer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales issuer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalOrganization_BR name="FiscalOrganization_BR">FiscalOrganization_BR</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOrganization_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IENum_BR name="IENum_BR">IENum_BR</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IENum_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsClosedWarehouse name="IsClosedWarehouse">IsClosedWarehouse</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is closed warehouse</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsClosedWarehouse attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is closed warehouse</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

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

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next ECF Daily Operation Report Number</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextFiscalPrinterDailyReportNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Next ECF Daily Operation Report Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#NIRE name="NIRE">NIRE</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

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

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDContribReportingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EFDocMatchNfeXmlOnPosting name="EFDocMatchNfeXmlOnPosting">EFDocMatchNfeXmlOnPosting</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Block NF-e posting if XML does not match</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocMatchNfeXmlOnPosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Block NF-e posting if XML does not match</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ConsumerEFDocAuthority name="ConsumerEFDocAuthority">ConsumerEFDocAuthority</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDocAuthority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumerEFDocCsc name="ConsumerEFDocCsc">ConsumerEFDocCsc</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDocCsc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumerEFDocCscToken name="ConsumerEFDocCscToken">ConsumerEFDocCscToken</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDocCscToken attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumerEFDocEmailApproved name="ConsumerEFDocEmailApproved">ConsumerEFDocEmailApproved</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Approved NFC-e</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDocEmailApproved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Approved NFC-e</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumerEFDocEnvironment name="ConsumerEFDocEnvironment">ConsumerEFDocEnvironment</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDocEnvironment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ConsumerEFDocSendPdfInEmail name="ConsumerEFDocSendPdfInEmail">ConsumerEFDocSendPdfInEmail</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attach the DANFE NFC-e as a PDF file to email</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDocSendPdfInEmail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attach the DANFE NFC-e as a PDF file to email</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ConsumerEFDocVersion name="ConsumerEFDocVersion">ConsumerEFDocVersion</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The version of the NFC-e feature</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDocVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The version of the NFC-e feature</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EFDocNFe402018005v110 name="EFDocNFe402018005v110">EFDocNFe402018005v110</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable NF-e technical notes</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocNFe402018005v110 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enable NF-e technical notes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EFDocNFeTechNotes name="EFDocNFeTechNotes">EFDocNFeTechNotes</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocNFeTechNotes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TechnicalResponsibleCNPJ name="TechnicalResponsibleCNPJ">TechnicalResponsibleCNPJ</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechnicalResponsibleCNPJ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalResponsibleContactName name="TechnicalResponsibleContactName">TechnicalResponsibleContactName</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechnicalResponsibleContactName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalResponsibleEmail name="TechnicalResponsibleEmail">TechnicalResponsibleEmail</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechnicalResponsibleEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalResponsiblePhone name="TechnicalResponsiblePhone">TechnicalResponsiblePhone</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechnicalResponsiblePhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalResponsibleIdCSRT name="TechnicalResponsibleIdCSRT">TechnicalResponsibleIdCSRT</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechnicalResponsibleIdCSRT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalResponsibleCSRT name="TechnicalResponsibleCSRT">TechnicalResponsibleCSRT</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechnicalResponsibleCSRT attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SPEDContribReportingTypeNFe name="SPEDContribReportingTypeNFe">SPEDContribReportingTypeNFe</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>NFe and ECF (Fiscal receipts)</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDContribReportingTypeNFe attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>NFe and ECF (Fiscal receipts)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SPEDContribReportingTypeNFCe name="SPEDContribReportingTypeNFCe">SPEDContribReportingTypeNFCe</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>NFCe</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDContribReportingTypeNFCe attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>NFCe</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EFDocKeyVaultCertificateRef name="EFDocKeyVaultCertificateRef">EFDocKeyVaultCertificateRef</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Certificate</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocKeyVaultCertificateRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Certificate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

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

### <a href=#Relationship_AccountantRelationshipId name="Relationship_AccountantRelationshipId">Relationship_AccountantRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountantRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/Accountant_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/Accountant_BR.cdm.json/Accountant_BR</a></td><td><a href="../../Ledger/Main/Accountant_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DirPartyLocationRelationshipId name="Relationship_DirPartyLocationRelationshipId">Relationship_DirPartyLocationRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DirPartyLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/DirPartyLocation.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/DirPartyLocation.cdm.json/DirPartyLocation</a></td><td><a href="../../../Common/GAB/Main/DirPartyLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EFDocApprovedEmailTemplateRelationshipId name="Relationship_EFDocApprovedEmailTemplateRelationshipId">Relationship_EFDocApprovedEmailTemplateRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDocApprovedEmailTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailTable.cdm.json/SysEmailTable</a></td><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EFDocAuthorityRelationshipId name="Relationship_EFDocAuthorityRelationshipId">Relationship_EFDocAuthorityRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDocAuthorityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/EFDocAuthority_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocAuthority_BR.cdm.json/EFDocAuthority_BR</a></td><td><a href="../Miscellaneous/EFDocAuthority_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EFDocCanceledEmailTemplateRelationshipId name="Relationship_EFDocCanceledEmailTemplateRelationshipId">Relationship_EFDocCanceledEmailTemplateRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDocCanceledEmailTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailTable.cdm.json/SysEmailTable</a></td><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EFDocEventEmailTemplateRelationshipId name="Relationship_EFDocEventEmailTemplateRelationshipId">Relationship_EFDocEventEmailTemplateRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDocEventEmailTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailTable.cdm.json/SysEmailTable</a></td><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EFDocWebServicesRelationshipId name="Relationship_EFDocWebServicesRelationshipId">Relationship_EFDocWebServicesRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDocWebServicesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/EFDocWebServiceParameters_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocWebServiceParameters_BR.cdm.json/EFDocWebServiceParameters_BR</a></td><td><a href="../Miscellaneous/EFDocWebServiceParameters_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalEstablishmentGroupRelationshipId name="Relationship_FiscalEstablishmentGroupRelationshipId">Relationship_FiscalEstablishmentGroupRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalEstablishmentGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/FiscalEstablishmentGroup_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Group/FiscalEstablishmentGroup_BR.cdm.json/FiscalEstablishmentGroup_BR</a></td><td><a href="../Group/FiscalEstablishmentGroup_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalOrganizationRelationshipId name="Relationship_FiscalOrganizationRelationshipId">Relationship_FiscalOrganizationRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalOrganizationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FiscalOrganization_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FiscalOrganization_BR.cdm.json/FiscalOrganization_BR</a></td><td><a href="FiscalOrganization_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ConsumerEFDocApprovedEmailTemplateRelationshipId name="Relationship_ConsumerEFDocApprovedEmailTemplateRelationshipId">Relationship_ConsumerEFDocApprovedEmailTemplateRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConsumerEFDocApprovedEmailTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailTable.cdm.json/SysEmailTable</a></td><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ConsumerEFDocAuthorityRelationshipId name="Relationship_ConsumerEFDocAuthorityRelationshipId">Relationship_ConsumerEFDocAuthorityRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConsumerEFDocAuthorityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/EFDocAuthority_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocAuthority_BR.cdm.json/EFDocAuthority_BR</a></td><td><a href="../Miscellaneous/EFDocAuthority_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ConsumerEFDocWebServicesRelationshipId name="Relationship_ConsumerEFDocWebServicesRelationshipId">Relationship_ConsumerEFDocWebServicesRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConsumerEFDocWebServicesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/EFDocWebServiceParameters_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocWebServiceParameters_BR.cdm.json/EFDocWebServiceParameters_BR</a></td><td><a href="../Miscellaneous/EFDocWebServiceParameters_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EFDocKeyVaultCertificateTableRelationshipId name="Relationship_EFDocKeyVaultCertificateTableRelationshipId">Relationship_EFDocKeyVaultCertificateTableRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDocKeyVaultCertificateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.cdm.json/KeyVaultCertificateTable</a></td><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/FiscalEstablishment_BR (this entity)  

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

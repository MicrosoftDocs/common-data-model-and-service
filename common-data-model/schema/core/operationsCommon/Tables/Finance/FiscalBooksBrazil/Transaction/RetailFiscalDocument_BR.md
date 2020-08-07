---
title: RetailFiscalDocument_BR in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Retail Fiscal Document in Transaction(RetailFiscalDocument_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/RetailFiscalDocument_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFiscalDocument_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail Fiscal Document</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[AccessKey](#AccessKey)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ApplicationVersion](#ApplicationVersion)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[AuthorityCode](#AuthorityCode)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[Channel](#Channel)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ConsumerEFDocInquiryUrl](#ConsumerEFDocInquiryUrl)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ContingencyDateTime](#ContingencyDateTime)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ContingencyDateTimeOffset](#ContingencyDateTimeOffset)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ContingencyMode](#ContingencyMode)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ContingencyReason](#ContingencyReason)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[DanfePrintFormat](#DanfePrintFormat)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[Direction](#Direction)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[EnvironmentType](#EnvironmentType)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FEAddressBacenCode](#FEAddressBacenCode)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FEAddressCity](#FEAddressCity)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FEAddressComplement](#FEAddressComplement)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FEAddressCountry](#FEAddressCountry)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FEAddressDistrict](#FEAddressDistrict)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FEAddressIBGECode](#FEAddressIBGECode)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FEAddressState](#FEAddressState)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FEAddressStreet](#FEAddressStreet)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FEAddressStreetNumber](#FEAddressStreetNumber)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FEAddressZipCode](#FEAddressZipCode)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FinalUser](#FinalUser)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalDocumentAccountNum](#FiscalDocumentAccountNum)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalDocumentDateTime](#FiscalDocumentDateTime)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalDocumentDateTimeOffset](#FiscalDocumentDateTimeOffset)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalDocumentNumber](#FiscalDocumentNumber)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalDocumentSeries](#FiscalDocumentSeries)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalEstablishment](#FiscalEstablishment)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalEstablishmentCCMNum](#FiscalEstablishmentCCMNum)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalEstablishmentCNAE](#FiscalEstablishmentCNAE)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalEstablishmentCNPJCPF](#FiscalEstablishmentCNPJCPF)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalEstablishmentIE](#FiscalEstablishmentIE)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalEstablishmentName](#FiscalEstablishmentName)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalEstablishmentPhone](#FiscalEstablishmentPhone)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalEstablishmentPostalAddress](#FiscalEstablishmentPostalAddress)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[MessageStatus](#MessageStatus)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[MessageType](#MessageType)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[Model](#Model)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[NumericCode](#NumericCode)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[OperationDescription](#OperationDescription)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[PresenceType](#PresenceType)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ProtocolDate](#ProtocolDate)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ProtocolNumber](#ProtocolNumber)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[QrcodeText](#QrcodeText)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ReceiptNumber](#ReceiptNumber)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ReceiptType](#ReceiptType)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ReplicationCounterFromOrigin](#ReplicationCounterFromOrigin)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ReturnCodeDescription](#ReturnCodeDescription)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ReturnCodeRefRecId](#ReturnCodeRefRecId)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ReturnMessage](#ReturnMessage)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[Status](#Status)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[store](#store)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[terminal](#terminal)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyAddressBacenCode](#ThirdPartyAddressBacenCode)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyAddressCity](#ThirdPartyAddressCity)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyAddressComplement](#ThirdPartyAddressComplement)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyAddressCountry](#ThirdPartyAddressCountry)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyAddressCountryRegionId](#ThirdPartyAddressCountryRegionId)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyAddressDistrict](#ThirdPartyAddressDistrict)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyAddressIBGECode](#ThirdPartyAddressIBGECode)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyAddressState](#ThirdPartyAddressState)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyAddressStreet](#ThirdPartyAddressStreet)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyAddressStreetNumber](#ThirdPartyAddressStreetNumber)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyAddressZipCode](#ThirdPartyAddressZipCode)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyCNPJCPF](#ThirdPartyCNPJCPF)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyEmail](#ThirdPartyEmail)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyForeignerId](#ThirdPartyForeignerId)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyName](#ThirdPartyName)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyPhone](#ThirdPartyPhone)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyPostalAddress](#ThirdPartyPostalAddress)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TotalAmount](#TotalAmount)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TotalGoodsAmount](#TotalGoodsAmount)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TotalMarkupFreightAmount](#TotalMarkupFreightAmount)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TotalMarkupInsuranceAmount](#TotalMarkupInsuranceAmount)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TotalMarkupOtherAmount](#TotalMarkupOtherAmount)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TotalServicesAmount](#TotalServicesAmount)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[transactionId](#transactionId)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[XmlRequest](#XmlRequest)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[XmlResponse](#XmlResponse)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[XmlReturnRequest](#XmlReturnRequest)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[XmlReturnResponse](#XmlReturnResponse)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[Purpose](#Purpose)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[SendByEmail](#SendByEmail)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyFormattedAddress](#ThirdPartyFormattedAddress)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyICMSContributor](#ThirdPartyICMSContributor)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ThirdPartyIE](#ThirdPartyIE)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[ChangeAmount](#ChangeAmount)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[EFRRegisterNumber](#EFRRegisterNumber)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[EFRSignature](#EFRSignature)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TaxAuthorityInfo](#TaxAuthorityInfo)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[OriginalDiscountAmount](#OriginalDiscountAmount)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[SoftwareHouseCNPJ](#SoftwareHouseCNPJ)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[FiscalEstablishmentTradeName](#FiscalEstablishmentTradeName)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TechnicalResponsibleCNPJ](#TechnicalResponsibleCNPJ)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TechnicalResponsibleContactName](#TechnicalResponsibleContactName)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TechnicalResponsibleEmail](#TechnicalResponsibleEmail)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[TechnicalResponsiblePhone](#TechnicalResponsiblePhone)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[Relationship_EFDReturnCode_BRRelationshipId](#Relationship_EFDReturnCode_BRRelationshipId)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[Relationship_FiscalEstablishmentPostalAddressRelationshipId](#Relationship_FiscalEstablishmentPostalAddressRelationshipId)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[Relationship_ThirdPartyPostalAddressRelationshipId](#Relationship_ThirdPartyPostalAddressRelationshipId)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailFiscalDocument_BR.md" target="_blank">Transaction/RetailFiscalDocument_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFiscalDocument_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccessKey name="AccessKey">AccessKey</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccessKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicationVersion name="ApplicationVersion">ApplicationVersion</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuthorityCode name="AuthorityCode">AuthorityCode</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuthorityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ConsumerEFDocInquiryUrl name="ConsumerEFDocInquiryUrl">ConsumerEFDocInquiryUrl</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Internet address for NFC-e inquiry</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDocInquiryUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Internet address for NFC-e inquiry</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContingencyDateTime name="ContingencyDateTime">ContingencyDateTime</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContingencyDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ContingencyDateTimeOffset name="ContingencyDateTimeOffset">ContingencyDateTimeOffset</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContingencyDateTimeOffset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ContingencyMode name="ContingencyMode">ContingencyMode</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContingencyMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ContingencyReason name="ContingencyReason">ContingencyReason</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContingencyReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DanfePrintFormat name="DanfePrintFormat">DanfePrintFormat</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The print format for DANFE</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DanfePrintFormat attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The print format for DANFE</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Direction name="Direction">Direction</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Direction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#EnvironmentType name="EnvironmentType">EnvironmentType</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FEAddressBacenCode name="FEAddressBacenCode">FEAddressBacenCode</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEAddressBacenCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FEAddressCity name="FEAddressCity">FEAddressCity</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FEAddressComplement name="FEAddressComplement">FEAddressComplement</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEAddressComplement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FEAddressCountry name="FEAddressCountry">FEAddressCountry</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEAddressCountry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FEAddressDistrict name="FEAddressDistrict">FEAddressDistrict</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEAddressDistrict attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FEAddressIBGECode name="FEAddressIBGECode">FEAddressIBGECode</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEAddressIBGECode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FEAddressState name="FEAddressState">FEAddressState</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEAddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FEAddressStreet name="FEAddressStreet">FEAddressStreet</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FEAddressStreetNumber name="FEAddressStreetNumber">FEAddressStreetNumber</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FEAddressZipCode name="FEAddressZipCode">FEAddressZipCode</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinalUser name="FinalUser">FinalUser</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinalUser attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FiscalDocumentAccountNum name="FiscalDocumentAccountNum">FiscalDocumentAccountNum</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentDateTime name="FiscalDocumentDateTime">FiscalDocumentDateTime</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#FiscalDocumentDateTimeOffset name="FiscalDocumentDateTimeOffset">FiscalDocumentDateTimeOffset</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentDateTimeOffset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocumentNumber name="FiscalDocumentNumber">FiscalDocumentNumber</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSeries name="FiscalDocumentSeries">FiscalDocumentSeries</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSeries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishment name="FiscalEstablishment">FiscalEstablishment</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentCCMNum name="FiscalEstablishmentCCMNum">FiscalEstablishmentCCMNum</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentCCMNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentCNAE name="FiscalEstablishmentCNAE">FiscalEstablishmentCNAE</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentCNAE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentCNPJCPF name="FiscalEstablishmentCNPJCPF">FiscalEstablishmentCNPJCPF</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentCNPJCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentIE name="FiscalEstablishmentIE">FiscalEstablishmentIE</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentIE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentName name="FiscalEstablishmentName">FiscalEstablishmentName</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentName attribute are listed below.</summary>

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

### <a href=#FiscalEstablishmentPhone name="FiscalEstablishmentPhone">FiscalEstablishmentPhone</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentPostalAddress name="FiscalEstablishmentPostalAddress">FiscalEstablishmentPostalAddress</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MessageStatus name="MessageStatus">MessageStatus</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MessageType name="MessageType">MessageType</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Model name="Model">Model</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Model</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Model attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Model</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumericCode name="NumericCode">NumericCode</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Numeric code</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumericCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Numeric code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#OperationDescription name="OperationDescription">OperationDescription</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PresenceType name="PresenceType">PresenceType</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresenceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProtocolDate name="ProtocolDate">ProtocolDate</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProtocolDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ProtocolNumber name="ProtocolNumber">ProtocolNumber</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProtocolNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QrcodeText name="QrcodeText">QrcodeText</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QrcodeText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptNumber name="ReceiptNumber">ReceiptNumber</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptType name="ReceiptType">ReceiptType</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReplicationCounterFromOrigin name="ReplicationCounterFromOrigin">ReplicationCounterFromOrigin</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplicationCounterFromOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReturnCodeDescription name="ReturnCodeDescription">ReturnCodeDescription</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnCodeRefRecId name="ReturnCodeRefRecId">ReturnCodeRefRecId</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnCodeRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReturnMessage name="ReturnMessage">ReturnMessage</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnMessage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#store name="store">store</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the store attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#terminal name="terminal">terminal</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressBacenCode name="ThirdPartyAddressBacenCode">ThirdPartyAddressBacenCode</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressBacenCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressCity name="ThirdPartyAddressCity">ThirdPartyAddressCity</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressComplement name="ThirdPartyAddressComplement">ThirdPartyAddressComplement</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressComplement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressCountry name="ThirdPartyAddressCountry">ThirdPartyAddressCountry</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressCountry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressCountryRegionId name="ThirdPartyAddressCountryRegionId">ThirdPartyAddressCountryRegionId</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressDistrict name="ThirdPartyAddressDistrict">ThirdPartyAddressDistrict</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressDistrict attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressIBGECode name="ThirdPartyAddressIBGECode">ThirdPartyAddressIBGECode</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressIBGECode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressState name="ThirdPartyAddressState">ThirdPartyAddressState</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressStreet name="ThirdPartyAddressStreet">ThirdPartyAddressStreet</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressStreetNumber name="ThirdPartyAddressStreetNumber">ThirdPartyAddressStreetNumber</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressZipCode name="ThirdPartyAddressZipCode">ThirdPartyAddressZipCode</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyCNPJCPF name="ThirdPartyCNPJCPF">ThirdPartyCNPJCPF</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyCNPJCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyEmail name="ThirdPartyEmail">ThirdPartyEmail</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyForeignerId name="ThirdPartyForeignerId">ThirdPartyForeignerId</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyForeignerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyName name="ThirdPartyName">ThirdPartyName</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyName attribute are listed below.</summary>

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

### <a href=#ThirdPartyPhone name="ThirdPartyPhone">ThirdPartyPhone</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyPostalAddress name="ThirdPartyPostalAddress">ThirdPartyPostalAddress</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TotalAmount name="TotalAmount">TotalAmount</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total discount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalGoodsAmount name="TotalGoodsAmount">TotalGoodsAmount</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalGoodsAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalMarkupFreightAmount name="TotalMarkupFreightAmount">TotalMarkupFreightAmount</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalMarkupFreightAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalMarkupInsuranceAmount name="TotalMarkupInsuranceAmount">TotalMarkupInsuranceAmount</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalMarkupInsuranceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalMarkupOtherAmount name="TotalMarkupOtherAmount">TotalMarkupOtherAmount</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalMarkupOtherAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalServicesAmount name="TotalServicesAmount">TotalServicesAmount</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalServicesAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#transactionId name="transactionId">transactionId</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XmlRequest name="XmlRequest">XmlRequest</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Request</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XmlRequest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XmlResponse name="XmlResponse">XmlResponse</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Response</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XmlResponse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Response</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XmlReturnRequest name="XmlReturnRequest">XmlReturnRequest</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Request</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XmlReturnRequest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XmlReturnResponse name="XmlReturnResponse">XmlReturnResponse</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Response</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XmlReturnResponse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Response</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Purpose name="Purpose">Purpose</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purpose attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SendByEmail name="SendByEmail">SendByEmail</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SendByEmail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ThirdPartyFormattedAddress name="ThirdPartyFormattedAddress">ThirdPartyFormattedAddress</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyFormattedAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyICMSContributor name="ThirdPartyICMSContributor">ThirdPartyICMSContributor</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyICMSContributor attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ThirdPartyIE name="ThirdPartyIE">ThirdPartyIE</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyIE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangeAmount name="ChangeAmount">ChangeAmount</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Change amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Change amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EFRRegisterNumber name="EFRRegisterNumber">EFRRegisterNumber</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFRRegisterNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EFRSignature name="EFRSignature">EFRSignature</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFRSignature attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAuthorityInfo name="TaxAuthorityInfo">TaxAuthorityInfo</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAuthorityInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalDiscountAmount name="OriginalDiscountAmount">OriginalDiscountAmount</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SoftwareHouseCNPJ name="SoftwareHouseCNPJ">SoftwareHouseCNPJ</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Software house CNPJ</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SoftwareHouseCNPJ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Software house CNPJ</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentTradeName name="FiscalEstablishmentTradeName">FiscalEstablishmentTradeName</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Trade name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentTradeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trade name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalResponsibleCNPJ name="TechnicalResponsibleCNPJ">TechnicalResponsibleCNPJ</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

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

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

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

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

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

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

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

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

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

### <a href=#Relationship_EFDReturnCode_BRRelationshipId name="Relationship_EFDReturnCode_BRRelationshipId">Relationship_EFDReturnCode_BRRelationshipId</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDReturnCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/EFDReturnCode_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDReturnCode_BR.cdm.json/EFDReturnCode_BR</a></td><td><a href="../Miscellaneous/EFDReturnCode_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalEstablishmentPostalAddressRelationshipId name="Relationship_FiscalEstablishmentPostalAddressRelationshipId">Relationship_FiscalEstablishmentPostalAddressRelationshipId</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalEstablishmentPostalAddressRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ThirdPartyPostalAddressRelationshipId name="Relationship_ThirdPartyPostalAddressRelationshipId">Relationship_ThirdPartyPostalAddressRelationshipId</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ThirdPartyPostalAddressRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RetailFiscalDocument_BR (this entity)  

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

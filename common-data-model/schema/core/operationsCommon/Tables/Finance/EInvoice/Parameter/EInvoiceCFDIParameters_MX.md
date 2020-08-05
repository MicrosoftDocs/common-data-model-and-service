---
title: EInvoiceCFDIParameters_MX in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Electronic invoice parameters in Parameter(EInvoiceCFDIParameters_MX)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/EInvoice/Parameter/EInvoiceCFDIParameters_MX.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EInvoiceCFDIParameters_MX/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic invoice parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[CertificateSubject](#CertificateSubject)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[CFDIDigestAlgorithm](#CFDIDigestAlgorithm)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[CFDIEnvironment](#CFDIEnvironment)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[CFDIForeignTradeVersion](#CFDIForeignTradeVersion)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[CFDIForeignTradeXsdFile](#CFDIForeignTradeXsdFile)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[CFDIPACCertificate](#CFDIPACCertificate)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[CFDIVersion](#CFDIVersion)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[CFDIXsdFile](#CFDIXsdFile)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[EmailId](#EmailId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[EnabledCFDI](#EnabledCFDI)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[EnabledCFDIWithholding](#EnabledCFDIWithholding)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[ForeignTradeReportingCurrency](#ForeignTradeReportingCurrency)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Key](#Key)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[PACAccount](#PACAccount)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[WithholdingDigestAlgorithm](#WithholdingDigestAlgorithm)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[WithholdingEmailId](#WithholdingEmailId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[WithholdingSendByMail](#WithholdingSendByMail)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[WithholdingXsdFile](#WithholdingXsdFile)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[WithholdingXsltFile](#WithholdingXsltFile)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[SendByMail](#SendByMail)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[SendReportFile](#SendReportFile)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[IncomingLimit](#IncomingLimit)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[OutgoingLimit](#OutgoingLimit)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[OperationType](#OperationType)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[SATProductCode_MX](#SATProductCode_MX)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[SATUnitCode_MX](#SATUnitCode_MX)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[PaymXsdFile](#PaymXsdFile)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[KeyVaultCertificateRef](#KeyVaultCertificateRef)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[PACKeyVaultCertificateRef](#PACKeyVaultCertificateRef)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[DocuRefCFDI](#DocuRefCFDI)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[DocuRefPaym](#DocuRefPaym)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[EnabledXsdValidation](#EnabledXsdValidation)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[DocuRefWithholding](#DocuRefWithholding)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[DocuRefForeignTrade](#DocuRefForeignTrade)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[RetailInvoiceRFC](#RetailInvoiceRFC)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[RetailItemDescription](#RetailItemDescription)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[RetailPaymMethod](#RetailPaymMethod)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[RetailProductCode](#RetailProductCode)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[RetailPurpose](#RetailPurpose)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[RetailUnitCode](#RetailUnitCode)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[SplitTaxAmountPerLines](#SplitTaxAmountPerLines)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[RetailExcludeCustOrdersFromCFDIGlobal](#RetailExcludeCustOrdersFromCFDIGlobal)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[RetailEnableRelatedCFDIInReturns](#RetailEnableRelatedCFDIInReturns)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[RetailRecalculateRoundingOfTaxBaseAmount](#RetailRecalculateRoundingOfTaxBaseAmount)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[DataAreaId](#DataAreaId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_PACTableRelationshipId](#Relationship_PACTableRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_SysEmailTableRelationshipId](#Relationship_SysEmailTableRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_KeyVaultCertificateTableRelationshipId](#Relationship_KeyVaultCertificateTableRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_PACKeyVaultCertificateTableRelationshipId](#Relationship_PACKeyVaultCertificateTableRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_SATProductCode_MXRelationshipId](#Relationship_SATProductCode_MXRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_SATUnitCode_MXRelationshipId](#Relationship_SATUnitCode_MXRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_WitholdingSysEmailTableRelationshipId](#Relationship_WitholdingSysEmailTableRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_DocuRefCFDIRelationshipId](#Relationship_DocuRefCFDIRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_DocuRefPaymRelationshipId](#Relationship_DocuRefPaymRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_DocuRefForeignTradeRelationshipId](#Relationship_DocuRefForeignTradeRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_DocuRefWithholdingRelationshipId](#Relationship_DocuRefWithholdingRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EInvoiceCFDIParameters_MX.md" target="_blank">Parameter/EInvoiceCFDIParameters_MX</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EInvoiceCFDIParameters_MX/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CertificateSubject name="CertificateSubject">CertificateSubject</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateSubject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDIDigestAlgorithm name="CFDIDigestAlgorithm">CFDIDigestAlgorithm</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFDI Encryption algorithm</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIDigestAlgorithm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFDI Encryption algorithm</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CFDIEnvironment name="CFDIEnvironment">CFDIEnvironment</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIEnvironment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CFDIForeignTradeVersion name="CFDIForeignTradeVersion">CFDIForeignTradeVersion</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIForeignTradeVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CFDIForeignTradeXsdFile name="CFDIForeignTradeXsdFile">CFDIForeignTradeXsdFile</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFDI XML schema file</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIForeignTradeXsdFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFDI XML schema file</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDIPACCertificate name="CFDIPACCertificate">CFDIPACCertificate</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIPACCertificate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDIVersion name="CFDIVersion">CFDIVersion</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CFDIXsdFile name="CFDIXsdFile">CFDIXsdFile</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFDI XML schema file</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIXsdFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFDI XML schema file</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailId name="EmailId">EmailId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnabledCFDI name="EnabledCFDI">EnabledCFDI</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable CFDI (electronic invoice)</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnabledCFDI attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enable CFDI (electronic invoice)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EnabledCFDIWithholding name="EnabledCFDIWithholding">EnabledCFDIWithholding</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable CFDI withholding</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnabledCFDIWithholding attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enable CFDI withholding</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ForeignTradeReportingCurrency name="ForeignTradeReportingCurrency">ForeignTradeReportingCurrency</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reporting currency</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignTradeReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reporting currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PACAccount name="PACAccount">PACAccount</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PACAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingDigestAlgorithm name="WithholdingDigestAlgorithm">WithholdingDigestAlgorithm</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFDI digest algorithm</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingDigestAlgorithm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFDI digest algorithm</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#WithholdingEmailId name="WithholdingEmailId">WithholdingEmailId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingEmailId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingSendByMail name="WithholdingSendByMail">WithholdingSendByMail</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingSendByMail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WithholdingXsdFile name="WithholdingXsdFile">WithholdingXsdFile</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFDI XML schema file</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingXsdFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFDI XML schema file</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingXsltFile name="WithholdingXsltFile">WithholdingXsltFile</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CDFI XSLT file</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingXsltFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CDFI XSLT file</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SendByMail name="SendByMail">SendByMail</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SendByMail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SendReportFile name="SendReportFile">SendReportFile</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SendReportFile attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IncomingLimit name="IncomingLimit">IncomingLimit</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Incoming</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomingLimit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Incoming</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OutgoingLimit name="OutgoingLimit">OutgoingLimit</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outgoing</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutgoingLimit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Outgoing</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OperationType name="OperationType">OperationType</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SATProductCode_MX name="SATProductCode_MX">SATProductCode_MX</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SATProductCode_MX attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SATUnitCode_MX name="SATUnitCode_MX">SATUnitCode_MX</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SATUnitCode_MX attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymXsdFile name="PaymXsdFile">PaymXsdFile</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFDI Payment XML schema file</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymXsdFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFDI Payment XML schema file</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyVaultCertificateRef name="KeyVaultCertificateRef">KeyVaultCertificateRef</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Certificate</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyVaultCertificateRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Certificate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PACKeyVaultCertificateRef name="PACKeyVaultCertificateRef">PACKeyVaultCertificateRef</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>PAC certificate</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PACKeyVaultCertificateRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>PAC certificate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocuRefCFDI name="DocuRefCFDI">DocuRefCFDI</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFDI XML schema file</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuRefCFDI attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFDI XML schema file</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocuRefPaym name="DocuRefPaym">DocuRefPaym</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFDI Payment XML schema file</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuRefPaym attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFDI Payment XML schema file</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EnabledXsdValidation name="EnabledXsdValidation">EnabledXsdValidation</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable validation against XML schema</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnabledXsdValidation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enable validation against XML schema</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DocuRefWithholding name="DocuRefWithholding">DocuRefWithholding</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFDI XML schema file</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuRefWithholding attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFDI XML schema file</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocuRefForeignTrade name="DocuRefForeignTrade">DocuRefForeignTrade</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFDI Foreign trade XML schema file</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuRefForeignTrade attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFDI Foreign trade XML schema file</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailInvoiceRFC name="RetailInvoiceRFC">RetailInvoiceRFC</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvoiceRFC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailItemDescription name="RetailItemDescription">RetailItemDescription</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailItemDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPaymMethod name="RetailPaymMethod">RetailPaymMethod</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPaymMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailProductCode name="RetailProductCode">RetailProductCode</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SAT product code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailProductCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>SAT product code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPurpose name="RetailPurpose">RetailPurpose</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purpose</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purpose</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailUnitCode name="RetailUnitCode">RetailUnitCode</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SAT unit code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailUnitCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>SAT unit code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SplitTaxAmountPerLines name="SplitTaxAmountPerLines">SplitTaxAmountPerLines</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Detailed tax amounts</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitTaxAmountPerLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Detailed tax amounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RetailExcludeCustOrdersFromCFDIGlobal name="RetailExcludeCustOrdersFromCFDIGlobal">RetailExcludeCustOrdersFromCFDIGlobal</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exclude customer orders from CFDI Global</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailExcludeCustOrdersFromCFDIGlobal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exclude customer orders from CFDI Global</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RetailEnableRelatedCFDIInReturns name="RetailEnableRelatedCFDIInReturns">RetailEnableRelatedCFDIInReturns</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Specify related CFDI in returns</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailEnableRelatedCFDIInReturns attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Specify related CFDI in returns</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RetailRecalculateRoundingOfTaxBaseAmount name="RetailRecalculateRoundingOfTaxBaseAmount">RetailRecalculateRoundingOfTaxBaseAmount</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recalculate rounding of tax base amounts</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailRecalculateRoundingOfTaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Recalculate rounding of tax base amounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PACTableRelationshipId name="Relationship_PACTableRelationshipId">Relationship_PACTableRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PACTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/EInvoiceCFDIPACTable_MX.md" target="_blank">/core/operationsCommon/Tables/Finance/EInvoice/Miscellaneous/EInvoiceCFDIPACTable_MX.cdm.json/EInvoiceCFDIPACTable_MX</a></td><td><a href="../Miscellaneous/EInvoiceCFDIPACTable_MX.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysEmailTableRelationshipId name="Relationship_SysEmailTableRelationshipId">Relationship_SysEmailTableRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysEmailTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_KeyVaultCertificateTableRelationshipId name="Relationship_KeyVaultCertificateTableRelationshipId">Relationship_KeyVaultCertificateTableRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_KeyVaultCertificateTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PACKeyVaultCertificateTableRelationshipId name="Relationship_PACKeyVaultCertificateTableRelationshipId">Relationship_PACKeyVaultCertificateTableRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PACKeyVaultCertificateTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SATProductCode_MXRelationshipId name="Relationship_SATProductCode_MXRelationshipId">Relationship_SATProductCode_MXRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SATProductCode_MXRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/EInvoiceExtCodeTable_MX.md" target="_blank">/core/operationsCommon/Tables/Finance/EInvoice/Group/EInvoiceExtCodeTable_MX.cdm.json/EInvoiceExtCodeTable_MX</a></td><td><a href="../Group/EInvoiceExtCodeTable_MX.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SATUnitCode_MXRelationshipId name="Relationship_SATUnitCode_MXRelationshipId">Relationship_SATUnitCode_MXRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SATUnitCode_MXRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/EInvoiceExtCodeTable_MX.md" target="_blank">/core/operationsCommon/Tables/Finance/EInvoice/Group/EInvoiceExtCodeTable_MX.cdm.json/EInvoiceExtCodeTable_MX</a></td><td><a href="../Group/EInvoiceExtCodeTable_MX.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WitholdingSysEmailTableRelationshipId name="Relationship_WitholdingSysEmailTableRelationshipId">Relationship_WitholdingSysEmailTableRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WitholdingSysEmailTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DocuRefCFDIRelationshipId name="Relationship_DocuRefCFDIRelationshipId">Relationship_DocuRefCFDIRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuRefCFDIRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/WorksheetLine/DocuRef.cdm.json/DocuRef</a></td><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DocuRefPaymRelationshipId name="Relationship_DocuRefPaymRelationshipId">Relationship_DocuRefPaymRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuRefPaymRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/WorksheetLine/DocuRef.cdm.json/DocuRef</a></td><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DocuRefForeignTradeRelationshipId name="Relationship_DocuRefForeignTradeRelationshipId">Relationship_DocuRefForeignTradeRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuRefForeignTradeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/WorksheetLine/DocuRef.cdm.json/DocuRef</a></td><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DocuRefWithholdingRelationshipId name="Relationship_DocuRefWithholdingRelationshipId">Relationship_DocuRefWithholdingRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuRefWithholdingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/WorksheetLine/DocuRef.cdm.json/DocuRef</a></td><td><a href="../../../System/SystemAdministration/WorksheetLine/DocuRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/EInvoiceCFDIParameters_MX (this entity)  

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

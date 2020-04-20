---
title: EInvoiceCFDIParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# EInvoiceCFDIParametersEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/EInvoiceCFDIParametersEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[Certificate](#Certificate)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[CFDIDigestAlgorithm](#CFDIDigestAlgorithm)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[CFDIEnvironment](#CFDIEnvironment)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[CFDIPACCertificate](#CFDIPACCertificate)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[CFDIVersion](#CFDIVersion)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[CFDIXMLSchemaFile](#CFDIXMLSchemaFile)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[EmailId](#EmailId)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[EnabledCFDI](#EnabledCFDI)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[Key](#Key)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[PACAccountId](#PACAccountId)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[SendByMail](#SendByMail)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[SendReportFile](#SendReportFile)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[RetailEnableRelatedCFDIInReturns](#RetailEnableRelatedCFDIInReturns)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[RetailExcludeCustOrdersFromCFDIGlobal](#RetailExcludeCustOrdersFromCFDIGlobal)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[RetailInvoiceRFC](#RetailInvoiceRFC)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[RetailItemDescription](#RetailItemDescription)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[RetailPaymMethod](#RetailPaymMethod)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[RetailProductCode](#RetailProductCode)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[RetailPurpose](#RetailPurpose)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[RetailRecalculateRoundingOfTaxBaseAmount](#RetailRecalculateRoundingOfTaxBaseAmount)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[RetailUnitCode](#RetailUnitCode)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[SplitTaxAmountPerLines](#SplitTaxAmountPerLines)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[BackingTable_EInvoiceCFDIParameters_MXRelationshipId](#BackingTable_EInvoiceCFDIParameters_MXRelationshipId)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="EInvoiceCFDIParametersEntity.md" target="_blank">AccountsReceivable/EInvoiceCFDIParametersEntity</a>|

### <a href=#Certificate name="Certificate">Certificate</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Certificate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDIDigestAlgorithm name="CFDIDigestAlgorithm">CFDIDigestAlgorithm</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIDigestAlgorithm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDIEnvironment name="CFDIEnvironment">CFDIEnvironment</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIEnvironment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDIPACCertificate name="CFDIPACCertificate">CFDIPACCertificate</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIPACCertificate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDIVersion name="CFDIVersion">CFDIVersion</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDIXMLSchemaFile name="CFDIXMLSchemaFile">CFDIXMLSchemaFile</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIXMLSchemaFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailId name="EmailId">EmailId</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnabledCFDI name="EnabledCFDI">EnabledCFDI</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnabledCFDI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PACAccountId name="PACAccountId">PACAccountId</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PACAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SendByMail name="SendByMail">SendByMail</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SendByMail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SendReportFile name="SendReportFile">SendReportFile</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SendReportFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailEnableRelatedCFDIInReturns name="RetailEnableRelatedCFDIInReturns">RetailEnableRelatedCFDIInReturns</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailEnableRelatedCFDIInReturns attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailExcludeCustOrdersFromCFDIGlobal name="RetailExcludeCustOrdersFromCFDIGlobal">RetailExcludeCustOrdersFromCFDIGlobal</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailExcludeCustOrdersFromCFDIGlobal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailInvoiceRFC name="RetailInvoiceRFC">RetailInvoiceRFC</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvoiceRFC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailItemDescription name="RetailItemDescription">RetailItemDescription</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailItemDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPaymMethod name="RetailPaymMethod">RetailPaymMethod</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPaymMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailProductCode name="RetailProductCode">RetailProductCode</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailProductCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPurpose name="RetailPurpose">RetailPurpose</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailRecalculateRoundingOfTaxBaseAmount name="RetailRecalculateRoundingOfTaxBaseAmount">RetailRecalculateRoundingOfTaxBaseAmount</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailRecalculateRoundingOfTaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailUnitCode name="RetailUnitCode">RetailUnitCode</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailUnitCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SplitTaxAmountPerLines name="SplitTaxAmountPerLines">SplitTaxAmountPerLines</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitTaxAmountPerLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EInvoiceCFDIParameters_MXRelationshipId name="BackingTable_EInvoiceCFDIParameters_MXRelationshipId">BackingTable_EInvoiceCFDIParameters_MXRelationshipId</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EInvoiceCFDIParameters_MXRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/EInvoice/Parameter/EInvoiceCFDIParameters_MX.md" target="_blank">/core/operationsCommon/Tables/Finance/EInvoice/Parameter/EInvoiceCFDIParameters_MX.cdm.json/EInvoiceCFDIParameters_MX</a></td><td><a href="../../../Tables/Finance/EInvoice/Parameter/EInvoiceCFDIParameters_MX.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/EInvoiceCFDIParametersEntity (this entity)  

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

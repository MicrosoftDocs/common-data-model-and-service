---
title: RetailFiscalDocumentPaymentTrans_BR in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Retail Fiscal Document Payment Transactions in Transaction(RetailFiscalDocumentPaymentTrans_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/RetailFiscalDocumentPaymentTrans_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFiscalDocumentPaymentTrans_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail Fiscal Document Payment Transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[Amount](#Amount)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[CardAuthorizationNumber](#CardAuthorizationNumber)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[CardLogo](#CardLogo)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[CardProcessorCNPJCPF](#CardProcessorCNPJCPF)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[CardProcessorCode](#CardProcessorCode)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[Channel](#Channel)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[lineNum](#lineNum)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[PaymentType](#PaymentType)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[ReplicationCounterFromOrigin](#ReplicationCounterFromOrigin)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[store](#store)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[TenderTypeId](#TenderTypeId)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[terminal](#terminal)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[transactionId](#transactionId)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[FiscalDocumentNumber](#FiscalDocumentNumber)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[FiscalDocumentSeries](#FiscalDocumentSeries)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[PaymentSystem](#PaymentSystem)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[Relationship_RetailFiscalDocument_BRRelationshipId](#Relationship_RetailFiscalDocument_BRRelationshipId)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailFiscalDocumentPaymentTrans_BR.md" target="_blank">Transaction/RetailFiscalDocumentPaymentTrans_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFiscalDocumentPaymentTrans_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CardAuthorizationNumber name="CardAuthorizationNumber">CardAuthorizationNumber</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardAuthorizationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardLogo name="CardLogo">CardLogo</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardLogo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CardProcessorCNPJCPF name="CardProcessorCNPJCPF">CardProcessorCNPJCPF</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Card processor CNPJ</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardProcessorCNPJCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Card processor CNPJ</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardProcessorCode name="CardProcessorCode">CardProcessorCode</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardProcessorCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

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

### <a href=#lineNum name="lineNum">lineNum</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PaymentType name="PaymentType">PaymentType</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReplicationCounterFromOrigin name="ReplicationCounterFromOrigin">ReplicationCounterFromOrigin</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

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

### <a href=#store name="store">store</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

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

### <a href=#TenderTypeId name="TenderTypeId">TenderTypeId</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#terminal name="terminal">terminal</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

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

### <a href=#transactionId name="transactionId">transactionId</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

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

### <a href=#FiscalDocumentNumber name="FiscalDocumentNumber">FiscalDocumentNumber</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

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

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

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

### <a href=#PaymentSystem name="PaymentSystem">PaymentSystem</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSystem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

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

### <a href=#Relationship_RetailFiscalDocument_BRRelationshipId name="Relationship_RetailFiscalDocument_BRRelationshipId">Relationship_RetailFiscalDocument_BRRelationshipId</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailFiscalDocument_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailFiscalDocument_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/RetailFiscalDocument_BR.cdm.json/RetailFiscalDocument_BR</a></td><td><a href="RetailFiscalDocument_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RetailFiscalDocumentPaymentTrans_BR (this entity)  

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

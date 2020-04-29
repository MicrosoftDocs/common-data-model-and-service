---
title: TaxReimbursementSlipTmp_HU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Tax reimbursement slip

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxReimbursementSlipTmp_HU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReimbursementSlipTmp_HU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax reimbursement slip</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[CompanyAddress](#CompanyAddress)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[CompanyName](#CompanyName)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[CustomerAddress](#CustomerAddress)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[CustomerName](#CustomerName)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[DocumentNumber](#DocumentNumber)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[InvoiceDate](#InvoiceDate)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[InvoiceId](#InvoiceId)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportIssuerCountry](#PassportIssuerCountry)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber1](#PassportNumber1)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber10](#PassportNumber10)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber11](#PassportNumber11)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber12](#PassportNumber12)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber13](#PassportNumber13)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber2](#PassportNumber2)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber3](#PassportNumber3)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber4](#PassportNumber4)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber5](#PassportNumber5)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber6](#PassportNumber6)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber7](#PassportNumber7)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber8](#PassportNumber8)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[PassportNumber9](#PassportNumber9)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAdminId1](#TaxAdminId1)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAdminId10](#TaxAdminId10)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAdminId11](#TaxAdminId11)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAdminId2](#TaxAdminId2)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAdminId3](#TaxAdminId3)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAdminId4](#TaxAdminId4)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAdminId5](#TaxAdminId5)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAdminId6](#TaxAdminId6)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAdminId7](#TaxAdminId7)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAdminId8](#TaxAdminId8)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAdminId9](#TaxAdminId9)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TaxAmount](#TaxAmount)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[TotalAmount](#TotalAmount)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxReimbursementSlipTmp_HU.md" target="_blank">Miscellaneous/TaxReimbursementSlipTmp_HU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReimbursementSlipTmp_HU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CompanyAddress name="CompanyAddress">CompanyAddress</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyName name="CompanyName">CompanyName</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAddress name="CustomerAddress">CustomerAddress</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerName name="CustomerName">CustomerName</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentNumber name="DocumentNumber">DocumentNumber</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PassportIssuerCountry name="PassportIssuerCountry">PassportIssuerCountry</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportIssuerCountry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PassportNumber1 name="PassportNumber1">PassportNumber1</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber10 name="PassportNumber10">PassportNumber10</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber11 name="PassportNumber11">PassportNumber11</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber12 name="PassportNumber12">PassportNumber12</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber12 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber13 name="PassportNumber13">PassportNumber13</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber13 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber2 name="PassportNumber2">PassportNumber2</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber3 name="PassportNumber3">PassportNumber3</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber4 name="PassportNumber4">PassportNumber4</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber5 name="PassportNumber5">PassportNumber5</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber6 name="PassportNumber6">PassportNumber6</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber7 name="PassportNumber7">PassportNumber7</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber8 name="PassportNumber8">PassportNumber8</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#PassportNumber9 name="PassportNumber9">PassportNumber9</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassportNumber9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAdminId1 name="TaxAdminId1">TaxAdminId1</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdminId1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAdminId10 name="TaxAdminId10">TaxAdminId10</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdminId10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAdminId11 name="TaxAdminId11">TaxAdminId11</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdminId11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAdminId2 name="TaxAdminId2">TaxAdminId2</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdminId2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAdminId3 name="TaxAdminId3">TaxAdminId3</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdminId3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAdminId4 name="TaxAdminId4">TaxAdminId4</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdminId4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAdminId5 name="TaxAdminId5">TaxAdminId5</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdminId5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAdminId6 name="TaxAdminId6">TaxAdminId6</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdminId6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAdminId7 name="TaxAdminId7">TaxAdminId7</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdminId7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAdminId8 name="TaxAdminId8">TaxAdminId8</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdminId8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAdminId9 name="TaxAdminId9">TaxAdminId9</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdminId9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalAmount name="TotalAmount">TotalAmount</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/TaxReimbursementSlipTmp_HU (this entity)  

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

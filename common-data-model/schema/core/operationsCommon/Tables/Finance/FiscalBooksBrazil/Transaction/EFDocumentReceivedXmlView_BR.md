---
title: EFDocumentReceivedXmlView_BR in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Received NF-e XML documents in Transaction(EFDocumentReceivedXmlView_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/EFDocumentReceivedXmlView_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocumentReceivedXmlView_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Received NF-e XML documents</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[EFDocumentReceivedXML_BR](#EFDocumentReceivedXML_BR)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[ICMSAmount](#ICMSAmount)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[ICMSBaseAmount](#ICMSBaseAmount)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[ICMSSTAmount](#ICMSSTAmount)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[ICMSSTBaseAmount](#ICMSSTBaseAmount)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[IPIAmount](#IPIAmount)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[IssueDate](#IssueDate)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[ThirdPartyCNPJ](#ThirdPartyCNPJ)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[ThirdPartyIE](#ThirdPartyIE)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[ThirdPartyIEST](#ThirdPartyIEST)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[ThirdPartyName](#ThirdPartyName)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[TotalAmount](#TotalAmount)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[TotalDiscount](#TotalDiscount)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[TotalMarkupFreightAmount](#TotalMarkupFreightAmount)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[TotalMarkupInsuranceAmount](#TotalMarkupInsuranceAmount)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[TotalMarkupOtherAmount](#TotalMarkupOtherAmount)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[TotalProductAmount](#TotalProductAmount)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[IssueTime](#IssueTime)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[IssueTimezone](#IssueTimezone)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[Relationship_EFDocumentReceivedXml_BRRelationshipId](#Relationship_EFDocumentReceivedXml_BRRelationshipId)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EFDocumentReceivedXmlView_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlView_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocumentReceivedXmlView_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EFDocumentReceivedXML_BR name="EFDocumentReceivedXML_BR">EFDocumentReceivedXML_BR</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocumentReceivedXML_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSAmount name="ICMSAmount">ICMSAmount</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ICMS</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>ICMS</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSBaseAmount name="ICMSBaseAmount">ICMSBaseAmount</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ICMS base amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>ICMS base amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSSTAmount name="ICMSSTAmount">ICMSSTAmount</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ICMS-ST</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSSTAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>ICMS-ST</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSSTBaseAmount name="ICMSSTBaseAmount">ICMSSTBaseAmount</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ICMS-ST base amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSSTBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>ICMS-ST base amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IPIAmount name="IPIAmount">IPIAmount</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IPI</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IPIAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>IPI</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IssueDate name="IssueDate">IssueDate</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ThirdPartyCNPJ name="ThirdPartyCNPJ">ThirdPartyCNPJ</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyCNPJ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyIE name="ThirdPartyIE">ThirdPartyIE</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

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

### <a href=#ThirdPartyIEST name="ThirdPartyIEST">ThirdPartyIEST</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tributary Substitution Registry</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyIEST attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tributary Substitution Registry</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyName name="ThirdPartyName">ThirdPartyName</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalAmount name="TotalAmount">TotalAmount</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

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

### <a href=#TotalDiscount name="TotalDiscount">TotalDiscount</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total discount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalMarkupFreightAmount name="TotalMarkupFreightAmount">TotalMarkupFreightAmount</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

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

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

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

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

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

### <a href=#TotalProductAmount name="TotalProductAmount">TotalProductAmount</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total products amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalProductAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total products amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IssueTime name="IssueTime">IssueTime</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#IssueTimezone name="IssueTimezone">IssueTimezone</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueTimezone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

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

### <a href=#Relationship_EFDocumentReceivedXml_BRRelationshipId name="Relationship_EFDocumentReceivedXml_BRRelationshipId">Relationship_EFDocumentReceivedXml_BRRelationshipId</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDocumentReceivedXml_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EFDocumentReceivedXML_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/EFDocumentReceivedXML_BR.cdm.json/EFDocumentReceivedXML_BR</a></td><td><a href="EFDocumentReceivedXML_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/EFDocumentReceivedXmlView_BR (this entity)  

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

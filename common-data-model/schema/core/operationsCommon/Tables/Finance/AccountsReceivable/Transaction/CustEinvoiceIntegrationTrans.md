---
title: CustEinvoiceIntegrationTrans in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# E-Invoice transactions in Transaction(CustEinvoiceIntegrationTrans)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustEinvoiceIntegrationTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustEinvoiceIntegrationTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>E-Invoice transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[Accepted](#Accepted)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[Action](#Action)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[BankFileArchTable](#BankFileArchTable)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[CustEinvoiceIntegrationError](#CustEinvoiceIntegrationError)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[CustEinvoiceIntegrationTypeTable](#CustEinvoiceIntegrationTypeTable)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[ErrorName](#ErrorName)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[ExtRef](#ExtRef)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[IntRecId](#IntRecId)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[NewStatus](#NewStatus)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[Posted](#Posted)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[Ref](#Ref)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo1](#RefInfo1)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo1Transfer](#RefInfo1Transfer)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo2](#RefInfo2)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo2Transfer](#RefInfo2Transfer)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo3](#RefInfo3)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo3Transfer](#RefInfo3Transfer)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo4](#RefInfo4)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo4Transfer](#RefInfo4Transfer)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo5](#RefInfo5)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo5Transfer](#RefInfo5Transfer)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo6](#RefInfo6)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo6Transfer](#RefInfo6Transfer)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo7](#RefInfo7)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo7Transfer](#RefInfo7Transfer)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo8](#RefInfo8)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo8Transfer](#RefInfo8Transfer)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo9](#RefInfo9)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[RefInfo9Transfer](#RefInfo9Transfer)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[ReturnStatus](#ReturnStatus)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[Sent](#Sent)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[Status](#Status)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[Relationship_CustEinvoiceIntegrationRelationshipId](#Relationship_CustEinvoiceIntegrationRelationshipId)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[Relationship_CustEinvoiceIntegrationErrorRelationshipId](#Relationship_CustEinvoiceIntegrationErrorRelationshipId)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[Relationship_CustEinvoiceIntegrationTypeTableRelationshipId](#Relationship_CustEinvoiceIntegrationTypeTableRelationshipId)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustEinvoiceIntegrationTrans.md" target="_blank">Transaction/CustEinvoiceIntegrationTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustEinvoiceIntegrationTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Accepted name="Accepted">Accepted</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Accepted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Action name="Action">Action</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Action attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BankFileArchTable name="BankFileArchTable">BankFileArchTable</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>File archive number</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankFileArchTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>File archive number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustEinvoiceIntegrationError name="CustEinvoiceIntegrationError">CustEinvoiceIntegrationError</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Error code</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustEinvoiceIntegrationError attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Error code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustEinvoiceIntegrationTypeTable name="CustEinvoiceIntegrationTypeTable">CustEinvoiceIntegrationTypeTable</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustEinvoiceIntegrationTypeTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ErrorName name="ErrorName">ErrorName</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtRef name="ExtRef">ExtRef</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntRecId name="IntRecId">IntRecId</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NewStatus name="NewStatus">NewStatus</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>New status</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>New status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Ref name="Ref">Ref</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ref attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefInfo1 name="RefInfo1">RefInfo1</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefInfo1Transfer name="RefInfo1Transfer">RefInfo1Transfer</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo1Transfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefInfo2 name="RefInfo2">RefInfo2</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefInfo2Transfer name="RefInfo2Transfer">RefInfo2Transfer</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo2Transfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefInfo3 name="RefInfo3">RefInfo3</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefInfo3Transfer name="RefInfo3Transfer">RefInfo3Transfer</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo3Transfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefInfo4 name="RefInfo4">RefInfo4</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefInfo4Transfer name="RefInfo4Transfer">RefInfo4Transfer</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo4Transfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefInfo5 name="RefInfo5">RefInfo5</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefInfo5Transfer name="RefInfo5Transfer">RefInfo5Transfer</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo5Transfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefInfo6 name="RefInfo6">RefInfo6</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefInfo6Transfer name="RefInfo6Transfer">RefInfo6Transfer</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo6Transfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefInfo7 name="RefInfo7">RefInfo7</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefInfo7Transfer name="RefInfo7Transfer">RefInfo7Transfer</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo7Transfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefInfo8 name="RefInfo8">RefInfo8</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefInfo8Transfer name="RefInfo8Transfer">RefInfo8Transfer</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo8Transfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefInfo9 name="RefInfo9">RefInfo9</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefInfo9Transfer name="RefInfo9Transfer">RefInfo9Transfer</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefInfo9Transfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReturnStatus name="ReturnStatus">ReturnStatus</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Return status</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Return status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Sent name="Sent">Sent</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>File status</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>File status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

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

### <a href=#Relationship_CustEinvoiceIntegrationRelationshipId name="Relationship_CustEinvoiceIntegrationRelationshipId">Relationship_CustEinvoiceIntegrationRelationshipId</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustEinvoiceIntegrationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CustEinvoiceIntegration.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustEinvoiceIntegration.cdm.json/CustEinvoiceIntegration</a></td><td><a href="CustEinvoiceIntegration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustEinvoiceIntegrationErrorRelationshipId name="Relationship_CustEinvoiceIntegrationErrorRelationshipId">Relationship_CustEinvoiceIntegrationErrorRelationshipId</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustEinvoiceIntegrationErrorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CustEinvoiceIntegrationError.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustEinvoiceIntegrationError.cdm.json/CustEinvoiceIntegrationError</a></td><td><a href="CustEinvoiceIntegrationError.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustEinvoiceIntegrationTypeTableRelationshipId name="Relationship_CustEinvoiceIntegrationTypeTableRelationshipId">Relationship_CustEinvoiceIntegrationTypeTableRelationshipId</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustEinvoiceIntegrationTypeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CustEinvoiceIntegrationTypeTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustEinvoiceIntegrationTypeTable.cdm.json/CustEinvoiceIntegrationTypeTable</a></td><td><a href="../Group/CustEinvoiceIntegrationTypeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/CustEinvoiceIntegrationTrans (this entity)  

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

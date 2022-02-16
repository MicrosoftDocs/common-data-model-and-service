---
title: TaxIntgrExportDocDataHeaderTmp_CN in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Export document in Miscellaneous(TaxIntgrExportDocDataHeaderTmp_CN)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxIntgrExportDocDataHeaderTmp_CN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Export document</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[HistoryRecId](#HistoryRecId)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[Id](#Id)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[LineCount](#LineCount)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[CustName](#CustName)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[RegistrationNumber](#RegistrationNumber)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[CustAddress](#CustAddress)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[CustPhone](#CustPhone)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[CustBankName](#CustBankName)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[CustBankAccountNum](#CustBankAccountNum)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[CreditNodeMemo](#CreditNodeMemo)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[InvoiceAuditorName](#InvoiceAuditorName)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[PaymentCollectorName](#PaymentCollectorName)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[MaxInvoiceLines](#MaxInvoiceLines)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[DocumentDate](#DocumentDate)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[CompanyBankName](#CompanyBankName)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[CompanyBankAccountNum](#CompanyBankAccountNum)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[Address](#Address)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[Phone](#Phone)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[IsExport](#IsExport)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[BatchPosition](#BatchPosition)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[TaxIncludedMark](#TaxIncludedMark)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[Relationship_TaxIntgrExportDocOperationHistory_CNRelationshipId](#Relationship_TaxIntgrExportDocOperationHistory_CNRelationshipId)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxIntgrExportDocDataHeaderTmp_CN.md" target="_blank">Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxIntgrExportDocDataHeaderTmp_CN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#HistoryRecId name="HistoryRecId">HistoryRecId</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HistoryRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Id name="Id">Id</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineCount name="LineCount">LineCount</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustName name="CustName">CustName</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationNumber name="RegistrationNumber">RegistrationNumber</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAddress name="CustAddress">CustAddress</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustPhone name="CustPhone">CustPhone</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustBankName name="CustBankName">CustBankName</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustBankName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustBankAccountNum name="CustBankAccountNum">CustBankAccountNum</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustBankAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditNodeMemo name="CreditNodeMemo">CreditNodeMemo</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNodeMemo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAuditorName name="InvoiceAuditorName">InvoiceAuditorName</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAuditorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentCollectorName name="PaymentCollectorName">PaymentCollectorName</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentCollectorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxInvoiceLines name="MaxInvoiceLines">MaxInvoiceLines</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxInvoiceLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CompanyBankName name="CompanyBankName">CompanyBankName</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyBankName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyBankAccountNum name="CompanyBankAccountNum">CompanyBankAccountNum</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyBankAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Address name="Address">Address</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

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

### <a href=#Phone name="Phone">Phone</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Phone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExport name="IsExport">IsExport</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExport attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BatchPosition name="BatchPosition">BatchPosition</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchPosition attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxIncludedMark name="TaxIncludedMark">TaxIncludedMark</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncludedMark attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

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

### <a href=#Relationship_TaxIntgrExportDocOperationHistory_CNRelationshipId name="Relationship_TaxIntgrExportDocOperationHistory_CNRelationshipId">Relationship_TaxIntgrExportDocOperationHistory_CNRelationshipId</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIntgrExportDocOperationHistory_CNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/TaxIntgrExportDocOperationHistory_CN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxIntgrExportDocOperationHistory_CN.cdm.json/TaxIntgrExportDocOperationHistory_CN</a></td><td><a href="../Transaction/TaxIntgrExportDocOperationHistory_CN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/TaxIntgrExportDocDataHeaderTmp_CN (this entity)  

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

---
title: FDTaxTransPresumedUncommitted_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Uncommitted presumed sales tax

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/FDTaxTransPresumedUncommitted_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FDTaxTransPresumedUncommitted_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Uncommitted presumed sales tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[ICMSTaxAmount](#ICMSTaxAmount)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[ICMSSTTaxAmount](#ICMSSTTaxAmount)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[ICMSSTTaxBaseAmount](#ICMSSTTaxBaseAmount)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[ICMSSTTaxValue](#ICMSSTTaxValue)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[FCPSTTaxAmount](#FCPSTTaxAmount)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[FCPSTTaxBaseAmount](#FCPSTTaxBaseAmount)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[FCPSTTaxValue](#FCPSTTaxValue)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[TaxUncommitted](#TaxUncommitted)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[SourceTableId](#SourceTableId)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[SourceRecId](#SourceRecId)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[Relationship_TaxUncommittedRelationshipId](#Relationship_TaxUncommittedRelationshipId)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[Relationship_VendInvoiceInfoLineRelationshipId](#Relationship_VendInvoiceInfoLineRelationshipId)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="FDTaxTransPresumedUncommitted_BR.md" target="_blank">WorksheetLine/FDTaxTransPresumedUncommitted_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FDTaxTransPresumedUncommitted_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSTaxAmount name="ICMSTaxAmount">ICMSTaxAmount</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSSTTaxAmount name="ICMSSTTaxAmount">ICMSSTTaxAmount</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSSTTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSSTTaxBaseAmount name="ICMSSTTaxBaseAmount">ICMSSTTaxBaseAmount</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSSTTaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSSTTaxValue name="ICMSSTTaxValue">ICMSSTTaxValue</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSSTTaxValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FCPSTTaxAmount name="FCPSTTaxAmount">FCPSTTaxAmount</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FCPSTTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FCPSTTaxBaseAmount name="FCPSTTaxBaseAmount">FCPSTTaxBaseAmount</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FCPSTTaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FCPSTTaxValue name="FCPSTTaxValue">FCPSTTaxValue</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FCPSTTaxValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxUncommitted name="TaxUncommitted">TaxUncommitted</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUncommitted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceTableId name="SourceTableId">SourceTableId</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceRecId name="SourceRecId">SourceRecId</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

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

### <a href=#Relationship_TaxUncommittedRelationshipId name="Relationship_TaxUncommittedRelationshipId">Relationship_TaxUncommittedRelationshipId</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxUncommittedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxUncommitted.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/TaxUncommitted.cdm.json/TaxUncommitted</a></td><td><a href="TaxUncommitted.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendInvoiceInfoLineRelationshipId name="Relationship_VendInvoiceInfoLineRelationshipId">Relationship_VendInvoiceInfoLineRelationshipId</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendInvoiceInfoLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/TransactionLine/VendInvoiceInfoLine.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/TransactionLine/VendInvoiceInfoLine.cdm.json/VendInvoiceInfoLine</a></td><td><a href="../../AccountsPayable/TransactionLine/VendInvoiceInfoLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/FDTaxTransPresumedUncommitted_BR (this entity)  

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

---
title: RetailTransactionTaxTrans_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailTransactionTaxTrans_IN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailTransactionTaxTrans_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTransactionTaxTrans_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[Channel](#Channel)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[IsTaxOnTax](#IsTaxOnTax)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[SaleLineNum](#SaleLineNum)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[StoreId](#StoreId)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[TaxBasis](#TaxBasis)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[TaxCode](#TaxCode)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[TaxComponent](#TaxComponent)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[TaxFormula](#TaxFormula)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[TaxIsExempt](#TaxIsExempt)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[TaxIsIncludedInPrice](#TaxIsIncludedInPrice)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[TaxPercentage](#TaxPercentage)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[TerminalId](#TerminalId)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[TransactionId](#TransactionId)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[Relationship_RetailTransactionTaxTransRelationshipId](#Relationship_RetailTransactionTaxTransRelationshipId)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailTransactionTaxTrans_IN.md" target="_blank">Miscellaneous/RetailTransactionTaxTrans_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTransactionTaxTrans_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

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

### <a href=#IsTaxOnTax name="IsTaxOnTax">IsTaxOnTax</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxOnTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SaleLineNum name="SaleLineNum">SaleLineNum</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaleLineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#StoreId name="StoreId">StoreId</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxBasis name="TaxBasis">TaxBasis</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBasis attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxComponent name="TaxComponent">TaxComponent</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxComponent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxFormula name="TaxFormula">TaxFormula</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFormula attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIsExempt name="TaxIsExempt">TaxIsExempt</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIsExempt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxIsIncludedInPrice name="TaxIsIncludedInPrice">TaxIsIncludedInPrice</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIsIncludedInPrice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxItemGroup name="TaxItemGroup">TaxItemGroup</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPercentage name="TaxPercentage">TaxPercentage</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TerminalId name="TerminalId">TerminalId</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionId name="TransactionId">TransactionId</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

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

### <a href=#Relationship_RetailTransactionTaxTransRelationshipId name="Relationship_RetailTransactionTaxTransRelationshipId">Relationship_RetailTransactionTaxTransRelationshipId</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionTaxTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/RetailTransactionTaxTrans.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailTransactionTaxTrans.cdm.json/RetailTransactionTaxTrans</a></td><td><a href="../Transaction/RetailTransactionTaxTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/RetailTransactionTaxTrans_IN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

---
title: RetailFiscalDocumentLine_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# RetailFiscalDocumentLine_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/RetailFiscalDocumentLine_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFiscalDocumentLine_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[ApproximateTaxAmount](#ApproximateTaxAmount)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[CFOP](#CFOP)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[Channel](#Channel)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[Description](#Description)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[FiscalClassification](#FiscalClassification)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[GlobalTradeItemNumber](#GlobalTradeItemNumber)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[ItemId](#ItemId)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[ItemType](#ItemType)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[LineAmount](#LineAmount)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[LineDiscount](#LineDiscount)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[LineNum](#LineNum)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[Quantity](#Quantity)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[ReplicationCounterFromOrigin](#ReplicationCounterFromOrigin)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[ServiceCode](#ServiceCode)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[store](#store)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[TaxationOrigin](#TaxationOrigin)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[terminal](#terminal)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[transactionId](#transactionId)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[Unit](#Unit)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[UnitPrice](#UnitPrice)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[LineId](#LineId)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[OriginalLineDiscount](#OriginalLineDiscount)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[CNPJManufacturer](#CNPJManufacturer)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[BenefitCode](#BenefitCode)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[ScaleIndicator](#ScaleIndicator)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[TaxSubstitutionCode](#TaxSubstitutionCode)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[FiscalDocumentNumber](#FiscalDocumentNumber)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[FiscalDocumentSeries](#FiscalDocumentSeries)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[Relationship_RetailFiscalDocument_BRRelationshipId](#Relationship_RetailFiscalDocument_BRRelationshipId)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailFiscalDocumentLine_BR.md" target="_blank">Transaction/RetailFiscalDocumentLine_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFiscalDocumentLine_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ApproximateTaxAmount name="ApproximateTaxAmount">ApproximateTaxAmount</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApproximateTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CFOP name="CFOP">CFOP</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

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

### <a href=#Description name="Description">Description</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalClassification name="FiscalClassification">FiscalClassification</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalClassification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GlobalTradeItemNumber name="GlobalTradeItemNumber">GlobalTradeItemNumber</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GlobalTradeItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemType name="ItemType">ItemType</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineDiscount name="LineDiscount">LineDiscount</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReplicationCounterFromOrigin name="ReplicationCounterFromOrigin">ReplicationCounterFromOrigin</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplicationCounterFromOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ServiceCode name="ServiceCode">ServiceCode</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#store name="store">store</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

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

### <a href=#TaxationOrigin name="TaxationOrigin">TaxationOrigin</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#terminal name="terminal">terminal</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

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

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

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

### <a href=#Unit name="Unit">Unit</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Unit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitPrice name="UnitPrice">UnitPrice</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineId name="LineId">LineId</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineId attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OriginalLineDiscount name="OriginalLineDiscount">OriginalLineDiscount</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalLineDiscount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CNPJManufacturer name="CNPJManufacturer">CNPJManufacturer</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CNPJManufacturer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitCode name="BenefitCode">BenefitCode</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScaleIndicator name="ScaleIndicator">ScaleIndicator</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScaleIndicator attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxSubstitutionCode name="TaxSubstitutionCode">TaxSubstitutionCode</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSubstitutionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentNumber name="FiscalDocumentNumber">FiscalDocumentNumber</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

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

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

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

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

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

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

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

First included in: Transaction/RetailFiscalDocumentLine_BR (this entity)  

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

---
title: FBICMSSTInventoryBalance_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# FBICMSSTInventoryBalance_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBICMSSTInventoryBalance_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBICMSSTInventoryBalance_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[CurrentPeriod](#CurrentPeriod)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[FBBookingPeriod_BR](#FBBookingPeriod_BR)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ICMSSTTaxAmount](#ICMSSTTaxAmount)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ICMSSTTaxAmountPerUnit](#ICMSSTTaxAmountPerUnit)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ICMSSTTaxBaseAmount](#ICMSSTTaxBaseAmount)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ICMSSTTaxBaseAmountPerUnit](#ICMSSTTaxBaseAmountPerUnit)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ICMSTaxAmount](#ICMSTaxAmount)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ICMSTaxAmountPerUnit](#ICMSTaxAmountPerUnit)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[InventDimDetails](#InventDimDetails)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[InventDimId](#InventDimId)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ItemId](#ItemId)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[NextPeriod](#NextPeriod)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ProductName](#ProductName)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[Quantity](#Quantity)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[Unit](#Unit)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[QuantitySales](#QuantitySales)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ICMSSTFCPTaxAmount](#ICMSSTFCPTaxAmount)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ICMSSTFCPTaxAmountPerUnit](#ICMSSTFCPTaxAmountPerUnit)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ICMSFCPTaxAmountPerUnit](#ICMSFCPTaxAmountPerUnit)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[ICMSFCPTaxAmount](#ICMSFCPTaxAmount)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[Relationship_FBBookingPeriod_BRRelationshipId](#Relationship_FBBookingPeriod_BRRelationshipId)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="FBICMSSTInventoryBalance_BR.md" target="_blank">Miscellaneous/FBICMSSTInventoryBalance_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBICMSSTInventoryBalance_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrentPeriod name="CurrentPeriod">CurrentPeriod</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FBBookingPeriod_BR name="FBBookingPeriod_BR">FBBookingPeriod_BR</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBBookingPeriod_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSSTTaxAmount name="ICMSSTTaxAmount">ICMSSTTaxAmount</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

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

### <a href=#ICMSSTTaxAmountPerUnit name="ICMSSTTaxAmountPerUnit">ICMSSTTaxAmountPerUnit</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSSTTaxAmountPerUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSSTTaxBaseAmount name="ICMSSTTaxBaseAmount">ICMSSTTaxBaseAmount</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

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

### <a href=#ICMSSTTaxBaseAmountPerUnit name="ICMSSTTaxBaseAmountPerUnit">ICMSSTTaxBaseAmountPerUnit</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSSTTaxBaseAmountPerUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSTaxAmount name="ICMSTaxAmount">ICMSTaxAmount</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

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

### <a href=#ICMSTaxAmountPerUnit name="ICMSTaxAmountPerUnit">ICMSTaxAmountPerUnit</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSTaxAmountPerUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventDimDetails name="InventDimDetails">InventDimDetails</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

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

### <a href=#NextPeriod name="NextPeriod">NextPeriod</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

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

### <a href=#Unit name="Unit">Unit</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

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

### <a href=#QuantitySales name="QuantitySales">QuantitySales</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantitySales attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSSTFCPTaxAmount name="ICMSSTFCPTaxAmount">ICMSSTFCPTaxAmount</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSSTFCPTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSSTFCPTaxAmountPerUnit name="ICMSSTFCPTaxAmountPerUnit">ICMSSTFCPTaxAmountPerUnit</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSSTFCPTaxAmountPerUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSFCPTaxAmountPerUnit name="ICMSFCPTaxAmountPerUnit">ICMSFCPTaxAmountPerUnit</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSFCPTaxAmountPerUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSFCPTaxAmount name="ICMSFCPTaxAmount">ICMSFCPTaxAmount</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSFCPTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

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

### <a href=#Relationship_FBBookingPeriod_BRRelationshipId name="Relationship_FBBookingPeriod_BRRelationshipId">Relationship_FBBookingPeriod_BRRelationshipId</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBBookingPeriod_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FBBookingPeriod_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBBookingPeriod_BR.cdm.json/FBBookingPeriod_BR</a></td><td><a href="../Transaction/FBBookingPeriod_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/FBICMSSTInventoryBalance_BR (this entity)  

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

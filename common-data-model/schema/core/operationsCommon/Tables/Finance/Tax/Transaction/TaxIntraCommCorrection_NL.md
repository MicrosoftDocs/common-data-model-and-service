---
title: TaxIntraCommCorrection_NL - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# TaxIntraCommCorrection_NL

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxIntraCommCorrection_NL.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxIntraCommCorrection_NL/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|
|[Amount](#Amount)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|
|[CountryRegion](#CountryRegion)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|
|[ServiceAmount](#ServiceAmount)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|
|[TaxIntraCommTable_NL](#TaxIntraCommTable_NL)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|
|[TaxPeriod](#TaxPeriod)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|
|[TriangularTrade](#TriangularTrade)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|
|[VatNum](#VatNum)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|
|[Relationship_LogisticsAddressCountryRegionRelationshipId](#Relationship_LogisticsAddressCountryRegionRelationshipId)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|
|[Relationship_TaxIntraCommTable_NLRelationshipId](#Relationship_TaxIntraCommTable_NLRelationshipId)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxIntraCommCorrection_NL.md" target="_blank">Transaction/TaxIntraCommCorrection_NL</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxIntraCommCorrection_NL/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CountryRegion name="CountryRegion">CountryRegion</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceAmount name="ServiceAmount">ServiceAmount</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxIntraCommTable_NL name="TaxIntraCommTable_NL">TaxIntraCommTable_NL</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIntraCommTable_NL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxPeriod name="TaxPeriod">TaxPeriod</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TriangularTrade name="TriangularTrade">TriangularTrade</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TriangularTrade attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VatNum name="VatNum">VatNum</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VatNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

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

### <a href=#Relationship_LogisticsAddressCountryRegionRelationshipId name="Relationship_LogisticsAddressCountryRegionRelationshipId">Relationship_LogisticsAddressCountryRegionRelationshipId</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressCountryRegionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxIntraCommTable_NLRelationshipId name="Relationship_TaxIntraCommTable_NLRelationshipId">Relationship_TaxIntraCommTable_NLRelationshipId</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIntraCommTable_NLRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxIntraCommTable_NL.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxIntraCommTable_NL.cdm.json/TaxIntraCommTable_NL</a></td><td><a href="TaxIntraCommTable_NL.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/TaxIntraCommCorrection_NL (this entity)  

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

---
title: TaxReport347Trans - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# TaxReport347Trans

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/TaxReport347Trans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReport347Trans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[Amount](#Amount)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[AmountInCash](#AmountInCash)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[AmountQuarter1](#AmountQuarter1)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[AmountQuarter2](#AmountQuarter2)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[AmountQuarter3](#AmountQuarter3)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[AmountQuarter4](#AmountQuarter4)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[CashInvoiceYear](#CashInvoiceYear)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[CountryRegionId](#CountryRegionId)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[CountyId](#CountyId)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[InsuranceOperation](#InsuranceOperation)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[Name](#Name)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[OperationKey](#OperationKey)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[Rent](#Rent)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[Representative](#Representative)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[TaxReport347Table](#TaxReport347Table)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[VATNum](#VATNum)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[CashAccountingRegime](#CashAccountingRegime)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[GoodsInDeposit](#GoodsInDeposit)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[ReverseCharge](#ReverseCharge)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[CashAccountingAmount](#CashAccountingAmount)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[Relationship_AddressCountryRelationshipId](#Relationship_AddressCountryRelationshipId)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[Relationship_LogisticsAddressCountryRegionRelationshipId](#Relationship_LogisticsAddressCountryRegionRelationshipId)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[Relationship_TaxReport347TableRelationshipId](#Relationship_TaxReport347TableRelationshipId)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[Relationship_taxVatNumTableRelationshipId](#Relationship_taxVatNumTableRelationshipId)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxReport347Trans.md" target="_blank">WorksheetLine/TaxReport347Trans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReport347Trans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountInCash name="AmountInCash">AmountInCash</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInCash attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountQuarter1 name="AmountQuarter1">AmountQuarter1</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountQuarter1 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountQuarter2 name="AmountQuarter2">AmountQuarter2</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountQuarter2 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountQuarter3 name="AmountQuarter3">AmountQuarter3</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountQuarter3 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountQuarter4 name="AmountQuarter4">AmountQuarter4</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountQuarter4 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CashInvoiceYear name="CashInvoiceYear">CashInvoiceYear</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashInvoiceYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountyId name="CountyId">CountyId</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuranceOperation name="InsuranceOperation">InsuranceOperation</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceOperation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationKey name="OperationKey">OperationKey</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationKey attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Rent name="Rent">Rent</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Rent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Representative name="Representative">Representative</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Representative attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxReport347Table name="TaxReport347Table">TaxReport347Table</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReport347Table attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VATNum name="VATNum">VATNum</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashAccountingRegime name="CashAccountingRegime">CashAccountingRegime</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashAccountingRegime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#GoodsInDeposit name="GoodsInDeposit">GoodsInDeposit</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GoodsInDeposit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReverseCharge name="ReverseCharge">ReverseCharge</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseCharge attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashAccountingAmount name="CashAccountingAmount">CashAccountingAmount</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashAccountingAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

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

### <a href=#Relationship_AddressCountryRelationshipId name="Relationship_AddressCountryRelationshipId">Relationship_AddressCountryRelationshipId</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AddressCountryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCounty.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCounty.cdm.json/LogisticsAddressCounty</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCounty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsAddressCountryRegionRelationshipId name="Relationship_LogisticsAddressCountryRegionRelationshipId">Relationship_LogisticsAddressCountryRegionRelationshipId</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

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

### <a href=#Relationship_TaxReport347TableRelationshipId name="Relationship_TaxReport347TableRelationshipId">Relationship_TaxReport347TableRelationshipId</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReport347TableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/TaxReport347Table.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/WorksheetHeader/TaxReport347Table.cdm.json/TaxReport347Table</a></td><td><a href="../WorksheetHeader/TaxReport347Table.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_taxVatNumTableRelationshipId name="Relationship_taxVatNumTableRelationshipId">Relationship_taxVatNumTableRelationshipId</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_taxVatNumTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxVATNumTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxVATNumTable.cdm.json/TaxVATNumTable</a></td><td><a href="../Main/TaxVATNumTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/TaxReport347Trans (this entity)  

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

---
title: MCRSourceCodeSetup - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# MCRSourceCodeSetup

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Main/MCRSourceCodeSetup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MCRSourceCodeSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[ActualCost](#ActualCost)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[Catalog](#Catalog)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[Description](#Description)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[DistributionQty](#DistributionQty)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[FutureOrderDate](#FutureOrderDate)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[MailDate](#MailDate)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[MailingCosts](#MailingCosts)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[OnlyCatalogPlans](#OnlyCatalogPlans)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[OtherCost](#OtherCost)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[PrintingCosts](#PrintingCosts)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[ProjOrderDate](#ProjOrderDate)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[ProjOrders](#ProjOrders)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[ProjReturns](#ProjReturns)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[ProjSales](#ProjSales)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[SourceID](#SourceID)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[TargetID](#TargetID)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[DataAreaId](#DataAreaId)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[Relationship_CatalogRelationshipId](#Relationship_CatalogRelationshipId)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[Relationship_MCRTargetSetupRelationshipId](#Relationship_MCRTargetSetupRelationshipId)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="MCRSourceCodeSetup.md" target="_blank">Main/MCRSourceCodeSetup</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MCRSourceCodeSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActualCost name="ActualCost">ActualCost</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualCost attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Catalog name="Catalog">Catalog</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Catalog attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

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

### <a href=#DistributionQty name="DistributionQty">DistributionQty</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistributionQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FutureOrderDate name="FutureOrderDate">FutureOrderDate</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FutureOrderDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#MailDate name="MailDate">MailDate</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MailDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#MailingCosts name="MailingCosts">MailingCosts</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MailingCosts attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OnlyCatalogPlans name="OnlyCatalogPlans">OnlyCatalogPlans</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnlyCatalogPlans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OtherCost name="OtherCost">OtherCost</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OtherCost attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrintingCosts name="PrintingCosts">PrintingCosts</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintingCosts attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ProjOrderDate name="ProjOrderDate">ProjOrderDate</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjOrderDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ProjOrders name="ProjOrders">ProjOrders</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjOrders attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProjReturns name="ProjReturns">ProjReturns</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjReturns attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ProjSales name="ProjSales">ProjSales</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjSales attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceID name="SourceID">SourceID</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetID name="TargetID">TargetID</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

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

### <a href=#Relationship_CatalogRelationshipId name="Relationship_CatalogRelationshipId">Relationship_CatalogRelationshipId</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatalogRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="Catalog.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/Catalog.cdm.json/Catalog</a></td><td><a href="Catalog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MCRTargetSetupRelationshipId name="Relationship_MCRTargetSetupRelationshipId">Relationship_MCRTargetSetupRelationshipId</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRTargetSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="MCRTargetSetup.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/MCRTargetSetup.cdm.json/MCRTargetSetup</a></td><td><a href="MCRTargetSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/MCRSourceCodeSetup (this entity)  

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

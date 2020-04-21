---
title: PdsRegionalRegulatedProductListEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# PdsRegionalRegulatedProductListEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/PdsRegionalRegulatedProductListEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RegulatingCountryRegionId](#RegulatingCountryRegionId)||<a href="PdsRegionalRegulatedProductListEntity.md" target="_blank">ProductInformationManagement/PdsRegionalRegulatedProductListEntity</a>|
|[RegulatingStateId](#RegulatingStateId)||<a href="PdsRegionalRegulatedProductListEntity.md" target="_blank">ProductInformationManagement/PdsRegionalRegulatedProductListEntity</a>|
|[IsReportingList](#IsReportingList)||<a href="PdsRegionalRegulatedProductListEntity.md" target="_blank">ProductInformationManagement/PdsRegionalRegulatedProductListEntity</a>|
|[ReportingListId](#ReportingListId)||<a href="PdsRegionalRegulatedProductListEntity.md" target="_blank">ProductInformationManagement/PdsRegionalRegulatedProductListEntity</a>|
|[ReportingListDescription](#ReportingListDescription)||<a href="PdsRegionalRegulatedProductListEntity.md" target="_blank">ProductInformationManagement/PdsRegionalRegulatedProductListEntity</a>|
|[BackingTable_PdsMRCReportingListRelationshipId](#BackingTable_PdsMRCReportingListRelationshipId)||<a href="PdsRegionalRegulatedProductListEntity.md" target="_blank">ProductInformationManagement/PdsRegionalRegulatedProductListEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PdsRegionalRegulatedProductListEntity.md" target="_blank">ProductInformationManagement/PdsRegionalRegulatedProductListEntity</a>|

### <a href=#RegulatingCountryRegionId name="RegulatingCountryRegionId">RegulatingCountryRegionId</a>

First included in: ProductInformationManagement/PdsRegionalRegulatedProductListEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegulatingCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegulatingStateId name="RegulatingStateId">RegulatingStateId</a>

First included in: ProductInformationManagement/PdsRegionalRegulatedProductListEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegulatingStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReportingList name="IsReportingList">IsReportingList</a>

First included in: ProductInformationManagement/PdsRegionalRegulatedProductListEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReportingList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingListId name="ReportingListId">ReportingListId</a>

First included in: ProductInformationManagement/PdsRegionalRegulatedProductListEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingListId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingListDescription name="ReportingListDescription">ReportingListDescription</a>

First included in: ProductInformationManagement/PdsRegionalRegulatedProductListEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingListDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PdsMRCReportingListRelationshipId name="BackingTable_PdsMRCReportingListRelationshipId">BackingTable_PdsMRCReportingListRelationshipId</a>

First included in: ProductInformationManagement/PdsRegionalRegulatedProductListEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PdsMRCReportingListRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/PdsMRCReportingList.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PdsMRCReportingList.cdm.json/PdsMRCReportingList</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/PdsMRCReportingList.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductInformationManagement/PdsRegionalRegulatedProductListEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

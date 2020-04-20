---
title: RetailSalesTaxOverrideGroupMemberEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailSalesTaxOverrideGroupMemberEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Retail/RetailSalesTaxOverrideGroupMemberEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[SalesTaxOverrideCode](#SalesTaxOverrideCode)||<a href="RetailSalesTaxOverrideGroupMemberEntity.md" target="_blank">Retail/RetailSalesTaxOverrideGroupMemberEntity</a>|
|[SalesTaxOverrideGroupCode](#SalesTaxOverrideGroupCode)||<a href="RetailSalesTaxOverrideGroupMemberEntity.md" target="_blank">Retail/RetailSalesTaxOverrideGroupMemberEntity</a>|
|[BackingTable_RetailSalesTaxOverrideGroupMemberRelationshipId](#BackingTable_RetailSalesTaxOverrideGroupMemberRelationshipId)||<a href="RetailSalesTaxOverrideGroupMemberEntity.md" target="_blank">Retail/RetailSalesTaxOverrideGroupMemberEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailSalesTaxOverrideGroupMemberEntity.md" target="_blank">Retail/RetailSalesTaxOverrideGroupMemberEntity</a>|

### <a href=#SalesTaxOverrideCode name="SalesTaxOverrideCode">SalesTaxOverrideCode</a>

First included in: Retail/RetailSalesTaxOverrideGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxOverrideCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxOverrideGroupCode name="SalesTaxOverrideGroupCode">SalesTaxOverrideGroupCode</a>

First included in: Retail/RetailSalesTaxOverrideGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxOverrideGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailSalesTaxOverrideGroupMemberRelationshipId name="BackingTable_RetailSalesTaxOverrideGroupMemberRelationshipId">BackingTable_RetailSalesTaxOverrideGroupMemberRelationshipId</a>

First included in: Retail/RetailSalesTaxOverrideGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailSalesTaxOverrideGroupMemberRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Parameter/RetailSalesTaxOverrideGroupMember.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Parameter/RetailSalesTaxOverrideGroupMember.cdm.json/RetailSalesTaxOverrideGroupMember</a></td><td><a href="../../../Tables/Commerce/Retail/Parameter/RetailSalesTaxOverrideGroupMember.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/RetailSalesTaxOverrideGroupMemberEntity (this entity)  

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

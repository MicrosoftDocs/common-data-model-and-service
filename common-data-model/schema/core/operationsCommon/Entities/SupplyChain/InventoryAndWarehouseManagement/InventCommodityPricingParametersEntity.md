---
title: InventCommodityPricingParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Commodity pricing parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commodity pricing parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CommodityCostBasisTypeId](#CommodityCostBasisTypeId)||<a href="InventCommodityPricingParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity</a>|
|[CommodityPricingTemplateId](#CommodityPricingTemplateId)||<a href="InventCommodityPricingParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity</a>|
|[AreBOMFormulaPriceCalculationsPreserved](#AreBOMFormulaPriceCalculationsPreserved)||<a href="InventCommodityPricingParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity</a>|
|[TradeAgreementJournalNameId](#TradeAgreementJournalNameId)||<a href="InventCommodityPricingParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity</a>|
|[BaseReferenceDepthValue](#BaseReferenceDepthValue)||<a href="InventCommodityPricingParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity</a>|
|[FinancialDimensionSetName](#FinancialDimensionSetName)||<a href="InventCommodityPricingParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity</a>|
|[BackingTable_PdsParametersRelationshipId](#BackingTable_PdsParametersRelationshipId)||<a href="InventCommodityPricingParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventCommodityPricingParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity</a>|

### <a href=#CommodityCostBasisTypeId name="CommodityCostBasisTypeId">CommodityCostBasisTypeId</a>

First included in: InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommodityCostBasisTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommodityPricingTemplateId name="CommodityPricingTemplateId">CommodityPricingTemplateId</a>

First included in: InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommodityPricingTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreBOMFormulaPriceCalculationsPreserved name="AreBOMFormulaPriceCalculationsPreserved">AreBOMFormulaPriceCalculationsPreserved</a>

First included in: InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreBOMFormulaPriceCalculationsPreserved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAgreementJournalNameId name="TradeAgreementJournalNameId">TradeAgreementJournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAgreementJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseReferenceDepthValue name="BaseReferenceDepthValue">BaseReferenceDepthValue</a>

First included in: InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseReferenceDepthValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinancialDimensionSetName name="FinancialDimensionSetName">FinancialDimensionSetName</a>

First included in: InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialDimensionSetName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PdsParametersRelationshipId name="BackingTable_PdsParametersRelationshipId">BackingTable_PdsParametersRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PdsParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Parameter/PdsParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Parameter/PdsParameters.cdm.json/PdsParameters</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Parameter/PdsParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventCommodityPricingParametersEntity (this entity)  

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

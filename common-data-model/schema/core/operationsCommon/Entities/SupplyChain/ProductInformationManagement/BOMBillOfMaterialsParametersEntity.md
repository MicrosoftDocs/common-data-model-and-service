---
title: BOMBillOfMaterialsParametersEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Bill of materials parameters in ProductInformationManagement(BOMBillOfMaterialsParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/BOMBillOfMaterialsParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bill of materials parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CircularityCheckLevel](#CircularityCheckLevel)||<a href="BOMBillOfMaterialsParametersEntity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsParametersEntity</a>|
|[MaximumBOMLevel](#MaximumBOMLevel)||<a href="BOMBillOfMaterialsParametersEntity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsParametersEntity</a>|
|[AreQuantitiesOnBOMLinesAndDatesOnBOMVersionMandatory](#AreQuantitiesOnBOMLinesAndDatesOnBOMVersionMandatory)||<a href="BOMBillOfMaterialsParametersEntity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsParametersEntity</a>|
|[IsBOMAndVersionApprovalRemovalBlocked](#IsBOMAndVersionApprovalRemovalBlocked)||<a href="BOMBillOfMaterialsParametersEntity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsParametersEntity</a>|
|[IsBOMEditingBlocked](#IsBOMEditingBlocked)||<a href="BOMBillOfMaterialsParametersEntity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsParametersEntity</a>|
|[CircularityCheckStrategy](#CircularityCheckStrategy)||<a href="BOMBillOfMaterialsParametersEntity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsParametersEntity</a>|
|[FallbackCostCalculationGroupId](#FallbackCostCalculationGroupId)||<a href="BOMBillOfMaterialsParametersEntity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsParametersEntity</a>|
|[BackingTable_BOMParametersRelationshipId](#BackingTable_BOMParametersRelationshipId)||<a href="BOMBillOfMaterialsParametersEntity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BOMBillOfMaterialsParametersEntity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsParametersEntity</a>|

### <a href=#CircularityCheckLevel name="CircularityCheckLevel">CircularityCheckLevel</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CircularityCheckLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumBOMLevel name="MaximumBOMLevel">MaximumBOMLevel</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumBOMLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreQuantitiesOnBOMLinesAndDatesOnBOMVersionMandatory name="AreQuantitiesOnBOMLinesAndDatesOnBOMVersionMandatory">AreQuantitiesOnBOMLinesAndDatesOnBOMVersionMandatory</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreQuantitiesOnBOMLinesAndDatesOnBOMVersionMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBOMAndVersionApprovalRemovalBlocked name="IsBOMAndVersionApprovalRemovalBlocked">IsBOMAndVersionApprovalRemovalBlocked</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBOMAndVersionApprovalRemovalBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBOMEditingBlocked name="IsBOMEditingBlocked">IsBOMEditingBlocked</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBOMEditingBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CircularityCheckStrategy name="CircularityCheckStrategy">CircularityCheckStrategy</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CircularityCheckStrategy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FallbackCostCalculationGroupId name="FallbackCostCalculationGroupId">FallbackCostCalculationGroupId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FallbackCostCalculationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BOMParametersRelationshipId name="BackingTable_BOMParametersRelationshipId">BackingTable_BOMParametersRelationshipId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BOMParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Parameter/BOMParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Parameter/BOMParameters.cdm.json/BOMParameters</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Parameter/BOMParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsParametersEntity (this entity)  

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

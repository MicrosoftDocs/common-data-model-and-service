---
title: ProjRevenueProfile - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# ProjRevenueProfile

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjRevenueProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjRevenueProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[AccruedLossCategoryId](#AccruedLossCategoryId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[CompletePrinciple](#CompletePrinciple)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[CostTemplate](#CostTemplate)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[CostLedgerStatus](#CostLedgerStatus)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[PostWIPCost](#PostWIPCost)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[EmplLedgerStatus](#EmplLedgerStatus)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[PostWIPEmpl](#PostWIPEmpl)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[ForeseeableLosses](#ForeseeableLosses)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[OnAccLedgerStatus](#OnAccLedgerStatus)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[ItemLedgerStatus](#ItemLedgerStatus)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[PostWIPItem](#PostWIPItem)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[MatchingPrinciple](#MatchingPrinciple)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[Name](#Name)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[PeriodId](#PeriodId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[ProductionCategoryId](#ProductionCategoryId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[ProfitCategoryId](#ProfitCategoryId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[ProjRevenueProfileId](#ProjRevenueProfileId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[PostWIPFee](#PostWIPFee)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[SalesPriceMatchingPrinciple](#SalesPriceMatchingPrinciple)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[SalesvalueCategoryId](#SalesvalueCategoryId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[BillingMethod](#BillingMethod)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[DataAreaId](#DataAreaId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[Relationship_ProjCategory_AccruedCostRelationshipId](#Relationship_ProjCategory_AccruedCostRelationshipId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[Relationship_ProjCategory_ProductionRelationshipId](#Relationship_ProjCategory_ProductionRelationshipId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[Relationship_ProjCategory_ProfitRelationshipId](#Relationship_ProjCategory_ProfitRelationshipId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[Relationship_ProjCategory_SalesValueRelationshipId](#Relationship_ProjCategory_SalesValueRelationshipId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[Relationship_ProjControlRelationshipId](#Relationship_ProjControlRelationshipId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[Relationship_ProjPeriodIDRelationshipId](#Relationship_ProjPeriodIDRelationshipId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ProjRevenueProfile.md" target="_blank">Group/ProjRevenueProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjRevenueProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccruedLossCategoryId name="AccruedLossCategoryId">AccruedLossCategoryId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccruedLossCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompletePrinciple name="CompletePrinciple">CompletePrinciple</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompletePrinciple attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CostTemplate name="CostTemplate">CostTemplate</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostLedgerStatus name="CostLedgerStatus">CostLedgerStatus</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostLedgerStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostWIPCost name="PostWIPCost">PostWIPCost</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostWIPCost attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EmplLedgerStatus name="EmplLedgerStatus">EmplLedgerStatus</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplLedgerStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostWIPEmpl name="PostWIPEmpl">PostWIPEmpl</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostWIPEmpl attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ForeseeableLosses name="ForeseeableLosses">ForeseeableLosses</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeseeableLosses attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OnAccLedgerStatus name="OnAccLedgerStatus">OnAccLedgerStatus</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccLedgerStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemLedgerStatus name="ItemLedgerStatus">ItemLedgerStatus</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemLedgerStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostWIPItem name="PostWIPItem">PostWIPItem</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostWIPItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MatchingPrinciple name="MatchingPrinciple">MatchingPrinciple</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchingPrinciple attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Group/ProjRevenueProfile (this entity)  

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

### <a href=#PeriodId name="PeriodId">PeriodId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionCategoryId name="ProductionCategoryId">ProductionCategoryId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitCategoryId name="ProfitCategoryId">ProfitCategoryId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjRevenueProfileId name="ProjRevenueProfileId">ProjRevenueProfileId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjRevenueProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostWIPFee name="PostWIPFee">PostWIPFee</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostWIPFee attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesPriceMatchingPrinciple name="SalesPriceMatchingPrinciple">SalesPriceMatchingPrinciple</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceMatchingPrinciple attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesvalueCategoryId name="SalesvalueCategoryId">SalesvalueCategoryId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesvalueCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingMethod name="BillingMethod">BillingMethod</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/ProjRevenueProfile (this entity)  

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

### <a href=#Relationship_ProjCategory_AccruedCostRelationshipId name="Relationship_ProjCategory_AccruedCostRelationshipId">Relationship_ProjCategory_AccruedCostRelationshipId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjCategory_AccruedCostRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProjCategory.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.cdm.json/ProjCategory</a></td><td><a href="ProjCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjCategory_ProductionRelationshipId name="Relationship_ProjCategory_ProductionRelationshipId">Relationship_ProjCategory_ProductionRelationshipId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjCategory_ProductionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProjCategory.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.cdm.json/ProjCategory</a></td><td><a href="ProjCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjCategory_ProfitRelationshipId name="Relationship_ProjCategory_ProfitRelationshipId">Relationship_ProjCategory_ProfitRelationshipId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjCategory_ProfitRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProjCategory.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.cdm.json/ProjCategory</a></td><td><a href="ProjCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjCategory_SalesValueRelationshipId name="Relationship_ProjCategory_SalesValueRelationshipId">Relationship_ProjCategory_SalesValueRelationshipId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjCategory_SalesValueRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProjCategory.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.cdm.json/ProjCategory</a></td><td><a href="ProjCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjControlRelationshipId name="Relationship_ProjControlRelationshipId">Relationship_ProjControlRelationshipId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjControlRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProjControl.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjControl.cdm.json/ProjControl</a></td><td><a href="ProjControl.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjPeriodIDRelationshipId name="Relationship_ProjPeriodIDRelationshipId">Relationship_ProjPeriodIDRelationshipId</a>

First included in: Group/ProjRevenueProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjPeriodIDRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProjPeriodTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPeriodTable.cdm.json/ProjPeriodTable</a></td><td><a href="ProjPeriodTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/ProjRevenueProfile (this entity)  

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

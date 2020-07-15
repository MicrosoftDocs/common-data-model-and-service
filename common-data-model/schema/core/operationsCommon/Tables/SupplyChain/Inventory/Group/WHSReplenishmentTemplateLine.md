---
title: WHSReplenishmentTemplateLine in Group - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Replenishment Template Lines in Group(WHSReplenishmentTemplateLine)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSReplenishmentTemplateLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSReplenishmentTemplateLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Replenishment Template Lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[ApplicableDemand](#ApplicableDemand)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[DemandIncrement](#DemandIncrement)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[Description](#Description)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[EvalEmptyFixed](#EvalEmptyFixed)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[ItemQuery](#ItemQuery)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[LocationQuery](#LocationQuery)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[LocDirHintCode](#LocDirHintCode)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[MaxQty](#MaxQty)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[MinQty](#MinQty)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[QtyUOM](#QtyUOM)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[ReplenFixedOnly](#ReplenFixedOnly)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[ReplenishmentUOM](#ReplenishmentUOM)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[ReplenishTemplateId](#ReplenishTemplateId)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[RequestTypeId](#RequestTypeId)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[SeqNum](#SeqNum)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[WorkTemplateCode](#WorkTemplateCode)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[ProductQueryMode](#ProductQueryMode)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[ProductVariantQuery](#ProductVariantQuery)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[ReplenishmentStrategy](#ReplenishmentStrategy)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[ReplenishmentThresholdScope](#ReplenishmentThresholdScope)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[InventLocationId](#InventLocationId)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[ZoneQuery](#ZoneQuery)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[DataAreaId](#DataAreaId)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[Relationship_WHSLocDirHintRelationshipId](#Relationship_WHSLocDirHintRelationshipId)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[Relationship_WHSReplenishmentTemplateRelationshipId](#Relationship_WHSReplenishmentTemplateRelationshipId)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[Relationship_WHSRequestTypeRelationshipId](#Relationship_WHSRequestTypeRelationshipId)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[Relationship_WHSWorkTemplateTableRelationshipId](#Relationship_WHSWorkTemplateTableRelationshipId)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[Relationship_InventLocationRelationshipId](#Relationship_InventLocationRelationshipId)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WHSReplenishmentTemplateLine.md" target="_blank">Group/WHSReplenishmentTemplateLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSReplenishmentTemplateLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ApplicableDemand name="ApplicableDemand">ApplicableDemand</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicableDemand attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DemandIncrement name="DemandIncrement">DemandIncrement</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandIncrement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EvalEmptyFixed name="EvalEmptyFixed">EvalEmptyFixed</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EvalEmptyFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ItemQuery name="ItemQuery">ItemQuery</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#LocationQuery name="LocationQuery">LocationQuery</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#LocDirHintCode name="LocDirHintCode">LocDirHintCode</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocDirHintCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxQty name="MaxQty">MaxQty</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MinQty name="MinQty">MinQty</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyUOM name="QtyUOM">QtyUOM</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyUOM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenFixedOnly name="ReplenFixedOnly">ReplenFixedOnly</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenFixedOnly attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReplenishmentUOM name="ReplenishmentUOM">ReplenishmentUOM</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentUOM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishTemplateId name="ReplenishTemplateId">ReplenishTemplateId</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestTypeId name="RequestTypeId">RequestTypeId</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SeqNum name="SeqNum">SeqNum</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SeqNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WorkTemplateCode name="WorkTemplateCode">WorkTemplateCode</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkTemplateCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductQueryMode name="ProductQueryMode">ProductQueryMode</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductQueryMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProductVariantQuery name="ProductVariantQuery">ProductVariantQuery</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentStrategy name="ReplenishmentStrategy">ReplenishmentStrategy</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentStrategy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReplenishmentThresholdScope name="ReplenishmentThresholdScope">ReplenishmentThresholdScope</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentThresholdScope attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventLocationId name="InventLocationId">InventLocationId</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZoneQuery name="ZoneQuery">ZoneQuery</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZoneQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

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

### <a href=#Relationship_WHSLocDirHintRelationshipId name="Relationship_WHSLocDirHintRelationshipId">Relationship_WHSLocDirHintRelationshipId</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSLocDirHintRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSLocDirHint.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSLocDirHint.cdm.json/WHSLocDirHint</a></td><td><a href="WHSLocDirHint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSReplenishmentTemplateRelationshipId name="Relationship_WHSReplenishmentTemplateRelationshipId">Relationship_WHSReplenishmentTemplateRelationshipId</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSReplenishmentTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSReplenishmentTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSReplenishmentTemplate.cdm.json/WHSReplenishmentTemplate</a></td><td><a href="WHSReplenishmentTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSRequestTypeRelationshipId name="Relationship_WHSRequestTypeRelationshipId">Relationship_WHSRequestTypeRelationshipId</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSRequestTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSRequestType.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSRequestType.cdm.json/WHSRequestType</a></td><td><a href="WHSRequestType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSWorkTemplateTableRelationshipId name="Relationship_WHSWorkTemplateTableRelationshipId">Relationship_WHSWorkTemplateTableRelationshipId</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSWorkTemplateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WHSWorkTemplateTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSWorkTemplateTable.cdm.json/WHSWorkTemplateTable</a></td><td><a href="../Main/WHSWorkTemplateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventLocationRelationshipId name="Relationship_InventLocationRelationshipId">Relationship_InventLocationRelationshipId</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/WHSReplenishmentTemplateLine (this entity)  

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

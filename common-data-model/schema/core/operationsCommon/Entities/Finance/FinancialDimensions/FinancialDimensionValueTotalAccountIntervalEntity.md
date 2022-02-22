---
title: FinancialDimensionValueTotalAccountIntervalEntity in FinancialDimensions - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Financial dimension value totaling account intervals in FinancialDimensions(FinancialDimensionValueTotalAccountIntervalEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial dimension value totaling account intervals</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FinancialDimension](#FinancialDimension)||<a href="FinancialDimensionValueTotalAccountIntervalEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity</a>|
|[LegalEntityId](#LegalEntityId)||<a href="FinancialDimensionValueTotalAccountIntervalEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity</a>|
|[DimensionValue](#DimensionValue)||<a href="FinancialDimensionValueTotalAccountIntervalEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity</a>|
|[FromValue](#FromValue)||<a href="FinancialDimensionValueTotalAccountIntervalEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity</a>|
|[ToValue](#ToValue)||<a href="FinancialDimensionValueTotalAccountIntervalEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity</a>|
|[InvertTotalSign](#InvertTotalSign)||<a href="FinancialDimensionValueTotalAccountIntervalEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity</a>|
|[Relationship_DimensionAttributeEntityRelationshipId](#Relationship_DimensionAttributeEntityRelationshipId)||<a href="FinancialDimensionValueTotalAccountIntervalEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity</a>|
|[Relationship_OfficeAddinLegalEntityEntityRelationshipId](#Relationship_OfficeAddinLegalEntityEntityRelationshipId)||<a href="FinancialDimensionValueTotalAccountIntervalEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity</a>|
|[BackingTable_DimensionAttributeValueTotallingCriteriaRelationshipId](#BackingTable_DimensionAttributeValueTotallingCriteriaRelationshipId)||<a href="FinancialDimensionValueTotalAccountIntervalEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity</a>|

### <a href=#FinancialDimension name="FinancialDimension">FinancialDimension</a>

First included in: FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financial dimension name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial dimension name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue name="DimensionValue">DimensionValue</a>

First included in: FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dimension value</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dimension value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromValue name="FromValue">FromValue</a>

First included in: FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToValue name="ToValue">ToValue</a>

First included in: FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvertTotalSign name="InvertTotalSign">InvertTotalSign</a>

First included in: FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invert sign</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvertTotalSign attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invert sign</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeEntityRelationshipId name="Relationship_DimensionAttributeEntityRelationshipId">Relationship_DimensionAttributeEntityRelationshipId</a>

First included in: FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OfficeAddinLegalEntityEntityRelationshipId name="Relationship_OfficeAddinLegalEntityEntityRelationshipId">Relationship_OfficeAddinLegalEntityEntityRelationshipId</a>

First included in: FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OfficeAddinLegalEntityEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DimensionAttributeValueTotallingCriteriaRelationshipId name="BackingTable_DimensionAttributeValueTotallingCriteriaRelationshipId">BackingTable_DimensionAttributeValueTotallingCriteriaRelationshipId</a>

First included in: FinancialDimensions/FinancialDimensionValueTotalAccountIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DimensionAttributeValueTotallingCriteriaRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueTotallingCriteria.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueTotallingCriteria.cdm.json/DimensionAttributeValueTotallingCriteria</a></td><td><a href="../../../Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueTotallingCriteria.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

---
title: FinancialDimensionValueLegalEntityOverrideEntity in FinancialDimensions - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Financial dimension value legal entity overrides in FinancialDimensions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial dimension value legal entity overrides</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FinancialDimension](#FinancialDimension)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[EntityInstance](#EntityInstance)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[DimensionValue](#DimensionValue)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[LegalEntityId](#LegalEntityId)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[ActiveFrom](#ActiveFrom)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[ActiveTo](#ActiveTo)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[IsSuspended](#IsSuspended)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[OwnerRefRecId](#OwnerRefRecId)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[Owner](#Owner)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[Relationship_DimensionAttributeRelationshipId](#Relationship_DimensionAttributeRelationshipId)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[Relationship_LegalEntityRelationshipId](#Relationship_LegalEntityRelationshipId)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[Relationship_HcmWorkerRelationshipId](#Relationship_HcmWorkerRelationshipId)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|
|[BackingTable_DimensionAttrValueLedgerOverrideRelationshipId](#BackingTable_DimensionAttrValueLedgerOverrideRelationshipId)||<a href="FinancialDimensionValueLegalEntityOverrideEntity.md" target="_blank">FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity</a>|

### <a href=#FinancialDimension name="FinancialDimension">FinancialDimension</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntityInstance name="EntityInstance">EntityInstance</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityInstance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue name="DimensionValue">DimensionValue</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

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

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Legal entity</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Legal entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveFrom name="ActiveFrom">ActiveFrom</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveTo name="ActiveTo">ActiveTo</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSuspended name="IsSuspended">IsSuspended</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSuspended attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OwnerRefRecId name="OwnerRefRecId">OwnerRefRecId</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OwnerRefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Owner name="Owner">Owner</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Owner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeRelationshipId name="Relationship_DimensionAttributeRelationshipId">Relationship_DimensionAttributeRelationshipId</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LegalEntityRelationshipId name="Relationship_LegalEntityRelationshipId">Relationship_LegalEntityRelationshipId</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LegalEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HcmWorkerRelationshipId name="Relationship_HcmWorkerRelationshipId">Relationship_HcmWorkerRelationshipId</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmWorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_DimensionAttrValueLedgerOverrideRelationshipId name="BackingTable_DimensionAttrValueLedgerOverrideRelationshipId">BackingTable_DimensionAttrValueLedgerOverrideRelationshipId</a>

First included in: FinancialDimensions/FinancialDimensionValueLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DimensionAttrValueLedgerOverrideRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FinancialDimensions/Main/DimensionAttrValueLedgerOverride.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttrValueLedgerOverride.cdm.json/DimensionAttrValueLedgerOverride</a></td><td><a href="../../../Tables/Finance/FinancialDimensions/Main/DimensionAttrValueLedgerOverride.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

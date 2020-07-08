---
title: TaxReportHierarchyNode_IN in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Sales tax hierarchy node in Main(TaxReportHierarchyNode_IN)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Main/TaxReportHierarchyNode_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReportHierarchyNode_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax hierarchy node</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[CanMatch](#CanMatch)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[CanPost](#CanPost)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[CanSettle](#CanSettle)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[ComboDisplayValue](#ComboDisplayValue)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[ComboDisplayValueStr](#ComboDisplayValueStr)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[DisplayValue](#DisplayValue)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[Enable](#Enable)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[LeftId](#LeftId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[Level](#Level)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[NodeId](#NodeId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[NodeType](#NodeType)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[ParentId](#ParentId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[RefClassId](#RefClassId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[RefEnumId](#RefEnumId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[RefEnumValue](#RefEnumValue)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[RefFieldId](#RefFieldId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[RefTableId](#RefTableId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[RefTableRecId](#RefTableRecId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[RightId](#RightId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[TaxReportHierarchyVersion_IN](#TaxReportHierarchyVersion_IN)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[GTEReferenceBindingVersion](#GTEReferenceBindingVersion)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[GTEReferenceSequence](#GTEReferenceSequence)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[GTERuntimeRecId](#GTERuntimeRecId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[GTERuntimeTableId](#GTERuntimeTableId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[Relationship_TaxReportHierarchyVersion_INRelationshipId](#Relationship_TaxReportHierarchyVersion_INRelationshipId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxReportHierarchyNode_IN.md" target="_blank">Main/TaxReportHierarchyNode_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReportHierarchyNode_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CanMatch name="CanMatch">CanMatch</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The selected node is used to match the transaction record</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanMatch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The selected node is used to match the transaction record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CanPost name="CanPost">CanPost</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The selected node is used to post sales tax payments</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanPost attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The selected node is used to post sales tax payments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CanSettle name="CanSettle">CanSettle</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The selected node is used to settle taxes</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanSettle attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The selected node is used to settle taxes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ComboDisplayValue name="ComboDisplayValue">ComboDisplayValue</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComboDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComboDisplayValueStr name="ComboDisplayValueStr">ComboDisplayValueStr</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComboDisplayValueStr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayValue name="DisplayValue">DisplayValue</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Enable name="Enable">Enable</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Enable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LeftId name="LeftId">LeftId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeftId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Level name="Level">Level</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NodeId name="NodeId">NodeId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NodeId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NodeType name="NodeType">NodeType</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NodeType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ParentId name="ParentId">ParentId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RefClassId name="RefClassId">RefClassId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefClassId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RefEnumId name="RefEnumId">RefEnumId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefEnumId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefEnumValue name="RefEnumValue">RefEnumValue</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefEnumValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefFieldId name="RefFieldId">RefFieldId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefTableRecId name="RefTableRecId">RefTableRecId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RightId name="RightId">RightId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RightId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxReportHierarchyVersion_IN name="TaxReportHierarchyVersion_IN">TaxReportHierarchyVersion_IN</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportHierarchyVersion_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GTEReferenceBindingVersion name="GTEReferenceBindingVersion">GTEReferenceBindingVersion</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GTEReferenceBindingVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GTEReferenceSequence name="GTEReferenceSequence">GTEReferenceSequence</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GTEReferenceSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GTERuntimeRecId name="GTERuntimeRecId">GTERuntimeRecId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GTERuntimeRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GTERuntimeTableId name="GTERuntimeTableId">GTERuntimeTableId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GTERuntimeTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

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

### <a href=#Relationship_TaxReportHierarchyVersion_INRelationshipId name="Relationship_TaxReportHierarchyVersion_INRelationshipId">Relationship_TaxReportHierarchyVersion_INRelationshipId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportHierarchyVersion_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxReportHierarchyVersion_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportHierarchyVersion_IN.cdm.json/TaxReportHierarchyVersion_IN</a></td><td><a href="../Group/TaxReportHierarchyVersion_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/TaxReportHierarchyNode_IN (this entity)  

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

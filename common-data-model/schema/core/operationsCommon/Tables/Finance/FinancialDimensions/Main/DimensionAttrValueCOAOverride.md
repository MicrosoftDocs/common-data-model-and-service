---
title: DimensionAttrValueCOAOverride in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Dimension code chart of accounts override in Main

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttrValueCOAOverride.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionAttrValueCOAOverride/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dimension code chart of accounts override</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|
|[ActiveFrom](#ActiveFrom)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|
|[ActiveTo](#ActiveTo)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|
|[ChartOfAccounts](#ChartOfAccounts)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|
|[DimensionAttributeValue](#DimensionAttributeValue)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|
|[IsDateRangeOverriddenByUser](#IsDateRangeOverriddenByUser)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|
|[IsOwnerOverriddenByUser](#IsOwnerOverriddenByUser)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|
|[IsSuspended](#IsSuspended)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|
|[IsSuspendedOverriddenByUser](#IsSuspendedOverriddenByUser)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|
|[Owner](#Owner)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|
|[Relationship_DimensionAttributeValueRelationshipId](#Relationship_DimensionAttributeValueRelationshipId)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|
|[Relationship_LedgerChartOfAccountsRelationshipId](#Relationship_LedgerChartOfAccountsRelationshipId)||<a href="DimensionAttrValueCOAOverride.md" target="_blank">Main/DimensionAttrValueCOAOverride</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionAttrValueCOAOverride/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActiveFrom name="ActiveFrom">ActiveFrom</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ActiveTo name="ActiveTo">ActiveTo</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ChartOfAccounts name="ChartOfAccounts">ChartOfAccounts</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Chart of accounts</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChartOfAccounts attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Chart of accounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DimensionAttributeValue name="DimensionAttributeValue">DimensionAttributeValue</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dimension value</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionAttributeValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dimension value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsDateRangeOverriddenByUser name="IsDateRangeOverriddenByUser">IsDateRangeOverriddenByUser</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDateRangeOverriddenByUser attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsOwnerOverriddenByUser name="IsOwnerOverriddenByUser">IsOwnerOverriddenByUser</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOwnerOverriddenByUser attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsSuspended name="IsSuspended">IsSuspended</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Suspended</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSuspended attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Suspended</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsSuspendedOverriddenByUser name="IsSuspendedOverriddenByUser">IsSuspendedOverriddenByUser</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSuspendedOverriddenByUser attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Owner name="Owner">Owner</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Owner attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_DimensionAttributeValueRelationshipId name="Relationship_DimensionAttributeValueRelationshipId">Relationship_DimensionAttributeValueRelationshipId</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerChartOfAccountsRelationshipId name="Relationship_LedgerChartOfAccountsRelationshipId">Relationship_LedgerChartOfAccountsRelationshipId</a>

First included in: Main/DimensionAttrValueCOAOverride (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerChartOfAccountsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/LedgerChartOfAccounts.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/LedgerChartOfAccounts.cdm.json/LedgerChartOfAccounts</a></td><td><a href="../../Ledger/Main/LedgerChartOfAccounts.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

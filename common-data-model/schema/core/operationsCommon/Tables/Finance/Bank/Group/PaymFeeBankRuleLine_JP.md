---
title: PaymFeeBankRuleLine_JP in Group - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Bank rules line for payment fee in Group(PaymFeeBankRuleLine_JP)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Bank/Group/PaymFeeBankRuleLine_JP.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PaymFeeBankRuleLine_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank rules line for payment fee</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PaymFeeBankRuleLine_JP.md" target="_blank">Group/PaymFeeBankRuleLine_JP</a>|
|[LineId](#LineId)||<a href="PaymFeeBankRuleLine_JP.md" target="_blank">Group/PaymFeeBankRuleLine_JP</a>|
|[CompanyFieldId](#CompanyFieldId)||<a href="PaymFeeBankRuleLine_JP.md" target="_blank">Group/PaymFeeBankRuleLine_JP</a>|
|[CompanyTableId](#CompanyTableId)||<a href="PaymFeeBankRuleLine_JP.md" target="_blank">Group/PaymFeeBankRuleLine_JP</a>|
|[CustVendFieldId](#CustVendFieldId)||<a href="PaymFeeBankRuleLine_JP.md" target="_blank">Group/PaymFeeBankRuleLine_JP</a>|
|[CustVendTableId](#CustVendTableId)||<a href="PaymFeeBankRuleLine_JP.md" target="_blank">Group/PaymFeeBankRuleLine_JP</a>|
|[PaymFeeBankRule_JP](#PaymFeeBankRule_JP)||<a href="PaymFeeBankRuleLine_JP.md" target="_blank">Group/PaymFeeBankRuleLine_JP</a>|
|[Relation](#Relation)||<a href="PaymFeeBankRuleLine_JP.md" target="_blank">Group/PaymFeeBankRuleLine_JP</a>|
|[Value](#Value)||<a href="PaymFeeBankRuleLine_JP.md" target="_blank">Group/PaymFeeBankRuleLine_JP</a>|
|[Relationship_PaymFeeBankRule_JPRelationshipId](#Relationship_PaymFeeBankRule_JPRelationshipId)||<a href="PaymFeeBankRuleLine_JP.md" target="_blank">Group/PaymFeeBankRuleLine_JP</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/PaymFeeBankRuleLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PaymFeeBankRuleLine_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineId name="LineId">LineId</a>

First included in: Group/PaymFeeBankRuleLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyFieldId name="CompanyFieldId">CompanyFieldId</a>

First included in: Group/PaymFeeBankRuleLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company bank group</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company bank group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CompanyTableId name="CompanyTableId">CompanyTableId</a>

First included in: Group/PaymFeeBankRuleLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Table</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CustVendFieldId name="CustVendFieldId">CustVendFieldId</a>

First included in: Group/PaymFeeBankRuleLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party bank group</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustVendFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party bank group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CustVendTableId name="CustVendTableId">CustVendTableId</a>

First included in: Group/PaymFeeBankRuleLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Table</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustVendTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PaymFeeBankRule_JP name="PaymFeeBankRule_JP">PaymFeeBankRule_JP</a>

First included in: Group/PaymFeeBankRuleLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymFeeBankRule_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relation name="Relation">Relation</a>

First included in: Group/PaymFeeBankRuleLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Value name="Value">Value</a>

First included in: Group/PaymFeeBankRuleLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymFeeBankRule_JPRelationshipId name="Relationship_PaymFeeBankRule_JPRelationshipId">Relationship_PaymFeeBankRule_JPRelationshipId</a>

First included in: Group/PaymFeeBankRuleLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymFeeBankRule_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PaymFeeBankRule_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymFeeBankRule_JP.cdm.json/PaymFeeBankRule_JP</a></td><td><a href="PaymFeeBankRule_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

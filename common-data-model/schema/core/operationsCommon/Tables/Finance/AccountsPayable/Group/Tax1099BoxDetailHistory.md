---
title: Tax1099BoxDetailHistory in Group - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Tax 1099 detail in Group(Tax1099BoxDetailHistory)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/Group/Tax1099BoxDetailHistory.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[Tax1099BoxDetailHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax 1099 detail</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[Tax1099AddressorLegalDesc](#Tax1099AddressorLegalDesc)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[Tax1099BoxDetailRecId](#Tax1099BoxDetailRecId)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[Tax1099BuyersTax](#Tax1099BuyersTax)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[Tax1099DateOfClosing](#Tax1099DateOfClosing)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[Tax1099PropertyOrServices](#Tax1099PropertyOrServices)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[Tax1099TaxYear](#Tax1099TaxYear)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[Tax1099TradeOrBusiness](#Tax1099TradeOrBusiness)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[ValidFrom](#ValidFrom)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[ValidTo](#ValidTo)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[DataAreaId](#DataAreaId)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[Relationship_Tax1099BoxDetailRelationshipId](#Relationship_Tax1099BoxDetailRelationshipId)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="Tax1099BoxDetailHistory.md" target="_blank">Group/Tax1099BoxDetailHistory</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[Tax1099BoxDetailHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Tax1099AddressorLegalDesc name="Tax1099AddressorLegalDesc">Tax1099AddressorLegalDesc</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099AddressorLegalDesc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099BoxDetailRecId name="Tax1099BoxDetailRecId">Tax1099BoxDetailRecId</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099BoxDetailRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Tax1099BuyersTax name="Tax1099BuyersTax">Tax1099BuyersTax</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099BuyersTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Tax1099DateOfClosing name="Tax1099DateOfClosing">Tax1099DateOfClosing</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099DateOfClosing attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#Tax1099PropertyOrServices name="Tax1099PropertyOrServices">Tax1099PropertyOrServices</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099PropertyOrServices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Tax1099TaxYear name="Tax1099TaxYear">Tax1099TaxYear</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099TaxYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Tax1099TradeOrBusiness name="Tax1099TradeOrBusiness">Tax1099TradeOrBusiness</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099TradeOrBusiness attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

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

### <a href=#Relationship_Tax1099BoxDetailRelationshipId name="Relationship_Tax1099BoxDetailRelationshipId">Relationship_Tax1099BoxDetailRelationshipId</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Tax1099BoxDetailRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/Tax1099BoxDetail.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Miscellaneous/Tax1099BoxDetail.cdm.json/Tax1099BoxDetail</a></td><td><a href="../Miscellaneous/Tax1099BoxDetail.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/Tax1099BoxDetailHistory (this entity)  

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

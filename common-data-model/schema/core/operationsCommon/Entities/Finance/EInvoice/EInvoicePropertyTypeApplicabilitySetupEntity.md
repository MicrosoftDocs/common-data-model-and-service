---
title: EInvoicePropertyTypeApplicabilitySetupEntity in EInvoice - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Electronic document property type applicability setup in EInvoice(EInvoicePropertyTypeApplicabilitySetupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/EInvoice/EInvoicePropertyTypeApplicabilitySetupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic document property type applicability setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RefTableId](#RefTableId)||<a href="EInvoicePropertyTypeApplicabilitySetupEntity.md" target="_blank">EInvoice/EInvoicePropertyTypeApplicabilitySetupEntity</a>|
|[TypeId](#TypeId)||<a href="EInvoicePropertyTypeApplicabilitySetupEntity.md" target="_blank">EInvoice/EInvoicePropertyTypeApplicabilitySetupEntity</a>|
|[PropertyType](#PropertyType)||<a href="EInvoicePropertyTypeApplicabilitySetupEntity.md" target="_blank">EInvoice/EInvoicePropertyTypeApplicabilitySetupEntity</a>|
|[TableName](#TableName)||<a href="EInvoicePropertyTypeApplicabilitySetupEntity.md" target="_blank">EInvoice/EInvoicePropertyTypeApplicabilitySetupEntity</a>|
|[BackingTable_EInvoicePropertyTypeApplicabilitySetupRelationshipId](#BackingTable_EInvoicePropertyTypeApplicabilitySetupRelationshipId)||<a href="EInvoicePropertyTypeApplicabilitySetupEntity.md" target="_blank">EInvoice/EInvoicePropertyTypeApplicabilitySetupEntity</a>|

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: EInvoice/EInvoicePropertyTypeApplicabilitySetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeId name="TypeId">TypeId</a>

First included in: EInvoice/EInvoicePropertyTypeApplicabilitySetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PropertyType name="PropertyType">PropertyType</a>

First included in: EInvoice/EInvoicePropertyTypeApplicabilitySetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TableName name="TableName">TableName</a>

First included in: EInvoice/EInvoicePropertyTypeApplicabilitySetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EInvoicePropertyTypeApplicabilitySetupRelationshipId name="BackingTable_EInvoicePropertyTypeApplicabilitySetupRelationshipId">BackingTable_EInvoicePropertyTypeApplicabilitySetupRelationshipId</a>

First included in: EInvoice/EInvoicePropertyTypeApplicabilitySetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EInvoicePropertyTypeApplicabilitySetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/EInvoice/Main/EInvoicePropertyTypeApplicabilitySetup.md" target="_blank">/core/operationsCommon/Tables/Finance/EInvoice/Main/EInvoicePropertyTypeApplicabilitySetup.cdm.json/EInvoicePropertyTypeApplicabilitySetup</a></td><td><a href="../../../Tables/Finance/EInvoice/Main/EInvoicePropertyTypeApplicabilitySetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

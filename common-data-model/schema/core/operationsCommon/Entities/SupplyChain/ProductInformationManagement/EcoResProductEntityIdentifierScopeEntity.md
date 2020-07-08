---
title: EcoResProductEntityIdentifierScopeEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Product entity identifier scope entity in ProductInformationManagement(EcoResProductEntityIdentifierScopeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product entity identifier scope entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LegalEntity](#LegalEntity)||<a href="EcoResProductEntityIdentifierScopeEntity.md" target="_blank">ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity</a>|
|[Code](#Code)||<a href="EcoResProductEntityIdentifierScopeEntity.md" target="_blank">ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity</a>|
|[CodeId](#CodeId)||<a href="EcoResProductEntityIdentifierScopeEntity.md" target="_blank">ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity</a>|
|[CodeType](#CodeType)||<a href="EcoResProductEntityIdentifierScopeEntity.md" target="_blank">ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="EcoResProductEntityIdentifierScopeEntity.md" target="_blank">ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity</a>|
|[CustomerGroup](#CustomerGroup)||<a href="EcoResProductEntityIdentifierScopeEntity.md" target="_blank">ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity</a>|
|[VendorAccount](#VendorAccount)||<a href="EcoResProductEntityIdentifierScopeEntity.md" target="_blank">ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity</a>|
|[VendorGroup](#VendorGroup)||<a href="EcoResProductEntityIdentifierScopeEntity.md" target="_blank">ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity</a>|
|[BackingTable_EcoResProductEntityIdentifierScopeRelationshipId](#BackingTable_EcoResProductEntityIdentifierScopeRelationshipId)||<a href="EcoResProductEntityIdentifierScopeEntity.md" target="_blank">ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity</a>|

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Code name="Code">Code</a>

First included in: ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Code attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CodeId name="CodeId">CodeId</a>

First included in: ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CodeType name="CodeType">CodeType</a>

First included in: ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerGroup name="CustomerGroup">CustomerGroup</a>

First included in: ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccount name="VendorAccount">VendorAccount</a>

First included in: ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorGroup name="VendorGroup">VendorGroup</a>

First included in: ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResProductEntityIdentifierScopeRelationshipId name="BackingTable_EcoResProductEntityIdentifierScopeRelationshipId">BackingTable_EcoResProductEntityIdentifierScopeRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductEntityIdentifierScopeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResProductEntityIdentifierScopeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductEntityIdentifierScope.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductEntityIdentifierScope.cdm.json/EcoResProductEntityIdentifierScope</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductEntityIdentifierScope.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

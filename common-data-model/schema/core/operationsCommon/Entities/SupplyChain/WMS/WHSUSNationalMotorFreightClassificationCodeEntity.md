---
title: WHSUSNationalMotorFreightClassificationCodeEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# US national motor freight classification codes in WMS(WHSUSNationalMotorFreightClassificationCodeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSUSNationalMotorFreightClassificationCodeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>US national motor freight classification codes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DefaultBillOfLadingHandlingType](#DefaultBillOfLadingHandlingType)||<a href="WHSUSNationalMotorFreightClassificationCodeEntity.md" target="_blank">WMS/WHSUSNationalMotorFreightClassificationCodeEntity</a>|
|[LTLClassCode](#LTLClassCode)||<a href="WHSUSNationalMotorFreightClassificationCodeEntity.md" target="_blank">WMS/WHSUSNationalMotorFreightClassificationCodeEntity</a>|
|[NMFCName](#NMFCName)||<a href="WHSUSNationalMotorFreightClassificationCodeEntity.md" target="_blank">WMS/WHSUSNationalMotorFreightClassificationCodeEntity</a>|
|[NMFCCode](#NMFCCode)||<a href="WHSUSNationalMotorFreightClassificationCodeEntity.md" target="_blank">WMS/WHSUSNationalMotorFreightClassificationCodeEntity</a>|
|[Relationship_LessThanTruckloadClassRelationshipId](#Relationship_LessThanTruckloadClassRelationshipId)||<a href="WHSUSNationalMotorFreightClassificationCodeEntity.md" target="_blank">WMS/WHSUSNationalMotorFreightClassificationCodeEntity</a>|
|[BackingTable_WHSNMFCRelationshipId](#BackingTable_WHSNMFCRelationshipId)||<a href="WHSUSNationalMotorFreightClassificationCodeEntity.md" target="_blank">WMS/WHSUSNationalMotorFreightClassificationCodeEntity</a>|

### <a href=#DefaultBillOfLadingHandlingType name="DefaultBillOfLadingHandlingType">DefaultBillOfLadingHandlingType</a>

First included in: WMS/WHSUSNationalMotorFreightClassificationCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBillOfLadingHandlingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LTLClassCode name="LTLClassCode">LTLClassCode</a>

First included in: WMS/WHSUSNationalMotorFreightClassificationCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LTLClassCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NMFCName name="NMFCName">NMFCName</a>

First included in: WMS/WHSUSNationalMotorFreightClassificationCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NMFCName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NMFCCode name="NMFCCode">NMFCCode</a>

First included in: WMS/WHSUSNationalMotorFreightClassificationCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NMFCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LessThanTruckloadClassRelationshipId name="Relationship_LessThanTruckloadClassRelationshipId">Relationship_LessThanTruckloadClassRelationshipId</a>

First included in: WMS/WHSUSNationalMotorFreightClassificationCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LessThanTruckloadClassRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSNMFCRelationshipId name="BackingTable_WHSNMFCRelationshipId">BackingTable_WHSNMFCRelationshipId</a>

First included in: WMS/WHSUSNationalMotorFreightClassificationCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSNMFCRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSNMFC.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSNMFC.cdm.json/WHSNMFC</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSNMFC.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

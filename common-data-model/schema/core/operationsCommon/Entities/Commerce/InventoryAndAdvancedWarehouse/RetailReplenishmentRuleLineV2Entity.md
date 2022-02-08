---
title: RetailReplenishmentRuleLineV2Entity in InventoryAndAdvancedWarehouse - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Replenishment rule lines v2 in InventoryAndAdvancedWarehouse(RetailReplenishmentRuleLineV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Replenishment rule lines v2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ReplenishmentRule](#ReplenishmentRule)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[Type](#Type)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[RelationId](#RelationId)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[ReplenishmentHierarchyTypeName](#ReplenishmentHierarchyTypeName)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[ReplenishmentOrganizationPartyNumber](#ReplenishmentOrganizationPartyNumber)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[ReplenishmentHierarchyValidFrom](#ReplenishmentHierarchyValidFrom)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[ReplenishmentHierarchyValidTo](#ReplenishmentHierarchyValidTo)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[RetailChannelId](#RetailChannelId)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[Description](#Description)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[Weight](#Weight)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[Percent](#Percent)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[DefaultWeight](#DefaultWeight)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[DefaultPercent](#DefaultPercent)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[Relationship_OperatingUnitRelationshipId](#Relationship_OperatingUnitRelationshipId)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[Relationship_DepartmentRelationshipId](#Relationship_DepartmentRelationshipId)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[Relationship_OrganizationHierarchyTypeRelationshipId](#Relationship_OrganizationHierarchyTypeRelationshipId)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[Relationship_ChannelRelationshipId](#Relationship_ChannelRelationshipId)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[Relationship_ReplenishmentRuleRelationshipId](#Relationship_ReplenishmentRuleRelationshipId)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[BackingTable_RetailReplenishmentRuleLinesRelationshipId](#BackingTable_RetailReplenishmentRuleLinesRelationshipId)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailReplenishmentRuleLineV2Entity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity</a>|

### <a href=#ReplenishmentRule name="ReplenishmentRule">ReplenishmentRule</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RelationId name="RelationId">RelationId</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentHierarchyTypeName name="ReplenishmentHierarchyTypeName">ReplenishmentHierarchyTypeName</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentHierarchyTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentOrganizationPartyNumber name="ReplenishmentOrganizationPartyNumber">ReplenishmentOrganizationPartyNumber</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOrganizationPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentHierarchyValidFrom name="ReplenishmentHierarchyValidFrom">ReplenishmentHierarchyValidFrom</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentHierarchyValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentHierarchyValidTo name="ReplenishmentHierarchyValidTo">ReplenishmentHierarchyValidTo</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentHierarchyValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelId name="RetailChannelId">RetailChannelId</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

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

### <a href=#Weight name="Weight">Weight</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Weight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Percent name="Percent">Percent</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultWeight name="DefaultWeight">DefaultWeight</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPercent name="DefaultPercent">DefaultPercent</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OperatingUnitRelationshipId name="Relationship_OperatingUnitRelationshipId">Relationship_OperatingUnitRelationshipId</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OperatingUnitRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DepartmentRelationshipId name="Relationship_DepartmentRelationshipId">Relationship_DepartmentRelationshipId</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DepartmentRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OrganizationHierarchyTypeRelationshipId name="Relationship_OrganizationHierarchyTypeRelationshipId">Relationship_OrganizationHierarchyTypeRelationshipId</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OrganizationHierarchyTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ChannelRelationshipId name="Relationship_ChannelRelationshipId">Relationship_ChannelRelationshipId</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ChannelRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReplenishmentRuleRelationshipId name="Relationship_ReplenishmentRuleRelationshipId">Relationship_ReplenishmentRuleRelationshipId</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReplenishmentRuleRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailReplenishmentRuleLinesRelationshipId name="BackingTable_RetailReplenishmentRuleLinesRelationshipId">BackingTable_RetailReplenishmentRuleLinesRelationshipId</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailReplenishmentRuleLinesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/InventoryAndAdvancedWarehouse/Main/RetailReplenishmentRuleLines.md" target="_blank">/core/operationsCommon/Tables/Commerce/InventoryAndAdvancedWarehouse/Main/RetailReplenishmentRuleLines.cdm.json/RetailReplenishmentRuleLines</a></td><td><a href="../../../Tables/Commerce/InventoryAndAdvancedWarehouse/Main/RetailReplenishmentRuleLines.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndAdvancedWarehouse/RetailReplenishmentRuleLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

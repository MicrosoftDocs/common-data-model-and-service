---
title: InventInventoryOwnershipChangeJournalNameEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Inventory ownership change journal names in InventoryAndWarehouseManagement(InventInventoryOwnershipChangeJournalNameEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory ownership change journal names</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[JournalNameId](#JournalNameId)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[DefaultJournalDescription](#DefaultJournalDescription)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[WillPostingDeleteLinesByDefault](#WillPostingDeleteLinesByDefault)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[DefaultPrivateUserGroupId](#DefaultPrivateUserGroupId)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[DefaultVoucherNumberAllocationRule](#DefaultVoucherNumberAllocationRule)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[DefaultVoucherNumberSelectionRule](#DefaultVoucherNumberSelectionRule)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[DefaultVoucherNumberSequenceRecId](#DefaultVoucherNumberSequenceRecId)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[DefaultVoucherNumberSequenceCode](#DefaultVoucherNumberSequenceCode)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[NumberSequenceTable_NumberSequenceScope](#NumberSequenceTable_NumberSequenceScope)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[DefaultVoucherNumberSequenceDataArea](#DefaultVoucherNumberSequenceDataArea)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[Relationship_DefaultVoucherNumberSequenceRelationshipId](#Relationship_DefaultVoucherNumberSequenceRelationshipId)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[Relationship_DefaultPrivateUserGroupRelationshipId](#Relationship_DefaultPrivateUserGroupRelationshipId)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[BackingTable_InventJournalNameRelationshipId](#BackingTable_InventJournalNameRelationshipId)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventInventoryOwnershipChangeJournalNameEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity</a>|

### <a href=#JournalNameId name="JournalNameId">JournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultJournalDescription name="DefaultJournalDescription">DefaultJournalDescription</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultJournalDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPostingDeleteLinesByDefault name="WillPostingDeleteLinesByDefault">WillPostingDeleteLinesByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPostingDeleteLinesByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPrivateUserGroupId name="DefaultPrivateUserGroupId">DefaultPrivateUserGroupId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPrivateUserGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVoucherNumberAllocationRule name="DefaultVoucherNumberAllocationRule">DefaultVoucherNumberAllocationRule</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVoucherNumberAllocationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVoucherNumberSelectionRule name="DefaultVoucherNumberSelectionRule">DefaultVoucherNumberSelectionRule</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVoucherNumberSelectionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVoucherNumberSequenceRecId name="DefaultVoucherNumberSequenceRecId">DefaultVoucherNumberSequenceRecId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVoucherNumberSequenceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVoucherNumberSequenceCode name="DefaultVoucherNumberSequenceCode">DefaultVoucherNumberSequenceCode</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVoucherNumberSequenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceTable_NumberSequenceScope name="NumberSequenceTable_NumberSequenceScope">NumberSequenceTable_NumberSequenceScope</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceTable_NumberSequenceScope attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVoucherNumberSequenceDataArea name="DefaultVoucherNumberSequenceDataArea">DefaultVoucherNumberSequenceDataArea</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVoucherNumberSequenceDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultVoucherNumberSequenceRelationshipId name="Relationship_DefaultVoucherNumberSequenceRelationshipId">Relationship_DefaultVoucherNumberSequenceRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultVoucherNumberSequenceRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultPrivateUserGroupRelationshipId name="Relationship_DefaultPrivateUserGroupRelationshipId">Relationship_DefaultPrivateUserGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultPrivateUserGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventJournalNameRelationshipId name="BackingTable_InventJournalNameRelationshipId">BackingTable_InventJournalNameRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventJournalName.cdm.json/InventJournalName</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryOwnershipChangeJournalNameEntity (this entity)  

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

---
title: RetailItemLabelSetupEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Product label setup in BrickAndMortarStore(RetailItemLabelSetupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailItemLabelSetupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product label setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ItemId](#ItemId)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[LabelType](#LabelType)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[OMHierarchyType](#OMHierarchyType)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[OMInternalOrganization](#OMInternalOrganization)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[ReportName](#ReportName)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[Text1](#Text1)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[Text1IsItemDescription](#Text1IsItemDescription)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[Text2](#Text2)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[OrganizationHierarchyTypeName](#OrganizationHierarchyTypeName)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[OrganizationPartyNumber](#OrganizationPartyNumber)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[Relationship_RetailInventItemLabelReportSetupEntityRelationshipId](#Relationship_RetailInventItemLabelReportSetupEntityRelationshipId)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[BackingTable_RetailInventItemLabelSetupRelationshipId](#BackingTable_RetailInventItemLabelSetupRelationshipId)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailItemLabelSetupEntity.md" target="_blank">BrickAndMortarStore/RetailItemLabelSetupEntity</a>|

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LabelType name="LabelType">LabelType</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMHierarchyType name="OMHierarchyType">OMHierarchyType</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMHierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMInternalOrganization name="OMInternalOrganization">OMInternalOrganization</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMInternalOrganization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportName name="ReportName">ReportName</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Text1 name="Text1">Text1</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Text1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Text1IsItemDescription name="Text1IsItemDescription">Text1IsItemDescription</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Text1IsItemDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Text2 name="Text2">Text2</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Text2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationHierarchyTypeName name="OrganizationHierarchyTypeName">OrganizationHierarchyTypeName</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationHierarchyTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationPartyNumber name="OrganizationPartyNumber">OrganizationPartyNumber</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInventItemLabelReportSetupEntityRelationshipId name="Relationship_RetailInventItemLabelReportSetupEntityRelationshipId">Relationship_RetailInventItemLabelReportSetupEntityRelationshipId</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInventItemLabelReportSetupEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailInventItemLabelSetupRelationshipId name="BackingTable_RetailInventItemLabelSetupRelationshipId">BackingTable_RetailInventItemLabelSetupRelationshipId</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailInventItemLabelSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/InventoryAndAdvancedWarehouse/Group/RetailInventItemLabelSetup.md" target="_blank">/core/operationsCommon/Tables/Commerce/InventoryAndAdvancedWarehouse/Group/RetailInventItemLabelSetup.cdm.json/RetailInventItemLabelSetup</a></td><td><a href="../../../../Tables/Commerce/InventoryAndAdvancedWarehouse/Group/RetailInventItemLabelSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: BrickAndMortarStore/RetailItemLabelSetupEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

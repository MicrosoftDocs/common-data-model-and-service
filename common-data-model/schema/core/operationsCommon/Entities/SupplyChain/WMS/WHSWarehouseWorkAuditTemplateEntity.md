---
title: WHSWarehouseWorkAuditTemplateEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Warehouse work audit templates in WMS(WHSWarehouseWorkAuditTemplateEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseWorkAuditTemplateEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse work audit templates</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AuditTriggeringEvent](#AuditTriggeringEvent)||<a href="WHSWarehouseWorkAuditTemplateEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateEntity</a>|
|[AuditTriggeringReferenceWarehouseWorkFieldName](#AuditTriggeringReferenceWarehouseWorkFieldName)||<a href="WHSWarehouseWorkAuditTemplateEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateEntity</a>|
|[AuditTriggeringFieldId](#AuditTriggeringFieldId)||<a href="WHSWarehouseWorkAuditTemplateEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateEntity</a>|
|[MobileDeviceDisplayLabel](#MobileDeviceDisplayLabel)||<a href="WHSWarehouseWorkAuditTemplateEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateEntity</a>|
|[TemplateDescription](#TemplateDescription)||<a href="WHSWarehouseWorkAuditTemplateEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateEntity</a>|
|[StatusChangeTriggeringValue](#StatusChangeTriggeringValue)||<a href="WHSWarehouseWorkAuditTemplateEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateEntity</a>|
|[TemplateId](#TemplateId)||<a href="WHSWarehouseWorkAuditTemplateEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateEntity</a>|
|[BackingTable_WHSWorkAuditTemplateTableRelationshipId](#BackingTable_WHSWorkAuditTemplateTableRelationshipId)||<a href="WHSWarehouseWorkAuditTemplateEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseWorkAuditTemplateEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateEntity</a>|

### <a href=#AuditTriggeringEvent name="AuditTriggeringEvent">AuditTriggeringEvent</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuditTriggeringEvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuditTriggeringReferenceWarehouseWorkFieldName name="AuditTriggeringReferenceWarehouseWorkFieldName">AuditTriggeringReferenceWarehouseWorkFieldName</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuditTriggeringReferenceWarehouseWorkFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuditTriggeringFieldId name="AuditTriggeringFieldId">AuditTriggeringFieldId</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuditTriggeringFieldId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MobileDeviceDisplayLabel name="MobileDeviceDisplayLabel">MobileDeviceDisplayLabel</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MobileDeviceDisplayLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateDescription name="TemplateDescription">TemplateDescription</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatusChangeTriggeringValue name="StatusChangeTriggeringValue">StatusChangeTriggeringValue</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatusChangeTriggeringValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateId name="TemplateId">TemplateId</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSWorkAuditTemplateTableRelationshipId name="BackingTable_WHSWorkAuditTemplateTableRelationshipId">BackingTable_WHSWorkAuditTemplateTableRelationshipId</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSWorkAuditTemplateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkAuditTemplateTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSWorkAuditTemplateTable.cdm.json/WHSWorkAuditTemplateTable</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkAuditTemplateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateEntity (this entity)  

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

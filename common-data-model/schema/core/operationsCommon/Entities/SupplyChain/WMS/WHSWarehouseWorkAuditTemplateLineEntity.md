---
title: WHSWarehouseWorkAuditTemplateLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Warehouse work audit template lines

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseWorkAuditTemplateLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse work audit template lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LineFunctionType](#LineFunctionType)||<a href="WHSWarehouseWorkAuditTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateLineEntity</a>|
|[MobileDeviceMenuLabel](#MobileDeviceMenuLabel)||<a href="WHSWarehouseWorkAuditTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateLineEntity</a>|
|[LineSequenceNumber](#LineSequenceNumber)||<a href="WHSWarehouseWorkAuditTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateLineEntity</a>|
|[LinePrintFunctionPrintSettings](#LinePrintFunctionPrintSettings)||<a href="WHSWarehouseWorkAuditTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateLineEntity</a>|
|[LineCustomMethod](#LineCustomMethod)||<a href="WHSWarehouseWorkAuditTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateLineEntity</a>|
|[LineEventFunctionEvent](#LineEventFunctionEvent)||<a href="WHSWarehouseWorkAuditTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateLineEntity</a>|
|[WarehouseWorkAuditTemplateId](#WarehouseWorkAuditTemplateId)||<a href="WHSWarehouseWorkAuditTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateLineEntity</a>|
|[LineReportFunctionReportName](#LineReportFunctionReportName)||<a href="WHSWarehouseWorkAuditTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateLineEntity</a>|
|[Relationship_WarehouseWorkAuditTemplateRelationshipId](#Relationship_WarehouseWorkAuditTemplateRelationshipId)||<a href="WHSWarehouseWorkAuditTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateLineEntity</a>|
|[BackingTable_WHSWorkAuditTemplateLineRelationshipId](#BackingTable_WHSWorkAuditTemplateLineRelationshipId)||<a href="WHSWarehouseWorkAuditTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseWorkAuditTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkAuditTemplateLineEntity</a>|

### <a href=#LineFunctionType name="LineFunctionType">LineFunctionType</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineFunctionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MobileDeviceMenuLabel name="MobileDeviceMenuLabel">MobileDeviceMenuLabel</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MobileDeviceMenuLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineSequenceNumber name="LineSequenceNumber">LineSequenceNumber</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LinePrintFunctionPrintSettings name="LinePrintFunctionPrintSettings">LinePrintFunctionPrintSettings</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinePrintFunctionPrintSettings attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineCustomMethod name="LineCustomMethod">LineCustomMethod</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineCustomMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineEventFunctionEvent name="LineEventFunctionEvent">LineEventFunctionEvent</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineEventFunctionEvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkAuditTemplateId name="WarehouseWorkAuditTemplateId">WarehouseWorkAuditTemplateId</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkAuditTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineReportFunctionReportName name="LineReportFunctionReportName">LineReportFunctionReportName</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineReportFunctionReportName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseWorkAuditTemplateRelationshipId name="Relationship_WarehouseWorkAuditTemplateRelationshipId">Relationship_WarehouseWorkAuditTemplateRelationshipId</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseWorkAuditTemplateRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSWorkAuditTemplateLineRelationshipId name="BackingTable_WHSWorkAuditTemplateLineRelationshipId">BackingTable_WHSWorkAuditTemplateLineRelationshipId</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSWorkAuditTemplateLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkAuditTemplateLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSWorkAuditTemplateLine.cdm.json/WHSWorkAuditTemplateLine</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkAuditTemplateLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseWorkAuditTemplateLineEntity (this entity)  

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

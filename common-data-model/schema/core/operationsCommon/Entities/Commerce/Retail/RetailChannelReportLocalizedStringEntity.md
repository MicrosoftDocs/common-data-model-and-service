---
title: RetailChannelReportLocalizedStringEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailChannelReportLocalizedStringEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Retail/RetailChannelReportLocalizedStringEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LocaleCode](#LocaleCode)||<a href="RetailChannelReportLocalizedStringEntity.md" target="_blank">Retail/RetailChannelReportLocalizedStringEntity</a>|
|[StringId](#StringId)||<a href="RetailChannelReportLocalizedStringEntity.md" target="_blank">Retail/RetailChannelReportLocalizedStringEntity</a>|
|[StringValue](#StringValue)||<a href="RetailChannelReportLocalizedStringEntity.md" target="_blank">Retail/RetailChannelReportLocalizedStringEntity</a>|
|[Version](#Version)||<a href="RetailChannelReportLocalizedStringEntity.md" target="_blank">Retail/RetailChannelReportLocalizedStringEntity</a>|
|[BackingTable_RetailReportLocalizedStringRelationshipId](#BackingTable_RetailReportLocalizedStringRelationshipId)||<a href="RetailChannelReportLocalizedStringEntity.md" target="_blank">Retail/RetailChannelReportLocalizedStringEntity</a>|

### <a href=#LocaleCode name="LocaleCode">LocaleCode</a>

First included in: Retail/RetailChannelReportLocalizedStringEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocaleCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StringId name="StringId">StringId</a>

First included in: Retail/RetailChannelReportLocalizedStringEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StringId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StringValue name="StringValue">StringValue</a>

First included in: Retail/RetailChannelReportLocalizedStringEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StringValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Version name="Version">Version</a>

First included in: Retail/RetailChannelReportLocalizedStringEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Version attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailReportLocalizedStringRelationshipId name="BackingTable_RetailReportLocalizedStringRelationshipId">BackingTable_RetailReportLocalizedStringRelationshipId</a>

First included in: Retail/RetailChannelReportLocalizedStringEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailReportLocalizedStringRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Miscellaneous/RetailReportLocalizedString.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailReportLocalizedString.cdm.json/RetailReportLocalizedString</a></td><td><a href="../../../Tables/Commerce/Retail/Miscellaneous/RetailReportLocalizedString.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

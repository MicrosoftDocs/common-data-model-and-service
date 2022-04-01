---
title: DocumentRoutingPrinterAppAssociation in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# DocumentRoutingPrinterAppAssociation in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/DocumentRoutingPrinterAppAssociation.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DocumentRoutingPrinterAppAssociation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DocumentRoutingPrinterAppAssociation.md" target="_blank">Miscellaneous/DocumentRoutingPrinterAppAssociation</a>|
|[ClientApp](#ClientApp)||<a href="DocumentRoutingPrinterAppAssociation.md" target="_blank">Miscellaneous/DocumentRoutingPrinterAppAssociation</a>|
|[Printer](#Printer)||<a href="DocumentRoutingPrinterAppAssociation.md" target="_blank">Miscellaneous/DocumentRoutingPrinterAppAssociation</a>|
|[Relationship_SysCorpNetPrintersFKRelationshipId](#Relationship_SysCorpNetPrintersFKRelationshipId)||<a href="DocumentRoutingPrinterAppAssociation.md" target="_blank">Miscellaneous/DocumentRoutingPrinterAppAssociation</a>|
|[Relationship_ClientAppFKRelationshipId](#Relationship_ClientAppFKRelationshipId)||<a href="DocumentRoutingPrinterAppAssociation.md" target="_blank">Miscellaneous/DocumentRoutingPrinterAppAssociation</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/DocumentRoutingPrinterAppAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DocumentRoutingPrinterAppAssociation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ClientApp name="ClientApp">ClientApp</a>

First included in: Miscellaneous/DocumentRoutingPrinterAppAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClientApp attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Printer name="Printer">Printer</a>

First included in: Miscellaneous/DocumentRoutingPrinterAppAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_SysCorpNetPrintersFKRelationshipId name="Relationship_SysCorpNetPrintersFKRelationshipId">Relationship_SysCorpNetPrintersFKRelationshipId</a>

First included in: Miscellaneous/DocumentRoutingPrinterAppAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysCorpNetPrintersFKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SysCorpNetPrinters.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/SysCorpNetPrinters.cdm.json/SysCorpNetPrinters</a></td><td><a href="SysCorpNetPrinters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ClientAppFKRelationshipId name="Relationship_ClientAppFKRelationshipId">Relationship_ClientAppFKRelationshipId</a>

First included in: Miscellaneous/DocumentRoutingPrinterAppAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ClientAppFKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="DocumentRoutingClientApp.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/DocumentRoutingClientApp.cdm.json/DocumentRoutingClientApp</a></td><td><a href="DocumentRoutingClientApp.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

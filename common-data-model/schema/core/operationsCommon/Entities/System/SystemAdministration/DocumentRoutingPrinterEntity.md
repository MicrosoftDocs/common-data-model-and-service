---
title: DocumentRoutingPrinterEntity in SystemAdministration - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# DocumentRoutingPrinterEntity in SystemAdministration

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/SystemAdministration/DocumentRoutingPrinterEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ClientApp](#ClientApp)||<a href="DocumentRoutingPrinterEntity.md" target="_blank">SystemAdministration/DocumentRoutingPrinterEntity</a>|
|[Printer](#Printer)||<a href="DocumentRoutingPrinterEntity.md" target="_blank">SystemAdministration/DocumentRoutingPrinterEntity</a>|
|[PrinterName](#PrinterName)||<a href="DocumentRoutingPrinterEntity.md" target="_blank">SystemAdministration/DocumentRoutingPrinterEntity</a>|
|[PrinterDescription](#PrinterDescription)||<a href="DocumentRoutingPrinterEntity.md" target="_blank">SystemAdministration/DocumentRoutingPrinterEntity</a>|
|[PrinterPath](#PrinterPath)||<a href="DocumentRoutingPrinterEntity.md" target="_blank">SystemAdministration/DocumentRoutingPrinterEntity</a>|
|[PrinterIsActive](#PrinterIsActive)||<a href="DocumentRoutingPrinterEntity.md" target="_blank">SystemAdministration/DocumentRoutingPrinterEntity</a>|
|[PrinterId](#PrinterId)||<a href="DocumentRoutingPrinterEntity.md" target="_blank">SystemAdministration/DocumentRoutingPrinterEntity</a>|
|[PrinterCompanyId](#PrinterCompanyId)||<a href="DocumentRoutingPrinterEntity.md" target="_blank">SystemAdministration/DocumentRoutingPrinterEntity</a>|
|[ClientApplicationId](#ClientApplicationId)||<a href="DocumentRoutingPrinterEntity.md" target="_blank">SystemAdministration/DocumentRoutingPrinterEntity</a>|
|[ClientApplicationDescription](#ClientApplicationDescription)||<a href="DocumentRoutingPrinterEntity.md" target="_blank">SystemAdministration/DocumentRoutingPrinterEntity</a>|
|[BackingTable_DocumentRoutingPrinterAppAssociationRelationshipId](#BackingTable_DocumentRoutingPrinterAppAssociationRelationshipId)||<a href="DocumentRoutingPrinterEntity.md" target="_blank">SystemAdministration/DocumentRoutingPrinterEntity</a>|

### <a href=#ClientApp name="ClientApp">ClientApp</a>

First included in: SystemAdministration/DocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClientApp attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer name="Printer">Printer</a>

First included in: SystemAdministration/DocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrinterName name="PrinterName">PrinterName</a>

First included in: SystemAdministration/DocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrinterName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrinterDescription name="PrinterDescription">PrinterDescription</a>

First included in: SystemAdministration/DocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrinterDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrinterPath name="PrinterPath">PrinterPath</a>

First included in: SystemAdministration/DocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrinterPath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrinterIsActive name="PrinterIsActive">PrinterIsActive</a>

First included in: SystemAdministration/DocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrinterIsActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrinterId name="PrinterId">PrinterId</a>

First included in: SystemAdministration/DocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrinterId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrinterCompanyId name="PrinterCompanyId">PrinterCompanyId</a>

First included in: SystemAdministration/DocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrinterCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClientApplicationId name="ClientApplicationId">ClientApplicationId</a>

First included in: SystemAdministration/DocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClientApplicationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClientApplicationDescription name="ClientApplicationDescription">ClientApplicationDescription</a>

First included in: SystemAdministration/DocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClientApplicationDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DocumentRoutingPrinterAppAssociationRelationshipId name="BackingTable_DocumentRoutingPrinterAppAssociationRelationshipId">BackingTable_DocumentRoutingPrinterAppAssociationRelationshipId</a>

First included in: SystemAdministration/DocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DocumentRoutingPrinterAppAssociationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/System/SystemAdministration/Miscellaneous/DocumentRoutingPrinterAppAssociation.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/DocumentRoutingPrinterAppAssociation.cdm.json/DocumentRoutingPrinterAppAssociation</a></td><td><a href="../../../Tables/System/SystemAdministration/Miscellaneous/DocumentRoutingPrinterAppAssociation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

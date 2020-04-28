---
title: CatVendorCatalogMaintenanceRequest - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Dependent

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorCatalogMaintenanceRequest.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CatVendorCatalogMaintenanceRequest/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dependent</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|
|[FileName](#FileName)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|
|[FileSize](#FileSize)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|
|[LastImportStatus](#LastImportStatus)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|
|[PriceValidFromDate](#PriceValidFromDate)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|
|[PriceValidToDate](#PriceValidToDate)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|
|[UploadType](#UploadType)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|
|[VendorCatalog](#VendorCatalog)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|
|[WorkflowStatus](#WorkflowStatus)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|
|[UploadDateTime](#UploadDateTime)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|
|[CategoryHierarchyType](#CategoryHierarchyType)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|
|[Relationship_CatVendorCatalogRelationshipId](#Relationship_CatVendorCatalogRelationshipId)||<a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">Main/CatVendorCatalogMaintenanceRequest</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CatVendorCatalogMaintenanceRequest/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FileName name="FileName">FileName</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FileSize name="FileSize">FileSize</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileSize attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LastImportStatus name="LastImportStatus">LastImportStatus</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastImportStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PriceValidFromDate name="PriceValidFromDate">PriceValidFromDate</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price valid from</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceValidFromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Price valid from</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#PriceValidToDate name="PriceValidToDate">PriceValidToDate</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price valid to</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceValidToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Price valid to</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#UploadType name="UploadType">UploadType</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UploadType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendorCatalog name="VendorCatalog">VendorCatalog</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorCatalog attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkflowStatus name="WorkflowStatus">WorkflowStatus</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Workflow status</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Workflow status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UploadDateTime name="UploadDateTime">UploadDateTime</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Upload date</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UploadDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Upload date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#CategoryHierarchyType name="CategoryHierarchyType">CategoryHierarchyType</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchyType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_CatVendorCatalogRelationshipId name="Relationship_CatVendorCatalogRelationshipId">Relationship_CatVendorCatalogRelationshipId</a>

First included in: Main/CatVendorCatalogMaintenanceRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatVendorCatalogRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CatVendorCatalog.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorCatalog.cdm.json/CatVendorCatalog</a></td><td><a href="CatVendorCatalog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

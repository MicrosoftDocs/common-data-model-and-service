---
title: SysDocuBrandDetails - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# SysDocuBrandDetails

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Group/SysDocuBrandDetails.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysDocuBrandDetails/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Address](#Address)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[AddressCollapse](#AddressCollapse)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[AddressDelimiter](#AddressDelimiter)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[BrandId](#BrandId)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[BrandName](#BrandName)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Email](#Email)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Image1](#Image1)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Image1Name](#Image1Name)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Image2](#Image2)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Image2Name](#Image2Name)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Image3](#Image3)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Image3Name](#Image3Name)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[LogisticsLocationRecId](#LogisticsLocationRecId)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[NotesLine1](#NotesLine1)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[NotesLine2](#NotesLine2)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[NotesLine3](#NotesLine3)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Phone](#Phone)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[PhoneLocal](#PhoneLocal)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[PrimaryColor](#PrimaryColor)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[SecondaryColor](#SecondaryColor)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[ReportName](#ReportName)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[DesignName](#DesignName)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[TeleFax](#TeleFax)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[URL](#URL)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[DataAreaId](#DataAreaId)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Relationship_SysDocuBrandDetailsRelationshipId](#Relationship_SysDocuBrandDetailsRelationshipId)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Relationship_SysDocuBrandImage1RelationshipId](#Relationship_SysDocuBrandImage1RelationshipId)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Relationship_SysDocuBrandImage2RelationshipId](#Relationship_SysDocuBrandImage2RelationshipId)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Relationship_SysDocuBrandImage3RelationshipId](#Relationship_SysDocuBrandImage3RelationshipId)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Relationship_LogisticsLocationRelationshipId](#Relationship_LogisticsLocationRelationshipId)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="SysDocuBrandDetails.md" target="_blank">Group/SysDocuBrandDetails</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysDocuBrandDetails/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Address name="Address">Address</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Address attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCollapse name="AddressCollapse">AddressCollapse</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCollapse attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AddressDelimiter name="AddressDelimiter">AddressDelimiter</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDelimiter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrandId name="BrandId">BrandId</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrandId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrandName name="BrandName">BrandName</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrandName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Image1 name="Image1">Image1</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Image1 attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#Image1Name name="Image1Name">Image1Name</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Image1Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Image2 name="Image2">Image2</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Image2 attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#Image2Name name="Image2Name">Image2Name</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Image2Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Image3 name="Image3">Image3</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Image3 attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#Image3Name name="Image3Name">Image3Name</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Image3Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsLocationRecId name="LogisticsLocationRecId">LogisticsLocationRecId</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsLocationRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NotesLine1 name="NotesLine1">NotesLine1</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotesLine1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NotesLine2 name="NotesLine2">NotesLine2</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotesLine2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NotesLine3 name="NotesLine3">NotesLine3</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotesLine3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Phone name="Phone">Phone</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Phone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneLocal name="PhoneLocal">PhoneLocal</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneLocal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryColor name="PrimaryColor">PrimaryColor</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryColor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryColor name="SecondaryColor">SecondaryColor</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryColor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportName name="ReportName">ReportName</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DesignName name="DesignName">DesignName</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DesignName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TeleFax name="TeleFax">TeleFax</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TeleFax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#URL name="URL">URL</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the URL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysDocuBrandDetailsRelationshipId name="Relationship_SysDocuBrandDetailsRelationshipId">Relationship_SysDocuBrandDetailsRelationshipId</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysDocuBrandDetailsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SysDocuBrands.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/SysDocuBrands.cdm.json/SysDocuBrands</a></td><td><a href="SysDocuBrands.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysDocuBrandImage1RelationshipId name="Relationship_SysDocuBrandImage1RelationshipId">Relationship_SysDocuBrandImage1RelationshipId</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysDocuBrandImage1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/SysDocuBrandImages.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Reference/SysDocuBrandImages.cdm.json/SysDocuBrandImages</a></td><td><a href="../Reference/SysDocuBrandImages.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysDocuBrandImage2RelationshipId name="Relationship_SysDocuBrandImage2RelationshipId">Relationship_SysDocuBrandImage2RelationshipId</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysDocuBrandImage2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/SysDocuBrandImages.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Reference/SysDocuBrandImages.cdm.json/SysDocuBrandImages</a></td><td><a href="../Reference/SysDocuBrandImages.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysDocuBrandImage3RelationshipId name="Relationship_SysDocuBrandImage3RelationshipId">Relationship_SysDocuBrandImage3RelationshipId</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysDocuBrandImage3RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/SysDocuBrandImages.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Reference/SysDocuBrandImages.cdm.json/SysDocuBrandImages</a></td><td><a href="../Reference/SysDocuBrandImages.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsLocationRelationshipId name="Relationship_LogisticsLocationRelationshipId">Relationship_LogisticsLocationRelationshipId</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsLocation.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsLocation.cdm.json/LogisticsLocation</a></td><td><a href="../../../Common/GAB/Main/LogisticsLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/SysDocuBrandDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

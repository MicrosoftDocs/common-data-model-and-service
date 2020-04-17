---
title: HcmCourseTypeCertificateProfileEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# HcmCourseTypeCertificateProfileEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/HumanResources/HRM/HcmCourseTypeCertificateProfileEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[CertificateType](#CertificateType)||<a href="HcmCourseTypeCertificateProfileEntity.md" target="_blank">HRM/HcmCourseTypeCertificateProfileEntity</a>|
|[CertificateTypeId](#CertificateTypeId)||<a href="HcmCourseTypeCertificateProfileEntity.md" target="_blank">HRM/HcmCourseTypeCertificateProfileEntity</a>|
|[CourseType](#CourseType)||<a href="HcmCourseTypeCertificateProfileEntity.md" target="_blank">HRM/HcmCourseTypeCertificateProfileEntity</a>|
|[CourseTypeId](#CourseTypeId)||<a href="HcmCourseTypeCertificateProfileEntity.md" target="_blank">HRM/HcmCourseTypeCertificateProfileEntity</a>|
|[Relationship_CertificateTypeRelationshipId](#Relationship_CertificateTypeRelationshipId)||<a href="HcmCourseTypeCertificateProfileEntity.md" target="_blank">HRM/HcmCourseTypeCertificateProfileEntity</a>|
|[Relationship_CourseTypeRelationshipId](#Relationship_CourseTypeRelationshipId)||<a href="HcmCourseTypeCertificateProfileEntity.md" target="_blank">HRM/HcmCourseTypeCertificateProfileEntity</a>|

### <a href=#CertificateType name="CertificateType">CertificateType</a>

First included in: HRM/HcmCourseTypeCertificateProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CertificateTypeId name="CertificateTypeId">CertificateTypeId</a>

First included in: HRM/HcmCourseTypeCertificateProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseType name="CourseType">CourseType</a>

First included in: HRM/HcmCourseTypeCertificateProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseTypeId name="CourseTypeId">CourseTypeId</a>

First included in: HRM/HcmCourseTypeCertificateProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CertificateTypeRelationshipId name="Relationship_CertificateTypeRelationshipId">Relationship_CertificateTypeRelationshipId</a>

First included in: HRM/HcmCourseTypeCertificateProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CertificateTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CourseTypeRelationshipId name="Relationship_CourseTypeRelationshipId">Relationship_CourseTypeRelationshipId</a>

First included in: HRM/HcmCourseTypeCertificateProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CourseTypeRelationshipId attribute are listed below.</summary>

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

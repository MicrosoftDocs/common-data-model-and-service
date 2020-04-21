---
title: VendRequestProfile - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# VendRequestProfile

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendRequestProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendRequestProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[AcceptAgreementText](#AcceptAgreementText)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[AgreementText](#AgreementText)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[CheckDisallowed](#CheckDisallowed)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[CheckEmbargoCountries](#CheckEmbargoCountries)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[CheckParties](#CheckParties)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[Description](#Description)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[IsDefault](#IsDefault)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[MetadataGroup](#MetadataGroup)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[Name](#Name)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[ProfileType](#ProfileType)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[RequireCategory](#RequireCategory)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[ShowAcceptAgreement](#ShowAcceptAgreement)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[ShowAgreementText](#ShowAgreementText)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[ShowBusinessInformation](#ShowBusinessInformation)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[SubmittedText](#SubmittedText)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|
|[Relationship_VendFieldMetadataGroupRelationshipId](#Relationship_VendFieldMetadataGroupRelationshipId)||<a href="VendRequestProfile.md" target="_blank">Transaction/VendRequestProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendRequestProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcceptAgreementText name="AcceptAgreementText">AcceptAgreementText</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptAgreementText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementText name="AgreementText">AgreementText</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckDisallowed name="CheckDisallowed">CheckDisallowed</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckDisallowed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckEmbargoCountries name="CheckEmbargoCountries">CheckEmbargoCountries</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckEmbargoCountries attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckParties name="CheckParties">CheckParties</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckParties attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefault name="IsDefault">IsDefault</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefault attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MetadataGroup name="MetadataGroup">MetadataGroup</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MetadataGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileType name="ProfileType">ProfileType</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RequireCategory name="RequireCategory">RequireCategory</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowAcceptAgreement name="ShowAcceptAgreement">ShowAcceptAgreement</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowAcceptAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowAgreementText name="ShowAgreementText">ShowAgreementText</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowAgreementText attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowBusinessInformation name="ShowBusinessInformation">ShowBusinessInformation</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowBusinessInformation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SubmittedText name="SubmittedText">SubmittedText</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubmittedText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendFieldMetadataGroupRelationshipId name="Relationship_VendFieldMetadataGroupRelationshipId">Relationship_VendFieldMetadataGroupRelationshipId</a>

First included in: Transaction/VendRequestProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendFieldMetadataGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendFieldMetadataGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendFieldMetadataGroup.cdm.json/VendFieldMetadataGroup</a></td><td><a href="../../Vendor/Main/VendFieldMetadataGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

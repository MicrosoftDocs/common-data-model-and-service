---
title: AssetLVPTransferProposal_AU in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Asset LVP transfer proposal temp in Main(AssetLVPTransferProposal_AU)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetLVPTransferProposal_AU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetLVPTransferProposal_AU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Asset LVP transfer proposal temp</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[AltProfileId](#AltProfileId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[AssetId](#AssetId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[BookId](#BookId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[CheckMaxPercentRB_DE](#CheckMaxPercentRB_DE)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[CurrentOperationsTax](#CurrentOperationsTax)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[Depreciation](#Depreciation)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[DepreciationStartDate](#DepreciationStartDate)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[DerogatoryBook_FR](#DerogatoryBook_FR)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[DerogatoryModel_FR](#DerogatoryModel_FR)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[LastDepreciationDate](#LastDepreciationDate)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[LifeTime](#LifeTime)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[LifeTimeRest](#LifeTimeRest)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[Name](#Name)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[NetBookValue](#NetBookValue)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[PostingProfile](#PostingProfile)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[ProfileId](#ProfileId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[ServiceLife](#ServiceLife)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[SessionId](#SessionId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[Status](#Status)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[TransferToPool](#TransferToPool)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[UTCTimestamp](#UTCTimestamp)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[Relationship_AssetBookTableRelationshipId](#Relationship_AssetBookTableRelationshipId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[Relationship_AssetDepreciationProfile_AltProfileRelationshipId](#Relationship_AssetDepreciationProfile_AltProfileRelationshipId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[Relationship_AssetDepreciationProfile_ProfileRelationshipId](#Relationship_AssetDepreciationProfile_ProfileRelationshipId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[Relationship_AssetLedgerRelationshipId](#Relationship_AssetLedgerRelationshipId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[Relationship_AssetTableRelationshipId](#Relationship_AssetTableRelationshipId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetLVPTransferProposal_AU.md" target="_blank">Main/AssetLVPTransferProposal_AU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetLVPTransferProposal_AU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AltProfileId name="AltProfileId">AltProfileId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AltProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetId name="AssetId">AssetId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BookId name="BookId">BookId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckMaxPercentRB_DE name="CheckMaxPercentRB_DE">CheckMaxPercentRB_DE</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckMaxPercentRB_DE attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CurrentOperationsTax name="CurrentOperationsTax">CurrentOperationsTax</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentOperationsTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Depreciation name="Depreciation">Depreciation</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Depreciation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DepreciationStartDate name="DepreciationStartDate">DepreciationStartDate</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationStartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DerogatoryBook_FR name="DerogatoryBook_FR">DerogatoryBook_FR</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerogatoryBook_FR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DerogatoryModel_FR name="DerogatoryModel_FR">DerogatoryModel_FR</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerogatoryModel_FR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastDepreciationDate name="LastDepreciationDate">LastDepreciationDate</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastDepreciationDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#LifeTime name="LifeTime">LifeTime</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LifeTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LifeTimeRest name="LifeTimeRest">LifeTimeRest</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LifeTimeRest attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetBookValue name="NetBookValue">NetBookValue</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetBookValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileId name="ProfileId">ProfileId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceLife name="ServiceLife">ServiceLife</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLife attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TransferToPool name="TransferToPool">TransferToPool</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transfer to low value pool</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferToPool attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transfer to low value pool</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UTCTimestamp name="UTCTimestamp">UTCTimestamp</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCTimestamp attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

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

### <a href=#Relationship_AssetBookTableRelationshipId name="Relationship_AssetBookTableRelationshipId">Relationship_AssetBookTableRelationshipId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetBookTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetBookTable.cdm.json/AssetBookTable</a></td><td><a href="AssetBookTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetDepreciationProfile_AltProfileRelationshipId name="Relationship_AssetDepreciationProfile_AltProfileRelationshipId">Relationship_AssetDepreciationProfile_AltProfileRelationshipId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDepreciationProfile_AltProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetDepreciationProfile.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetDepreciationProfile.cdm.json/AssetDepreciationProfile</a></td><td><a href="../Parameter/AssetDepreciationProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetDepreciationProfile_ProfileRelationshipId name="Relationship_AssetDepreciationProfile_ProfileRelationshipId">Relationship_AssetDepreciationProfile_ProfileRelationshipId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDepreciationProfile_ProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetDepreciationProfile.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetDepreciationProfile.cdm.json/AssetDepreciationProfile</a></td><td><a href="../Parameter/AssetDepreciationProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetLedgerRelationshipId name="Relationship_AssetLedgerRelationshipId">Relationship_AssetLedgerRelationshipId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetLedgerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AssetLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Parameter/AssetLedger.cdm.json/AssetLedger</a></td><td><a href="../Parameter/AssetLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetTableRelationshipId name="Relationship_AssetTableRelationshipId">Relationship_AssetTableRelationshipId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetTable.cdm.json/AssetTable</a></td><td><a href="AssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/AssetLVPTransferProposal_AU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

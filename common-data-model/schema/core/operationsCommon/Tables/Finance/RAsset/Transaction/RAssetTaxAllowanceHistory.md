---
title: RAssetTaxAllowanceHistory - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# History of tax allowance changing

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/RAsset/Transaction/RAssetTaxAllowanceHistory.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RAssetTaxAllowanceHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>History of tax allowance changing</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[AssetId](#AssetId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[DenominatorShare](#DenominatorShare)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[NumeratorShare](#NumeratorShare)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[StartDate](#StartDate)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[TaxAllowance395RecId](#TaxAllowance395RecId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[TaxAllowanceRecId](#TaxAllowanceRecId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[UntaxedAreaPartAllowanceRecId](#UntaxedAreaPartAllowanceRecId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[DenominatorShareOwned](#DenominatorShareOwned)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[LandCadastralNum](#LandCadastralNum)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[RoomCadastralNum](#RoomCadastralNum)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[LandType](#LandType)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[NumeratorShareOwned](#NumeratorShareOwned)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[RAssetDistribution](#RAssetDistribution)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[TaxBase](#TaxBase)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[DataAreaId](#DataAreaId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[Relationship_RAssetTableRelationshipId](#Relationship_RAssetTableRelationshipId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[Relationship_TaxAllowanceRelationshipId](#Relationship_TaxAllowanceRelationshipId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[Relationship_TaxAllowance395RelationshipId](#Relationship_TaxAllowance395RelationshipId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[Relationship_UntaxedAreaPartAllowanceRelationshipId](#Relationship_UntaxedAreaPartAllowanceRelationshipId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[Relationship_RAssetDistributionRelationshipId](#Relationship_RAssetDistributionRelationshipId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[Relationship_LandTypeTable_WRelationshipId](#Relationship_LandTypeTable_WRelationshipId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RAssetTaxAllowanceHistory.md" target="_blank">Transaction/RAssetTaxAllowanceHistory</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RAssetTaxAllowanceHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetId name="AssetId">AssetId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DenominatorShare name="DenominatorShare">DenominatorShare</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allowance share denominator</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DenominatorShare attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allowance share denominator</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#NumeratorShare name="NumeratorShare">NumeratorShare</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allowance share numerator</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumeratorShare attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allowance share numerator</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#TaxAllowance395RecId name="TaxAllowance395RecId">TaxAllowance395RecId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Land tax exemption (art.395)</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAllowance395RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Land tax exemption (art.395)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAllowanceRecId name="TaxAllowanceRecId">TaxAllowanceRecId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Land tax exemption (art.387)</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAllowanceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Land tax exemption (art.387)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UntaxedAreaPartAllowanceRecId name="UntaxedAreaPartAllowanceRecId">UntaxedAreaPartAllowanceRecId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UntaxedAreaPartAllowanceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DenominatorShareOwned name="DenominatorShareOwned">DenominatorShareOwned</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owned share denominator</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DenominatorShareOwned attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owned share denominator</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#LandCadastralNum name="LandCadastralNum">LandCadastralNum</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LandCadastralNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoomCadastralNum name="RoomCadastralNum">RoomCadastralNum</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoomCadastralNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LandType name="LandType">LandType</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LandType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumeratorShareOwned name="NumeratorShareOwned">NumeratorShareOwned</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owned share numerator</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumeratorShareOwned attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owned share numerator</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RAssetDistribution name="RAssetDistribution">RAssetDistribution</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RAssetDistribution attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxBase name="TaxBase">TaxBase</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax base</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax base</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

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

### <a href=#Relationship_RAssetTableRelationshipId name="Relationship_RAssetTableRelationshipId">Relationship_RAssetTableRelationshipId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RAssetTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RAssetTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Main/RAssetTable.cdm.json/RAssetTable</a></td><td><a href="../Main/RAssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxAllowanceRelationshipId name="Relationship_TaxAllowanceRelationshipId">Relationship_TaxAllowanceRelationshipId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAllowanceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RAssetTaxAllowance.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Main/RAssetTaxAllowance.cdm.json/RAssetTaxAllowance</a></td><td><a href="../Main/RAssetTaxAllowance.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxAllowance395RelationshipId name="Relationship_TaxAllowance395RelationshipId">Relationship_TaxAllowance395RelationshipId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAllowance395RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RAssetTaxAllowance.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Main/RAssetTaxAllowance.cdm.json/RAssetTaxAllowance</a></td><td><a href="../Main/RAssetTaxAllowance.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UntaxedAreaPartAllowanceRelationshipId name="Relationship_UntaxedAreaPartAllowanceRelationshipId">Relationship_UntaxedAreaPartAllowanceRelationshipId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UntaxedAreaPartAllowanceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RAssetTaxAllowance.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Main/RAssetTaxAllowance.cdm.json/RAssetTaxAllowance</a></td><td><a href="../Main/RAssetTaxAllowance.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RAssetDistributionRelationshipId name="Relationship_RAssetDistributionRelationshipId">Relationship_RAssetDistributionRelationshipId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RAssetDistributionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RAssetDistribution.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Transaction/RAssetDistribution.cdm.json/RAssetDistribution</a></td><td><a href="RAssetDistribution.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LandTypeTable_WRelationshipId name="Relationship_LandTypeTable_WRelationshipId">Relationship_LandTypeTable_WRelationshipId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LandTypeTable_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Main/LandTypeTable_W.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Main/LandTypeTable_W.cdm.json/LandTypeTable_W</a></td><td><a href="../../APARShared/Main/LandTypeTable_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RAssetTaxAllowanceHistory (this entity)  

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

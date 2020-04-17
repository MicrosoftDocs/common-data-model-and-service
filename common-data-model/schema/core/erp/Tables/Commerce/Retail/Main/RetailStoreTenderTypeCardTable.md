---
title: RetailStoreTenderTypeCardTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailStoreTenderTypeCardTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Main/RetailStoreTenderTypeCardTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailStoreTenderTypeCardTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[accountType](#accountType)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[allowManualInput](#allowManualInput)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[brokerId](#brokerId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[cardFee](#cardFee)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[CardFeeLedgerDimension](#CardFeeLedgerDimension)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[cardFeeMax](#cardFeeMax)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[cardFeeMin](#cardFeeMin)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[CardFeeOffsetLedgerDimension](#CardFeeOffsetLedgerDimension)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[cardInquiryFee](#cardInquiryFee)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[cardNumberSwiped](#cardNumberSwiped)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[cardTypeId](#cardTypeId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[cashBackLimit](#cashBackLimit)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[Channel](#Channel)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[checkExpiredDate](#checkExpiredDate)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[checkModulus](#checkModulus)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[countingRequired](#countingRequired)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[DiffAccBigDiffLedgerDimension](#DiffAccBigDiffLedgerDimension)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[DifferenceAccLedgerDimension](#DifferenceAccLedgerDimension)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[enterFleetInfo](#enterFleetInfo)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[LedgerDimension](#LedgerDimension)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[manualAuthorization](#manualAuthorization)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[maxNormalDifferenceAmount](#maxNormalDifferenceAmount)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[name](#name)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[processLocally](#processLocally)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[sameCardAllowed](#sameCardAllowed)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[tenderTypeId](#tenderTypeId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[cardFeeAccountType](#cardFeeAccountType)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[cardFeeOffsetAccountType](#cardFeeOffsetAccountType)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[IsExpirationDateRequired](#IsExpirationDateRequired)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[IsPinRequired](#IsPinRequired)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[Relationship_DimensionAttributeValueCombinationRelationshipId](#Relationship_DimensionAttributeValueCombinationRelationshipId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[Relationship_DimensionAttributeValueCombination1RelationshipId](#Relationship_DimensionAttributeValueCombination1RelationshipId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[Relationship_DimensionAttributeValueCombination2RelationshipId](#Relationship_DimensionAttributeValueCombination2RelationshipId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[Relationship_DimensionAttributeValueCombination3RelationshipId](#Relationship_DimensionAttributeValueCombination3RelationshipId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[Relationship_DimensionAttributeValueCombination4RelationshipId](#Relationship_DimensionAttributeValueCombination4RelationshipId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[Relationship_RetailChannelTableRelationshipId](#Relationship_RetailChannelTableRelationshipId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[Relationship_RetailStoreTenderTypeTableRelationshipId](#Relationship_RetailStoreTenderTypeTableRelationshipId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[Relationship_RetailTenderTypeCardTableRelationshipId](#Relationship_RetailTenderTypeCardTableRelationshipId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailStoreTenderTypeCardTable.md" target="_blank">Main/RetailStoreTenderTypeCardTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailStoreTenderTypeCardTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#accountType name="accountType">accountType</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the accountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowManualInput name="allowManualInput">allowManualInput</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowManualInput attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#brokerId name="brokerId">brokerId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the brokerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#cardFee name="cardFee">cardFee</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cardFee attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CardFeeLedgerDimension name="CardFeeLedgerDimension">CardFeeLedgerDimension</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardFeeLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#cardFeeMax name="cardFeeMax">cardFeeMax</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cardFeeMax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#cardFeeMin name="cardFeeMin">cardFeeMin</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cardFeeMin attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CardFeeOffsetLedgerDimension name="CardFeeOffsetLedgerDimension">CardFeeOffsetLedgerDimension</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardFeeOffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#cardInquiryFee name="cardInquiryFee">cardInquiryFee</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cardInquiryFee attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#cardNumberSwiped name="cardNumberSwiped">cardNumberSwiped</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cardNumberSwiped attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#cardTypeId name="cardTypeId">cardTypeId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cardTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#cashBackLimit name="cashBackLimit">cashBackLimit</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cashBackLimit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#checkExpiredDate name="checkExpiredDate">checkExpiredDate</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the checkExpiredDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#checkModulus name="checkModulus">checkModulus</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the checkModulus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#countingRequired name="countingRequired">countingRequired</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the countingRequired attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DiffAccBigDiffLedgerDimension name="DiffAccBigDiffLedgerDimension">DiffAccBigDiffLedgerDimension</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiffAccBigDiffLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DifferenceAccLedgerDimension name="DifferenceAccLedgerDimension">DifferenceAccLedgerDimension</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DifferenceAccLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#enterFleetInfo name="enterFleetInfo">enterFleetInfo</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the enterFleetInfo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#manualAuthorization name="manualAuthorization">manualAuthorization</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the manualAuthorization attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#maxNormalDifferenceAmount name="maxNormalDifferenceAmount">maxNormalDifferenceAmount</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxNormalDifferenceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#name name="name">name</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#processLocally name="processLocally">processLocally</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the processLocally attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#sameCardAllowed name="sameCardAllowed">sameCardAllowed</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sameCardAllowed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#tenderTypeId name="tenderTypeId">tenderTypeId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the tenderTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#cardFeeAccountType name="cardFeeAccountType">cardFeeAccountType</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cardFeeAccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#cardFeeOffsetAccountType name="cardFeeOffsetAccountType">cardFeeOffsetAccountType</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cardFeeOffsetAccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsExpirationDateRequired name="IsExpirationDateRequired">IsExpirationDateRequired</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExpirationDateRequired attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsPinRequired name="IsPinRequired">IsPinRequired</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPinRequired attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

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

### <a href=#Relationship_DimensionAttributeValueCombinationRelationshipId name="Relationship_DimensionAttributeValueCombinationRelationshipId">Relationship_DimensionAttributeValueCombinationRelationshipId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeValueCombination1RelationshipId name="Relationship_DimensionAttributeValueCombination1RelationshipId">Relationship_DimensionAttributeValueCombination1RelationshipId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueCombination1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeValueCombination2RelationshipId name="Relationship_DimensionAttributeValueCombination2RelationshipId">Relationship_DimensionAttributeValueCombination2RelationshipId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueCombination2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeValueCombination3RelationshipId name="Relationship_DimensionAttributeValueCombination3RelationshipId">Relationship_DimensionAttributeValueCombination3RelationshipId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueCombination3RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeValueCombination4RelationshipId name="Relationship_DimensionAttributeValueCombination4RelationshipId">Relationship_DimensionAttributeValueCombination4RelationshipId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueCombination4RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailChannelTableRelationshipId name="Relationship_RetailChannelTableRelationshipId">Relationship_RetailChannelTableRelationshipId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailChannelTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailChannelTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailChannelTable.cdm.json/RetailChannelTable</a></td><td><a href="RetailChannelTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreTenderTypeTableRelationshipId name="Relationship_RetailStoreTenderTypeTableRelationshipId">Relationship_RetailStoreTenderTypeTableRelationshipId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreTenderTypeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailStoreTenderTypeTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailStoreTenderTypeTable.cdm.json/RetailStoreTenderTypeTable</a></td><td><a href="RetailStoreTenderTypeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTenderTypeCardTableRelationshipId name="Relationship_RetailTenderTypeCardTableRelationshipId">Relationship_RetailTenderTypeCardTableRelationshipId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTenderTypeCardTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailTenderTypeCardTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailTenderTypeCardTable.cdm.json/RetailTenderTypeCardTable</a></td><td><a href="RetailTenderTypeCardTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/RetailStoreTenderTypeCardTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

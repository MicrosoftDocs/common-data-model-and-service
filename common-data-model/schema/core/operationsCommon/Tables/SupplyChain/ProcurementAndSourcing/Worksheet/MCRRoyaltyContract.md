---
title: MCRRoyaltyContract - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# MCRRoyaltyContract

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Worksheet/MCRRoyaltyContract.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MCRRoyaltyContract/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[ApprovalRequired](#ApprovalRequired)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[CalcDates](#CalcDates)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[CumulateSalesBy](#CumulateSalesBy)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[Currency](#Currency)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[Description](#Description)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[EffectiveFromDate](#EffectiveFromDate)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[EffectiveToDate](#EffectiveToDate)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[ItemRoyaltyCode](#ItemRoyaltyCode)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[ItemRoyaltyRelation](#ItemRoyaltyRelation)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[LedgerDimension](#LedgerDimension)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[OffsetLedgerDimension](#OffsetLedgerDimension)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[RoyaltyContract](#RoyaltyContract)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[RoyaltyCustomizedPeriodType](#RoyaltyCustomizedPeriodType)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[RoyaltyDetails](#RoyaltyDetails)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[RoyaltyLineBreakType](#RoyaltyLineBreakType)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[RoyaltyTakenFrom](#RoyaltyTakenFrom)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[RoyaltyUOMOption](#RoyaltyUOMOption)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[UnitID](#UnitID)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[UnitType](#UnitType)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[Validated](#Validated)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[VendAccount](#VendAccount)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[VendRoyaltyCode](#VendRoyaltyCode)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[VendRoyaltyRelation](#VendRoyaltyRelation)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[Verifier](#Verifier)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[DataAreaId](#DataAreaId)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[Relationship_CustomizedPeriodTypeRelationshipId](#Relationship_CustomizedPeriodTypeRelationshipId)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[Relationship_LedgerDimensionRelationshipId](#Relationship_LedgerDimensionRelationshipId)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[Relationship_OffsetLedgerDimensionRelationshipId](#Relationship_OffsetLedgerDimensionRelationshipId)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[Relationship_VendAccountRelationshipId](#Relationship_VendAccountRelationshipId)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="MCRRoyaltyContract.md" target="_blank">Worksheet/MCRRoyaltyContract</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MCRRoyaltyContract/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ApprovalRequired name="ApprovalRequired">ApprovalRequired</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovalRequired attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CalcDates name="CalcDates">CalcDates</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcDates attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CumulateSalesBy name="CumulateSalesBy">CumulateSalesBy</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CumulateSalesBy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

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

### <a href=#EffectiveFromDate name="EffectiveFromDate">EffectiveFromDate</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveFromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#EffectiveToDate name="EffectiveToDate">EffectiveToDate</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ItemRoyaltyCode name="ItemRoyaltyCode">ItemRoyaltyCode</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRoyaltyCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemRoyaltyRelation name="ItemRoyaltyRelation">ItemRoyaltyRelation</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRoyaltyRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

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

### <a href=#OffsetLedgerDimension name="OffsetLedgerDimension">OffsetLedgerDimension</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RoyaltyContract name="RoyaltyContract">RoyaltyContract</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyContract attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyCustomizedPeriodType name="RoyaltyCustomizedPeriodType">RoyaltyCustomizedPeriodType</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyCustomizedPeriodType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyDetails name="RoyaltyDetails">RoyaltyDetails</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyLineBreakType name="RoyaltyLineBreakType">RoyaltyLineBreakType</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyLineBreakType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RoyaltyTakenFrom name="RoyaltyTakenFrom">RoyaltyTakenFrom</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyTakenFrom attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RoyaltyUOMOption name="RoyaltyUOMOption">RoyaltyUOMOption</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyUOMOption attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UnitID name="UnitID">UnitID</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitType name="UnitType">UnitType</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Validated name="Validated">Validated</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Validated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#VendAccount name="VendAccount">VendAccount</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendRoyaltyCode name="VendRoyaltyCode">VendRoyaltyCode</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRoyaltyCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendRoyaltyRelation name="VendRoyaltyRelation">VendRoyaltyRelation</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRoyaltyRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Verifier name="Verifier">Verifier</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Verifier attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomizedPeriodTypeRelationshipId name="Relationship_CustomizedPeriodTypeRelationshipId">Relationship_CustomizedPeriodTypeRelationshipId</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomizedPeriodTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPeriodTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPeriodTable.cdm.json/ProjPeriodTable</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPeriodTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionRelationshipId name="Relationship_LedgerDimensionRelationshipId">Relationship_LedgerDimensionRelationshipId</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OffsetLedgerDimensionRelationshipId name="Relationship_OffsetLedgerDimensionRelationshipId">Relationship_OffsetLedgerDimensionRelationshipId</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendAccountRelationshipId name="Relationship_VendAccountRelationshipId">Relationship_VendAccountRelationshipId</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Worksheet/MCRRoyaltyContract (this entity)  

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

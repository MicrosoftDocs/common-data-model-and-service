---
title: RLedgerTurnoverSheet - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RLedgerTurnoverSheet

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Ledger/TransactionHeader/RLedgerTurnoverSheet.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RLedgerTurnoverSheet/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[CurrencyCode](#CurrencyCode)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[CurrencyType](#CurrencyType)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[DeleteZero](#DeleteZero)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[DimensionCriteria](#DimensionCriteria)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[FromDate](#FromDate)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[GroupKey](#GroupKey)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[GroupKeyExp](#GroupKeyExp)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[MainAccountNum](#MainAccountNum)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[MainAccountNumCorr](#MainAccountNumCorr)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[PackedCaller](#PackedCaller)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[PackedQuery](#PackedQuery)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[PrintRanges](#PrintRanges)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[ReportType](#ReportType)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[ShowBalance](#ShowBalance)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[ShowBalanceTrans](#ShowBalanceTrans)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[ShowOrigin](#ShowOrigin)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[ShowSumAccount](#ShowSumAccount)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[ShowTrans](#ShowTrans)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[ToDate](#ToDate)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[DataAreaId](#DataAreaId)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RLedgerTurnoverSheet.md" target="_blank">TransactionHeader/RLedgerTurnoverSheet</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RLedgerTurnoverSheet/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyType name="CurrencyType">CurrencyType</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeleteZero name="DeleteZero">DeleteZero</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeleteZero attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DimensionCriteria name="DimensionCriteria">DimensionCriteria</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionCriteria attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#GroupKey name="GroupKey">GroupKey</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupKey attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#GroupKeyExp name="GroupKeyExp">GroupKeyExp</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupKeyExp attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountNum name="MainAccountNum">MainAccountNum</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountNumCorr name="MainAccountNumCorr">MainAccountNumCorr</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountNumCorr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackedCaller name="PackedCaller">PackedCaller</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedCaller attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#PackedQuery name="PackedQuery">PackedQuery</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#PrintRanges name="PrintRanges">PrintRanges</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintRanges attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReportType name="ReportType">ReportType</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowBalance name="ShowBalance">ShowBalance</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowBalance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowBalanceTrans name="ShowBalanceTrans">ShowBalanceTrans</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowBalanceTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowOrigin name="ShowOrigin">ShowOrigin</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowSumAccount name="ShowSumAccount">ShowSumAccount</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowSumAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowTrans name="ShowTrans">ShowTrans</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

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

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionHeader/RLedgerTurnoverSheet (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

---
title: CustInterestCodeWithFeeEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Interest codes with fees in AccountsReceivable(CustInterestCodeWithFeeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustInterestCodeWithFeeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Interest codes with fees</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InterestCode](#InterestCode)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[InterestType](#InterestType)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[Description](#Description)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[InterestGraceDays](#InterestGraceDays)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[ValidTo](#ValidTo)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[FeeType](#FeeType)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[InterestByRange](#InterestByRange)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[InterestCalcType](#InterestCalcType)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[InterestCalculateBy](#InterestCalculateBy)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[InterestCalculateByInterval](#InterestCalculateByInterval)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[InterestPercent](#InterestPercent)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[LedgerPostingAccount](#LedgerPostingAccount)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[LedgerPostingAccountDisplayValue](#LedgerPostingAccountDisplayValue)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[FeeCurrencyCode](#FeeCurrencyCode)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[FeeDescription](#FeeDescription)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[FeeInterestValue](#FeeInterestValue)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[MaximumInterestAmount](#MaximumInterestAmount)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[MinimumInterestAmount](#MinimumInterestAmount)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[ChargeCustWhenInterestExceeds](#ChargeCustWhenInterestExceeds)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[FeeLedgerDimension](#FeeLedgerDimension)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[FeeLedgerDimensionDisplayValue](#FeeLedgerDimensionDisplayValue)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[Fee](#Fee)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[FeeTaxItemGroup](#FeeTaxItemGroup)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[BackingTable_CustInterestRelationshipId](#BackingTable_CustInterestRelationshipId)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustInterestCodeWithFeeEntity.md" target="_blank">AccountsReceivable/CustInterestCodeWithFeeEntity</a>|

### <a href=#InterestCode name="InterestCode">InterestCode</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestType name="InterestType">InterestType</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestGraceDays name="InterestGraceDays">InterestGraceDays</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestGraceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeType name="FeeType">FeeType</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestByRange name="InterestByRange">InterestByRange</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestByRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestCalcType name="InterestCalcType">InterestCalcType</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestCalcType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestCalculateBy name="InterestCalculateBy">InterestCalculateBy</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestCalculateBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestCalculateByInterval name="InterestCalculateByInterval">InterestCalculateByInterval</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestCalculateByInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestPercent name="InterestPercent">InterestPercent</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestPercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerPostingAccount name="LedgerPostingAccount">LedgerPostingAccount</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPostingAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerPostingAccountDisplayValue name="LedgerPostingAccountDisplayValue">LedgerPostingAccountDisplayValue</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPostingAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeCurrencyCode name="FeeCurrencyCode">FeeCurrencyCode</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeDescription name="FeeDescription">FeeDescription</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeInterestValue name="FeeInterestValue">FeeInterestValue</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeInterestValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumInterestAmount name="MaximumInterestAmount">MaximumInterestAmount</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumInterestAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumInterestAmount name="MinimumInterestAmount">MinimumInterestAmount</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumInterestAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeCustWhenInterestExceeds name="ChargeCustWhenInterestExceeds">ChargeCustWhenInterestExceeds</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCustWhenInterestExceeds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeLedgerDimension name="FeeLedgerDimension">FeeLedgerDimension</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeLedgerDimensionDisplayValue name="FeeLedgerDimensionDisplayValue">FeeLedgerDimensionDisplayValue</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Fee name="Fee">Fee</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Fee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeTaxItemGroup name="FeeTaxItemGroup">FeeTaxItemGroup</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeTaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustInterestRelationshipId name="BackingTable_CustInterestRelationshipId">BackingTable_CustInterestRelationshipId</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustInterestRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Group/CustInterest.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustInterest.cdm.json/CustInterest</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Group/CustInterest.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CustInterestCodeWithFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

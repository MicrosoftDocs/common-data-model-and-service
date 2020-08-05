---
title: TaxWithholdingTaxCodeEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Withholding tax codes in Tax(TaxWithholdingTaxCodeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxWithholdingTaxCodeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax codes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CurrencyCodeID](#CurrencyCodeID)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[MainAccountId](#MainAccountId)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[WithholdingTaxBase](#WithholdingTaxBase)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[WithholdingCode](#WithholdingCode)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[WithholdingTaxName](#WithholdingTaxName)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[WithholdingTaxRoundOff](#WithholdingTaxRoundOff)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[WithholdingTaxRoundOffType](#WithholdingTaxRoundOffType)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[MainAccountIdDisplayValue](#MainAccountIdDisplayValue)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[TaxWithholdLedgerAccountGroupRecId](#TaxWithholdLedgerAccountGroupRecId)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[TaxWithholdPeriodHeadRecId](#TaxWithholdPeriodHeadRecId)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[TaxWithholdAccountGroup](#TaxWithholdAccountGroup)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[TaxWithholdPeriod](#TaxWithholdPeriod)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[WithholdingTaxReceivable](#WithholdingTaxReceivable)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[BrazilianTaxWithholdPeriod](#BrazilianTaxWithholdPeriod)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[BrazilianTaxWithholdType](#BrazilianTaxWithholdType)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[SettlementAccount](#SettlementAccount)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[WithholdingTaxReceivableDisplayValue](#WithholdingTaxReceivableDisplayValue)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[SettlementAccountDisplayValue](#SettlementAccountDisplayValue)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[ApplyThreshold](#ApplyThreshold)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[TaxType](#TaxType)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[TaxWithholdComponent](#TaxWithholdComponent)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[ReceivableAccount](#ReceivableAccount)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[ReceivableAccountDisplayValue](#ReceivableAccountDisplayValue)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[WithholdingTaxComponent](#WithholdingTaxComponent)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[WithholdingComponentGroup](#WithholdingComponentGroup)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[SettlementPeriod](#SettlementPeriod)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[Relationship_MainAccountIdCombinationRelationshipId](#Relationship_MainAccountIdCombinationRelationshipId)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[Relationship_TaxWithholdLedgerAccountGroupRecIdRelationshipId](#Relationship_TaxWithholdLedgerAccountGroupRecIdRelationshipId)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[Relationship_TaxWithholdPeriodHeadRecIdRelationshipId](#Relationship_TaxWithholdPeriodHeadRecIdRelationshipId)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[BackingTable_TaxWithholdTableRelationshipId](#BackingTable_TaxWithholdTableRelationshipId)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TaxWithholdingTaxCodeEntity.md" target="_blank">Tax/TaxWithholdingTaxCodeEntity</a>|

### <a href=#CurrencyCodeID name="CurrencyCodeID">CurrencyCodeID</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCodeID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountId name="MainAccountId">MainAccountId</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxBase name="WithholdingTaxBase">WithholdingTaxBase</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxBase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingCode name="WithholdingCode">WithholdingCode</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxName name="WithholdingTaxName">WithholdingTaxName</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxRoundOff name="WithholdingTaxRoundOff">WithholdingTaxRoundOff</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxRoundOff attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxRoundOffType name="WithholdingTaxRoundOffType">WithholdingTaxRoundOffType</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxRoundOffType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdDisplayValue name="MainAccountIdDisplayValue">MainAccountIdDisplayValue</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdLedgerAccountGroupRecId name="TaxWithholdLedgerAccountGroupRecId">TaxWithholdLedgerAccountGroupRecId</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdLedgerAccountGroupRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdPeriodHeadRecId name="TaxWithholdPeriodHeadRecId">TaxWithholdPeriodHeadRecId</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdPeriodHeadRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdAccountGroup name="TaxWithholdAccountGroup">TaxWithholdAccountGroup</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdAccountGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdPeriod name="TaxWithholdPeriod">TaxWithholdPeriod</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxReceivable name="WithholdingTaxReceivable">WithholdingTaxReceivable</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxReceivable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianTaxWithholdPeriod name="BrazilianTaxWithholdPeriod">BrazilianTaxWithholdPeriod</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianTaxWithholdPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianTaxWithholdType name="BrazilianTaxWithholdType">BrazilianTaxWithholdType</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianTaxWithholdType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementAccount name="SettlementAccount">SettlementAccount</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxReceivableDisplayValue name="WithholdingTaxReceivableDisplayValue">WithholdingTaxReceivableDisplayValue</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxReceivableDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementAccountDisplayValue name="SettlementAccountDisplayValue">SettlementAccountDisplayValue</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplyThreshold name="ApplyThreshold">ApplyThreshold</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplyThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdComponent name="TaxWithholdComponent">TaxWithholdComponent</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdComponent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivableAccount name="ReceivableAccount">ReceivableAccount</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivableAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivableAccountDisplayValue name="ReceivableAccountDisplayValue">ReceivableAccountDisplayValue</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivableAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxComponent name="WithholdingTaxComponent">WithholdingTaxComponent</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxComponent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingComponentGroup name="WithholdingComponentGroup">WithholdingComponentGroup</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingComponentGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementPeriod name="SettlementPeriod">SettlementPeriod</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountIdCombinationRelationshipId name="Relationship_MainAccountIdCombinationRelationshipId">Relationship_MainAccountIdCombinationRelationshipId</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxWithholdLedgerAccountGroupRecIdRelationshipId name="Relationship_TaxWithholdLedgerAccountGroupRecIdRelationshipId">Relationship_TaxWithholdLedgerAccountGroupRecIdRelationshipId</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdLedgerAccountGroupRecIdRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxWithholdPeriodHeadRecIdRelationshipId name="Relationship_TaxWithholdPeriodHeadRecIdRelationshipId">Relationship_TaxWithholdPeriodHeadRecIdRelationshipId</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdPeriodHeadRecIdRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_TaxWithholdTableRelationshipId name="BackingTable_TaxWithholdTableRelationshipId">BackingTable_TaxWithholdTableRelationshipId</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TaxWithholdTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Main/TaxWithholdTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxWithholdTable.cdm.json/TaxWithholdTable</a></td><td><a href="../../../Tables/Finance/Tax/Main/TaxWithholdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Tax/TaxWithholdingTaxCodeEntity (this entity)  

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

---
title: CustAgingEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Customer aged balances in AccountsReceivable(CustAgingEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustAgingEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer aged balances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustName](#CustName)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[CustAccount](#CustAccount)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[Company](#Company)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriodDefinition](#AgingPeriodDefinition)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgedBy](#AgedBy)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingDate](#AgingDate)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[SumOfAmountDueMst](#SumOfAmountDueMst)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriodLabel1](#AgingPeriodLabel1)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod1](#AgingPeriod1)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod1ReportingCurrency](#AgingPeriod1ReportingCurrency)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriodLabel2](#AgingPeriodLabel2)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod2](#AgingPeriod2)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod2ReportingCurrency](#AgingPeriod2ReportingCurrency)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriodLabel3](#AgingPeriodLabel3)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod3](#AgingPeriod3)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod3ReportingCurrency](#AgingPeriod3ReportingCurrency)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriodLabel4](#AgingPeriodLabel4)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod4](#AgingPeriod4)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod4ReportingCurrency](#AgingPeriod4ReportingCurrency)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriodLabel5](#AgingPeriodLabel5)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod5](#AgingPeriod5)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod5ReportingCurrency](#AgingPeriod5ReportingCurrency)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriodLabel6](#AgingPeriodLabel6)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod6](#AgingPeriod6)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[AgingPeriod6ReportingCurrency](#AgingPeriod6ReportingCurrency)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[FirstNonzeroBalancePeriod](#FirstNonzeroBalancePeriod)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[LastPaymentAmount](#LastPaymentAmount)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[LastPaymentDate](#LastPaymentDate)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[NumOpenInvoices](#NumOpenInvoices)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[MSTCurrency](#MSTCurrency)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[BackingTable_CustAgingRelationshipId](#BackingTable_CustAgingRelationshipId)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustAgingEntity.md" target="_blank">AccountsReceivable/CustAgingEntity</a>|

### <a href=#CustName name="CustName">CustName</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccount name="CustAccount">CustAccount</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriodDefinition name="AgingPeriodDefinition">AgingPeriodDefinition</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriodDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgedBy name="AgedBy">AgedBy</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingDate name="AgingDate">AgingDate</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumOfAmountDueMst name="SumOfAmountDueMst">SumOfAmountDueMst</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumOfAmountDueMst attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriodLabel1 name="AgingPeriodLabel1">AgingPeriodLabel1</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriodLabel1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod1 name="AgingPeriod1">AgingPeriod1</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod1ReportingCurrency name="AgingPeriod1ReportingCurrency">AgingPeriod1ReportingCurrency</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod1ReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriodLabel2 name="AgingPeriodLabel2">AgingPeriodLabel2</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriodLabel2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod2 name="AgingPeriod2">AgingPeriod2</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod2ReportingCurrency name="AgingPeriod2ReportingCurrency">AgingPeriod2ReportingCurrency</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod2ReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriodLabel3 name="AgingPeriodLabel3">AgingPeriodLabel3</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriodLabel3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod3 name="AgingPeriod3">AgingPeriod3</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod3ReportingCurrency name="AgingPeriod3ReportingCurrency">AgingPeriod3ReportingCurrency</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod3ReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriodLabel4 name="AgingPeriodLabel4">AgingPeriodLabel4</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriodLabel4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod4 name="AgingPeriod4">AgingPeriod4</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod4ReportingCurrency name="AgingPeriod4ReportingCurrency">AgingPeriod4ReportingCurrency</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod4ReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriodLabel5 name="AgingPeriodLabel5">AgingPeriodLabel5</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriodLabel5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod5 name="AgingPeriod5">AgingPeriod5</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod5ReportingCurrency name="AgingPeriod5ReportingCurrency">AgingPeriod5ReportingCurrency</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod5ReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriodLabel6 name="AgingPeriodLabel6">AgingPeriodLabel6</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriodLabel6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod6 name="AgingPeriod6">AgingPeriod6</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingPeriod6ReportingCurrency name="AgingPeriod6ReportingCurrency">AgingPeriod6ReportingCurrency</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriod6ReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstNonzeroBalancePeriod name="FirstNonzeroBalancePeriod">FirstNonzeroBalancePeriod</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstNonzeroBalancePeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastPaymentAmount name="LastPaymentAmount">LastPaymentAmount</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastPaymentAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastPaymentDate name="LastPaymentDate">LastPaymentDate</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastPaymentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumOpenInvoices name="NumOpenInvoices">NumOpenInvoices</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumOpenInvoices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MSTCurrency name="MSTCurrency">MSTCurrency</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MSTCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustAgingRelationshipId name="BackingTable_CustAgingRelationshipId">BackingTable_CustAgingRelationshipId</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustAgingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Group/CustAging.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustAging.cdm.json/CustAging</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Group/CustAging.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CustAgingEntity (this entity)  

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

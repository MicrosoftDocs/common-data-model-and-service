---
title: SalesChargeCDSEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# CDS sales charge codes in SalesAndMarketing(SalesChargeCDSEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesChargeCDSEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CDS sales charge codes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ChargeClassification](#ChargeClassification)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[ChargeCode](#ChargeCode)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[ChargeDescription](#ChargeDescription)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[CreditPostingMainAccountIdDisplayValue](#CreditPostingMainAccountIdDisplayValue)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[CreditPostingMethod](#CreditPostingMethod)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[CreditPostingType](#CreditPostingType)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[DebitPostingMainAccountIdDisplayValue](#DebitPostingMainAccountIdDisplayValue)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[DebitPostingMethod](#DebitPostingMethod)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[DebitPostingType](#DebitPostingType)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[SalesTaxItemGroupCode](#SalesTaxItemGroupCode)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[WillIntrastatInvoiceValueIncludeChargeAmounts](#WillIntrastatInvoiceValueIncludeChargeAmounts)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[WillIntrastatStatisticalValueIncludeChargeAmounts](#WillIntrastatStatisticalValueIncludeChargeAmounts)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[WillSalesInvoicingProrateChargeAmounts](#WillSalesInvoicingProrateChargeAmounts)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[LedgerName](#LedgerName)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[ChartOfAccountsName](#ChartOfAccountsName)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[BackingTable_SalesChargeEntityRelationshipId](#BackingTable_SalesChargeEntityRelationshipId)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesChargeCDSEntity.md" target="_blank">SalesAndMarketing/SalesChargeCDSEntity</a>|

### <a href=#ChargeClassification name="ChargeClassification">ChargeClassification</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeClassification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeCode name="ChargeCode">ChargeCode</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeDescription name="ChargeDescription">ChargeDescription</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditPostingMainAccountIdDisplayValue name="CreditPostingMainAccountIdDisplayValue">CreditPostingMainAccountIdDisplayValue</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditPostingMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditPostingMethod name="CreditPostingMethod">CreditPostingMethod</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditPostingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditPostingType name="CreditPostingType">CreditPostingType</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditPostingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitPostingMainAccountIdDisplayValue name="DebitPostingMainAccountIdDisplayValue">DebitPostingMainAccountIdDisplayValue</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitPostingMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitPostingMethod name="DebitPostingMethod">DebitPostingMethod</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitPostingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitPostingType name="DebitPostingType">DebitPostingType</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitPostingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxItemGroupCode name="SalesTaxItemGroupCode">SalesTaxItemGroupCode</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillIntrastatInvoiceValueIncludeChargeAmounts name="WillIntrastatInvoiceValueIncludeChargeAmounts">WillIntrastatInvoiceValueIncludeChargeAmounts</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillIntrastatInvoiceValueIncludeChargeAmounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillIntrastatStatisticalValueIncludeChargeAmounts name="WillIntrastatStatisticalValueIncludeChargeAmounts">WillIntrastatStatisticalValueIncludeChargeAmounts</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillIntrastatStatisticalValueIncludeChargeAmounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesInvoicingProrateChargeAmounts name="WillSalesInvoicingProrateChargeAmounts">WillSalesInvoicingProrateChargeAmounts</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesInvoicingProrateChargeAmounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerName name="LedgerName">LedgerName</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChartOfAccountsName name="ChartOfAccountsName">ChartOfAccountsName</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChartOfAccountsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_SalesChargeEntityRelationshipId name="BackingTable_SalesChargeEntityRelationshipId">BackingTable_SalesChargeEntityRelationshipId</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesChargeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesChargeCDSEntity (this entity)  

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

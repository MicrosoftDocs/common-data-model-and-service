---
title: MarkupDocumentChargeEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Charges code

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/MarkupDocumentChargeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Charges code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountingDate](#AccountingDate)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[CalculatedDocumentCurrencyAmount](#CalculatedDocumentCurrencyAmount)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ChargeAccountingCurrencyCode](#ChargeAccountingCurrencyCode)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ChargeCategory](#ChargeCategory)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ChargeCode](#ChargeCode)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ChargeCreationMethod](#ChargeCreationMethod)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ChargeDescription](#ChargeDescription)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ChargeLineNumber](#ChargeLineNumber)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ChargeOverrideInformationSubcodeId](#ChargeOverrideInformationSubcodeId)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[CorrectedDocumentChargeRecId](#CorrectedDocumentChargeRecId)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[DocumentCurrencyAmount](#DocumentCurrencyAmount)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[DocumentStatus](#DocumentStatus)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[FromTotalLineAmount](#FromTotalLineAmount)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[InfocodeNumber](#InfocodeNumber)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[IsAutomaticCharge](#IsAutomaticCharge)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[IsBrokerContractCharge](#IsBrokerContractCharge)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[IsChargeDeleted](#IsChargeDeleted)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[IsChargeModified](#IsChargeModified)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[IsChargeOverridden](#IsChargeOverridden)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[IsCouponCharge](#IsCouponCharge)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[IsIntercompanyCharge](#IsIntercompanyCharge)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[IsInstallmentPlanCharge](#IsInstallmentPlanCharge)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[IsSalesTaxAutogenerated](#IsSalesTaxAutogenerated)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[IsTieredCharge](#IsTieredCharge)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ModuleCategory](#ModuleCategory)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ModuleType](#ModuleType)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[OriginalChargeAmount](#OriginalChargeAmount)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[SalesTaxDocumentCurrencyAmount](#SalesTaxDocumentCurrencyAmount)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[SalesTaxItemGroupCode](#SalesTaxItemGroupCode)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[SalesTaxPrintCode](#SalesTaxPrintCode)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ToTotalLineAmount](#ToTotalLineAmount)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[Voucher](#Voucher)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[WillInvoiceProcessingKeepCharge](#WillInvoiceProcessingKeepCharge)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[Value](#Value)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[MCRSavedRecID](#MCRSavedRecID)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[MCRSavedTableID](#MCRSavedTableID)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ChargeRecId](#ChargeRecId)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ChargeTableId](#ChargeTableId)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[SourceDocumentLineRecId](#SourceDocumentLineRecId)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[DocumentRecId](#DocumentRecId)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[DocumentTableId](#DocumentTableId)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[CustInvoiceLineRefId](#CustInvoiceLineRefId)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[CustInvoiceLineTemplate](#CustInvoiceLineTemplate)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ChargePercentage](#ChargePercentage)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[FixedChargeAmount](#FixedChargeAmount)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[IntercompanyChargePercentage](#IntercompanyChargePercentage)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[UnitChargeAmount](#UnitChargeAmount)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ExternalChargeAmount](#ExternalChargeAmount)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ProportionalChargeAmount](#ProportionalChargeAmount)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[ChargeClassification](#ChargeClassification)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[BackingTable_MarkupTransRelationshipId](#BackingTable_MarkupTransRelationshipId)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="MarkupDocumentChargeEntity.md" target="_blank">SalesAndMarketing/MarkupDocumentChargeEntity</a>|

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculatedDocumentCurrencyAmount name="CalculatedDocumentCurrencyAmount">CalculatedDocumentCurrencyAmount</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatedDocumentCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeAccountingCurrencyCode name="ChargeAccountingCurrencyCode">ChargeAccountingCurrencyCode</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeAccountingCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeCategory name="ChargeCategory">ChargeCategory</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeCode name="ChargeCode">ChargeCode</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

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

### <a href=#ChargeCreationMethod name="ChargeCreationMethod">ChargeCreationMethod</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCreationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeDescription name="ChargeDescription">ChargeDescription</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

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

### <a href=#ChargeLineNumber name="ChargeLineNumber">ChargeLineNumber</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeOverrideInformationSubcodeId name="ChargeOverrideInformationSubcodeId">ChargeOverrideInformationSubcodeId</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeOverrideInformationSubcodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedDocumentChargeRecId name="CorrectedDocumentChargeRecId">CorrectedDocumentChargeRecId</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedDocumentChargeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentCurrencyAmount name="DocumentCurrencyAmount">DocumentCurrencyAmount</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentStatus name="DocumentStatus">DocumentStatus</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromTotalLineAmount name="FromTotalLineAmount">FromTotalLineAmount</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromTotalLineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InfocodeNumber name="InfocodeNumber">InfocodeNumber</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InfocodeNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAutomaticCharge name="IsAutomaticCharge">IsAutomaticCharge</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutomaticCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBrokerContractCharge name="IsBrokerContractCharge">IsBrokerContractCharge</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBrokerContractCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsChargeDeleted name="IsChargeDeleted">IsChargeDeleted</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsChargeDeleted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsChargeModified name="IsChargeModified">IsChargeModified</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsChargeModified attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsChargeOverridden name="IsChargeOverridden">IsChargeOverridden</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsChargeOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCouponCharge name="IsCouponCharge">IsCouponCharge</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCouponCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyCharge name="IsIntercompanyCharge">IsIntercompanyCharge</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInstallmentPlanCharge name="IsInstallmentPlanCharge">IsInstallmentPlanCharge</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInstallmentPlanCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesTaxAutogenerated name="IsSalesTaxAutogenerated">IsSalesTaxAutogenerated</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesTaxAutogenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTieredCharge name="IsTieredCharge">IsTieredCharge</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTieredCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModuleCategory name="ModuleCategory">ModuleCategory</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModuleCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModuleType name="ModuleType">ModuleType</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModuleType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalChargeAmount name="OriginalChargeAmount">OriginalChargeAmount</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxDocumentCurrencyAmount name="SalesTaxDocumentCurrencyAmount">SalesTaxDocumentCurrencyAmount</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxDocumentCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxItemGroupCode name="SalesTaxItemGroupCode">SalesTaxItemGroupCode</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

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

### <a href=#SalesTaxPrintCode name="SalesTaxPrintCode">SalesTaxPrintCode</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxPrintCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToTotalLineAmount name="ToTotalLineAmount">ToTotalLineAmount</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToTotalLineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInvoiceProcessingKeepCharge name="WillInvoiceProcessingKeepCharge">WillInvoiceProcessingKeepCharge</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInvoiceProcessingKeepCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Value name="Value">Value</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRSavedRecID name="MCRSavedRecID">MCRSavedRecID</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRSavedRecID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRSavedTableID name="MCRSavedTableID">MCRSavedTableID</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRSavedTableID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeRecId name="ChargeRecId">ChargeRecId</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeTableId name="ChargeTableId">ChargeTableId</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceDocumentLineRecId name="SourceDocumentLineRecId">SourceDocumentLineRecId</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLineRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentRecId name="DocumentRecId">DocumentRecId</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentTableId name="DocumentTableId">DocumentTableId</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustInvoiceLineRefId name="CustInvoiceLineRefId">CustInvoiceLineRefId</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceLineRefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustInvoiceLineTemplate name="CustInvoiceLineTemplate">CustInvoiceLineTemplate</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceLineTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargePercentage name="ChargePercentage">ChargePercentage</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedChargeAmount name="FixedChargeAmount">FixedChargeAmount</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntercompanyChargePercentage name="IntercompanyChargePercentage">IntercompanyChargePercentage</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntercompanyChargePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitChargeAmount name="UnitChargeAmount">UnitChargeAmount</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalChargeAmount name="ExternalChargeAmount">ExternalChargeAmount</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProportionalChargeAmount name="ProportionalChargeAmount">ProportionalChargeAmount</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProportionalChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeClassification name="ChargeClassification">ChargeClassification</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

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

### <a href=#BackingTable_MarkupTransRelationshipId name="BackingTable_MarkupTransRelationshipId">BackingTable_MarkupTransRelationshipId</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MarkupTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/MarkupTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/MarkupTrans.cdm.json/MarkupTrans</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/MarkupTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/MarkupDocumentChargeEntity (this entity)  

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

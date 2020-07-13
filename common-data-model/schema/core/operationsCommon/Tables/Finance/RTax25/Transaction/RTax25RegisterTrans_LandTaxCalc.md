---
title: RTax25RegisterTrans_LandTaxCalc in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Tax register line in Transaction(RTax25RegisterTrans_LandTaxCalc)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/RTax25/Transaction/RTax25RegisterTrans_LandTaxCalc.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RTax25RegisterTrans_LandTaxCalc/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax register line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[AllowanceAmount378](#AllowanceAmount378)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[AllowanceAmount391](#AllowanceAmount391)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[AllowanceAmountRateReduction](#AllowanceAmountRateReduction)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[AllowanceBaseReduction387](#AllowanceBaseReduction387)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[AllowanceBaseReduction391](#AllowanceBaseReduction391)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[AllowanceNonTaxableShare](#AllowanceNonTaxableShare)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[AllowanceRateReduction](#AllowanceRateReduction)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[AllowanceTaxReduction](#AllowanceTaxReduction)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[AssetId](#AssetId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[BlockType](#BlockType)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[BudgetRevenueCode](#BudgetRevenueCode)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[CadastralCost](#CadastralCost)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[CadastralNumber](#CadastralNumber)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[CategoryID](#CategoryID)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[ChangePeriod](#ChangePeriod)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Corrected](#Corrected)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[DesignAndBuildingPeriod](#DesignAndBuildingPeriod)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[ExemptionAmount387](#ExemptionAmount387)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[ExemptionAmount395](#ExemptionAmount395)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[FactorK1](#FactorK1)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[FactorK2](#FactorK2)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[GracePeriod](#GracePeriod)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[JournalTransRefRecId](#JournalTransRefRecId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[LandTaxExemption387](#LandTaxExemption387)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[LandTaxExemption395](#LandTaxExemption395)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[LineDescription](#LineDescription)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[LineNumber](#LineNumber)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[ManualInput](#ManualInput)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[NonTaxableAreaShare](#NonTaxableAreaShare)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[OwnedShare](#OwnedShare)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[ProfitAmount](#ProfitAmount)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[RCOAD](#RCOAD)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[RefRecId](#RefRecId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[RefTableId](#RefTableId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[RTax25ProfitTable](#RTax25ProfitTable)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[SalesTaxCode](#SalesTaxCode)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Tax](#Tax)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[TaxAllowanceAmount378](#TaxAllowanceAmount378)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[TaxAmount](#TaxAmount)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[TaxBase](#TaxBase)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[TaxValue](#TaxValue)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[FactorK3](#FactorK3)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[OwnershipPeriod](#OwnershipPeriod)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[RefLineNumber](#RefLineNumber)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[TaxAuthority](#TaxAuthority)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Location](#Location)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Branch](#Branch)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[DataAreaId](#DataAreaId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Relationship_LandTypeTable_WRelationshipId](#Relationship_LandTypeTable_WRelationshipId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId](#Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Relationship_RAssetTableRelationshipId](#Relationship_RAssetTableRelationshipId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Relationship_RAssetTableAssetIdRelationshipId](#Relationship_RAssetTableAssetIdRelationshipId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Relationship_RTax25ProfitTableRelationshipId](#Relationship_RTax25ProfitTableRelationshipId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Relationship_RTax25RegisterJournalTransRecIdRelationshipId](#Relationship_RTax25RegisterJournalTransRecIdRelationshipId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Relationship_TaxTableRelationshipId](#Relationship_TaxTableRelationshipId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Relationship_TaxAuthorityAddressRelationshipId](#Relationship_TaxAuthorityAddressRelationshipId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RTax25RegisterTrans_LandTaxCalc.md" target="_blank">Transaction/RTax25RegisterTrans_LandTaxCalc</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RTax25RegisterTrans_LandTaxCalc/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AllowanceAmount378 name="AllowanceAmount378">AllowanceAmount378</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax allowance amount (p. 2 of art.378)</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceAmount378 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax allowance amount (p. 2 of art.378)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AllowanceAmount391 name="AllowanceAmount391">AllowanceAmount391</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax allowance amount (p.5 art.391)</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceAmount391 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax allowance amount (p.5 art.391)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AllowanceAmountRateReduction name="AllowanceAmountRateReduction">AllowanceAmountRateReduction</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allowance by reduction of rate amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceAmountRateReduction attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allowance by reduction of rate amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AllowanceBaseReduction387 name="AllowanceBaseReduction387">AllowanceBaseReduction387</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax allowance of base reduction (p.2 art.378)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceBaseReduction387 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax allowance of base reduction (p.2 art.378)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceBaseReduction391 name="AllowanceBaseReduction391">AllowanceBaseReduction391</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax privilege of base reduction (p. 5 art.391)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceBaseReduction391 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax privilege of base reduction (p. 5 art.391)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceNonTaxableShare name="AllowanceNonTaxableShare">AllowanceNonTaxableShare</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Land tax allowance as non-taxable share</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceNonTaxableShare attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Land tax allowance as non-taxable share</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceRateReduction name="AllowanceRateReduction">AllowanceRateReduction</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allowance by reduction of rate</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceRateReduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allowance by reduction of rate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceTaxReduction name="AllowanceTaxReduction">AllowanceTaxReduction</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allowance by reduction of tax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceTaxReduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allowance by reduction of tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetId name="AssetId">AssetId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BlockType name="BlockType">BlockType</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line type</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BudgetRevenueCode name="BudgetRevenueCode">BudgetRevenueCode</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetRevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CadastralCost name="CadastralCost">CadastralCost</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cadastral cost</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CadastralCost attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cadastral cost</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CadastralNumber name="CadastralNumber">CadastralNumber</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CadastralNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryID name="CategoryID">CategoryID</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangePeriod name="ChangePeriod">ChangePeriod</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost change period</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangePeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost change period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Corrected name="Corrected">Corrected</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Corrected</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Corrected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Corrected</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DesignAndBuildingPeriod name="DesignAndBuildingPeriod">DesignAndBuildingPeriod</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DesignAndBuildingPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExemptionAmount387 name="ExemptionAmount387">ExemptionAmount387</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allowance amount (art.387)</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExemptionAmount387 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allowance amount (art.387)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExemptionAmount395 name="ExemptionAmount395">ExemptionAmount395</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allowance amount (art.395)</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExemptionAmount395 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allowance amount (art.395)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FactorK1 name="FactorK1">FactorK1</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allowance factor</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactorK1 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allowance factor</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FactorK2 name="FactorK2">FactorK2</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ownership factor</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactorK2 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ownership factor</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GracePeriod name="GracePeriod">GracePeriod</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Grace period</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GracePeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Grace period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#JournalTransRefRecId name="JournalTransRefRecId">JournalTransRefRecId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalTransRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LandTaxExemption387 name="LandTaxExemption387">LandTaxExemption387</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Land tax exemption (art.387)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LandTaxExemption387 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Land tax exemption (art.387)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LandTaxExemption395 name="LandTaxExemption395">LandTaxExemption395</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Land tax exemption (art.395)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LandTaxExemption395 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Land tax exemption (art.395)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDescription name="LineDescription">LineDescription</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ManualInput name="ManualInput">ManualInput</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual data input</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualInput attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manual data input</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#NonTaxableAreaShare name="NonTaxableAreaShare">NonTaxableAreaShare</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Non-taxable area share</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonTaxableAreaShare attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Non-taxable area share</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OwnedShare name="OwnedShare">OwnedShare</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owned share</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OwnedShare attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owned share</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitAmount name="ProfitAmount">ProfitAmount</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RCOAD name="RCOAD">RCOAD</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RCOAD attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RTax25ProfitTable name="RTax25ProfitTable">RTax25ProfitTable</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SalesTaxCode name="SalesTaxCode">SalesTaxCode</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax name="Tax">Tax</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculated advance payment/Tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculated advance payment/Tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAllowanceAmount378 name="TaxAllowanceAmount378">TaxAllowanceAmount378</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax allowance amount (p. 2 of art.378)</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAllowanceAmount378 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax allowance amount (p. 2 of art.378)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advance payment amount/Tax amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance payment amount/Tax amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBase name="TaxBase">TaxBase</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax base</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax base</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxValue name="TaxValue">TaxValue</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax value</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FactorK3 name="FactorK3">FactorK3</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost change factor</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactorK3 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost change factor</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OwnershipPeriod name="OwnershipPeriod">OwnershipPeriod</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ownership period</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OwnershipPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ownership period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RefLineNumber name="RefLineNumber">RefLineNumber</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reference row</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefLineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reference row</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAuthority name="TaxAuthority">TaxAuthority</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAuthority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Location name="Location">Location</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Location attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Branch name="Branch">Branch</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Branch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

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

### <a href=#Relationship_LandTypeTable_WRelationshipId name="Relationship_LandTypeTable_WRelationshipId">Relationship_LandTypeTable_WRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

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

### <a href=#Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId name="Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId">Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.cdm.json/PaymentOrderBudgetReceiptClassTable_RU</a></td><td><a href="../../Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RAssetTableRelationshipId name="Relationship_RAssetTableRelationshipId">Relationship_RAssetTableRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RAsset/Main/RAssetTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Main/RAssetTable.cdm.json/RAssetTable</a></td><td><a href="../../RAsset/Main/RAssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RAssetTableAssetIdRelationshipId name="Relationship_RAssetTableAssetIdRelationshipId">Relationship_RAssetTableAssetIdRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RAssetTableAssetIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RAsset/Main/RAssetTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Main/RAssetTable.cdm.json/RAssetTable</a></td><td><a href="../../RAsset/Main/RAssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableRelationshipId name="Relationship_RTax25ProfitTableRelationshipId">Relationship_RTax25ProfitTableRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/RTax25ProfitTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25RegisterJournalTransRecIdRelationshipId name="Relationship_RTax25RegisterJournalTransRecIdRelationshipId">Relationship_RTax25RegisterJournalTransRecIdRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25RegisterJournalTransRecIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/RTax25RegisterJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/WorksheetLine/RTax25RegisterJournalTrans.cdm.json/RTax25RegisterJournalTrans</a></td><td><a href="../WorksheetLine/RTax25RegisterJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxTableRelationshipId name="Relationship_TaxTableRelationshipId">Relationship_TaxTableRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../../Tax/Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxAuthorityAddressRelationshipId name="Relationship_TaxAuthorityAddressRelationshipId">Relationship_TaxAuthorityAddressRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAuthorityAddressRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxAuthorityAddress.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxAuthorityAddress.cdm.json/TaxAuthorityAddress</a></td><td><a href="../../Tax/Group/TaxAuthorityAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_LandTaxCalc (this entity)  

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

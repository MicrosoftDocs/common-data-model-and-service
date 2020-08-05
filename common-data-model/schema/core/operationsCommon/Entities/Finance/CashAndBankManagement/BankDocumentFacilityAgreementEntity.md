---
title: BankDocumentFacilityAgreementEntity in CashAndBankManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Bank facility agreements in CashAndBankManagement(BankDocumentFacilityAgreementEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/CashAndBankManagement/BankDocumentFacilityAgreementEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank facility agreements</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FacilityTypeRecId](#FacilityTypeRecId)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[AgreementLine](#AgreementLine)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[AmountUsed](#AmountUsed)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[AmountLimit](#AmountLimit)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[AgreementNumber](#AgreementNumber)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[BankAccount](#BankAccount)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[StartDate](#StartDate)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[EndDate](#EndDate)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[FacilityType](#FacilityType)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGCashMarginAmount](#LGCashMarginAmount)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGCashMarginPercentage](#LGCashMarginPercentage)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGCashMarginCalcMethod](#LGCashMarginCalcMethod)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGDecreaseValueCommissionAmount](#LGDecreaseValueCommissionAmount)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGDecreaseValueCommissionCalcMethod](#LGDecreaseValueCommissionCalcMethod)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGDecreaseValueCommissionPercentage](#LGDecreaseValueCommissionPercentage)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGExtensionCommissionAmount](#LGExtensionCommissionAmount)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGExtensionCommissionCalcMethod](#LGExtensionCommissionCalcMethod)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGExtensionCommissionPercentage](#LGExtensionCommissionPercentage)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGIncreaseValueCommissionAmount](#LGIncreaseValueCommissionAmount)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGIncreaseValueCommissionPercentage](#LGIncreaseValueCommissionPercentage)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGIncreaseValueCommissionCalcMethod](#LGIncreaseValueCommissionCalcMethod)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGIssuanceCommissionAmount](#LGIssuanceCommissionAmount)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGIssuanceCommissionPercentage](#LGIssuanceCommissionPercentage)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[LGIssuanceCommissionCalcMethod](#LGIssuanceCommissionCalcMethod)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[BackingTable_BankDocumentFacilityAgreementRelationshipId](#BackingTable_BankDocumentFacilityAgreementRelationshipId)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BankDocumentFacilityAgreementEntity.md" target="_blank">CashAndBankManagement/BankDocumentFacilityAgreementEntity</a>|

### <a href=#FacilityTypeRecId name="FacilityTypeRecId">FacilityTypeRecId</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FacilityTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementLine name="AgreementLine">AgreementLine</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountUsed name="AmountUsed">AmountUsed</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount used</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount used</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountLimit name="AmountLimit">AmountLimit</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Limit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Limit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementNumber name="AgreementNumber">AgreementNumber</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccount name="BankAccount">BankAccount</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Start date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>End date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FacilityType name="FacilityType">FacilityType</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FacilityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGCashMarginAmount name="LGCashMarginAmount">LGCashMarginAmount</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGCashMarginAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGCashMarginPercentage name="LGCashMarginPercentage">LGCashMarginPercentage</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGCashMarginPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGCashMarginCalcMethod name="LGCashMarginCalcMethod">LGCashMarginCalcMethod</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGCashMarginCalcMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGDecreaseValueCommissionAmount name="LGDecreaseValueCommissionAmount">LGDecreaseValueCommissionAmount</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGDecreaseValueCommissionAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGDecreaseValueCommissionCalcMethod name="LGDecreaseValueCommissionCalcMethod">LGDecreaseValueCommissionCalcMethod</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGDecreaseValueCommissionCalcMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGDecreaseValueCommissionPercentage name="LGDecreaseValueCommissionPercentage">LGDecreaseValueCommissionPercentage</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGDecreaseValueCommissionPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGExtensionCommissionAmount name="LGExtensionCommissionAmount">LGExtensionCommissionAmount</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGExtensionCommissionAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGExtensionCommissionCalcMethod name="LGExtensionCommissionCalcMethod">LGExtensionCommissionCalcMethod</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGExtensionCommissionCalcMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGExtensionCommissionPercentage name="LGExtensionCommissionPercentage">LGExtensionCommissionPercentage</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGExtensionCommissionPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGIncreaseValueCommissionAmount name="LGIncreaseValueCommissionAmount">LGIncreaseValueCommissionAmount</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGIncreaseValueCommissionAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGIncreaseValueCommissionPercentage name="LGIncreaseValueCommissionPercentage">LGIncreaseValueCommissionPercentage</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGIncreaseValueCommissionPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGIncreaseValueCommissionCalcMethod name="LGIncreaseValueCommissionCalcMethod">LGIncreaseValueCommissionCalcMethod</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGIncreaseValueCommissionCalcMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGIssuanceCommissionAmount name="LGIssuanceCommissionAmount">LGIssuanceCommissionAmount</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGIssuanceCommissionAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGIssuanceCommissionPercentage name="LGIssuanceCommissionPercentage">LGIssuanceCommissionPercentage</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGIssuanceCommissionPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LGIssuanceCommissionCalcMethod name="LGIssuanceCommissionCalcMethod">LGIssuanceCommissionCalcMethod</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LGIssuanceCommissionCalcMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BankDocumentFacilityAgreementRelationshipId name="BackingTable_BankDocumentFacilityAgreementRelationshipId">BackingTable_BankDocumentFacilityAgreementRelationshipId</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BankDocumentFacilityAgreementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/WorksheetHeader/BankDocumentFacilityAgreement.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetHeader/BankDocumentFacilityAgreement.cdm.json/BankDocumentFacilityAgreement</a></td><td><a href="../../../Tables/Finance/Bank/WorksheetHeader/BankDocumentFacilityAgreement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: CashAndBankManagement/BankDocumentFacilityAgreementEntity (this entity)  

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

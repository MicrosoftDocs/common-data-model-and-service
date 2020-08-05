---
title: FBParametersPerState_BR in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Fiscal books parameters per state in Parameter(FBParametersPerState_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Parameter/FBParametersPerState_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBParametersPerState_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal books parameters per state</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[CIAPCalculateInstallmentForOutgoing](#CIAPCalculateInstallmentForOutgoing)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[CountryRegionId](#CountryRegionId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSAdjustmentByFiscalDocument](#ICMSAdjustmentByFiscalDocument)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSFBObservationCodeTable](#ICMSFBObservationCodeTable)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSFiscalDocumentAdjCodeFixedAsset](#ICMSFiscalDocumentAdjCodeFixedAsset)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSFiscalDocumentAdjustmentCode](#ICMSFiscalDocumentAdjustmentCode)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSGeneralAdjustmentCode](#ICMSGeneralAdjustmentCode)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSGeneralAdjustmentCodeFixedAsset](#ICMSGeneralAdjustmentCodeFixedAsset)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[StateId](#StateId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[GroupICMSDifPaymentByDocument](#GroupICMSDifPaymentByDocument)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[PresumedTaxAlgorithm](#PresumedTaxAlgorithm)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Block1900](#Block1900)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Consolidate1923ForOutgoing](#Consolidate1923ForOutgoing)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[FBSubTaxAssessment_BR](#FBSubTaxAssessment_BR)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[PresumedTaxAlgorithmSPED](#PresumedTaxAlgorithmSPED)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[SubTaxAssessmentDescription](#SubTaxAssessmentDescription)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[IsRetailCompany](#IsRetailCompany)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSGeneralAdjustmentCodeTaxableOutgoing](#ICMSGeneralAdjustmentCodeTaxableOutgoing)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSGeneralAdjustmentCodeTaxableIncoming](#ICMSGeneralAdjustmentCodeTaxableIncoming)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSGeneralAdjustmentCodeCreditReversal](#ICMSGeneralAdjustmentCodeCreditReversal)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSGeneralAdjustmentCodeCreditInventory](#ICMSGeneralAdjustmentCodeCreditInventory)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSGeneralAdjustmentCodeComplement](#ICMSGeneralAdjustmentCodeComplement)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSGeneralAdjustmentCodeRestitution](#ICMSGeneralAdjustmentCodeRestitution)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSGeneralAdjustmentCodeComplementE220](#ICMSGeneralAdjustmentCodeComplementE220)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[ICMSGeneralAdjustmentCodeRestitutionE111](#ICMSGeneralAdjustmentCodeRestitutionE111)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[EnableC180C185](#EnableC180C185)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[SubTaxAssesmentLedgerJournalNameId](#SubTaxAssesmentLedgerJournalNameId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[EnableDocumentAdjustment](#EnableDocumentAdjustment)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[TaxAdjustmentJournalName](#TaxAdjustmentJournalName)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId](#Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_FBGeneralAdjustmentCode_BRRelationshipId](#Relationship_FBGeneralAdjustmentCode_BRRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_FBObservationCodeTable_BRRelationshipId](#Relationship_FBObservationCodeTable_BRRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_ICMSFiscalDocumentAdjCodeFixedAssetRelationshipId](#Relationship_ICMSFiscalDocumentAdjCodeFixedAssetRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_ICMSGeneralAdjustmentCodeFixedAssetRelationshipId](#Relationship_ICMSGeneralAdjustmentCodeFixedAssetRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_LogisticsAddressStateRelationshipId](#Relationship_LogisticsAddressStateRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_ICMSGeneralAdjustmentCodeTaxableOutgoingRelationshipId](#Relationship_ICMSGeneralAdjustmentCodeTaxableOutgoingRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_ICMSGeneralAdjustmentCodeTaxableIncomingRelationshipId](#Relationship_ICMSGeneralAdjustmentCodeTaxableIncomingRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_ICMSGeneralAdjustmentCodeCreditReversalRelationshipId](#Relationship_ICMSGeneralAdjustmentCodeCreditReversalRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_ICMSGeneralAdjustmentCodeCreditInventoryRelationshipId](#Relationship_ICMSGeneralAdjustmentCodeCreditInventoryRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_ICMSGeneralAdjustmentCodeComplementRelationshipId](#Relationship_ICMSGeneralAdjustmentCodeComplementRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_ICMSGeneralAdjustmentCodeRestitutionRelationshipId](#Relationship_ICMSGeneralAdjustmentCodeRestitutionRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_ICMSGeneralAdjustmentCodeComplementE220RelationshipId](#Relationship_ICMSGeneralAdjustmentCodeComplementE220RelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_ICMSGeneralAdjustmentCodeRestitutionE111RelationshipId](#Relationship_ICMSGeneralAdjustmentCodeRestitutionE111RelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_SubTaxAssesmentLedgerJournalNameIdRelationshipId](#Relationship_SubTaxAssesmentLedgerJournalNameIdRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|
|[Relationship_LedgerJournalNameRelationshipId](#Relationship_LedgerJournalNameRelationshipId)||<a href="FBParametersPerState_BR.md" target="_blank">Parameter/FBParametersPerState_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBParametersPerState_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CIAPCalculateInstallmentForOutgoing name="CIAPCalculateInstallmentForOutgoing">CIAPCalculateInstallmentForOutgoing</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculate installment for outgoing transactions</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CIAPCalculateInstallmentForOutgoing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculate installment for outgoing transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ICMSAdjustmentByFiscalDocument name="ICMSAdjustmentByFiscalDocument">ICMSAdjustmentByFiscalDocument</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>By fiscal document</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSAdjustmentByFiscalDocument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>By fiscal document</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ICMSFBObservationCodeTable name="ICMSFBObservationCodeTable">ICMSFBObservationCodeTable</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Observation code</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSFBObservationCodeTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Observation code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSFiscalDocumentAdjCodeFixedAsset name="ICMSFiscalDocumentAdjCodeFixedAsset">ICMSFiscalDocumentAdjCodeFixedAsset</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment code for fixed asset</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSFiscalDocumentAdjCodeFixedAsset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Adjustment code for fixed asset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSFiscalDocumentAdjustmentCode name="ICMSFiscalDocumentAdjustmentCode">ICMSFiscalDocumentAdjustmentCode</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment code for item consumption</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSFiscalDocumentAdjustmentCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Adjustment code for item consumption</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSGeneralAdjustmentCode name="ICMSGeneralAdjustmentCode">ICMSGeneralAdjustmentCode</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment code for item consumption</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSGeneralAdjustmentCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Adjustment code for item consumption</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSGeneralAdjustmentCodeFixedAsset name="ICMSGeneralAdjustmentCodeFixedAsset">ICMSGeneralAdjustmentCodeFixedAsset</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment code for fixed asset</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSGeneralAdjustmentCodeFixedAsset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Adjustment code for fixed asset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#StateId name="StateId">StateId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupICMSDifPaymentByDocument name="GroupICMSDifPaymentByDocument">GroupICMSDifPaymentByDocument</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group ICMS-DIF payments by document</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupICMSDifPaymentByDocument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Group ICMS-DIF payments by document</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PresumedTaxAlgorithm name="PresumedTaxAlgorithm">PresumedTaxAlgorithm</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedTaxAlgorithm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Block1900 name="Block1900">Block1900</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Block 1900</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Block1900 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Block 1900</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Consolidate1923ForOutgoing name="Consolidate1923ForOutgoing">Consolidate1923ForOutgoing</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Consolidate record 1923</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Consolidate1923ForOutgoing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Consolidate record 1923</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FBSubTaxAssessment_BR name="FBSubTaxAssessment_BR">FBSubTaxAssessment_BR</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBSubTaxAssessment_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PresumedTaxAlgorithmSPED name="PresumedTaxAlgorithmSPED">PresumedTaxAlgorithmSPED</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SPED presumed tax calculation algorithm</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedTaxAlgorithmSPED attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>SPED presumed tax calculation algorithm</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SubTaxAssessmentDescription name="SubTaxAssessmentDescription">SubTaxAssessmentDescription</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sub tax assessment description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubTaxAssessmentDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sub tax assessment description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRetailCompany name="IsRetailCompany">IsRetailCompany</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retail company</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRetailCompany attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ICMSGeneralAdjustmentCodeTaxableOutgoing name="ICMSGeneralAdjustmentCodeTaxableOutgoing">ICMSGeneralAdjustmentCodeTaxableOutgoing</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Debit from outgoing fiscal document</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSGeneralAdjustmentCodeTaxableOutgoing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Debit from outgoing fiscal document</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSGeneralAdjustmentCodeTaxableIncoming name="ICMSGeneralAdjustmentCodeTaxableIncoming">ICMSGeneralAdjustmentCodeTaxableIncoming</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit from incoming fiscal document</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSGeneralAdjustmentCodeTaxableIncoming attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit from incoming fiscal document</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSGeneralAdjustmentCodeCreditReversal name="ICMSGeneralAdjustmentCodeCreditReversal">ICMSGeneralAdjustmentCodeCreditReversal</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit reversal</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSGeneralAdjustmentCodeCreditReversal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit reversal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSGeneralAdjustmentCodeCreditInventory name="ICMSGeneralAdjustmentCodeCreditInventory">ICMSGeneralAdjustmentCodeCreditInventory</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit of inventory</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSGeneralAdjustmentCodeCreditInventory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit of inventory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSGeneralAdjustmentCodeComplement name="ICMSGeneralAdjustmentCodeComplement">ICMSGeneralAdjustmentCodeComplement</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Complement (reverse)</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSGeneralAdjustmentCodeComplement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Complement (reverse)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSGeneralAdjustmentCodeRestitution name="ICMSGeneralAdjustmentCodeRestitution">ICMSGeneralAdjustmentCodeRestitution</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Restitution (reverse)</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSGeneralAdjustmentCodeRestitution attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Restitution (reverse)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSGeneralAdjustmentCodeComplementE220 name="ICMSGeneralAdjustmentCodeComplementE220">ICMSGeneralAdjustmentCodeComplementE220</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Complement (E210-E220)</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSGeneralAdjustmentCodeComplementE220 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Complement (E210-E220)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSGeneralAdjustmentCodeRestitutionE111 name="ICMSGeneralAdjustmentCodeRestitutionE111">ICMSGeneralAdjustmentCodeRestitutionE111</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Restitution (E111)</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSGeneralAdjustmentCodeRestitutionE111 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Restitution (E111)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EnableC180C185 name="EnableC180C185">EnableC180C185</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable record C180 and C185</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableC180C185 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enable record C180 and C185</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SubTaxAssesmentLedgerJournalNameId name="SubTaxAssesmentLedgerJournalNameId">SubTaxAssesmentLedgerJournalNameId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Journal name for restitution/complement adjustment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubTaxAssesmentLedgerJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Journal name for restitution/complement adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableDocumentAdjustment name="EnableDocumentAdjustment">EnableDocumentAdjustment</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document adjustment</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableDocumentAdjustment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxAdjustmentJournalName name="TaxAdjustmentJournalName">TaxAdjustmentJournalName</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Journal name for adjustments</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdjustmentJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Journal name for adjustments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId name="Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId">Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBFiscalDocumentAdjustmentCodeICMS_BR.cdm.json/FBFiscalDocumentAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBGeneralAdjustmentCode_BRRelationshipId name="Relationship_FBGeneralAdjustmentCode_BRRelationshipId">Relationship_FBGeneralAdjustmentCode_BRRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBGeneralAdjustmentCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCode_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCode_BR.cdm.json/FBGeneralAdjustmentCode_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCode_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBObservationCodeTable_BRRelationshipId name="Relationship_FBObservationCodeTable_BRRelationshipId">Relationship_FBObservationCodeTable_BRRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBObservationCodeTable_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBObservationCodeTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBObservationCodeTable_BR.cdm.json/FBObservationCodeTable_BR</a></td><td><a href="../Main/FBObservationCodeTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ICMSFiscalDocumentAdjCodeFixedAssetRelationshipId name="Relationship_ICMSFiscalDocumentAdjCodeFixedAssetRelationshipId">Relationship_ICMSFiscalDocumentAdjCodeFixedAssetRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ICMSFiscalDocumentAdjCodeFixedAssetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBFiscalDocumentAdjustmentCodeICMS_BR.cdm.json/FBFiscalDocumentAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ICMSGeneralAdjustmentCodeFixedAssetRelationshipId name="Relationship_ICMSGeneralAdjustmentCodeFixedAssetRelationshipId">Relationship_ICMSGeneralAdjustmentCodeFixedAssetRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ICMSGeneralAdjustmentCodeFixedAssetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsAddressStateRelationshipId name="Relationship_LogisticsAddressStateRelationshipId">Relationship_LogisticsAddressStateRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressStateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressState.cdm.json/LogisticsAddressState</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ICMSGeneralAdjustmentCodeTaxableOutgoingRelationshipId name="Relationship_ICMSGeneralAdjustmentCodeTaxableOutgoingRelationshipId">Relationship_ICMSGeneralAdjustmentCodeTaxableOutgoingRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ICMSGeneralAdjustmentCodeTaxableOutgoingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ICMSGeneralAdjustmentCodeTaxableIncomingRelationshipId name="Relationship_ICMSGeneralAdjustmentCodeTaxableIncomingRelationshipId">Relationship_ICMSGeneralAdjustmentCodeTaxableIncomingRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ICMSGeneralAdjustmentCodeTaxableIncomingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ICMSGeneralAdjustmentCodeCreditReversalRelationshipId name="Relationship_ICMSGeneralAdjustmentCodeCreditReversalRelationshipId">Relationship_ICMSGeneralAdjustmentCodeCreditReversalRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ICMSGeneralAdjustmentCodeCreditReversalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ICMSGeneralAdjustmentCodeCreditInventoryRelationshipId name="Relationship_ICMSGeneralAdjustmentCodeCreditInventoryRelationshipId">Relationship_ICMSGeneralAdjustmentCodeCreditInventoryRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ICMSGeneralAdjustmentCodeCreditInventoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ICMSGeneralAdjustmentCodeComplementRelationshipId name="Relationship_ICMSGeneralAdjustmentCodeComplementRelationshipId">Relationship_ICMSGeneralAdjustmentCodeComplementRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ICMSGeneralAdjustmentCodeComplementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ICMSGeneralAdjustmentCodeRestitutionRelationshipId name="Relationship_ICMSGeneralAdjustmentCodeRestitutionRelationshipId">Relationship_ICMSGeneralAdjustmentCodeRestitutionRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ICMSGeneralAdjustmentCodeRestitutionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ICMSGeneralAdjustmentCodeComplementE220RelationshipId name="Relationship_ICMSGeneralAdjustmentCodeComplementE220RelationshipId">Relationship_ICMSGeneralAdjustmentCodeComplementE220RelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ICMSGeneralAdjustmentCodeComplementE220RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ICMSGeneralAdjustmentCodeRestitutionE111RelationshipId name="Relationship_ICMSGeneralAdjustmentCodeRestitutionE111RelationshipId">Relationship_ICMSGeneralAdjustmentCodeRestitutionE111RelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ICMSGeneralAdjustmentCodeRestitutionE111RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SubTaxAssesmentLedgerJournalNameIdRelationshipId name="Relationship_SubTaxAssesmentLedgerJournalNameIdRelationshipId">Relationship_SubTaxAssesmentLedgerJournalNameIdRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SubTaxAssesmentLedgerJournalNameIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/LedgerJournalName.cdm.json/LedgerJournalName</a></td><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalNameRelationshipId name="Relationship_LedgerJournalNameRelationshipId">Relationship_LedgerJournalNameRelationshipId</a>

First included in: Parameter/FBParametersPerState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/LedgerJournalName.cdm.json/LedgerJournalName</a></td><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

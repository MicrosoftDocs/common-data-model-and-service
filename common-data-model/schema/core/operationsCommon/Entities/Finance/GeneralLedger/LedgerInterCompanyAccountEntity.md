---
title: LedgerInterCompanyAccountEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Intercompany accounting in GeneralLedger(LedgerInterCompanyAccountEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerInterCompanyAccountEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intercompany accounting</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[OriginatingLegalEntityId](#OriginatingLegalEntityId)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[DestinationLegalEntityId](#DestinationLegalEntityId)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[PostCashDiscount](#PostCashDiscount)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[PostCurrencyExchangeGainOrLoss](#PostCurrencyExchangeGainOrLoss)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[PostFine](#PostFine)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[PostInterest](#PostInterest)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[Journal](#Journal)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[OriginatingCreditAccount](#OriginatingCreditAccount)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[OriginatingDebitAccount](#OriginatingDebitAccount)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[OriginatingCreditAccountDisplayValue](#OriginatingCreditAccountDisplayValue)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[OriginatingDebitAccountDisplayValue](#OriginatingDebitAccountDisplayValue)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[DestinationCreditAccount](#DestinationCreditAccount)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[DestinationDebitAccount](#DestinationDebitAccount)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[DestinationCreditAccountDisplayValue](#DestinationCreditAccountDisplayValue)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[DestinationDebitAccountDisplayValue](#DestinationDebitAccountDisplayValue)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[VendorPaymentPostFine](#VendorPaymentPostFine)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[VendorPaymentPostFinancialInterest](#VendorPaymentPostFinancialInterest)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[Relationship_OriginatingCreditAccountCombinationRelationshipId](#Relationship_OriginatingCreditAccountCombinationRelationshipId)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[Relationship_OriginatingDebitAccountCombinationRelationshipId](#Relationship_OriginatingDebitAccountCombinationRelationshipId)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[Relationship_DestinationCreditAccountCombinationRelationshipId](#Relationship_DestinationCreditAccountCombinationRelationshipId)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[Relationship_DestinationDebitAccountCombinationRelationshipId](#Relationship_DestinationDebitAccountCombinationRelationshipId)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[Relationship_LedgerJournalNameEntityRelationshipId](#Relationship_LedgerJournalNameEntityRelationshipId)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|
|[BackingTable_LedgerInterCompanyRelationshipId](#BackingTable_LedgerInterCompanyRelationshipId)||<a href="LedgerInterCompanyAccountEntity.md" target="_blank">GeneralLedger/LedgerInterCompanyAccountEntity</a>|

### <a href=#OriginatingLegalEntityId name="OriginatingLegalEntityId">OriginatingLegalEntityId</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationLegalEntityId name="DestinationLegalEntityId">DestinationLegalEntityId</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostCashDiscount name="PostCashDiscount">PostCashDiscount</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post cash discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostCashDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Post cash discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostCurrencyExchangeGainOrLoss name="PostCurrencyExchangeGainOrLoss">PostCurrencyExchangeGainOrLoss</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post currency exchange gain or loss</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostCurrencyExchangeGainOrLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Post currency exchange gain or loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostFine name="PostFine">PostFine</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post fine</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostFine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Post fine</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostInterest name="PostInterest">PostInterest</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post interest</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostInterest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Post interest</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Journal name="Journal">Journal</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Journal</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Journal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatingCreditAccount name="OriginatingCreditAccount">OriginatingCreditAccount</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingCreditAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatingDebitAccount name="OriginatingDebitAccount">OriginatingDebitAccount</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Debit account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingDebitAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Debit account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatingCreditAccountDisplayValue name="OriginatingCreditAccountDisplayValue">OriginatingCreditAccountDisplayValue</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating company credit account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingCreditAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Originating company credit account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatingDebitAccountDisplayValue name="OriginatingDebitAccountDisplayValue">OriginatingDebitAccountDisplayValue</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating company debit account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingDebitAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Originating company debit account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationCreditAccount name="DestinationCreditAccount">DestinationCreditAccount</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationCreditAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationDebitAccount name="DestinationDebitAccount">DestinationDebitAccount</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Debit account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationDebitAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Debit account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationCreditAccountDisplayValue name="DestinationCreditAccountDisplayValue">DestinationCreditAccountDisplayValue</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Destination company credit account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationCreditAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Destination company credit account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationDebitAccountDisplayValue name="DestinationDebitAccountDisplayValue">DestinationDebitAccountDisplayValue</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Destination company debit account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationDebitAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Destination company debit account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPaymentPostFine name="VendorPaymentPostFine">VendorPaymentPostFine</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPaymentPostFine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPaymentPostFinancialInterest name="VendorPaymentPostFinancialInterest">VendorPaymentPostFinancialInterest</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPaymentPostFinancialInterest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginatingCreditAccountCombinationRelationshipId name="Relationship_OriginatingCreditAccountCombinationRelationshipId">Relationship_OriginatingCreditAccountCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginatingCreditAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OriginatingDebitAccountCombinationRelationshipId name="Relationship_OriginatingDebitAccountCombinationRelationshipId">Relationship_OriginatingDebitAccountCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginatingDebitAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DestinationCreditAccountCombinationRelationshipId name="Relationship_DestinationCreditAccountCombinationRelationshipId">Relationship_DestinationCreditAccountCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DestinationCreditAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DestinationDebitAccountCombinationRelationshipId name="Relationship_DestinationDebitAccountCombinationRelationshipId">Relationship_DestinationDebitAccountCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DestinationDebitAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerJournalNameEntityRelationshipId name="Relationship_LedgerJournalNameEntityRelationshipId">Relationship_LedgerJournalNameEntityRelationshipId</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalNameEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_LedgerInterCompanyRelationshipId name="BackingTable_LedgerInterCompanyRelationshipId">BackingTable_LedgerInterCompanyRelationshipId</a>

First included in: GeneralLedger/LedgerInterCompanyAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerInterCompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Group/LedgerInterCompany.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerInterCompany.cdm.json/LedgerInterCompany</a></td><td><a href="../../../Tables/Finance/Ledger/Group/LedgerInterCompany.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

---
title: VendBankAccount - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Vendor bank accounts

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendBankAccount.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendBankAccount/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor bank accounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[AccountID](#AccountID)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[AccountNum](#AccountNum)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[ActiveDate](#ActiveDate)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[BankAccountNameKana_JP](#BankAccountNameKana_JP)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[BankAccountType](#BankAccountType)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[BankCIN](#BankCIN)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[BankCodeType](#BankCodeType)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[BankConstantSymbol](#BankConstantSymbol)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[BankContractAccount](#BankContractAccount)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[BankGroupID](#BankGroupID)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[BankIBAN](#BankIBAN)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[CellularPhone](#CellularPhone)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[ContactPerson](#ContactPerson)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[CorrAccount_W](#CorrAccount_W)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[CorrespBank_EE](#CorrespBank_EE)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[CurrencyCode](#CurrencyCode)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[DirDunsNumber](#DirDunsNumber)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Email](#Email)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[ExchRate](#ExchRate)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[ExchRateRef](#ExchRateRef)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[ExpiryDate](#ExpiryDate)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[ForeignAccount_RU](#ForeignAccount_RU)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[ForeignBank_RU](#ForeignBank_RU)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[ForeignSWIFT_RU](#ForeignSWIFT_RU)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[IntermAccount_EE](#IntermAccount_EE)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[IntermBank_EE](#IntermBank_EE)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[IntermBankAccountId](#IntermBankAccountId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Location](#Location)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[LogisticsLocation](#LogisticsLocation)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[LvDefaultBank](#LvDefaultBank)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[MsgToBank](#MsgToBank)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Name](#Name)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Pager](#Pager)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Phone](#Phone)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[PhoneLocal](#PhoneLocal)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[RegistrationNum](#RegistrationNum)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[SMS](#SMS)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[SpecificSymbol](#SpecificSymbol)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[SWIFTNo](#SWIFTNo)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[TeleFax](#TeleFax)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Telex](#Telex)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[TransType_JP](#TransType_JP)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[URL](#URL)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[VendAccount](#VendAccount)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[VendDuns4Number](#VendDuns4Number)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[VendPaymentTextCode](#VendPaymentTextCode)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[FICreditorID_DK](#FICreditorID_DK)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[CorrespondentBankAccount_LT](#CorrespondentBankAccount_LT)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[CorrespondentBankAddress_LT](#CorrespondentBankAddress_LT)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[CorrespondentBankName_LT](#CorrespondentBankName_LT)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[CorrespondentBankSWIFT_LT](#CorrespondentBankSWIFT_LT)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[IntermediateBankAccount_LT](#IntermediateBankAccount_LT)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[IntermediateBankAddress_LT](#IntermediateBankAddress_LT)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[IntermediateBankName_LT](#IntermediateBankName_LT)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[IntermediateBankSWIFT_LT](#IntermediateBankSWIFT_LT)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[QRIBAN_CH](#QRIBAN_CH)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[SpecParameters_CH](#SpecParameters_CH)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[DataAreaId](#DataAreaId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_BankConstantSymbolRelationshipId](#Relationship_BankConstantSymbolRelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_BankGroupRelationshipId](#Relationship_BankGroupRelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_BankGroup_RURelationshipId](#Relationship_BankGroup_RURelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_BankGroupForeign_RURelationshipId](#Relationship_BankGroupForeign_RURelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_CorrespBank_EERelationshipId](#Relationship_CorrespBank_EERelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_DirDunsNumberRelationshipId](#Relationship_DirDunsNumberRelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_IntermBank_EERelationshipId](#Relationship_IntermBank_EERelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_Location_FKRelationshipId](#Relationship_Location_FKRelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_LogisticsLocationRelationshipId](#Relationship_LogisticsLocationRelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendBankAccount.md" target="_blank">Main/VendBankAccount</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendBankAccount/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountID name="AccountID">AccountID</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveDate name="ActiveDate">ActiveDate</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#BankAccountNameKana_JP name="BankAccountNameKana_JP">BankAccountNameKana_JP</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountNameKana_JP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountType name="BankAccountType">BankAccountType</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankCIN name="BankCIN">BankCIN</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCIN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankCodeType name="BankCodeType">BankCodeType</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCodeType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankConstantSymbol name="BankConstantSymbol">BankConstantSymbol</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Constant symbol</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankConstantSymbol attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Constant symbol</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankContractAccount name="BankContractAccount">BankContractAccount</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankContractAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankGroupID name="BankGroupID">BankGroupID</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankGroupID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankIBAN name="BankIBAN">BankIBAN</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankIBAN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CellularPhone name="CellularPhone">CellularPhone</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CellularPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPerson name="ContactPerson">ContactPerson</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPerson attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrAccount_W name="CorrAccount_W">CorrAccount_W</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrAccount_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrespBank_EE name="CorrespBank_EE">CorrespBank_EE</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Correspondence bank</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrespBank_EE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Correspondence bank</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Main/VendBankAccount (this entity)  

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

### <a href=#DirDunsNumber name="DirDunsNumber">DirDunsNumber</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirDunsNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRate name="ExchRate">ExchRate</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExchRateRef name="ExchRateRef">ExchRateRef</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpiryDate name="ExpiryDate">ExpiryDate</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpiryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ForeignAccount_RU name="ForeignAccount_RU">ForeignAccount_RU</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignAccount_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignBank_RU name="ForeignBank_RU">ForeignBank_RU</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignBank_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignSWIFT_RU name="ForeignSWIFT_RU">ForeignSWIFT_RU</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SWIFT</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignSWIFT_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>SWIFT</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntermAccount_EE name="IntermAccount_EE">IntermAccount_EE</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interim account</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntermAccount_EE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Interim account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntermBank_EE name="IntermBank_EE">IntermBank_EE</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interim bank</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntermBank_EE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Interim bank</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntermBankAccountId name="IntermBankAccountId">IntermBankAccountId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Intermediate bank account</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntermBankAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intermediate bank account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Location name="Location">Location</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Location attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LogisticsLocation name="LogisticsLocation">LogisticsLocation</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LvDefaultBank name="LvDefaultBank">LvDefaultBank</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LvDefaultBank attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MsgToBank name="MsgToBank">MsgToBank</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MsgToBank attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Pager name="Pager">Pager</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Pager attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Phone name="Phone">Phone</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Phone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneLocal name="PhoneLocal">PhoneLocal</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneLocal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationNum name="RegistrationNum">RegistrationNum</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SMS name="SMS">SMS</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SMS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecificSymbol name="SpecificSymbol">SpecificSymbol</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecificSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SWIFTNo name="SWIFTNo">SWIFTNo</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SWIFTNo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TeleFax name="TeleFax">TeleFax</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TeleFax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Telex name="Telex">Telex</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Telex attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransType_JP name="TransType_JP">TransType_JP</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransType_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#URL name="URL">URL</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the URL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendAccount name="VendAccount">VendAccount</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendDuns4Number name="VendDuns4Number">VendDuns4Number</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendDuns4Number attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendPaymentTextCode name="VendPaymentTextCode">VendPaymentTextCode</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPaymentTextCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FICreditorID_DK name="FICreditorID_DK">FICreditorID_DK</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FICreditorID_DK attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrespondentBankAccount_LT name="CorrespondentBankAccount_LT">CorrespondentBankAccount_LT</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrespondentBankAccount_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrespondentBankAddress_LT name="CorrespondentBankAddress_LT">CorrespondentBankAddress_LT</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrespondentBankAddress_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrespondentBankName_LT name="CorrespondentBankName_LT">CorrespondentBankName_LT</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrespondentBankName_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrespondentBankSWIFT_LT name="CorrespondentBankSWIFT_LT">CorrespondentBankSWIFT_LT</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrespondentBankSWIFT_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntermediateBankAccount_LT name="IntermediateBankAccount_LT">IntermediateBankAccount_LT</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntermediateBankAccount_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntermediateBankAddress_LT name="IntermediateBankAddress_LT">IntermediateBankAddress_LT</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntermediateBankAddress_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntermediateBankName_LT name="IntermediateBankName_LT">IntermediateBankName_LT</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntermediateBankName_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntermediateBankSWIFT_LT name="IntermediateBankSWIFT_LT">IntermediateBankSWIFT_LT</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntermediateBankSWIFT_LT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QRIBAN_CH name="QRIBAN_CH">QRIBAN_CH</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QRIBAN_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecParameters_CH name="SpecParameters_CH">SpecParameters_CH</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecParameters_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/VendBankAccount (this entity)  

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

### <a href=#Relationship_BankConstantSymbolRelationshipId name="Relationship_BankConstantSymbolRelationshipId">Relationship_BankConstantSymbolRelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankConstantSymbolRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Miscellaneous/BankConstantSymbol.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Miscellaneous/BankConstantSymbol.cdm.json/BankConstantSymbol</a></td><td><a href="../../../Finance/Bank/Miscellaneous/BankConstantSymbol.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankGroupRelationshipId name="Relationship_BankGroupRelationshipId">Relationship_BankGroupRelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/BankGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankGroup.cdm.json/BankGroup</a></td><td><a href="../../../Finance/Bank/Group/BankGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankGroup_RURelationshipId name="Relationship_BankGroup_RURelationshipId">Relationship_BankGroup_RURelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankGroup_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/BankGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankGroup.cdm.json/BankGroup</a></td><td><a href="../../../Finance/Bank/Group/BankGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankGroupForeign_RURelationshipId name="Relationship_BankGroupForeign_RURelationshipId">Relationship_BankGroupForeign_RURelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankGroupForeign_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/BankGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankGroup.cdm.json/BankGroup</a></td><td><a href="../../../Finance/Bank/Group/BankGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CorrespBank_EERelationshipId name="Relationship_CorrespBank_EERelationshipId">Relationship_CorrespBank_EERelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CorrespBank_EERelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/BankGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankGroup.cdm.json/BankGroup</a></td><td><a href="../../../Finance/Bank/Group/BankGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DirDunsNumberRelationshipId name="Relationship_DirDunsNumberRelationshipId">Relationship_DirDunsNumberRelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DirDunsNumberRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/DirDunsNumber.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/DirDunsNumber.cdm.json/DirDunsNumber</a></td><td><a href="../../../Common/GAB/Main/DirDunsNumber.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntermBank_EERelationshipId name="Relationship_IntermBank_EERelationshipId">Relationship_IntermBank_EERelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntermBank_EERelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/BankGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankGroup.cdm.json/BankGroup</a></td><td><a href="../../../Finance/Bank/Group/BankGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Location_FKRelationshipId name="Relationship_Location_FKRelationshipId">Relationship_Location_FKRelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Location_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsLocation.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsLocation.cdm.json/LogisticsLocation</a></td><td><a href="../../../Common/GAB/Main/LogisticsLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsLocationRelationshipId name="Relationship_LogisticsLocationRelationshipId">Relationship_LogisticsLocationRelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsLocation.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsLocation.cdm.json/LogisticsLocation</a></td><td><a href="../../../Common/GAB/Main/LogisticsLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/VendBankAccount (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

---
title: CustPaymModeTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# CustPaymModeTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Bank/Group/CustPaymModeTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustPaymModeTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[AccountType](#AccountType)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[BankClientDocumentTypeId_RU](#BankClientDocumentTypeId_RU)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[BankCustPaymIdTable](#BankCustPaymIdTable)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[BankTransType](#BankTransType)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ClassId](#ClassId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ClassIdFileAnalyze](#ClassIdFileAnalyze)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ClassIdIn](#ClassIdIn)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ClassIdRemittance](#ClassIdRemittance)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ClassIdReturn](#ClassIdReturn)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[DescPrimaryMethod_BR](#DescPrimaryMethod_BR)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[DimCtrl](#DimCtrl)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[DimensionAttributeSet](#DimensionAttributeSet)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[DimUse](#DimUse)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[DiscGraceDays](#DiscGraceDays)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ExportLayoutGroupId_BR](#ExportLayoutGroupId_BR)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ExportOnInvoice](#ExportOnInvoice)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[FurtherPosting](#FurtherPosting)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[InterCompanyLedgerDimension](#InterCompanyLedgerDimension)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[IsSEPA](#IsSEPA)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[LastSequenceNumber](#LastSequenceNumber)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[LastSequenceNumDate](#LastSequenceNumDate)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[LastSequenceNumToday](#LastSequenceNumToday)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Name](#Name)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[NumberSequenceTable_LT](#NumberSequenceTable_LT)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PaymentLedgerDimension](#PaymentLedgerDimension)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PaymentType](#PaymentType)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PaymJournalNameId](#PaymJournalNameId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PaymMode](#PaymMode)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PaymOnInvoice](#PaymOnInvoice)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PaymStatus](#PaymStatus)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PaymSumBy](#PaymSumBy)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PDCClearingPosting](#PDCClearingPosting)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PrimaryMethod_BR](#PrimaryMethod_BR)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ReturnLayoutGroupId_BR](#ReturnLayoutGroupId_BR)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[TypeOfDraft](#TypeOfDraft)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[UseCustomFormat_RU](#UseCustomFormat_RU)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PaymentType_MX](#PaymentType_MX)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ERFormatMappingID](#ERFormatMappingID)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[UseGERConfiguration](#UseGERConfiguration)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ERModelMappingTable](#ERModelMappingTable)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[UseGERImport](#UseGERImport)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[CategoryPurpose_W](#CategoryPurpose_W)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ChargeBearer_W](#ChargeBearer_W)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[LocalInstrument_W](#LocalInstrument_W)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[ServiceLevel_W](#ServiceLevel_W)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PaymentMethod_BR](#PaymentMethod_BR)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[DirectDebit](#DirectDebit)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[BankClientClassId_RU](#BankClientClassId_RU)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[SplitPayment_W](#SplitPayment_W)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PostingProfileBillsRemitDiscount_IT](#PostingProfileBillsRemitDiscount_IT)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[PostingProfileBillsRemitCollection_IT](#PostingProfileBillsRemitCollection_IT)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[DataAreaId](#DataAreaId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_BankClientDocumentType_RURelationshipId](#Relationship_BankClientDocumentType_RURelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_BankCustPaymIdTableRelationshipId](#Relationship_BankCustPaymIdTableRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_BankTransTypeRelationshipId](#Relationship_BankTransTypeRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_ConfLayoutGroups_BRRelationshipId](#Relationship_ConfLayoutGroups_BRRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_DimensionAttributeSetRelationshipId](#Relationship_DimensionAttributeSetRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_EPRemitOccCodes_BRRelationshipId](#Relationship_EPRemitOccCodes_BRRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_EPRetOccCodes_BRRelationshipId](#Relationship_EPRetOccCodes_BRRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_InterCompanyLedgerDimensionRelationshipId](#Relationship_InterCompanyLedgerDimensionRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_LedgerJournalNameRelationshipId](#Relationship_LedgerJournalNameRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_NumberSequenceTable_LTRelationshipId](#Relationship_NumberSequenceTable_LTRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_PaymentLedgerDimensionRelationshipId](#Relationship_PaymentLedgerDimensionRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_RCashRelationshipId](#Relationship_RCashRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId](#Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId](#Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId](#Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId](#Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustPaymModeTable.md" target="_blank">Group/CustPaymModeTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustPaymModeTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankClientDocumentTypeId_RU name="BankClientDocumentTypeId_RU">BankClientDocumentTypeId_RU</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankClientDocumentTypeId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankCustPaymIdTable name="BankCustPaymIdTable">BankCustPaymIdTable</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankCustPaymIdTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankTransType name="BankTransType">BankTransType</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankTransType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClassId name="ClassId">ClassId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClassIdFileAnalyze name="ClassIdFileAnalyze">ClassIdFileAnalyze</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassIdFileAnalyze attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClassIdIn name="ClassIdIn">ClassIdIn</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassIdIn attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClassIdRemittance name="ClassIdRemittance">ClassIdRemittance</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassIdRemittance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClassIdReturn name="ClassIdReturn">ClassIdReturn</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassIdReturn attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DescPrimaryMethod_BR name="DescPrimaryMethod_BR">DescPrimaryMethod_BR</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DescPrimaryMethod_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimCtrl name="DimCtrl">DimCtrl</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimCtrl attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DimensionAttributeSet name="DimensionAttributeSet">DimensionAttributeSet</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionAttributeSet attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DimUse name="DimUse">DimUse</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimUse attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DiscGraceDays name="DiscGraceDays">DiscGraceDays</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscGraceDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExportLayoutGroupId_BR name="ExportLayoutGroupId_BR">ExportLayoutGroupId_BR</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportLayoutGroupId_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportOnInvoice name="ExportOnInvoice">ExportOnInvoice</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportOnInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FurtherPosting name="FurtherPosting">FurtherPosting</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FurtherPosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InterCompanyLedgerDimension name="InterCompanyLedgerDimension">InterCompanyLedgerDimension</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterCompanyLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsSEPA name="IsSEPA">IsSEPA</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSEPA attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LastSequenceNumber name="LastSequenceNumber">LastSequenceNumber</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastSequenceNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LastSequenceNumDate name="LastSequenceNumDate">LastSequenceNumDate</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastSequenceNumDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#LastSequenceNumToday name="LastSequenceNumToday">LastSequenceNumToday</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastSequenceNumToday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Group/CustPaymModeTable (this entity)  

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

### <a href=#NumberSequenceTable_LT name="NumberSequenceTable_LT">NumberSequenceTable_LT</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceTable_LT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PaymentLedgerDimension name="PaymentLedgerDimension">PaymentLedgerDimension</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PaymentType name="PaymentType">PaymentType</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymJournalNameId name="PaymJournalNameId">PaymJournalNameId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymMode name="PaymMode">PaymMode</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymOnInvoice name="PaymOnInvoice">PaymOnInvoice</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymOnInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymStatus name="PaymStatus">PaymStatus</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymSumBy name="PaymSumBy">PaymSumBy</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymSumBy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PDCClearingPosting name="PDCClearingPosting">PDCClearingPosting</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PDCClearingPosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrimaryMethod_BR name="PrimaryMethod_BR">PrimaryMethod_BR</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryMethod_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReturnLayoutGroupId_BR name="ReturnLayoutGroupId_BR">ReturnLayoutGroupId_BR</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnLayoutGroupId_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeOfDraft name="TypeOfDraft">TypeOfDraft</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeOfDraft attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseCustomFormat_RU name="UseCustomFormat_RU">UseCustomFormat_RU</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseCustomFormat_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymentType_MX name="PaymentType_MX">PaymentType_MX</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentType_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ERFormatMappingID name="ERFormatMappingID">ERFormatMappingID</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UseGERConfiguration name="UseGERConfiguration">UseGERConfiguration</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseGERConfiguration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ERModelMappingTable name="ERModelMappingTable">ERModelMappingTable</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERModelMappingTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UseGERImport name="UseGERImport">UseGERImport</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseGERImport attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CategoryPurpose_W name="CategoryPurpose_W">CategoryPurpose_W</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryPurpose_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ChargeBearer_W name="ChargeBearer_W">ChargeBearer_W</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeBearer_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LocalInstrument_W name="LocalInstrument_W">LocalInstrument_W</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocalInstrument_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceLevel_W name="ServiceLevel_W">ServiceLevel_W</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLevel_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PaymentMethod_BR name="PaymentMethod_BR">PaymentMethod_BR</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentMethod_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DirectDebit name="DirectDebit">DirectDebit</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BankClientClassId_RU name="BankClientClassId_RU">BankClientClassId_RU</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankClientClassId_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SplitPayment_W name="SplitPayment_W">SplitPayment_W</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitPayment_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostingProfileBillsRemitDiscount_IT name="PostingProfileBillsRemitDiscount_IT">PostingProfileBillsRemitDiscount_IT</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileBillsRemitDiscount_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileBillsRemitCollection_IT name="PostingProfileBillsRemitCollection_IT">PostingProfileBillsRemitCollection_IT</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileBillsRemitCollection_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/CustPaymModeTable (this entity)  

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

### <a href=#Relationship_BankClientDocumentType_RURelationshipId name="Relationship_BankClientDocumentType_RURelationshipId">Relationship_BankClientDocumentType_RURelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankClientDocumentType_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankClientDocumentType_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankClientDocumentType_RU.cdm.json/BankClientDocumentType_RU</a></td><td><a href="BankClientDocumentType_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankCustPaymIdTableRelationshipId name="Relationship_BankCustPaymIdTableRelationshipId">Relationship_BankCustPaymIdTableRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankCustPaymIdTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/BankCustPaymIdTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/BankCustPaymIdTable.cdm.json/BankCustPaymIdTable</a></td><td><a href="../Main/BankCustPaymIdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankTransTypeRelationshipId name="Relationship_BankTransTypeRelationshipId">Relationship_BankTransTypeRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankTransTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankTransType.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankTransType.cdm.json/BankTransType</a></td><td><a href="BankTransType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ConfLayoutGroups_BRRelationshipId name="Relationship_ConfLayoutGroups_BRRelationshipId">Relationship_ConfLayoutGroups_BRRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConfLayoutGroups_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/ConfLayoutGroups_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Miscellaneous/ConfLayoutGroups_BR.cdm.json/ConfLayoutGroups_BR</a></td><td><a href="../Miscellaneous/ConfLayoutGroups_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeSetRelationshipId name="Relationship_DimensionAttributeSetRelationshipId">Relationship_DimensionAttributeSetRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Reference/DimensionAttributeSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Reference/DimensionAttributeSet.cdm.json/DimensionAttributeSet</a></td><td><a href="../../FinancialDimensions/Reference/DimensionAttributeSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EPRemitOccCodes_BRRelationshipId name="Relationship_EPRemitOccCodes_BRRelationshipId">Relationship_EPRemitOccCodes_BRRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EPRemitOccCodes_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/EPRemitOccCodes_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Miscellaneous/EPRemitOccCodes_BR.cdm.json/EPRemitOccCodes_BR</a></td><td><a href="../Miscellaneous/EPRemitOccCodes_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EPRetOccCodes_BRRelationshipId name="Relationship_EPRetOccCodes_BRRelationshipId">Relationship_EPRetOccCodes_BRRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EPRetOccCodes_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/EPRetOccCodes_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Miscellaneous/EPRetOccCodes_BR.cdm.json/EPRetOccCodes_BR</a></td><td><a href="../Miscellaneous/EPRetOccCodes_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InterCompanyLedgerDimensionRelationshipId name="Relationship_InterCompanyLedgerDimensionRelationshipId">Relationship_InterCompanyLedgerDimensionRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InterCompanyLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalNameRelationshipId name="Relationship_LedgerJournalNameRelationshipId">Relationship_LedgerJournalNameRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

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

### <a href=#Relationship_NumberSequenceTable_LTRelationshipId name="Relationship_NumberSequenceTable_LTRelationshipId">Relationship_NumberSequenceTable_LTRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceTable_LTRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentLedgerDimensionRelationshipId name="Relationship_PaymentLedgerDimensionRelationshipId">Relationship_PaymentLedgerDimensionRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RCashRelationshipId name="Relationship_RCashRelationshipId">Relationship_RCashRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RCashRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RCash/Main/RCashTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RCash/Main/RCashTable.cdm.json/RCashTable</a></td><td><a href="../../RCash/Main/RCashTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId name="Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId">Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId name="Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId">Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId name="Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId">Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId name="Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId">Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/CustPaymModeTable (this entity)  

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

---
title: VendorPaymentMethodEntity in AccountsPayable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Vendor payment method in AccountsPayable(VendorPaymentMethodEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsPayable/VendorPaymentMethodEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor payment method</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountType](#AccountType)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[AllowPaymentCopies](#AllowPaymentCopies)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[BankTransactionType](#BankTransactionType)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ExportFormatClassId](#ExportFormatClassId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[RemittanceFormatClassId](#RemittanceFormatClassId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ReturnFormatClassId](#ReturnFormatClassId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[DiscountGracePeriodDays](#DiscountGracePeriodDays)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ExportPromissoryNoteDuringInvoicePosting](#ExportPromissoryNoteDuringInvoicePosting)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[BridgingPostingEnabled](#BridgingPostingEnabled)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[BridgingPostingAccount](#BridgingPostingAccount)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[LastFileNumber](#LastFileNumber)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[LastFileDate](#LastFileDate)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[LastFileNumberToday](#LastFileNumberToday)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[Description](#Description)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[PaymentAccount](#PaymentAccount)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[PaymentType](#PaymentType)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[PaymentJournalName](#PaymentJournalName)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[Name](#Name)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[CreateAndDrawPromissoryNoteDuringInvoicePosting](#CreateAndDrawPromissoryNoteDuringInvoicePosting)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[PaymentStatus](#PaymentStatus)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[SumByPeriod](#SumByPeriod)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[EnablePostdatedCheckClearingPosting](#EnablePostdatedCheckClearingPosting)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[PromissoryNoteDraftType](#PromissoryNoteDraftType)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[BridgingPostingAccountDisplayValue](#BridgingPostingAccountDisplayValue)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[PaymentAccountDisplayValue](#PaymentAccountDisplayValue)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ValidateTransactionTypeIsBank](#ValidateTransactionTypeIsBank)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ValidateOffsetTransactionTypeIsBank](#ValidateOffsetTransactionTypeIsBank)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ValidateCheckNumberIsMandatory](#ValidateCheckNumberIsMandatory)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ValidatePaymentSpecificationIsMandatory](#ValidatePaymentSpecificationIsMandatory)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ValidatePaymentIdIsMandatory](#ValidatePaymentIdIsMandatory)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ValidatePaymentNoteIsMandatory](#ValidatePaymentNoteIsMandatory)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ValidatePaymentReferenceIsMandatory](#ValidatePaymentReferenceIsMandatory)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[AttributePaymentAccountEnabled](#AttributePaymentAccountEnabled)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[AttributeThirdPartyBankEnabled](#AttributeThirdPartyBankEnabled)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[AttributePaymentIdEnabled](#AttributePaymentIdEnabled)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[AttributeBelgianStructuredPaymentIdEnabled](#AttributeBelgianStructuredPaymentIdEnabled)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ExportFormatClassName](#ExportFormatClassName)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[RemittanceFormatClassName](#RemittanceFormatClassName)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ReturnFormatClassName](#ReturnFormatClassName)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[UseGERConfiguration](#UseGERConfiguration)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[SATPaymentType](#SATPaymentType)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ERFormatMapping](#ERFormatMapping)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ElectronicReportingSolution](#ElectronicReportingSolution)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ElectronicReportingVendor](#ElectronicReportingVendor)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[SPEDPrimaryPaymentMethodDescription](#SPEDPrimaryPaymentMethodDescription)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[SPEDPrimaryPaymentMethod](#SPEDPrimaryPaymentMethod)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[GeneratePaymentOneVoucher](#GeneratePaymentOneVoucher)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[DimensionControl](#DimensionControl)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[DimensionAttributeSet](#DimensionAttributeSet)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[DimensionAttributeDisplayValue](#DimensionAttributeDisplayValue)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ExportLayoutGroupId](#ExportLayoutGroupId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ReturnLayoutGroupId](#ReturnLayoutGroupId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[CategoryPurpose](#CategoryPurpose)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ChargeBearer](#ChargeBearer)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[LocalInstrument](#LocalInstrument)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ServiceLevel](#ServiceLevel)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[ChargeBearerValue](#ChargeBearerValue)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[DirectDebit](#DirectDebit)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[PostingProfileRemitNotes](#PostingProfileRemitNotes)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[Relationship_BridgingPostingAccountCombinationRelationshipId](#Relationship_BridgingPostingAccountCombinationRelationshipId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[Relationship_PaymentAccountCombinationRelationshipId](#Relationship_PaymentAccountCombinationRelationshipId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[Relationship_PaymentJournalNameRelationshipId](#Relationship_PaymentJournalNameRelationshipId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[Relationship_ExportFormatRelationshipId](#Relationship_ExportFormatRelationshipId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[Relationship_RemittanceFormatRelationshipId](#Relationship_RemittanceFormatRelationshipId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[Relationship_ReturnFormatRelationshipId](#Relationship_ReturnFormatRelationshipId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[BackingTable_VendPaymModeTableRelationshipId](#BackingTable_VendPaymModeTableRelationshipId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendorPaymentMethodEntity.md" target="_blank">AccountsPayable/VendorPaymentMethodEntity</a>|

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowPaymentCopies name="AllowPaymentCopies">AllowPaymentCopies</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowPaymentCopies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankTransactionType name="BankTransactionType">BankTransactionType</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportFormatClassId name="ExportFormatClassId">ExportFormatClassId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportFormatClassId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceFormatClassId name="RemittanceFormatClassId">RemittanceFormatClassId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceFormatClassId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnFormatClassId name="ReturnFormatClassId">ReturnFormatClassId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnFormatClassId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountGracePeriodDays name="DiscountGracePeriodDays">DiscountGracePeriodDays</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountGracePeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportPromissoryNoteDuringInvoicePosting name="ExportPromissoryNoteDuringInvoicePosting">ExportPromissoryNoteDuringInvoicePosting</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportPromissoryNoteDuringInvoicePosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BridgingPostingEnabled name="BridgingPostingEnabled">BridgingPostingEnabled</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BridgingPostingEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BridgingPostingAccount name="BridgingPostingAccount">BridgingPostingAccount</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BridgingPostingAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastFileNumber name="LastFileNumber">LastFileNumber</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastFileNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastFileDate name="LastFileDate">LastFileDate</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastFileDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastFileNumberToday name="LastFileNumberToday">LastFileNumberToday</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastFileNumberToday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentAccount name="PaymentAccount">PaymentAccount</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentType name="PaymentType">PaymentType</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentJournalName name="PaymentJournalName">PaymentJournalName</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateAndDrawPromissoryNoteDuringInvoicePosting name="CreateAndDrawPromissoryNoteDuringInvoicePosting">CreateAndDrawPromissoryNoteDuringInvoicePosting</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateAndDrawPromissoryNoteDuringInvoicePosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentStatus name="PaymentStatus">PaymentStatus</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumByPeriod name="SumByPeriod">SumByPeriod</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumByPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnablePostdatedCheckClearingPosting name="EnablePostdatedCheckClearingPosting">EnablePostdatedCheckClearingPosting</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnablePostdatedCheckClearingPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PromissoryNoteDraftType name="PromissoryNoteDraftType">PromissoryNoteDraftType</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromissoryNoteDraftType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BridgingPostingAccountDisplayValue name="BridgingPostingAccountDisplayValue">BridgingPostingAccountDisplayValue</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bridging account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BridgingPostingAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bridging account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentAccountDisplayValue name="PaymentAccountDisplayValue">PaymentAccountDisplayValue</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateTransactionTypeIsBank name="ValidateTransactionTypeIsBank">ValidateTransactionTypeIsBank</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bank transaction type is mandatory</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateTransactionTypeIsBank attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank transaction type is mandatory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateOffsetTransactionTypeIsBank name="ValidateOffsetTransactionTypeIsBank">ValidateOffsetTransactionTypeIsBank</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset account has the type bank</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateOffsetTransactionTypeIsBank attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset account has the type bank</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateCheckNumberIsMandatory name="ValidateCheckNumberIsMandatory">ValidateCheckNumberIsMandatory</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check number is mandatory</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateCheckNumberIsMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Check number is mandatory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidatePaymentSpecificationIsMandatory name="ValidatePaymentSpecificationIsMandatory">ValidatePaymentSpecificationIsMandatory</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment specification is mandatory</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatePaymentSpecificationIsMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment specification is mandatory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidatePaymentIdIsMandatory name="ValidatePaymentIdIsMandatory">ValidatePaymentIdIsMandatory</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment ID is mandatory</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatePaymentIdIsMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment ID is mandatory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidatePaymentNoteIsMandatory name="ValidatePaymentNoteIsMandatory">ValidatePaymentNoteIsMandatory</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment note is mandatory</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatePaymentNoteIsMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment note is mandatory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidatePaymentReferenceIsMandatory name="ValidatePaymentReferenceIsMandatory">ValidatePaymentReferenceIsMandatory</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment reference is mandatory</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatePaymentReferenceIsMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment reference is mandatory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributePaymentAccountEnabled name="AttributePaymentAccountEnabled">AttributePaymentAccountEnabled</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributePaymentAccountEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeThirdPartyBankEnabled name="AttributeThirdPartyBankEnabled">AttributeThirdPartyBankEnabled</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third-party bank</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeThirdPartyBankEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third-party bank</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributePaymentIdEnabled name="AttributePaymentIdEnabled">AttributePaymentIdEnabled</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributePaymentIdEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeBelgianStructuredPaymentIdEnabled name="AttributeBelgianStructuredPaymentIdEnabled">AttributeBelgianStructuredPaymentIdEnabled</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Belgian structured payment ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeBelgianStructuredPaymentIdEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Belgian structured payment ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportFormatClassName name="ExportFormatClassName">ExportFormatClassName</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Export format</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportFormatClassName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Export format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceFormatClassName name="RemittanceFormatClassName">RemittanceFormatClassName</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remittance format</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceFormatClassName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remittance format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnFormatClassName name="ReturnFormatClassName">ReturnFormatClassName</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Return format</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnFormatClassName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Return format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseGERConfiguration name="UseGERConfiguration">UseGERConfiguration</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseGERConfiguration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SATPaymentType name="SATPaymentType">SATPaymentType</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SATPaymentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERFormatMapping name="ERFormatMapping">ERFormatMapping</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMapping attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicReportingSolution name="ElectronicReportingSolution">ElectronicReportingSolution</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Configuration</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicReportingSolution attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Configuration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicReportingVendor name="ElectronicReportingVendor">ElectronicReportingVendor</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Configuration provider</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicReportingVendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Configuration provider</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SPEDPrimaryPaymentMethodDescription name="SPEDPrimaryPaymentMethodDescription">SPEDPrimaryPaymentMethodDescription</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDPrimaryPaymentMethodDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SPEDPrimaryPaymentMethod name="SPEDPrimaryPaymentMethod">SPEDPrimaryPaymentMethod</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDPrimaryPaymentMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneratePaymentOneVoucher name="GeneratePaymentOneVoucher">GeneratePaymentOneVoucher</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneratePaymentOneVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionControl name="DimensionControl">DimensionControl</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionAttributeSet name="DimensionAttributeSet">DimensionAttributeSet</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionAttributeSet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionAttributeDisplayValue name="DimensionAttributeDisplayValue">DimensionAttributeDisplayValue</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionAttributeDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportLayoutGroupId name="ExportLayoutGroupId">ExportLayoutGroupId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportLayoutGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnLayoutGroupId name="ReturnLayoutGroupId">ReturnLayoutGroupId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnLayoutGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryPurpose name="CategoryPurpose">CategoryPurpose</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeBearer name="ChargeBearer">ChargeBearer</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeBearer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocalInstrument name="LocalInstrument">LocalInstrument</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocalInstrument attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceLevel name="ServiceLevel">ServiceLevel</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeBearerValue name="ChargeBearerValue">ChargeBearerValue</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeBearerValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebit name="DirectDebit">DirectDebit</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileRemitNotes name="PostingProfileRemitNotes">PostingProfileRemitNotes</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileRemitNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BridgingPostingAccountCombinationRelationshipId name="Relationship_BridgingPostingAccountCombinationRelationshipId">Relationship_BridgingPostingAccountCombinationRelationshipId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BridgingPostingAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymentAccountCombinationRelationshipId name="Relationship_PaymentAccountCombinationRelationshipId">Relationship_PaymentAccountCombinationRelationshipId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymentJournalNameRelationshipId name="Relationship_PaymentJournalNameRelationshipId">Relationship_PaymentJournalNameRelationshipId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ExportFormatRelationshipId name="Relationship_ExportFormatRelationshipId">Relationship_ExportFormatRelationshipId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExportFormatRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RemittanceFormatRelationshipId name="Relationship_RemittanceFormatRelationshipId">Relationship_RemittanceFormatRelationshipId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RemittanceFormatRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReturnFormatRelationshipId name="Relationship_ReturnFormatRelationshipId">Relationship_ReturnFormatRelationshipId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReturnFormatRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_VendPaymModeTableRelationshipId name="BackingTable_VendPaymModeTableRelationshipId">BackingTable_VendPaymModeTableRelationshipId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendPaymModeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Group/VendPaymModeTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/VendPaymModeTable.cdm.json/VendPaymModeTable</a></td><td><a href="../../../Tables/Finance/Bank/Group/VendPaymModeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsPayable/VendorPaymentMethodEntity (this entity)  

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

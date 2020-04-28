---
title: ProjFundingSourceEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Project funding source

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjFundingSourceEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project funding source</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CashDiscount](#CashDiscount)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[ContactID](#ContactID)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[ProjectContractID](#ProjectContractID)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[CustomerOrOrganization](#CustomerOrOrganization)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[CustomerRequisition](#CustomerRequisition)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[CustomerReference](#CustomerReference)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[Dimension](#Dimension)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[DimensionAccount](#DimensionAccount)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[EInvoiceLineSpec](#EInvoiceLineSpec)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[FundingSourceId](#FundingSourceId)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[FundingType](#FundingType)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AssociatedPaymentAttachmentOnTheProjectInvoice](#AssociatedPaymentAttachmentOnTheProjectInvoice)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[IndividualBufferDays](#IndividualBufferDays)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[InvoiceName](#InvoiceName)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[Language](#Language)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[NumberSequenceGroup](#NumberSequenceGroup)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[Name](#Name)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[PaymentSchedule](#PaymentSchedule)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[TermsOfPayment](#TermsOfPayment)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[PostingProfile](#PostingProfile)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[ProjectGrant](#ProjectGrant)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[CustomerPaymentRetentionTerms](#CustomerPaymentRetentionTerms)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[InvoiceFormat](#InvoiceFormat)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[VATReportDateCode](#VATReportDateCode)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[PartyNumber](#PartyNumber)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[GrantId](#GrantId)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[RetentionTermId](#RetentionTermId)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[DimensionDisplayValue](#DimensionDisplayValue)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressTimeZone](#AddressTimeZone)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressDescription](#AddressDescription)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressCountry](#AddressCountry)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressCountryISOCode](#AddressCountryISOCode)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressState](#AddressState)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressCounty](#AddressCounty)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressCity](#AddressCity)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressStreet](#AddressStreet)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressZipCode](#AddressZipCode)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressDistrictName](#AddressDistrictName)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressLatitude](#AddressLatitude)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressLongitude](#AddressLongitude)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressValidTo](#AddressValidTo)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[AddressValidFrom](#AddressValidFrom)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[InvoiceLocationId](#InvoiceLocationId)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[InvoiceLocation](#InvoiceLocation)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[CreateDefaultFundingRule](#CreateDefaultFundingRule)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[IsPrimaryFundingSource](#IsPrimaryFundingSource)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[Relationship_DimensionDimensionSetRelationshipId](#Relationship_DimensionDimensionSetRelationshipId)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[BackingTable_ProjFundingSourceRelationshipId](#BackingTable_ProjFundingSourceRelationshipId)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjFundingSourceEntity.md" target="_blank">ProjectManagementAndAccounting/ProjFundingSourceEntity</a>|

### <a href=#CashDiscount name="CashDiscount">CashDiscount</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactID name="ContactID">ContactID</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectContractID name="ProjectContractID">ProjectContractID</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectContractID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerOrOrganization name="CustomerOrOrganization">CustomerOrOrganization</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerOrOrganization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRequisition name="CustomerRequisition">CustomerRequisition</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRequisition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerReference name="CustomerReference">CustomerReference</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension name="Dimension">Dimension</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionAccount name="DimensionAccount">DimensionAccount</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EInvoiceLineSpec name="EInvoiceLineSpec">EInvoiceLineSpec</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EInvoiceLineSpec attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FundingSourceId name="FundingSourceId">FundingSourceId</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundingSourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FundingType name="FundingType">FundingType</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssociatedPaymentAttachmentOnTheProjectInvoice name="AssociatedPaymentAttachmentOnTheProjectInvoice">AssociatedPaymentAttachmentOnTheProjectInvoice</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociatedPaymentAttachmentOnTheProjectInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndividualBufferDays name="IndividualBufferDays">IndividualBufferDays</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndividualBufferDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceName name="InvoiceName">InvoiceName</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Language name="Language">Language</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Language attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroup name="NumberSequenceGroup">NumberSequenceGroup</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

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

### <a href=#PaymentSchedule name="PaymentSchedule">PaymentSchedule</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TermsOfPayment name="TermsOfPayment">TermsOfPayment</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TermsOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectGrant name="ProjectGrant">ProjectGrant</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectGrant attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentRetentionTerms name="CustomerPaymentRetentionTerms">CustomerPaymentRetentionTerms</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentRetentionTerms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceFormat name="InvoiceFormat">InvoiceFormat</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATReportDateCode name="VATReportDateCode">VATReportDateCode</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATReportDateCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantId name="GrantId">GrantId</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetentionTermId name="RetentionTermId">RetentionTermId</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetentionTermId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionDisplayValue name="DimensionDisplayValue">DimensionDisplayValue</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressTimeZone name="AddressTimeZone">AddressTimeZone</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDescription name="AddressDescription">AddressDescription</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountry name="AddressCountry">AddressCountry</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountryISOCode name="AddressCountryISOCode">AddressCountryISOCode</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressState name="AddressState">AddressState</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCounty name="AddressCounty">AddressCounty</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCity name="AddressCity">AddressCity</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreet name="AddressStreet">AddressStreet</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressZipCode name="AddressZipCode">AddressZipCode</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDistrictName name="AddressDistrictName">AddressDistrictName</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLatitude name="AddressLatitude">AddressLatitude</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLongitude name="AddressLongitude">AddressLongitude</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidTo name="AddressValidTo">AddressValidTo</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidFrom name="AddressValidFrom">AddressValidFrom</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceLocationId name="InvoiceLocationId">InvoiceLocationId</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceLocation name="InvoiceLocation">InvoiceLocation</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateDefaultFundingRule name="CreateDefaultFundingRule">CreateDefaultFundingRule</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Create default funding rule</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateDefaultFundingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Create default funding rule</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryFundingSource name="IsPrimaryFundingSource">IsPrimaryFundingSource</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is primary funding source</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryFundingSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is primary funding source</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDimensionSetRelationshipId name="Relationship_DimensionDimensionSetRelationshipId">Relationship_DimensionDimensionSetRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_ProjFundingSourceRelationshipId name="BackingTable_ProjFundingSourceRelationshipId">BackingTable_ProjFundingSourceRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjFundingSourceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjFundingSource.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjFundingSource.cdm.json/ProjFundingSource</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjFundingSource.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjFundingSourceEntity (this entity)  

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

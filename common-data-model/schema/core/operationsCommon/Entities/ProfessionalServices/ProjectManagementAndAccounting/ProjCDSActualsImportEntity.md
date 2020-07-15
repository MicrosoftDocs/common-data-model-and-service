---
title: ProjCDSActualsImportEntity in ProjectManagementAndAccounting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Integration entity for project actuals in ProjectManagementAndAccounting(ProjCDSActualsImportEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjCDSActualsImportEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Integration entity for project actuals</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountingDate](#AccountingDate)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ActualId](#ActualId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ActualsImportId](#ActualsImportId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[AdjustmentStatus](#AdjustmentStatus)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[Amount](#Amount)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[AmountMST](#AmountMST)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[BillingStatusId](#BillingStatusId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[BillingType](#BillingType)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ContractId](#ContractId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ContractLine](#ContractLine)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ContractingUnit](#ContractingUnit)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[Description](#Description)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[DocumentDate](#DocumentDate)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[EndDate](#EndDate)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ExchangeRateDate](#ExchangeRateDate)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ExternalDescription](#ExternalDescription)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ExternalReference](#ExternalReference)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[InvoiceId](#InvoiceId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[IsJournalized](#IsJournalized)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[OwningBusinessId](#OwningBusinessId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[OwningUser](#OwningUser)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ProjectId](#ProjectId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[Quantity](#Quantity)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[Status](#Status)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[StatusReason](#StatusReason)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[StartDate](#StartDate)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[TaskId](#TaskId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[TransactionClassification](#TransactionClassification)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[TransactionCategory](#TransactionCategory)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[TransactionCurrencyId](#TransactionCurrencyId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[UnitOfMeasure](#UnitOfMeasure)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[TransType](#TransType)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[UnitPrice](#UnitPrice)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[UnitPriceMST](#UnitPriceMST)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ResourceId](#ResourceId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ResourceOperationUnitId](#ResourceOperationUnitId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[Voucher](#Voucher)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[ProjectDataAreaId](#ProjectDataAreaId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[IsDuplicate](#IsDuplicate)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[BackingTable_ProjCDSActualsImportRelationshipId](#BackingTable_ProjCDSActualsImportRelationshipId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjCDSActualsImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSActualsImportEntity</a>|

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

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

### <a href=#ActualId name="ActualId">ActualId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualsImportId name="ActualsImportId">ActualsImportId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualsImportId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdjustmentStatus name="AdjustmentStatus">AdjustmentStatus</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountMST name="AmountMST">AmountMST</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountMST attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingStatusId name="BillingStatusId">BillingStatusId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingType name="BillingType">BillingType</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContractId name="ContractId">ContractId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContractId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContractLine name="ContractLine">ContractLine</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContractLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContractingUnit name="ContractingUnit">ContractingUnit</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContractingUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

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

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateDate name="ExchangeRateDate">ExchangeRateDate</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalDescription name="ExternalDescription">ExternalDescription</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalReference name="ExternalReference">ExternalReference</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJournalized name="IsJournalized">IsJournalized</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJournalized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OwningBusinessId name="OwningBusinessId">OwningBusinessId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OwningBusinessId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OwningUser name="OwningUser">OwningUser</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OwningUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatusReason name="StatusReason">StatusReason</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatusReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaskId name="TaskId">TaskId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaskId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionClassification name="TransactionClassification">TransactionClassification</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionClassification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCategory name="TransactionCategory">TransactionCategory</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyId name="TransactionCurrencyId">TransactionCurrencyId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitOfMeasure name="UnitOfMeasure">UnitOfMeasure</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransType name="TransType">TransType</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitPrice name="UnitPrice">UnitPrice</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitPriceMST name="UnitPriceMST">UnitPriceMST</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPriceMST attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceId name="ResourceId">ResourceId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceOperationUnitId name="ResourceOperationUnitId">ResourceOperationUnitId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceOperationUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

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

### <a href=#ProjectDataAreaId name="ProjectDataAreaId">ProjectDataAreaId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDuplicate name="IsDuplicate">IsDuplicate</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDuplicate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProjCDSActualsImportRelationshipId name="BackingTable_ProjCDSActualsImportRelationshipId">BackingTable_ProjCDSActualsImportRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjCDSActualsImportRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ProjCDSActualsImport.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ProjCDSActualsImport.cdm.json/ProjCDSActualsImport</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ProjCDSActualsImport.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjCDSActualsImportEntity (this entity)  

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

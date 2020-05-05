---
title: VendInvoiceInfoTable_W - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Vendor invoice information for various geographies

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/TransactionHeader/VendInvoiceInfoTable_W.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendInvoiceInfoTable_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor invoice information for various geographies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[AccessKey_BR](#AccessKey_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[CFPSId_BR](#CFPSId_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[ConsignmentNoteNum_IN](#ConsignmentNoteNum_IN)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[ConsTarget_JP](#ConsTarget_JP)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[CustomsBillOfEntryNumberTable_IN](#CustomsBillOfEntryNumberTable_IN)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[CustomsImportInvoiceNumberTable_IN](#CustomsImportInvoiceNumberTable_IN)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[ElectronicInvoice_BR](#ElectronicInvoice_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[EmplAccount_RU](#EmplAccount_RU)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[FiscalDocumentModel_BR](#FiscalDocumentModel_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[FiscalDocumentSeries_BR](#FiscalDocumentSeries_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[FiscalDocumentSpecie_BR](#FiscalDocumentSpecie_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[FiscalDocumentType_BR](#FiscalDocumentType_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[ImportDeclaration_BR](#ImportDeclaration_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[IntrastatFulfillmentDate_HU](#IntrastatFulfillmentDate_HU)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[PackingSlipIdForUpdate_W](#PackingSlipIdForUpdate_W)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[PurchReceiptDate_W](#PurchReceiptDate_W)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[ReasonTableRef_BR](#ReasonTableRef_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[SalesPurchOperationType_BR](#SalesPurchOperationType_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[ServiceCodeOnDlvAddress_BR](#ServiceCodeOnDlvAddress_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[TaxInformation_IN](#TaxInformation_IN)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[TaxPeriodPaymentCode_PL](#TaxPeriodPaymentCode_PL)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[TypeOfCTe_BR](#TypeOfCTe_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[UseStateInvoice_LV](#UseStateInvoice_LV)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[VatDueDate_W](#VatDueDate_W)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[VendFinalUser_BR](#VendFinalUser_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[VendFineSetup_BR](#VendFineSetup_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[VendInterestSetup_BR](#VendInterestSetup_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[VendInvoiceInfoTable](#VendInvoiceInfoTable)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[BOLCarrierName_BR](#BOLCarrierName_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[BOLFreightedBy_BR](#BOLFreightedBy_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[DlvFreightType_BR](#DlvFreightType_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[DlvNoOfCarrier_BR](#DlvNoOfCarrier_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[DlvPackingName_BR](#DlvPackingName_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[DlvStateRegistered_BR](#DlvStateRegistered_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[DlvTransportBrand_BR](#DlvTransportBrand_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[InvoiceType_MY](#InvoiceType_MY)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[PresenceType_BR](#PresenceType_BR)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[TaxGSTImportDeclarationNo_MY](#TaxGSTImportDeclarationNo_MY)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[CFDIUUID_MX](#CFDIUUID_MX)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[InvoiceSeries_MX](#InvoiceSeries_MX)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[DocAutoNumbering_LT](#DocAutoNumbering_LT)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[DataAreaId](#DataAreaId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_CustomsBillOfEntryNumberTable_INRelationshipId](#Relationship_CustomsBillOfEntryNumberTable_INRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_CustomsImportInvoiceNumberTable_INRelationshipId](#Relationship_CustomsImportInvoiceNumberTable_INRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_EmployeeTable_RURelationshipId](#Relationship_EmployeeTable_RURelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_FiscalDocModel_BRRelationshipId](#Relationship_FiscalDocModel_BRRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_FiscalDocumentType_BRRelationshipId](#Relationship_FiscalDocumentType_BRRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_PlTaxDueTableRelationshipId](#Relationship_PlTaxDueTableRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_PurchImportDeclaration_BRRelationshipId](#Relationship_PurchImportDeclaration_BRRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_ReasonTableRefRelationshipId](#Relationship_ReasonTableRefRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_SalesPurchOperationType_BRRelationshipId](#Relationship_SalesPurchOperationType_BRRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_TaxInformation_INRelationshipId](#Relationship_TaxInformation_INRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_VendFineCode_BRRelationshipId](#Relationship_VendFineCode_BRRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_VendInterestCode_BRRelationshipId](#Relationship_VendInterestCode_BRRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_VendInvoiceInfoTableRelationshipId](#Relationship_VendInvoiceInfoTableRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_SalesCarrier_BRRelationshipId](#Relationship_SalesCarrier_BRRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendInvoiceInfoTable_W.md" target="_blank">TransactionHeader/VendInvoiceInfoTable_W</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendInvoiceInfoTable_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccessKey_BR name="AccessKey_BR">AccessKey_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccessKey_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFPSId_BR name="CFPSId_BR">CFPSId_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFPSId_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsignmentNoteNum_IN name="ConsignmentNoteNum_IN">ConsignmentNoteNum_IN</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsignmentNoteNum_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsTarget_JP name="ConsTarget_JP">ConsTarget_JP</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsTarget_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustomsBillOfEntryNumberTable_IN name="CustomsBillOfEntryNumberTable_IN">CustomsBillOfEntryNumberTable_IN</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill of entry</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsBillOfEntryNumberTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bill of entry</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomsImportInvoiceNumberTable_IN name="CustomsImportInvoiceNumberTable_IN">CustomsImportInvoiceNumberTable_IN</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import invoice number</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsImportInvoiceNumberTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import invoice number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ElectronicInvoice_BR name="ElectronicInvoice_BR">ElectronicInvoice_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicInvoice_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EmplAccount_RU name="EmplAccount_RU">EmplAccount_RU</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplAccount_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentModel_BR name="FiscalDocumentModel_BR">FiscalDocumentModel_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentModel_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSeries_BR name="FiscalDocumentSeries_BR">FiscalDocumentSeries_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSeries_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSpecie_BR name="FiscalDocumentSpecie_BR">FiscalDocumentSpecie_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSpecie_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FiscalDocumentType_BR name="FiscalDocumentType_BR">FiscalDocumentType_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal document type</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal document type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ImportDeclaration_BR name="ImportDeclaration_BR">ImportDeclaration_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImportDeclaration_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IntrastatFulfillmentDate_HU name="IntrastatFulfillmentDate_HU">IntrastatFulfillmentDate_HU</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatFulfillmentDate_HU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#PackingSlipIdForUpdate_W name="PackingSlipIdForUpdate_W">PackingSlipIdForUpdate_W</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipIdForUpdate_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchReceiptDate_W name="PurchReceiptDate_W">PurchReceiptDate_W</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchReceiptDate_W attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ReasonTableRef_BR name="ReasonTableRef_BR">ReasonTableRef_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonTableRef_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SalesPurchOperationType_BR name="SalesPurchOperationType_BR">SalesPurchOperationType_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPurchOperationType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCodeOnDlvAddress_BR name="ServiceCodeOnDlvAddress_BR">ServiceCodeOnDlvAddress_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCodeOnDlvAddress_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxInformation_IN name="TaxInformation_IN">TaxInformation_IN</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInformation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxPeriodPaymentCode_PL name="TaxPeriodPaymentCode_PL">TaxPeriodPaymentCode_PL</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPeriodPaymentCode_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeOfCTe_BR name="TypeOfCTe_BR">TypeOfCTe_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeOfCTe_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UseStateInvoice_LV name="UseStateInvoice_LV">UseStateInvoice_LV</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State invoice</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseStateInvoice_LV attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>State invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#VatDueDate_W name="VatDueDate_W">VatDueDate_W</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VatDueDate_W attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#VendFinalUser_BR name="VendFinalUser_BR">VendFinalUser_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use and consumption</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendFinalUser_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use and consumption</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#VendFineSetup_BR name="VendFineSetup_BR">VendFineSetup_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendFineSetup_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendInterestSetup_BR name="VendInterestSetup_BR">VendInterestSetup_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInterestSetup_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendInvoiceInfoTable name="VendInvoiceInfoTable">VendInvoiceInfoTable</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceInfoTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BOLCarrierName_BR name="BOLCarrierName_BR">BOLCarrierName_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLCarrierName_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLFreightedBy_BR name="BOLFreightedBy_BR">BOLFreightedBy_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLFreightedBy_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DlvFreightType_BR name="DlvFreightType_BR">DlvFreightType_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvFreightType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DlvNoOfCarrier_BR name="DlvNoOfCarrier_BR">DlvNoOfCarrier_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvNoOfCarrier_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DlvPackingName_BR name="DlvPackingName_BR">DlvPackingName_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvPackingName_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DlvStateRegistered_BR name="DlvStateRegistered_BR">DlvStateRegistered_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvStateRegistered_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DlvTransportBrand_BR name="DlvTransportBrand_BR">DlvTransportBrand_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvTransportBrand_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceType_MY name="InvoiceType_MY">InvoiceType_MY</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceType_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PresenceType_BR name="PresenceType_BR">PresenceType_BR</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresenceType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxGSTImportDeclarationNo_MY name="TaxGSTImportDeclarationNo_MY">TaxGSTImportDeclarationNo_MY</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGSTImportDeclarationNo_MY attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDIUUID_MX name="CFDIUUID_MX">CFDIUUID_MX</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIUUID_MX attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceSeries_MX name="InvoiceSeries_MX">InvoiceSeries_MX</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceSeries_MX attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocAutoNumbering_LT name="DocAutoNumbering_LT">DocAutoNumbering_LT</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocAutoNumbering_LT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

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

### <a href=#Relationship_CustomsBillOfEntryNumberTable_INRelationshipId name="Relationship_CustomsBillOfEntryNumberTable_INRelationshipId">Relationship_CustomsBillOfEntryNumberTable_INRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomsBillOfEntryNumberTable_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Main/CustomsBillOfEntryNumberTable_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/CustomsBillOfEntryNumberTable_IN.cdm.json/CustomsBillOfEntryNumberTable_IN</a></td><td><a href="../../AccountsReceivable/Main/CustomsBillOfEntryNumberTable_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomsImportInvoiceNumberTable_INRelationshipId name="Relationship_CustomsImportInvoiceNumberTable_INRelationshipId">Relationship_CustomsImportInvoiceNumberTable_INRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomsImportInvoiceNumberTable_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Main/CustomsImportInvoiceNumberTable_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/CustomsImportInvoiceNumberTable_IN.cdm.json/CustomsImportInvoiceNumberTable_IN</a></td><td><a href="../../AccountsReceivable/Main/CustomsImportInvoiceNumberTable_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EmployeeTable_RURelationshipId name="Relationship_EmployeeTable_RURelationshipId">Relationship_EmployeeTable_RURelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EmployeeTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Expense/Main/EmployeeTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/Main/EmployeeTable_RU.cdm.json/EmployeeTable_RU</a></td><td><a href="../../Expense/Main/EmployeeTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocModel_BRRelationshipId name="Relationship_FiscalDocModel_BRRelationshipId">Relationship_FiscalDocModel_BRRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocModel_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FiscalBooksBrazil/Group/FiscalDocModel_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Group/FiscalDocModel_BR.cdm.json/FiscalDocModel_BR</a></td><td><a href="../../FiscalBooksBrazil/Group/FiscalDocModel_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentType_BRRelationshipId name="Relationship_FiscalDocumentType_BRRelationshipId">Relationship_FiscalDocumentType_BRRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentType_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.cdm.json/FiscalDocumentType_BR</a></td><td><a href="../../FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PlTaxDueTableRelationshipId name="Relationship_PlTaxDueTableRelationshipId">Relationship_PlTaxDueTableRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlTaxDueTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/PlTaxDueTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/PlTaxDueTable.cdm.json/PlTaxDueTable</a></td><td><a href="../../Tax/Group/PlTaxDueTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchImportDeclaration_BRRelationshipId name="Relationship_PurchImportDeclaration_BRRelationshipId">Relationship_PurchImportDeclaration_BRRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchImportDeclaration_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/PurchImportDeclaration_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/PurchImportDeclaration_BR.cdm.json/PurchImportDeclaration_BR</a></td><td><a href="../Transaction/PurchImportDeclaration_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReasonTableRefRelationshipId name="Relationship_ReasonTableRefRelationshipId">Relationship_ReasonTableRefRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReasonTableRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Transaction/ReasonTableRef.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Transaction/ReasonTableRef.cdm.json/ReasonTableRef</a></td><td><a href="../../Ledger/Transaction/ReasonTableRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesPurchOperationType_BRRelationshipId name="Relationship_SalesPurchOperationType_BRRelationshipId">Relationship_SalesPurchOperationType_BRRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesPurchOperationType_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Main/SalesPurchOperationType_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/SalesPurchOperationType_BR.cdm.json/SalesPurchOperationType_BR</a></td><td><a href="../../AccountsReceivable/Main/SalesPurchOperationType_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxInformation_INRelationshipId name="Relationship_TaxInformation_INRelationshipId">Relationship_TaxInformation_INRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxInformation_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Miscellaneous/TaxInformation_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxInformation_IN.cdm.json/TaxInformation_IN</a></td><td><a href="../../Tax/Miscellaneous/TaxInformation_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendFineCode_BRRelationshipId name="Relationship_VendFineCode_BRRelationshipId">Relationship_VendFineCode_BRRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendFineCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/VendFineSetup_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Main/VendFineSetup_BR.cdm.json/VendFineSetup_BR</a></td><td><a href="../Main/VendFineSetup_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendInterestCode_BRRelationshipId name="Relationship_VendInterestCode_BRRelationshipId">Relationship_VendInterestCode_BRRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendInterestCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/VendInterestSetup_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Main/VendInterestSetup_BR.cdm.json/VendInterestSetup_BR</a></td><td><a href="../Main/VendInterestSetup_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendInvoiceInfoTableRelationshipId name="Relationship_VendInvoiceInfoTableRelationshipId">Relationship_VendInvoiceInfoTableRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendInvoiceInfoTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="VendInvoiceInfoTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/TransactionHeader/VendInvoiceInfoTable.cdm.json/VendInvoiceInfoTable</a></td><td><a href="VendInvoiceInfoTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesCarrier_BRRelationshipId name="Relationship_SalesCarrier_BRRelationshipId">Relationship_SalesCarrier_BRRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesCarrier_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/SalesCarrier.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/SalesCarrier.cdm.json/SalesCarrier</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/SalesCarrier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoTable_W (this entity)  

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

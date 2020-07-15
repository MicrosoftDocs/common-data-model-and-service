---
title: PurchLine_IN in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Purchase order line information for India in WorksheetLine(PurchLine_IN)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/WorksheetLine/PurchLine_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchLine_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order line information for India</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[PurchLine](#PurchLine)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[AssessableValueAccountingCurrency](#AssessableValueAccountingCurrency)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[AssessableValueTransactionCurrency](#AssessableValueTransactionCurrency)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[CreditNoteDate](#CreditNoteDate)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[CustomsMaxRetailPrice](#CustomsMaxRetailPrice)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[MaximumRetailPrice](#MaximumRetailPrice)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TaxAsPerOriginalInvoice](#TaxAsPerOriginalInvoice)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TaxWithholdLineNum](#TaxWithholdLineNum)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TaxWithholdVoucher](#TaxWithholdVoucher)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TCSGroup](#TCSGroup)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TDSGroup](#TDSGroup)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[VendorLocation](#VendorLocation)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TaxAsPerOriginalInvoice_IN](#TaxAsPerOriginalInvoice_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[AssessableValue_IN](#AssessableValue_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[CENVATCreditAvailed_IN](#CENVATCreditAvailed_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[CompanyLocation_IN](#CompanyLocation_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[Consignment_IN](#Consignment_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[CreditNoteDate_IN](#CreditNoteDate_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[CustomsMaxRetailPrice_IN](#CustomsMaxRetailPrice_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[CustomsTariffCodeTable_IN](#CustomsTariffCodeTable_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[DirectSettlement_IN](#DirectSettlement_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[DSA_IN](#DSA_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[ExciseRecordType_IN](#ExciseRecordType_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[ExciseTariffCodes_IN](#ExciseTariffCodes_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[ExciseType_IN](#ExciseType_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[Exempt](#Exempt)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[GTAServiceCategory_IN](#GTAServiceCategory_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[HSNCodeTable](#HSNCodeTable)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[InclTax](#InclTax)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[IsRecoverableServiceTax_IN](#IsRecoverableServiceTax_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[ITCCategory](#ITCCategory)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[MaximumRetailPrice_IN](#MaximumRetailPrice_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[NonBusinessUsagePercentage](#NonBusinessUsagePercentage)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[NonRecoverablePercent_IN](#NonRecoverablePercent_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[SalesTaxFormTypes_IN](#SalesTaxFormTypes_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[ServiceAccountingCodeTable](#ServiceAccountingCodeTable)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[ServiceCategory](#ServiceCategory)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[ServiceCodeTable_IN](#ServiceCodeTable_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[SoftwareDeclReceived_IN](#SoftwareDeclReceived_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TaxInformation_IN](#TaxInformation_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TaxWithholdAcknowledgementNumber](#TaxWithholdAcknowledgementNumber)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TaxWithholdCountryRegionToRemittance](#TaxWithholdCountryRegionToRemittance)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TaxWithholdLineNum_IN](#TaxWithholdLineNum_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TaxWithholdNatureOfRemittance](#TaxWithholdNatureOfRemittance)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TaxWithholdVoucher_IN](#TaxWithholdVoucher_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TCSGroup_IN](#TCSGroup_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[TDSGroup_IN](#TDSGroup_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[VATGoodsType_IN](#VATGoodsType_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[VendorLocation_IN](#VendorLocation_IN)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[VendorTaxInformation](#VendorTaxInformation)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[Relationship_PurchLineRelationshipId](#Relationship_PurchLineRelationshipId)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[Relationship_TaxWithholdGroupHeadingTCSRelationshipId](#Relationship_TaxWithholdGroupHeadingTCSRelationshipId)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[Relationship_TaxWithholdGroupHeadingTDSRelationshipId](#Relationship_TaxWithholdGroupHeadingTDSRelationshipId)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[Relationship_VendorLocationRelationshipId](#Relationship_VendorLocationRelationshipId)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchLine_IN.md" target="_blank">WorksheetLine/PurchLine_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchLine_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchLine name="PurchLine">PurchLine</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssessableValueAccountingCurrency name="AssessableValueAccountingCurrency">AssessableValueAccountingCurrency</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assessable value in the accounting currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValueAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Assessable value in the accounting currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AssessableValueTransactionCurrency name="AssessableValueTransactionCurrency">AssessableValueTransactionCurrency</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assessable value</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValueTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Assessable value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CreditNoteDate name="CreditNoteDate">CreditNoteDate</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CustomsMaxRetailPrice name="CustomsMaxRetailPrice">CustomsMaxRetailPrice</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max. retail price in customs currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsMaxRetailPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Max. retail price in customs currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MaximumRetailPrice name="MaximumRetailPrice">MaximumRetailPrice</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRetailPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAsPerOriginalInvoice name="TaxAsPerOriginalInvoice">TaxAsPerOriginalInvoice</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax as per original invoice</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAsPerOriginalInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax as per original invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxWithholdLineNum name="TaxWithholdLineNum">TaxWithholdLineNum</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdLineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxWithholdVoucher name="TaxWithholdVoucher">TaxWithholdVoucher</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TCSGroup name="TCSGroup">TCSGroup</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>TCS group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TCSGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>TCS group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TDSGroup name="TDSGroup">TDSGroup</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>TDS group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TDSGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>TDS group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorLocation name="VendorLocation">VendorLocation</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAsPerOriginalInvoice_IN name="TaxAsPerOriginalInvoice_IN">TaxAsPerOriginalInvoice_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax as per original invoice</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAsPerOriginalInvoice_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax as per original invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AssessableValue_IN name="AssessableValue_IN">AssessableValue_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValue_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CENVATCreditAvailed_IN name="CENVATCreditAvailed_IN">CENVATCreditAvailed_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CENVATCreditAvailed_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CompanyLocation_IN name="CompanyLocation_IN">CompanyLocation_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyLocation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Consignment_IN name="Consignment_IN">Consignment_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Consignment_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CreditNoteDate_IN name="CreditNoteDate_IN">CreditNoteDate_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteDate_IN attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CustomsMaxRetailPrice_IN name="CustomsMaxRetailPrice_IN">CustomsMaxRetailPrice_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsMaxRetailPrice_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CustomsTariffCodeTable_IN name="CustomsTariffCodeTable_IN">CustomsTariffCodeTable_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsTariffCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DirectSettlement_IN name="DirectSettlement_IN">DirectSettlement_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectSettlement_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DSA_IN name="DSA_IN">DSA_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DSA_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExciseRecordType_IN name="ExciseRecordType_IN">ExciseRecordType_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseRecordType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExciseTariffCodes_IN name="ExciseTariffCodes_IN">ExciseTariffCodes_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseTariffCodes_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExciseType_IN name="ExciseType_IN">ExciseType_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Exempt name="Exempt">Exempt</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Exempt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GTAServiceCategory_IN name="GTAServiceCategory_IN">GTAServiceCategory_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GTAServiceCategory_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HSNCodeTable name="HSNCodeTable">HSNCodeTable</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HSNCodeTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InclTax name="InclTax">InclTax</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsRecoverableServiceTax_IN name="IsRecoverableServiceTax_IN">IsRecoverableServiceTax_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRecoverableServiceTax_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ITCCategory name="ITCCategory">ITCCategory</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ITCCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MaximumRetailPrice_IN name="MaximumRetailPrice_IN">MaximumRetailPrice_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRetailPrice_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NonBusinessUsagePercentage name="NonBusinessUsagePercentage">NonBusinessUsagePercentage</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonBusinessUsagePercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NonRecoverablePercent_IN name="NonRecoverablePercent_IN">NonRecoverablePercent_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonRecoverablePercent_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesTaxFormTypes_IN name="SalesTaxFormTypes_IN">SalesTaxFormTypes_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxFormTypes_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceAccountingCodeTable name="ServiceAccountingCodeTable">ServiceAccountingCodeTable</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAccountingCodeTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCategory name="ServiceCategory">ServiceCategory</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ServiceCodeTable_IN name="ServiceCodeTable_IN">ServiceCodeTable_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SoftwareDeclReceived_IN name="SoftwareDeclReceived_IN">SoftwareDeclReceived_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SoftwareDeclReceived_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxInformation_IN name="TaxInformation_IN">TaxInformation_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

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

### <a href=#TaxWithholdAcknowledgementNumber name="TaxWithholdAcknowledgementNumber">TaxWithholdAcknowledgementNumber</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdAcknowledgementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdCountryRegionToRemittance name="TaxWithholdCountryRegionToRemittance">TaxWithholdCountryRegionToRemittance</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCountryRegionToRemittance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdLineNum_IN name="TaxWithholdLineNum_IN">TaxWithholdLineNum_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdLineNum_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxWithholdNatureOfRemittance name="TaxWithholdNatureOfRemittance">TaxWithholdNatureOfRemittance</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdNatureOfRemittance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdVoucher_IN name="TaxWithholdVoucher_IN">TaxWithholdVoucher_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdVoucher_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TCSGroup_IN name="TCSGroup_IN">TCSGroup_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TCSGroup_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TDSGroup_IN name="TDSGroup_IN">TDSGroup_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TDSGroup_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATGoodsType_IN name="VATGoodsType_IN">VATGoodsType_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATGoodsType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VendorLocation_IN name="VendorLocation_IN">VendorLocation_IN</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLocation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendorTaxInformation name="VendorTaxInformation">VendorTaxInformation</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorTaxInformation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

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

### <a href=#Relationship_PurchLineRelationshipId name="Relationship_PurchLineRelationshipId">Relationship_PurchLineRelationshipId</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.cdm.json/PurchLine</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdGroupHeadingTCSRelationshipId name="Relationship_TaxWithholdGroupHeadingTCSRelationshipId">Relationship_TaxWithholdGroupHeadingTCSRelationshipId</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdGroupHeadingTCSRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxWithholdGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdGroupHeading.cdm.json/TaxWithholdGroupHeading</a></td><td><a href="../../Tax/Group/TaxWithholdGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdGroupHeadingTDSRelationshipId name="Relationship_TaxWithholdGroupHeadingTDSRelationshipId">Relationship_TaxWithholdGroupHeadingTDSRelationshipId</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdGroupHeadingTDSRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxWithholdGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdGroupHeading.cdm.json/TaxWithholdGroupHeading</a></td><td><a href="../../Tax/Group/TaxWithholdGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendorLocationRelationshipId name="Relationship_VendorLocationRelationshipId">Relationship_VendorLocationRelationshipId</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/PurchLine_IN (this entity)  

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

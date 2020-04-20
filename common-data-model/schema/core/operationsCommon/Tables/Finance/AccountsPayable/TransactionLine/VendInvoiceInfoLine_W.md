---
title: VendInvoiceInfoLine_W - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# VendInvoiceInfoLine_W

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/TransactionLine/VendInvoiceInfoLine_W.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendInvoiceInfoLine_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[AlcoholLicenseSeriesNum_RU](#AlcoholLicenseSeriesNum_RU)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[AssessableValue_IN](#AssessableValue_IN)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CFOPTable_BR](#CFOPTable_BR)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CountryRegionName_RU](#CountryRegionName_RU)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CustomsBillOfEntryNumberTable_IN](#CustomsBillOfEntryNumberTable_IN)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CustomsImportInvoiceNumberTable_IN](#CustomsImportInvoiceNumberTable_IN)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CustomsInvoiceRegnRecId_IN](#CustomsInvoiceRegnRecId_IN)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[DeviationQty_RU](#DeviationQty_RU)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[DIAddition_BR](#DIAddition_BR)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[FreightNature_BR](#FreightNature_BR)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[IntrastatFulfillmentDate_HU](#IntrastatFulfillmentDate_HU)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[InventProfileType_RU](#InventProfileType_RU)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[InvoiceGTDId_RU](#InvoiceGTDId_RU)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[LedgerDimension_RU](#LedgerDimension_RU)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[MarkupCode_RU](#MarkupCode_RU)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[MaximumRetailPrice_IN](#MaximumRetailPrice_IN)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[PostingProfile_RU](#PostingProfile_RU)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[SADInvoiceLineNo_PL](#SADInvoiceLineNo_PL)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[SADLineNo_PL](#SADLineNo_PL)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[SADNumberCode_PL](#SADNumberCode_PL)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[TaxServiceCode_BR](#TaxServiceCode_BR)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[ValueFromSADInvoice_PL](#ValueFromSADInvoice_PL)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[ValueFromSADTrans_PL](#ValueFromSADTrans_PL)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[VendInvoiceInfoLine](#VendInvoiceInfoLine)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[AssessableValueAccountingCurrency_IN](#AssessableValueAccountingCurrency_IN)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[DiotOperationType](#DiotOperationType)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CFDIBeneficiaryRetains_MX](#CFDIBeneficiaryRetains_MX)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CFDIFinancialSystem_MX](#CFDIFinancialSystem_MX)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CFDIInterestBelongsDerivedFinOp_MX](#CFDIInterestBelongsDerivedFinOp_MX)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CFDIInterestCashedInTheCurrentPeriod_MX](#CFDIInterestCashedInTheCurrentPeriod_MX)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CFDIInterestLossAmount_MX](#CFDIInterestLossAmount_MX)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CFDIInterestNominalAmount_MX](#CFDIInterestNominalAmount_MX)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[CFDIInterestRealAmount_MX](#CFDIInterestRealAmount_MX)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[WithholdingTypeCode_MX](#WithholdingTypeCode_MX)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[DataAreaId](#DataAreaId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_AlcoholLicenseTable_RURelationshipId](#Relationship_AlcoholLicenseTable_RURelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_CFOPTable_BRRelationshipId](#Relationship_CFOPTable_BRRelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_CustomsBillOfEntryNumberTable_INRelationshipId](#Relationship_CustomsBillOfEntryNumberTable_INRelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_CustomsImportInvoiceNumberTable_INRelationshipId](#Relationship_CustomsImportInvoiceNumberTable_INRelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_CustomsInvoiceRegnTrans_INRelationshipId](#Relationship_CustomsInvoiceRegnTrans_INRelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_LedgerDimension_RURelationshipId](#Relationship_LedgerDimension_RURelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_LogisticsAddressCountryRegion_RURelationshipId](#Relationship_LogisticsAddressCountryRegion_RURelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_PlSADInvoiceRelationshipId](#Relationship_PlSADInvoiceRelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_PlSADTableRelationshipId](#Relationship_PlSADTableRelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_PlSADTransRelationshipId](#Relationship_PlSADTransRelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_VendInvoiceInfoLineRelationshipId](#Relationship_VendInvoiceInfoLineRelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_VendLedgerRelationshipId](#Relationship_VendLedgerRelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_CFDIWithholdingType_MXRelationshipId](#Relationship_CFDIWithholdingType_MXRelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendInvoiceInfoLine_W.md" target="_blank">TransactionLine/VendInvoiceInfoLine_W</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendInvoiceInfoLine_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AlcoholLicenseSeriesNum_RU name="AlcoholLicenseSeriesNum_RU">AlcoholLicenseSeriesNum_RU</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlcoholLicenseSeriesNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssessableValue_IN name="AssessableValue_IN">AssessableValue_IN</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValue_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CFOPTable_BR name="CFOPTable_BR">CFOPTable_BR</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPTable_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CountryRegionName_RU name="CountryRegionName_RU">CountryRegionName_RU</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionName_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsBillOfEntryNumberTable_IN name="CustomsBillOfEntryNumberTable_IN">CustomsBillOfEntryNumberTable_IN</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsBillOfEntryNumberTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomsImportInvoiceNumberTable_IN name="CustomsImportInvoiceNumberTable_IN">CustomsImportInvoiceNumberTable_IN</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsImportInvoiceNumberTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomsInvoiceRegnRecId_IN name="CustomsInvoiceRegnRecId_IN">CustomsInvoiceRegnRecId_IN</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsInvoiceRegnRecId_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DeviationQty_RU name="DeviationQty_RU">DeviationQty_RU</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeviationQty_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DIAddition_BR name="DIAddition_BR">DIAddition_BR</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DIAddition_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightNature_BR name="FreightNature_BR">FreightNature_BR</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightNature_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IntrastatFulfillmentDate_HU name="IntrastatFulfillmentDate_HU">IntrastatFulfillmentDate_HU</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatFulfillmentDate_HU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#InventProfileType_RU name="InventProfileType_RU">InventProfileType_RU</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceGTDId_RU name="InvoiceGTDId_RU">InvoiceGTDId_RU</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceGTDId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension_RU name="LedgerDimension_RU">LedgerDimension_RU</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MarkupCode_RU name="MarkupCode_RU">MarkupCode_RU</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRetailPrice_IN name="MaximumRetailPrice_IN">MaximumRetailPrice_IN</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRetailPrice_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PostingProfile_RU name="PostingProfile_RU">PostingProfile_RU</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SADInvoiceLineNo_PL name="SADInvoiceLineNo_PL">SADInvoiceLineNo_PL</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SADInvoiceLineNo_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SADLineNo_PL name="SADLineNo_PL">SADLineNo_PL</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SADLineNo_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SADNumberCode_PL name="SADNumberCode_PL">SADNumberCode_PL</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SADNumberCode_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxServiceCode_BR name="TaxServiceCode_BR">TaxServiceCode_BR</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxServiceCode_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValueFromSADInvoice_PL name="ValueFromSADInvoice_PL">ValueFromSADInvoice_PL</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueFromSADInvoice_PL attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ValueFromSADTrans_PL name="ValueFromSADTrans_PL">ValueFromSADTrans_PL</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueFromSADTrans_PL attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VendInvoiceInfoLine name="VendInvoiceInfoLine">VendInvoiceInfoLine</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceInfoLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssessableValueAccountingCurrency_IN name="AssessableValueAccountingCurrency_IN">AssessableValueAccountingCurrency_IN</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValueAccountingCurrency_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DiotOperationType name="DiotOperationType">DiotOperationType</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiotOperationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CFDIBeneficiaryRetains_MX name="CFDIBeneficiaryRetains_MX">CFDIBeneficiaryRetains_MX</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIBeneficiaryRetains_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CFDIFinancialSystem_MX name="CFDIFinancialSystem_MX">CFDIFinancialSystem_MX</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIFinancialSystem_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CFDIInterestBelongsDerivedFinOp_MX name="CFDIInterestBelongsDerivedFinOp_MX">CFDIInterestBelongsDerivedFinOp_MX</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIInterestBelongsDerivedFinOp_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CFDIInterestCashedInTheCurrentPeriod_MX name="CFDIInterestCashedInTheCurrentPeriod_MX">CFDIInterestCashedInTheCurrentPeriod_MX</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIInterestCashedInTheCurrentPeriod_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CFDIInterestLossAmount_MX name="CFDIInterestLossAmount_MX">CFDIInterestLossAmount_MX</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIInterestLossAmount_MX attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CFDIInterestNominalAmount_MX name="CFDIInterestNominalAmount_MX">CFDIInterestNominalAmount_MX</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIInterestNominalAmount_MX attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CFDIInterestRealAmount_MX name="CFDIInterestRealAmount_MX">CFDIInterestRealAmount_MX</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIInterestRealAmount_MX attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WithholdingTypeCode_MX name="WithholdingTypeCode_MX">WithholdingTypeCode_MX</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTypeCode_MX attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

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

### <a href=#Relationship_AlcoholLicenseTable_RURelationshipId name="Relationship_AlcoholLicenseTable_RURelationshipId">Relationship_AlcoholLicenseTable_RURelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AlcoholLicenseTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../EGAIS/Parameter/AlcoholLicenseTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/Parameter/AlcoholLicenseTable_RU.cdm.json/AlcoholLicenseTable_RU</a></td><td><a href="../../EGAIS/Parameter/AlcoholLicenseTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CFOPTable_BRRelationshipId name="Relationship_CFOPTable_BRRelationshipId">Relationship_CFOPTable_BRRelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CFOPTable_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/CFOPTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/CFOPTable_BR.cdm.json/CFOPTable_BR</a></td><td><a href="../../Bank/Group/CFOPTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomsBillOfEntryNumberTable_INRelationshipId name="Relationship_CustomsBillOfEntryNumberTable_INRelationshipId">Relationship_CustomsBillOfEntryNumberTable_INRelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

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

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

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

### <a href=#Relationship_CustomsInvoiceRegnTrans_INRelationshipId name="Relationship_CustomsInvoiceRegnTrans_INRelationshipId">Relationship_CustomsInvoiceRegnTrans_INRelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomsInvoiceRegnTrans_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustomsInvoiceRegnTrans_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustomsInvoiceRegnTrans_IN.cdm.json/CustomsInvoiceRegnTrans_IN</a></td><td><a href="../../AccountsReceivable/Transaction/CustomsInvoiceRegnTrans_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimension_RURelationshipId name="Relationship_LedgerDimension_RURelationshipId">Relationship_LedgerDimension_RURelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimension_RURelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LogisticsAddressCountryRegion_RURelationshipId name="Relationship_LogisticsAddressCountryRegion_RURelationshipId">Relationship_LogisticsAddressCountryRegion_RURelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressCountryRegion_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegionTranslation.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCountryRegionTranslation.cdm.json/LogisticsAddressCountryRegionTranslation</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegionTranslation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PlSADInvoiceRelationshipId name="Relationship_PlSADInvoiceRelationshipId">Relationship_PlSADInvoiceRelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlSADInvoiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/WorksheetLine/PlSADInvoice.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/WorksheetLine/PlSADInvoice.cdm.json/PlSADInvoice</a></td><td><a href="../../AccountsReceivable/WorksheetLine/PlSADInvoice.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PlSADTableRelationshipId name="Relationship_PlSADTableRelationshipId">Relationship_PlSADTableRelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlSADTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/WorksheetHeader/PlSADTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/WorksheetHeader/PlSADTable.cdm.json/PlSADTable</a></td><td><a href="../../AccountsReceivable/WorksheetHeader/PlSADTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PlSADTransRelationshipId name="Relationship_PlSADTransRelationshipId">Relationship_PlSADTransRelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlSADTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/PlSADTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/PlSADTrans.cdm.json/PlSADTrans</a></td><td><a href="../../AccountsReceivable/Transaction/PlSADTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendInvoiceInfoLineRelationshipId name="Relationship_VendInvoiceInfoLineRelationshipId">Relationship_VendInvoiceInfoLineRelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendInvoiceInfoLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="VendInvoiceInfoLine.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/TransactionLine/VendInvoiceInfoLine.cdm.json/VendInvoiceInfoLine</a></td><td><a href="VendInvoiceInfoLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendLedgerRelationshipId name="Relationship_VendLedgerRelationshipId">Relationship_VendLedgerRelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendLedgerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/VendLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Group/VendLedger.cdm.json/VendLedger</a></td><td><a href="../Group/VendLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CFDIWithholdingType_MXRelationshipId name="Relationship_CFDIWithholdingType_MXRelationshipId">Relationship_CFDIWithholdingType_MXRelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CFDIWithholdingType_MXRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../EInvoice/Group/CFDIWithholdingType_MX.md" target="_blank">/core/operationsCommon/Tables/Finance/EInvoice/Group/CFDIWithholdingType_MX.cdm.json/CFDIWithholdingType_MX</a></td><td><a href="../../EInvoice/Group/CFDIWithholdingType_MX.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionLine/VendInvoiceInfoLine_W (this entity)  

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

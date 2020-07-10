---
title: ProjCostTransTaxExtensionIN in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Expense tax extension for India taxes in Transaction(ProjCostTransTaxExtensionIN)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjCostTransTaxExtensionIN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjCostTransTaxExtensionIN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expense tax extension for India taxes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[MaximumRetailPrice](#MaximumRetailPrice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ProjCostTrans](#ProjCostTrans)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ServiceEventGroup](#ServiceEventGroup)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[AssessableValueTransactionCurrency](#AssessableValueTransactionCurrency)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[TaxInformationForInvoice](#TaxInformationForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[CompanyLocation](#CompanyLocation)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[CustomerLocation](#CustomerLocation)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[CustomerTaxInformation](#CustomerTaxInformation)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[CustomsTariffCodeTable](#CustomsTariffCodeTable)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[DirectSettlement](#DirectSettlement)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ExciseRecordType](#ExciseRecordType)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ExciseTariffCodes](#ExciseTariffCodes)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ExciseType](#ExciseType)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[Exempt](#Exempt)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[HSNCodeTable](#HSNCodeTable)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ITCCategory](#ITCCategory)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[NonBusinessUsagePercentage](#NonBusinessUsagePercentage)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[SalesTaxFormTypes](#SalesTaxFormTypes)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ServiceAccountingCodeTable](#ServiceAccountingCodeTable)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ServiceCodeTable](#ServiceCodeTable)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ServiceCategory](#ServiceCategory)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[TaxInventVATCommodityCodeId](#TaxInventVATCommodityCodeId)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[VendorLocation](#VendorLocation)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[VendorTaxInformation](#VendorTaxInformation)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[AssessableValue](#AssessableValue)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[TaxInformation](#TaxInformation)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[CompanyLocationForInvoice](#CompanyLocationForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[CustomerLocationForInvoice](#CustomerLocationForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[CustomerTaxInformationForInvoice](#CustomerTaxInformationForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[CustomsTariffCodeTableForInvoice](#CustomsTariffCodeTableForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[DirectSettlementForInvoice](#DirectSettlementForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ExciseRecordTypeForInvoice](#ExciseRecordTypeForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ExciseTariffCodesForInvoice](#ExciseTariffCodesForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ExciseTypeForInvoice](#ExciseTypeForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ExemptForInvoice](#ExemptForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[HSNCodeTableForInvoice](#HSNCodeTableForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ITCCategoryForInvoice](#ITCCategoryForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[SalesTaxFormTypesForInvoice](#SalesTaxFormTypesForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ServiceAccountingCodeTableForInvoice](#ServiceAccountingCodeTableForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[ServiceCodeTableForInvoice](#ServiceCodeTableForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[TaxInventVATCommodityCodeIdForInvoice](#TaxInventVATCommodityCodeIdForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[VendorLocationForInvoice](#VendorLocationForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[VendorTaxInformationForInvoice](#VendorTaxInformationForInvoice)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[DataAreaId](#DataAreaId)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[Relationship_ProjCostTransRelationshipId](#Relationship_ProjCostTransRelationshipId)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[Relationship_TaxInformation_INRelationshipId](#Relationship_TaxInformation_INRelationshipId)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ProjCostTransTaxExtensionIN.md" target="_blank">Transaction/ProjCostTransTaxExtensionIN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjCostTransTaxExtensionIN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MaximumRetailPrice name="MaximumRetailPrice">MaximumRetailPrice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

### <a href=#ProjCostTrans name="ProjCostTrans">ProjCostTrans</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjCostTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceEventGroup name="ServiceEventGroup">ServiceEventGroup</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceEventGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssessableValueTransactionCurrency name="AssessableValueTransactionCurrency">AssessableValueTransactionCurrency</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

### <a href=#TaxInformationForInvoice name="TaxInformationForInvoice">TaxInformationForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInformationForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CompanyLocation name="CompanyLocation">CompanyLocation</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomerLocation name="CustomerLocation">CustomerLocation</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomerTaxInformation name="CustomerTaxInformation">CustomerTaxInformation</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTaxInformation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomsTariffCodeTable name="CustomsTariffCodeTable">CustomsTariffCodeTable</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsTariffCodeTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DirectSettlement name="DirectSettlement">DirectSettlement</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectSettlement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExciseRecordType name="ExciseRecordType">ExciseRecordType</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseRecordType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExciseTariffCodes name="ExciseTariffCodes">ExciseTariffCodes</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseTariffCodes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExciseType name="ExciseType">ExciseType</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Exempt name="Exempt">Exempt</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

### <a href=#HSNCodeTable name="HSNCodeTable">HSNCodeTable</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

### <a href=#ITCCategory name="ITCCategory">ITCCategory</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

### <a href=#NonBusinessUsagePercentage name="NonBusinessUsagePercentage">NonBusinessUsagePercentage</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

### <a href=#SalesTaxFormTypes name="SalesTaxFormTypes">SalesTaxFormTypes</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxFormTypes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceAccountingCodeTable name="ServiceAccountingCodeTable">ServiceAccountingCodeTable</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

### <a href=#ServiceCodeTable name="ServiceCodeTable">ServiceCodeTable</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCodeTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCategory name="ServiceCategory">ServiceCategory</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

### <a href=#TaxInventVATCommodityCodeId name="TaxInventVATCommodityCodeId">TaxInventVATCommodityCodeId</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInventVATCommodityCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorLocation name="VendorLocation">VendorLocation</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

### <a href=#VendorTaxInformation name="VendorTaxInformation">VendorTaxInformation</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

### <a href=#AssessableValue name="AssessableValue">AssessableValue</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxInformation name="TaxInformation">TaxInformation</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInformation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CompanyLocationForInvoice name="CompanyLocationForInvoice">CompanyLocationForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyLocationForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomerLocationForInvoice name="CustomerLocationForInvoice">CustomerLocationForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerLocationForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomerTaxInformationForInvoice name="CustomerTaxInformationForInvoice">CustomerTaxInformationForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTaxInformationForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomsTariffCodeTableForInvoice name="CustomsTariffCodeTableForInvoice">CustomsTariffCodeTableForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsTariffCodeTableForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DirectSettlementForInvoice name="DirectSettlementForInvoice">DirectSettlementForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectSettlementForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExciseRecordTypeForInvoice name="ExciseRecordTypeForInvoice">ExciseRecordTypeForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseRecordTypeForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExciseTariffCodesForInvoice name="ExciseTariffCodesForInvoice">ExciseTariffCodesForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseTariffCodesForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExciseTypeForInvoice name="ExciseTypeForInvoice">ExciseTypeForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseTypeForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExemptForInvoice name="ExemptForInvoice">ExemptForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExemptForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HSNCodeTableForInvoice name="HSNCodeTableForInvoice">HSNCodeTableForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HSNCodeTableForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ITCCategoryForInvoice name="ITCCategoryForInvoice">ITCCategoryForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ITCCategoryForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesTaxFormTypesForInvoice name="SalesTaxFormTypesForInvoice">SalesTaxFormTypesForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxFormTypesForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceAccountingCodeTableForInvoice name="ServiceAccountingCodeTableForInvoice">ServiceAccountingCodeTableForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAccountingCodeTableForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCodeTableForInvoice name="ServiceCodeTableForInvoice">ServiceCodeTableForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCodeTableForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxInventVATCommodityCodeIdForInvoice name="TaxInventVATCommodityCodeIdForInvoice">TaxInventVATCommodityCodeIdForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInventVATCommodityCodeIdForInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorLocationForInvoice name="VendorLocationForInvoice">VendorLocationForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLocationForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendorTaxInformationForInvoice name="VendorTaxInformationForInvoice">VendorTaxInformationForInvoice</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorTaxInformationForInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

### <a href=#Relationship_ProjCostTransRelationshipId name="Relationship_ProjCostTransRelationshipId">Relationship_ProjCostTransRelationshipId</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjCostTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProjCostTrans.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjCostTrans.cdm.json/ProjCostTrans</a></td><td><a href="ProjCostTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxInformation_INRelationshipId name="Relationship_TaxInformation_INRelationshipId">Relationship_TaxInformation_INRelationshipId</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Miscellaneous/TaxInformation_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxInformation_IN.cdm.json/TaxInformation_IN</a></td><td><a href="../../../Finance/Tax/Miscellaneous/TaxInformation_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/ProjCostTransTaxExtensionIN (this entity)  

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

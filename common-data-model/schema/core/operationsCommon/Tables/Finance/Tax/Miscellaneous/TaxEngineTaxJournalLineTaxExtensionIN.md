---
title: TaxEngineTaxJournalLineTaxExtensionIN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# TaxEngineTaxJournalLineTaxExtensionIN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxEngineTaxJournalLineTaxExtensionIN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[CompanyLocation_IN](#CompanyLocation_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[ConsignmentNoteNum_IN](#ConsignmentNoteNum_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[CustomerLocation_IN](#CustomerLocation_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[CustomerTaxInformation_IN](#CustomerTaxInformation_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[CustomsTariffCodeTable_IN](#CustomsTariffCodeTable_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[CustomsTariffDirection_IN](#CustomsTariffDirection_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[ExciseRecordType_IN](#ExciseRecordType_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[ExciseTariffCodes_IN](#ExciseTariffCodes_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[ExciseType_IN](#ExciseType_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[GTAServiceCategory_IN](#GTAServiceCategory_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[HSNCodeTable_IN](#HSNCodeTable_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[ITCCategory_IN](#ITCCategory_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[NatureOfAssessee_IN](#NatureOfAssessee_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[NonBusinessUsagePercentage_IN](#NonBusinessUsagePercentage_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[NonRecoverablePercent_IN](#NonRecoverablePercent_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[SalesTaxFormTypes_IN](#SalesTaxFormTypes_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[ServiceAccountingCodeTable_IN](#ServiceAccountingCodeTable_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[ServiceCategory_IN](#ServiceCategory_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[ServiceCodeTable_IN](#ServiceCodeTable_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[SoftwareDeclReceived_IN](#SoftwareDeclReceived_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[TaxEngineTaxJournalLine](#TaxEngineTaxJournalLine)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[TaxInformation_IN](#TaxInformation_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[VATGoodsType_IN](#VATGoodsType_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[VendorLocation_IN](#VendorLocation_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[VendorTaxInformation_IN](#VendorTaxInformation_IN)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxEngineTaxJournalLineTaxExtensionIN.md" target="_blank">Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxEngineTaxJournalLineTaxExtensionIN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CompanyLocation_IN name="CompanyLocation_IN">CompanyLocation_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

### <a href=#ConsignmentNoteNum_IN name="ConsignmentNoteNum_IN">ConsignmentNoteNum_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

### <a href=#CustomerLocation_IN name="CustomerLocation_IN">CustomerLocation_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerLocation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomerTaxInformation_IN name="CustomerTaxInformation_IN">CustomerTaxInformation_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTaxInformation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomsTariffCodeTable_IN name="CustomsTariffCodeTable_IN">CustomsTariffCodeTable_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

### <a href=#CustomsTariffDirection_IN name="CustomsTariffDirection_IN">CustomsTariffDirection_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsTariffDirection_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExciseRecordType_IN name="ExciseRecordType_IN">ExciseRecordType_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

### <a href=#GTAServiceCategory_IN name="GTAServiceCategory_IN">GTAServiceCategory_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

### <a href=#HSNCodeTable_IN name="HSNCodeTable_IN">HSNCodeTable_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HSNCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ITCCategory_IN name="ITCCategory_IN">ITCCategory_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ITCCategory_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#NatureOfAssessee_IN name="NatureOfAssessee_IN">NatureOfAssessee_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NatureOfAssessee_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#NonBusinessUsagePercentage_IN name="NonBusinessUsagePercentage_IN">NonBusinessUsagePercentage_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonBusinessUsagePercentage_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NonRecoverablePercent_IN name="NonRecoverablePercent_IN">NonRecoverablePercent_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

### <a href=#ServiceAccountingCodeTable_IN name="ServiceAccountingCodeTable_IN">ServiceAccountingCodeTable_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAccountingCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCategory_IN name="ServiceCategory_IN">ServiceCategory_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCategory_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ServiceCodeTable_IN name="ServiceCodeTable_IN">ServiceCodeTable_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

### <a href=#TaxEngineTaxJournalLine name="TaxEngineTaxJournalLine">TaxEngineTaxJournalLine</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxEngineTaxJournalLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxInformation_IN name="TaxInformation_IN">TaxInformation_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

### <a href=#VATGoodsType_IN name="VATGoodsType_IN">VATGoodsType_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

### <a href=#VendorTaxInformation_IN name="VendorTaxInformation_IN">VendorTaxInformation_IN</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorTaxInformation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/TaxEngineTaxJournalLineTaxExtensionIN (this entity)  

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

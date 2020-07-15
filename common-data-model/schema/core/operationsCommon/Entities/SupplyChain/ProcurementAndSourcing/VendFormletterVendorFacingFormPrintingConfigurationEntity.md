---
title: VendFormletterVendorFacingFormPrintingConfigurationEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Vendor facing form printing configurations in ProcurementAndSourcing(VendFormletterVendorFacingFormPrintingConfigurationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor facing form printing configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AreEuroAmountsDisplayed](#AreEuroAmountsDisplayed)||<a href="VendFormletterVendorFacingFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity</a>|
|[TotalAmountDisplayRule](#TotalAmountDisplayRule)||<a href="VendFormletterVendorFacingFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity</a>|
|[SalesTaxDisplayRule](#SalesTaxDisplayRule)||<a href="VendFormletterVendorFacingFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity</a>|
|[IsSalesTaxExemptBalanceAmountDisplayedSeparately](#IsSalesTaxExemptBalanceAmountDisplayedSeparately)||<a href="VendFormletterVendorFacingFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity</a>|
|[VendorProductDescriptionDisplayRule](#VendorProductDescriptionDisplayRule)||<a href="VendFormletterVendorFacingFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity</a>|
|[ProductDimensionsDisplayRule](#ProductDimensionsDisplayRule)||<a href="VendFormletterVendorFacingFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity</a>|
|[ProductDimensionsDisplaySeparator](#ProductDimensionsDisplaySeparator)||<a href="VendFormletterVendorFacingFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity</a>|
|[IsDisplayedProductDescriptionIncludingProductName](#IsDisplayedProductDescriptionIncludingProductName)||<a href="VendFormletterVendorFacingFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity</a>|
|[ProductNumberDisplayRule](#ProductNumberDisplayRule)||<a href="VendFormletterVendorFacingFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity</a>|
|[BackingTable_VendFormletterParametersRelationshipId](#BackingTable_VendFormletterParametersRelationshipId)||<a href="VendFormletterVendorFacingFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendFormletterVendorFacingFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity</a>|

### <a href=#AreEuroAmountsDisplayed name="AreEuroAmountsDisplayed">AreEuroAmountsDisplayed</a>

First included in: ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreEuroAmountsDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalAmountDisplayRule name="TotalAmountDisplayRule">TotalAmountDisplayRule</a>

First included in: ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmountDisplayRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxDisplayRule name="SalesTaxDisplayRule">SalesTaxDisplayRule</a>

First included in: ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxDisplayRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesTaxExemptBalanceAmountDisplayedSeparately name="IsSalesTaxExemptBalanceAmountDisplayedSeparately">IsSalesTaxExemptBalanceAmountDisplayedSeparately</a>

First included in: ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesTaxExemptBalanceAmountDisplayedSeparately attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorProductDescriptionDisplayRule name="VendorProductDescriptionDisplayRule">VendorProductDescriptionDisplayRule</a>

First included in: ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorProductDescriptionDisplayRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDimensionsDisplayRule name="ProductDimensionsDisplayRule">ProductDimensionsDisplayRule</a>

First included in: ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDimensionsDisplayRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDimensionsDisplaySeparator name="ProductDimensionsDisplaySeparator">ProductDimensionsDisplaySeparator</a>

First included in: ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDimensionsDisplaySeparator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDisplayedProductDescriptionIncludingProductName name="IsDisplayedProductDescriptionIncludingProductName">IsDisplayedProductDescriptionIncludingProductName</a>

First included in: ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDisplayedProductDescriptionIncludingProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumberDisplayRule name="ProductNumberDisplayRule">ProductNumberDisplayRule</a>

First included in: ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumberDisplayRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_VendFormletterParametersRelationshipId name="BackingTable_VendFormletterParametersRelationshipId">BackingTable_VendFormletterParametersRelationshipId</a>

First included in: ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendFormletterParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsPayable/Parameter/VendFormletterParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Parameter/VendFormletterParameters.cdm.json/VendFormletterParameters</a></td><td><a href="../../../Tables/Finance/AccountsPayable/Parameter/VendFormletterParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/VendFormletterVendorFacingFormPrintingConfigurationEntity (this entity)  

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

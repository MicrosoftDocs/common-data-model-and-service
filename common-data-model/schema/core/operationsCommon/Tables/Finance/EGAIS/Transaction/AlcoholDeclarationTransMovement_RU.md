---
title: AlcoholDeclarationTransMovement_RU in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Alcohol declaration lines - movement in Transaction(AlcoholDeclarationTransMovement_RU)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/EGAIS/Transaction/AlcoholDeclarationTransMovement_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AlcoholDeclarationTransMovement_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Alcohol declaration lines - movement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[AlcoholDeclarationType](#AlcoholDeclarationType)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[AlcoholProductionTypeId](#AlcoholProductionTypeId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[BranchId](#BranchId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[ExportSalesQty](#ExportSalesQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[ImportPurchQty](#ImportPurchQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[InternalTransferIssueQty](#InternalTransferIssueQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[InternalTransferReceiptQty](#InternalTransferReceiptQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[JournalId](#JournalId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[ManufacturerId](#ManufacturerId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[ManufacturerPurchQty](#ManufacturerPurchQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[OtherIssueQty](#OtherIssueQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[OtherRecieptQty](#OtherRecieptQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[PeriodEndQty](#PeriodEndQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[PeriodStartQty](#PeriodStartQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[PurchReturnQty](#PurchReturnQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[RetailSalesQty](#RetailSalesQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[SalesReturnQty](#SalesReturnQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[TotalIssueQty](#TotalIssueQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[TotalPurchQty](#TotalPurchQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[TotalReceiptQty](#TotalReceiptQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[TotalSalesQty](#TotalSalesQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[WholesalePurchQty](#WholesalePurchQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[WholesaleSalesQty](#WholesaleSalesQty)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[Relationship_AlcoholDeclarationJournalTable_RURelationshipId](#Relationship_AlcoholDeclarationJournalTable_RURelationshipId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[Relationship_AlcoholDeclarationJournalTransBranch_RURelationshipId](#Relationship_AlcoholDeclarationJournalTransBranch_RURelationshipId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[Relationship_AlcoholManufacturer_RURelationshipId](#Relationship_AlcoholManufacturer_RURelationshipId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[Relationship_AlcoholProductionType_RURelationshipId](#Relationship_AlcoholProductionType_RURelationshipId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[Relationship_Branches_RURelationshipId](#Relationship_Branches_RURelationshipId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AlcoholDeclarationTransMovement_RU.md" target="_blank">Transaction/AlcoholDeclarationTransMovement_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AlcoholDeclarationTransMovement_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AlcoholDeclarationType name="AlcoholDeclarationType">AlcoholDeclarationType</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlcoholDeclarationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AlcoholProductionTypeId name="AlcoholProductionTypeId">AlcoholProductionTypeId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlcoholProductionTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BranchId name="BranchId">BranchId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BranchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportSalesQty name="ExportSalesQty">ExportSalesQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>For export</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportSalesQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For export</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ImportPurchQty name="ImportPurchQty">ImportPurchQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From import</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImportPurchQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>From import</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InternalTransferIssueQty name="InternalTransferIssueQty">InternalTransferIssueQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Moving within the same organization</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalTransferIssueQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Moving within the same organization</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InternalTransferReceiptQty name="InternalTransferReceiptQty">InternalTransferReceiptQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Moving within the same organization</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalTransferReceiptQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Moving within the same organization</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManufacturerId name="ManufacturerId">ManufacturerId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManufacturerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManufacturerPurchQty name="ManufacturerPurchQty">ManufacturerPurchQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From the manufacturers</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManufacturerPurchQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>From the manufacturers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OtherIssueQty name="OtherIssueQty">OtherIssueQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other issue transactions</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OtherIssueQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Other issue transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OtherRecieptQty name="OtherRecieptQty">OtherRecieptQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other receipt</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OtherRecieptQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Other receipt</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PeriodEndQty name="PeriodEndQty">PeriodEndQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity at end of reporting period</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodEndQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity at end of reporting period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PeriodStartQty name="PeriodStartQty">PeriodStartQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity at start of reporting period</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodStartQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity at start of reporting period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchReturnQty name="PurchReturnQty">PurchReturnQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Production return</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchReturnQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production return</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RetailSalesQty name="RetailSalesQty">RetailSalesQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To the retail trade organizations</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailSalesQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>To the retail trade organizations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesReturnQty name="SalesReturnQty">SalesReturnQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Return to vendors</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesReturnQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Return to vendors</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalIssueQty name="TotalIssueQty">TotalIssueQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total issue transactions</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalIssueQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total issue transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalPurchQty name="TotalPurchQty">TotalPurchQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total purchases</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPurchQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total purchases</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalReceiptQty name="TotalReceiptQty">TotalReceiptQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total receipt</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalReceiptQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total receipt</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalSalesQty name="TotalSalesQty">TotalSalesQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total sales</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalSalesQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WholesalePurchQty name="WholesalePurchQty">WholesalePurchQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From the wholesale trade organizations</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WholesalePurchQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>From the wholesale trade organizations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WholesaleSalesQty name="WholesaleSalesQty">WholesaleSalesQty</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To the wholesale trade organizations</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WholesaleSalesQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>To the wholesale trade organizations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

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

### <a href=#Relationship_AlcoholDeclarationJournalTable_RURelationshipId name="Relationship_AlcoholDeclarationJournalTable_RURelationshipId">Relationship_AlcoholDeclarationJournalTable_RURelationshipId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AlcoholDeclarationJournalTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/AlcoholDeclarationJournalTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/WorksheetHeader/AlcoholDeclarationJournalTable_RU.cdm.json/AlcoholDeclarationJournalTable_RU</a></td><td><a href="../WorksheetHeader/AlcoholDeclarationJournalTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AlcoholDeclarationJournalTransBranch_RURelationshipId name="Relationship_AlcoholDeclarationJournalTransBranch_RURelationshipId">Relationship_AlcoholDeclarationJournalTransBranch_RURelationshipId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AlcoholDeclarationJournalTransBranch_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/AlcoholDeclarationJournalTransBranch_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/WorksheetLine/AlcoholDeclarationJournalTransBranch_RU.cdm.json/AlcoholDeclarationJournalTransBranch_RU</a></td><td><a href="../WorksheetLine/AlcoholDeclarationJournalTransBranch_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AlcoholManufacturer_RURelationshipId name="Relationship_AlcoholManufacturer_RURelationshipId">Relationship_AlcoholManufacturer_RURelationshipId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AlcoholManufacturer_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AlcoholProductionType_RURelationshipId name="Relationship_AlcoholProductionType_RURelationshipId">Relationship_AlcoholProductionType_RURelationshipId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AlcoholProductionType_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/AlcoholProductionType_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/Parameter/AlcoholProductionType_RU.cdm.json/AlcoholProductionType_RU</a></td><td><a href="../Parameter/AlcoholProductionType_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Branches_RURelationshipId name="Relationship_Branches_RURelationshipId">Relationship_Branches_RURelationshipId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Branches_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Group/Branches_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Group/Branches_RU.cdm.json/Branches_RU</a></td><td><a href="../../APARShared/Group/Branches_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/AlcoholDeclarationTransMovement_RU (this entity)  

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

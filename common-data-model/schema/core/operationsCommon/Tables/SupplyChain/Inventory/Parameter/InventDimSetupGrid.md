---
title: InventDimSetupGrid in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# View dimensions in Parameter(InventDimSetupGrid)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Parameter/InventDimSetupGrid.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventDimSetupGrid/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>View dimensions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[dimFieldId](#dimFieldId)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[MCRShowGridMCROrderEventTable](#MCRShowGridMCROrderEventTable)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[MCRShowGridMCRPickingWorkbenchWaveTrans](#MCRShowGridMCRPickingWorkbenchWaveTrans)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[MCRShowGridMCRProdBOMReportFinish](#MCRShowGridMCRProdBOMReportFinish)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[MCRShowGridMCRShipmentItem](#MCRShowGridMCRShipmentItem)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridAsset](#ShowGridAsset)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridBOMMain](#ShowGridBOMMain)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridCertificateOfAnalysis](#ShowGridCertificateOfAnalysis)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridInventBlocking](#ShowGridInventBlocking)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridInventCounting](#ShowGridInventCounting)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridInventLossProfit](#ShowGridInventLossProfit)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridInventQuarantineOrder](#ShowGridInventQuarantineOrder)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridInventTrans](#ShowGridInventTrans)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridInventTransaction](#ShowGridInventTransaction)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridInventTransfer](#ShowGridInventTransfer)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridNonConformance](#ShowGridNonConformance)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridProdJournalBOM](#ShowGridProdJournalBOM)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridProdJournalProd](#ShowGridProdJournalProd)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridProdJourRelease_RU](#ShowGridProdJourRelease_RU)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridProdLine](#ShowGridProdLine)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridProduction](#ShowGridProduction)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridProject](#ShowGridProject)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridPurchLine](#ShowGridPurchLine)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridQualityOrder](#ShowGridQualityOrder)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridSalesLine](#ShowGridSalesLine)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridSalesQuotationLine](#ShowGridSalesQuotationLine)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridSalesQuotationLineProject](#ShowGridSalesQuotationLineProject)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridTransferOrder](#ShowGridTransferOrder)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridWMSPickingLines](#ShowGridWMSPickingLines)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridWMSReception](#ShowGridWMSReception)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridWMSReceptionProd](#ShowGridWMSReceptionProd)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridInventOwnershipChange](#ShowGridInventOwnershipChange)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[ShowGridConsignmentReplenishmentOrderLine](#ShowGridConsignmentReplenishmentOrderLine)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[DataAreaId](#DataAreaId)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventDimSetupGrid.md" target="_blank">Parameter/InventDimSetupGrid</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventDimSetupGrid/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#dimFieldId name="dimFieldId">dimFieldId</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dimFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRShowGridMCROrderEventTable name="MCRShowGridMCROrderEventTable">MCRShowGridMCROrderEventTable</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRShowGridMCROrderEventTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MCRShowGridMCRPickingWorkbenchWaveTrans name="MCRShowGridMCRPickingWorkbenchWaveTrans">MCRShowGridMCRPickingWorkbenchWaveTrans</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRShowGridMCRPickingWorkbenchWaveTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MCRShowGridMCRProdBOMReportFinish name="MCRShowGridMCRProdBOMReportFinish">MCRShowGridMCRProdBOMReportFinish</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRShowGridMCRProdBOMReportFinish attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MCRShowGridMCRShipmentItem name="MCRShowGridMCRShipmentItem">MCRShowGridMCRShipmentItem</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRShowGridMCRShipmentItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridAsset name="ShowGridAsset">ShowGridAsset</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridAsset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridBOMMain name="ShowGridBOMMain">ShowGridBOMMain</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridBOMMain attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridCertificateOfAnalysis name="ShowGridCertificateOfAnalysis">ShowGridCertificateOfAnalysis</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridCertificateOfAnalysis attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridInventBlocking name="ShowGridInventBlocking">ShowGridInventBlocking</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridInventBlocking attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridInventCounting name="ShowGridInventCounting">ShowGridInventCounting</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridInventCounting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridInventLossProfit name="ShowGridInventLossProfit">ShowGridInventLossProfit</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridInventLossProfit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridInventQuarantineOrder name="ShowGridInventQuarantineOrder">ShowGridInventQuarantineOrder</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridInventQuarantineOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridInventTrans name="ShowGridInventTrans">ShowGridInventTrans</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridInventTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridInventTransaction name="ShowGridInventTransaction">ShowGridInventTransaction</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridInventTransaction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridInventTransfer name="ShowGridInventTransfer">ShowGridInventTransfer</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridInventTransfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridNonConformance name="ShowGridNonConformance">ShowGridNonConformance</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridNonConformance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridProdJournalBOM name="ShowGridProdJournalBOM">ShowGridProdJournalBOM</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridProdJournalBOM attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridProdJournalProd name="ShowGridProdJournalProd">ShowGridProdJournalProd</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridProdJournalProd attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridProdJourRelease_RU name="ShowGridProdJourRelease_RU">ShowGridProdJourRelease_RU</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridProdJourRelease_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridProdLine name="ShowGridProdLine">ShowGridProdLine</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridProdLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridProduction name="ShowGridProduction">ShowGridProduction</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridProduction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridProject name="ShowGridProject">ShowGridProject</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridProject attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridPurchLine name="ShowGridPurchLine">ShowGridPurchLine</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridPurchLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridQualityOrder name="ShowGridQualityOrder">ShowGridQualityOrder</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridQualityOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridSalesLine name="ShowGridSalesLine">ShowGridSalesLine</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridSalesLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridSalesQuotationLine name="ShowGridSalesQuotationLine">ShowGridSalesQuotationLine</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridSalesQuotationLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridSalesQuotationLineProject name="ShowGridSalesQuotationLineProject">ShowGridSalesQuotationLineProject</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridSalesQuotationLineProject attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridTransferOrder name="ShowGridTransferOrder">ShowGridTransferOrder</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridTransferOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridWMSPickingLines name="ShowGridWMSPickingLines">ShowGridWMSPickingLines</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridWMSPickingLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridWMSReception name="ShowGridWMSReception">ShowGridWMSReception</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridWMSReception attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridWMSReceptionProd name="ShowGridWMSReceptionProd">ShowGridWMSReceptionProd</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridWMSReceptionProd attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridInventOwnershipChange name="ShowGridInventOwnershipChange">ShowGridInventOwnershipChange</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridInventOwnershipChange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGridConsignmentReplenishmentOrderLine name="ShowGridConsignmentReplenishmentOrderLine">ShowGridConsignmentReplenishmentOrderLine</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridConsignmentReplenishmentOrderLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/InventDimSetupGrid (this entity)  

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

First included in: Parameter/InventDimSetupGrid (this entity)  

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

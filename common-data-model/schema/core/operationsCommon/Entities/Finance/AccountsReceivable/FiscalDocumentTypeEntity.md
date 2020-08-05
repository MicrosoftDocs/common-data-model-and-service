---
title: FiscalDocumentTypeEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Fiscal document types in AccountsReceivable(FiscalDocumentTypeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/FiscalDocumentTypeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal document types</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[FiscalDocumentType](#FiscalDocumentType)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[Name](#Name)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[Series](#Series)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[FiscalDocumentIssueDate](#FiscalDocumentIssueDate)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[DocumentModel](#DocumentModel)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[Specie](#Specie)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[ElectronicFiscalDocumentForServices](#ElectronicFiscalDocumentForServices)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[ERExportFormatMappingName](#ERExportFormatMappingName)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[ERExportFormatSolutionName](#ERExportFormatSolutionName)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[ERExportFormatVendorUrl](#ERExportFormatVendorUrl)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[ExportFileLayoutGroup](#ExportFileLayoutGroup)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[ReturnFileLayoutGroup](#ReturnFileLayoutGroup)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[MaxItemLines](#MaxItemLines)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[MaxItemDescriptionSize](#MaxItemDescriptionSize)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[CutOffItemDescription](#CutOffItemDescription)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[MaxServiceItemLines](#MaxServiceItemLines)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[MaxServiceItemDescription](#MaxServiceItemDescription)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[CutOffServiceItemDescription](#CutOffServiceItemDescription)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[MaxMemoLines](#MaxMemoLines)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[MaxMemoDescriptionSize](#MaxMemoDescriptionSize)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[CutoffMemoDescription](#CutoffMemoDescription)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[PrintDeliveryAddressAtMemo](#PrintDeliveryAddressAtMemo)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[MaxInstallments](#MaxInstallments)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[FiscalEstablishment_BR](#FiscalEstablishment_BR)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[FiscalDocumentTypeBR](#FiscalDocumentTypeBR)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[FiscalDocumentModel](#FiscalDocumentModel)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[FiscalDocumentTypeNumberSequence](#FiscalDocumentTypeNumberSequence)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[Company](#Company)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[FiscalDocumentNumberSequence](#FiscalDocumentNumberSequence)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[BackingTable_FiscalDocumentType_BRRelationshipId](#BackingTable_FiscalDocumentType_BRRelationshipId)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="FiscalDocumentTypeEntity.md" target="_blank">AccountsReceivable/FiscalDocumentTypeEntity</a>|

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentType name="FiscalDocumentType">FiscalDocumentType</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Series name="Series">Series</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Series attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentIssueDate name="FiscalDocumentIssueDate">FiscalDocumentIssueDate</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentIssueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentModel name="DocumentModel">DocumentModel</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Specie name="Specie">Specie</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Specie attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFiscalDocumentForServices name="ElectronicFiscalDocumentForServices">ElectronicFiscalDocumentForServices</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFiscalDocumentForServices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERExportFormatMappingName name="ERExportFormatMappingName">ERExportFormatMappingName</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Format mapping export name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERExportFormatMappingName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Format mapping export name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERExportFormatSolutionName name="ERExportFormatSolutionName">ERExportFormatSolutionName</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Format mapping export solution name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERExportFormatSolutionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Format mapping export solution name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERExportFormatVendorUrl name="ERExportFormatVendorUrl">ERExportFormatVendorUrl</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Format mapping export vendor url</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERExportFormatVendorUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Format mapping export vendor url</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportFileLayoutGroup name="ExportFileLayoutGroup">ExportFileLayoutGroup</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportFileLayoutGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnFileLayoutGroup name="ReturnFileLayoutGroup">ReturnFileLayoutGroup</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnFileLayoutGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxItemLines name="MaxItemLines">MaxItemLines</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxItemLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxItemDescriptionSize name="MaxItemDescriptionSize">MaxItemDescriptionSize</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxItemDescriptionSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CutOffItemDescription name="CutOffItemDescription">CutOffItemDescription</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CutOffItemDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxServiceItemLines name="MaxServiceItemLines">MaxServiceItemLines</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxServiceItemLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxServiceItemDescription name="MaxServiceItemDescription">MaxServiceItemDescription</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxServiceItemDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CutOffServiceItemDescription name="CutOffServiceItemDescription">CutOffServiceItemDescription</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CutOffServiceItemDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxMemoLines name="MaxMemoLines">MaxMemoLines</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxMemoLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxMemoDescriptionSize name="MaxMemoDescriptionSize">MaxMemoDescriptionSize</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxMemoDescriptionSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CutoffMemoDescription name="CutoffMemoDescription">CutoffMemoDescription</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CutoffMemoDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintDeliveryAddressAtMemo name="PrintDeliveryAddressAtMemo">PrintDeliveryAddressAtMemo</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintDeliveryAddressAtMemo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxInstallments name="MaxInstallments">MaxInstallments</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxInstallments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishment_BR name="FiscalEstablishment_BR">FiscalEstablishment_BR</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishment_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentTypeBR name="FiscalDocumentTypeBR">FiscalDocumentTypeBR</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTypeBR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentModel name="FiscalDocumentModel">FiscalDocumentModel</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentTypeNumberSequence name="FiscalDocumentTypeNumberSequence">FiscalDocumentTypeNumberSequence</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTypeNumberSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentNumberSequence name="FiscalDocumentNumberSequence">FiscalDocumentNumberSequence</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentNumberSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_FiscalDocumentType_BRRelationshipId name="BackingTable_FiscalDocumentType_BRRelationshipId">BackingTable_FiscalDocumentType_BRRelationshipId</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FiscalDocumentType_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.cdm.json/FiscalDocumentType_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/FiscalDocumentTypeEntity (this entity)  

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

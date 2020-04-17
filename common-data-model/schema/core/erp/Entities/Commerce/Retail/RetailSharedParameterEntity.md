---
title: RetailSharedParameterEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @Commerce:COMM5792

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailSharedParameterEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@Commerce:COMM5792</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AllowTerminalAssociationFromDevice](#AllowTerminalAssociationFromDevice)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[CatalogDefaultAttributeGroup](#CatalogDefaultAttributeGroup)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[CatalogAttributeBulkEditMaxRows](#CatalogAttributeBulkEditMaxRows)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[CategoryDefaultAttributeGroup](#CategoryDefaultAttributeGroup)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[CustomerDefaultAttributeGroup](#CustomerDefaultAttributeGroup)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[DeviceTokenAlgorithm](#DeviceTokenAlgorithm)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[EarnLoyaltyOffline](#EarnLoyaltyOffline)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[EFTPasswordEncryption](#EFTPasswordEncryption)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[EntityValidationTemplate](#EntityValidationTemplate)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[ExchangeRateType](#ExchangeRateType)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[HtmlAttributeType](#HtmlAttributeType)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[ImagesAttributeType](#ImagesAttributeType)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[ItemLabelCreation](#ItemLabelCreation)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[Key](#Key)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[LocalStoreId](#LocalStoreId)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[ProductDefaultAttributeGroup](#ProductDefaultAttributeGroup)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[SharepointAssetPickerUrl](#SharepointAssetPickerUrl)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[ShelfLabelCreation](#ShelfLabelCreation)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[StaffPasswordHash](#StaffPasswordHash)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[TransactionServiceProfile](#TransactionServiceProfile)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[TransactionServicePasswordEncryption](#TransactionServicePasswordEncryption)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[VideosAttributeType](#VideosAttributeType)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[WorkerDefaultAttributeGroup](#WorkerDefaultAttributeGroup)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[DeploymentRootPath](#DeploymentRootPath)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[ExchangeRateTypeName](#ExchangeRateTypeName)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[WindowsPhoneAppInsightsInstrumentationKey](#WindowsPhoneAppInsightsInstrumentationKey)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[AsyncClientAppInsightsInstrumentationKey](#AsyncClientAppInsightsInstrumentationKey)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[HardwareStationAppInsightsInstrumentationKey](#HardwareStationAppInsightsInstrumentationKey)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[CloudPosAppInsightsInstrumentationKey](#CloudPosAppInsightsInstrumentationKey)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[RetailServerAppInsightsInstrumentationKey](#RetailServerAppInsightsInstrumentationKey)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[ClientAppInsightsInstrumentationKey](#ClientAppInsightsInstrumentationKey)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[CatalogDefaultAttributeGroupName](#CatalogDefaultAttributeGroupName)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[CategoryDefaultAttributeGroupName](#CategoryDefaultAttributeGroupName)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[CustomerDefaultAttributeGroupName](#CustomerDefaultAttributeGroupName)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[ProductDefaultAttributeGroupName](#ProductDefaultAttributeGroupName)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[WorkerDefaultAttributeGroupName](#WorkerDefaultAttributeGroupName)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[HtmlAttributeTypeName](#HtmlAttributeTypeName)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[ImagesAttributeTypeName](#ImagesAttributeTypeName)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[VideosAttributeTypeName](#VideosAttributeTypeName)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[PostLoyaltyPointsPerSalesLine](#PostLoyaltyPointsPerSalesLine)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[BlockTransferBetweenDifferentLoyalty](#BlockTransferBetweenDifferentLoyalty)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[EnableOmniChannelPayments](#EnableOmniChannelPayments)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[EnableFiscalIntegration](#EnableFiscalIntegration)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[RecoListEnabled](#RecoListEnabled)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[RecoListBestsellingTransactionsIntervalDays](#RecoListBestsellingTransactionsIntervalDays)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[RecoListTrendingMaxAgeDays](#RecoListTrendingMaxAgeDays)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[RecoListTrendingTransactionsIntervalDays](#RecoListTrendingTransactionsIntervalDays)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[RecoPersonalizationEnabled](#RecoPersonalizationEnabled)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[EnableLocalStorageBackup](#EnableLocalStorageBackup)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[UseSalesReceiptAsDefaultReceiptTypeInJournal](#UseSalesReceiptAsDefaultReceiptTypeInJournal)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[ProductAvailabilityJobPolicy](#ProductAvailabilityJobPolicy)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[InventoryAvailabilityCachePeriod](#InventoryAvailabilityCachePeriod)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[InventoryAvailabilitySumDeltaCachePeriod](#InventoryAvailabilitySumDeltaCachePeriod)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[ValidateCustomerToRedeemLoyalty](#ValidateCustomerToRedeemLoyalty)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[EnableAdvancedExternalGiftCard](#EnableAdvancedExternalGiftCard)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|
|[BackingTable_RetailSharedParametersRelationshipId](#BackingTable_RetailSharedParametersRelationshipId)||<a href="RetailSharedParameterEntity.md" target="_blank">Retail/RetailSharedParameterEntity</a>|

### <a href=#AllowTerminalAssociationFromDevice name="AllowTerminalAssociationFromDevice">AllowTerminalAssociationFromDevice</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTerminalAssociationFromDevice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatalogDefaultAttributeGroup name="CatalogDefaultAttributeGroup">CatalogDefaultAttributeGroup</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogDefaultAttributeGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatalogAttributeBulkEditMaxRows name="CatalogAttributeBulkEditMaxRows">CatalogAttributeBulkEditMaxRows</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogAttributeBulkEditMaxRows attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryDefaultAttributeGroup name="CategoryDefaultAttributeGroup">CategoryDefaultAttributeGroup</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryDefaultAttributeGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerDefaultAttributeGroup name="CustomerDefaultAttributeGroup">CustomerDefaultAttributeGroup</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDefaultAttributeGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeviceTokenAlgorithm name="DeviceTokenAlgorithm">DeviceTokenAlgorithm</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeviceTokenAlgorithm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EarnLoyaltyOffline name="EarnLoyaltyOffline">EarnLoyaltyOffline</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarnLoyaltyOffline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFTPasswordEncryption name="EFTPasswordEncryption">EFTPasswordEncryption</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFTPasswordEncryption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntityValidationTemplate name="EntityValidationTemplate">EntityValidationTemplate</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityValidationTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateType name="ExchangeRateType">ExchangeRateType</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HtmlAttributeType name="HtmlAttributeType">HtmlAttributeType</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HtmlAttributeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImagesAttributeType name="ImagesAttributeType">ImagesAttributeType</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImagesAttributeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemLabelCreation name="ItemLabelCreation">ItemLabelCreation</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemLabelCreation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocalStoreId name="LocalStoreId">LocalStoreId</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocalStoreId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDefaultAttributeGroup name="ProductDefaultAttributeGroup">ProductDefaultAttributeGroup</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDefaultAttributeGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SharepointAssetPickerUrl name="SharepointAssetPickerUrl">SharepointAssetPickerUrl</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharepointAssetPickerUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShelfLabelCreation name="ShelfLabelCreation">ShelfLabelCreation</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShelfLabelCreation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StaffPasswordHash name="StaffPasswordHash">StaffPasswordHash</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StaffPasswordHash attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionServiceProfile name="TransactionServiceProfile">TransactionServiceProfile</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionServiceProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionServicePasswordEncryption name="TransactionServicePasswordEncryption">TransactionServicePasswordEncryption</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionServicePasswordEncryption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VideosAttributeType name="VideosAttributeType">VideosAttributeType</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VideosAttributeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerDefaultAttributeGroup name="WorkerDefaultAttributeGroup">WorkerDefaultAttributeGroup</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerDefaultAttributeGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeploymentRootPath name="DeploymentRootPath">DeploymentRootPath</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeploymentRootPath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateTypeName name="ExchangeRateTypeName">ExchangeRateTypeName</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WindowsPhoneAppInsightsInstrumentationKey name="WindowsPhoneAppInsightsInstrumentationKey">WindowsPhoneAppInsightsInstrumentationKey</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WindowsPhoneAppInsightsInstrumentationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AsyncClientAppInsightsInstrumentationKey name="AsyncClientAppInsightsInstrumentationKey">AsyncClientAppInsightsInstrumentationKey</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AsyncClientAppInsightsInstrumentationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HardwareStationAppInsightsInstrumentationKey name="HardwareStationAppInsightsInstrumentationKey">HardwareStationAppInsightsInstrumentationKey</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardwareStationAppInsightsInstrumentationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CloudPosAppInsightsInstrumentationKey name="CloudPosAppInsightsInstrumentationKey">CloudPosAppInsightsInstrumentationKey</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CloudPosAppInsightsInstrumentationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailServerAppInsightsInstrumentationKey name="RetailServerAppInsightsInstrumentationKey">RetailServerAppInsightsInstrumentationKey</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailServerAppInsightsInstrumentationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClientAppInsightsInstrumentationKey name="ClientAppInsightsInstrumentationKey">ClientAppInsightsInstrumentationKey</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClientAppInsightsInstrumentationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatalogDefaultAttributeGroupName name="CatalogDefaultAttributeGroupName">CatalogDefaultAttributeGroupName</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogDefaultAttributeGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryDefaultAttributeGroupName name="CategoryDefaultAttributeGroupName">CategoryDefaultAttributeGroupName</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryDefaultAttributeGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerDefaultAttributeGroupName name="CustomerDefaultAttributeGroupName">CustomerDefaultAttributeGroupName</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDefaultAttributeGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDefaultAttributeGroupName name="ProductDefaultAttributeGroupName">ProductDefaultAttributeGroupName</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDefaultAttributeGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerDefaultAttributeGroupName name="WorkerDefaultAttributeGroupName">WorkerDefaultAttributeGroupName</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerDefaultAttributeGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HtmlAttributeTypeName name="HtmlAttributeTypeName">HtmlAttributeTypeName</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HtmlAttributeTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImagesAttributeTypeName name="ImagesAttributeTypeName">ImagesAttributeTypeName</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImagesAttributeTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VideosAttributeTypeName name="VideosAttributeTypeName">VideosAttributeTypeName</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VideosAttributeTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostLoyaltyPointsPerSalesLine name="PostLoyaltyPointsPerSalesLine">PostLoyaltyPointsPerSalesLine</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostLoyaltyPointsPerSalesLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BlockTransferBetweenDifferentLoyalty name="BlockTransferBetweenDifferentLoyalty">BlockTransferBetweenDifferentLoyalty</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockTransferBetweenDifferentLoyalty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableOmniChannelPayments name="EnableOmniChannelPayments">EnableOmniChannelPayments</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableOmniChannelPayments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableFiscalIntegration name="EnableFiscalIntegration">EnableFiscalIntegration</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableFiscalIntegration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecoListEnabled name="RecoListEnabled">RecoListEnabled</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoListEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecoListBestsellingTransactionsIntervalDays name="RecoListBestsellingTransactionsIntervalDays">RecoListBestsellingTransactionsIntervalDays</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoListBestsellingTransactionsIntervalDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecoListTrendingMaxAgeDays name="RecoListTrendingMaxAgeDays">RecoListTrendingMaxAgeDays</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoListTrendingMaxAgeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecoListTrendingTransactionsIntervalDays name="RecoListTrendingTransactionsIntervalDays">RecoListTrendingTransactionsIntervalDays</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoListTrendingTransactionsIntervalDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecoPersonalizationEnabled name="RecoPersonalizationEnabled">RecoPersonalizationEnabled</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoPersonalizationEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableLocalStorageBackup name="EnableLocalStorageBackup">EnableLocalStorageBackup</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableLocalStorageBackup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseSalesReceiptAsDefaultReceiptTypeInJournal name="UseSalesReceiptAsDefaultReceiptTypeInJournal">UseSalesReceiptAsDefaultReceiptTypeInJournal</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSalesReceiptAsDefaultReceiptTypeInJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductAvailabilityJobPolicy name="ProductAvailabilityJobPolicy">ProductAvailabilityJobPolicy</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAvailabilityJobPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryAvailabilityCachePeriod name="InventoryAvailabilityCachePeriod">InventoryAvailabilityCachePeriod</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAvailabilityCachePeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryAvailabilitySumDeltaCachePeriod name="InventoryAvailabilitySumDeltaCachePeriod">InventoryAvailabilitySumDeltaCachePeriod</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAvailabilitySumDeltaCachePeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateCustomerToRedeemLoyalty name="ValidateCustomerToRedeemLoyalty">ValidateCustomerToRedeemLoyalty</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateCustomerToRedeemLoyalty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableAdvancedExternalGiftCard name="EnableAdvancedExternalGiftCard">EnableAdvancedExternalGiftCard</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableAdvancedExternalGiftCard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailSharedParametersRelationshipId name="BackingTable_RetailSharedParametersRelationshipId">BackingTable_RetailSharedParametersRelationshipId</a>

First included in: Retail/RetailSharedParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailSharedParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

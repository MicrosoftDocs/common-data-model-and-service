---
title: RetailSharedParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailSharedParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Parameter/RetailSharedParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailSharedParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[AllowTerminalAssociationFromDevice](#AllowTerminalAssociationFromDevice)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[barcodeSetupId](#barcodeSetupId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[CatalogDefaultAttributeGroup](#CatalogDefaultAttributeGroup)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[CatAttriBulkEditMaxRows](#CatAttriBulkEditMaxRows)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[CategoryDefaultAttributeGroup](#CategoryDefaultAttributeGroup)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[CustomerDefaultAttributeGroup](#CustomerDefaultAttributeGroup)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[DeviceTokenAlgorithm](#DeviceTokenAlgorithm)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[EarnLoyaltyOffline](#EarnLoyaltyOffline)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[EFTPasswordEncryption](#EFTPasswordEncryption)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[EPRefreshIntervalInSeconds](#EPRefreshIntervalInSeconds)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ExchangeRateType](#ExchangeRateType)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[HtmlAttributeType](#HtmlAttributeType)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ImagesAttributeType](#ImagesAttributeType)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ItemLabelCreation](#ItemLabelCreation)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Key](#Key)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[LocalStoreId](#LocalStoreId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ProductDefaultAttributeGroup](#ProductDefaultAttributeGroup)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[SharepointAssetPickerUrl](#SharepointAssetPickerUrl)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ShelfLabelCreation](#ShelfLabelCreation)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[StaffPasswordHash](#StaffPasswordHash)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[transactionServiceProfile](#transactionServiceProfile)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[TSPasswordEncryption](#TSPasswordEncryption)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[VideosAttributeType](#VideosAttributeType)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[WorkerDefaultAttributeGroup](#WorkerDefaultAttributeGroup)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ConsumerEFDocCscEncryption](#ConsumerEFDocCscEncryption)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[DeploymentRootPath](#DeploymentRootPath)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[SideloadingKey](#SideloadingKey)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ClxStorageSasKeyLifetimeInHours](#ClxStorageSasKeyLifetimeInHours)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ClxStorageSasKeyRecycleWindowInHours](#ClxStorageSasKeyRecycleWindowInHours)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[DeviceTokenExpiration](#DeviceTokenExpiration)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[EntityValidationTemplate](#EntityValidationTemplate)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[DefaultHWSSelfServicePkg](#DefaultHWSSelfServicePkg)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[DefaultHardwarePeripheralSimulatorPkg](#DefaultHardwarePeripheralSimulatorPkg)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[DefaultRetailStoreUnitSelfServicePkg](#DefaultRetailStoreUnitSelfServicePkg)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[HardwareStationAppInsightsInstrumentationKey](#HardwareStationAppInsightsInstrumentationKey)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ClientAppInsightsInstrumentationKey](#ClientAppInsightsInstrumentationKey)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[EnvironmentId](#EnvironmentId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[TenantId](#TenantId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[CloudPosAppInsightsInstrumentationKey](#CloudPosAppInsightsInstrumentationKey)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[RetailServerAppInsightsInstrumentationKey](#RetailServerAppInsightsInstrumentationKey)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[AsyncClientAppInsightsInstrumentationKey](#AsyncClientAppInsightsInstrumentationKey)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[WindowsPhoneAppInsightsInstrumentationKey](#WindowsPhoneAppInsightsInstrumentationKey)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[DefaultMPOSWindowsPhonePkg](#DefaultMPOSWindowsPhonePkg)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[DefaultMPOSAndroidPkg](#DefaultMPOSAndroidPkg)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[DefaultMPOSiOSPkg](#DefaultMPOSiOSPkg)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[CouponBarcodeSetupId](#CouponBarcodeSetupId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[LegacyRegKeyData2Value](#LegacyRegKeyData2Value)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ExtensionServiceUrl](#ExtensionServiceUrl)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ProvisioningUrl](#ProvisioningUrl)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[AsyncServerConnectorServiceAppInsightsInstrumentationKey](#AsyncServerConnectorServiceAppInsightsInstrumentationKey)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[RealtimeServiceAX63AppInsightsInstrumentationKey](#RealtimeServiceAX63AppInsightsInstrumentationKey)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[LegacyDeviceTokenAlgorithm](#LegacyDeviceTokenAlgorithm)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[PostLoyaltyPointsPerSalesLine](#PostLoyaltyPointsPerSalesLine)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[BlockTransferBetweenDifferentLoyalty](#BlockTransferBetweenDifferentLoyalty)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[EnableOmniChannelPayments](#EnableOmniChannelPayments)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[EnableFiscalIntegration](#EnableFiscalIntegration)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[RecoListEnabled](#RecoListEnabled)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[RecoPersonalizationEnabled](#RecoPersonalizationEnabled)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[RecoListTrendingMaxAgeDays](#RecoListTrendingMaxAgeDays)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[RecoListTrendingTransactionsIntervalDays](#RecoListTrendingTransactionsIntervalDays)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[RecoListBestsellingTransactionsIntervalDays](#RecoListBestsellingTransactionsIntervalDays)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[EnableLocalStorageBackup](#EnableLocalStorageBackup)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[UseSalesReceiptAsDefaultReceiptTypeInJournal](#UseSalesReceiptAsDefaultReceiptTypeInJournal)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ProductAvailabilityJobPolicy](#ProductAvailabilityJobPolicy)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[InventoryAvailabilityCachePeriod](#InventoryAvailabilityCachePeriod)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[InventoryAvailabilitySumDeltaCachePeriod](#InventoryAvailabilitySumDeltaCachePeriod)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[TaskManagementInitialized](#TaskManagementInitialized)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[ValidateCustomerToRedeemLoyalty](#ValidateCustomerToRedeemLoyalty)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[EnableAdvancedExternalGiftCard](#EnableAdvancedExternalGiftCard)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_CatalogDefaultAttributeGroupRelationshipId](#Relationship_CatalogDefaultAttributeGroupRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_CategoryDefaultAttributeGroupRelationshipId](#Relationship_CategoryDefaultAttributeGroupRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_CustomerDefaultAttributeGroupRelationshipId](#Relationship_CustomerDefaultAttributeGroupRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_ExchangeRateTypeRelationshipId](#Relationship_ExchangeRateTypeRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_HtmlAttributeTypeRelationshipId](#Relationship_HtmlAttributeTypeRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_ImagesAttributeTypeRelationshipId](#Relationship_ImagesAttributeTypeRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_ProductDefaultAttributeGroupRelationshipId](#Relationship_ProductDefaultAttributeGroupRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_RetailStoreTableRelationshipId](#Relationship_RetailStoreTableRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_RetailTransactionServiceProfileRelationshipId](#Relationship_RetailTransactionServiceProfileRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_VideosAttributeTypeRelationshipId](#Relationship_VideosAttributeTypeRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_WorkerDefaultAttributeGroupRelationshipId](#Relationship_WorkerDefaultAttributeGroupRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_DefaultHardwareStationPackageRelationshipId](#Relationship_DefaultHardwareStationPackageRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_DefaultHardwarePeripheralSimulatorPackageRelationshipId](#Relationship_DefaultHardwarePeripheralSimulatorPackageRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_DefaultRetailStoreUnitPackageRelationshipId](#Relationship_DefaultRetailStoreUnitPackageRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_DefaultMPOSWindowsPhonePackageRelationshipId](#Relationship_DefaultMPOSWindowsPhonePackageRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_DefaultMPOSAndroidPackageRelationshipId](#Relationship_DefaultMPOSAndroidPackageRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|
|[Relationship_DefaultMPOSiOSPackageRelationshipId](#Relationship_DefaultMPOSiOSPackageRelationshipId)||<a href="RetailSharedParameters.md" target="_blank">Parameter/RetailSharedParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailSharedParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AllowTerminalAssociationFromDevice name="AllowTerminalAssociationFromDevice">AllowTerminalAssociationFromDevice</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTerminalAssociationFromDevice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#barcodeSetupId name="barcodeSetupId">barcodeSetupId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the barcodeSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatalogDefaultAttributeGroup name="CatalogDefaultAttributeGroup">CatalogDefaultAttributeGroup</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogDefaultAttributeGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CatAttriBulkEditMaxRows name="CatAttriBulkEditMaxRows">CatAttriBulkEditMaxRows</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatAttriBulkEditMaxRows attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CategoryDefaultAttributeGroup name="CategoryDefaultAttributeGroup">CategoryDefaultAttributeGroup</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryDefaultAttributeGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomerDefaultAttributeGroup name="CustomerDefaultAttributeGroup">CustomerDefaultAttributeGroup</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDefaultAttributeGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DeviceTokenAlgorithm name="DeviceTokenAlgorithm">DeviceTokenAlgorithm</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarnLoyaltyOffline attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EFTPasswordEncryption name="EFTPasswordEncryption">EFTPasswordEncryption</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

### <a href=#EPRefreshIntervalInSeconds name="EPRefreshIntervalInSeconds">EPRefreshIntervalInSeconds</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPRefreshIntervalInSeconds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchangeRateType name="ExchangeRateType">ExchangeRateType</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#HtmlAttributeType name="HtmlAttributeType">HtmlAttributeType</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HtmlAttributeType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ImagesAttributeType name="ImagesAttributeType">ImagesAttributeType</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImagesAttributeType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ItemLabelCreation name="ItemLabelCreation">ItemLabelCreation</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemLabelCreation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LocalStoreId name="LocalStoreId">LocalStoreId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDefaultAttributeGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SharepointAssetPickerUrl name="SharepointAssetPickerUrl">SharepointAssetPickerUrl</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShelfLabelCreation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StaffPasswordHash name="StaffPasswordHash">StaffPasswordHash</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

### <a href=#transactionServiceProfile name="transactionServiceProfile">transactionServiceProfile</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionServiceProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TSPasswordEncryption name="TSPasswordEncryption">TSPasswordEncryption</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSPasswordEncryption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VideosAttributeType name="VideosAttributeType">VideosAttributeType</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VideosAttributeType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkerDefaultAttributeGroup name="WorkerDefaultAttributeGroup">WorkerDefaultAttributeGroup</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerDefaultAttributeGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ConsumerEFDocCscEncryption name="ConsumerEFDocCscEncryption">ConsumerEFDocCscEncryption</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDocCscEncryption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeploymentRootPath name="DeploymentRootPath">DeploymentRootPath</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

### <a href=#SideloadingKey name="SideloadingKey">SideloadingKey</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SideloadingKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClxStorageSasKeyLifetimeInHours name="ClxStorageSasKeyLifetimeInHours">ClxStorageSasKeyLifetimeInHours</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClxStorageSasKeyLifetimeInHours attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClxStorageSasKeyRecycleWindowInHours name="ClxStorageSasKeyRecycleWindowInHours">ClxStorageSasKeyRecycleWindowInHours</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClxStorageSasKeyRecycleWindowInHours attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeviceTokenExpiration name="DeviceTokenExpiration">DeviceTokenExpiration</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeviceTokenExpiration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EntityValidationTemplate name="EntityValidationTemplate">EntityValidationTemplate</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

### <a href=#DefaultHWSSelfServicePkg name="DefaultHWSSelfServicePkg">DefaultHWSSelfServicePkg</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultHWSSelfServicePkg attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultHardwarePeripheralSimulatorPkg name="DefaultHardwarePeripheralSimulatorPkg">DefaultHardwarePeripheralSimulatorPkg</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultHardwarePeripheralSimulatorPkg attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultRetailStoreUnitSelfServicePkg name="DefaultRetailStoreUnitSelfServicePkg">DefaultRetailStoreUnitSelfServicePkg</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRetailStoreUnitSelfServicePkg attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#HardwareStationAppInsightsInstrumentationKey name="HardwareStationAppInsightsInstrumentationKey">HardwareStationAppInsightsInstrumentationKey</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

### <a href=#ClientAppInsightsInstrumentationKey name="ClientAppInsightsInstrumentationKey">ClientAppInsightsInstrumentationKey</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

### <a href=#EnvironmentId name="EnvironmentId">EnvironmentId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenantId name="TenantId">TenantId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenantId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CloudPosAppInsightsInstrumentationKey name="CloudPosAppInsightsInstrumentationKey">CloudPosAppInsightsInstrumentationKey</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

First included in: Parameter/RetailSharedParameters (this entity)  

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

### <a href=#AsyncClientAppInsightsInstrumentationKey name="AsyncClientAppInsightsInstrumentationKey">AsyncClientAppInsightsInstrumentationKey</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

### <a href=#WindowsPhoneAppInsightsInstrumentationKey name="WindowsPhoneAppInsightsInstrumentationKey">WindowsPhoneAppInsightsInstrumentationKey</a>

First included in: Parameter/RetailSharedParameters (this entity)  

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

### <a href=#DefaultMPOSWindowsPhonePkg name="DefaultMPOSWindowsPhonePkg">DefaultMPOSWindowsPhonePkg</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultMPOSWindowsPhonePkg attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultMPOSAndroidPkg name="DefaultMPOSAndroidPkg">DefaultMPOSAndroidPkg</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultMPOSAndroidPkg attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultMPOSiOSPkg name="DefaultMPOSiOSPkg">DefaultMPOSiOSPkg</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultMPOSiOSPkg attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CouponBarcodeSetupId name="CouponBarcodeSetupId">CouponBarcodeSetupId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CouponBarcodeSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegacyRegKeyData2Value name="LegacyRegKeyData2Value">LegacyRegKeyData2Value</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegacyRegKeyData2Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtensionServiceUrl name="ExtensionServiceUrl">ExtensionServiceUrl</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtensionServiceUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProvisioningUrl name="ProvisioningUrl">ProvisioningUrl</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProvisioningUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AsyncServerConnectorServiceAppInsightsInstrumentationKey name="AsyncServerConnectorServiceAppInsightsInstrumentationKey">AsyncServerConnectorServiceAppInsightsInstrumentationKey</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AsyncServerConnectorServiceAppInsightsInstrumentationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealtimeServiceAX63AppInsightsInstrumentationKey name="RealtimeServiceAX63AppInsightsInstrumentationKey">RealtimeServiceAX63AppInsightsInstrumentationKey</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealtimeServiceAX63AppInsightsInstrumentationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegacyDeviceTokenAlgorithm name="LegacyDeviceTokenAlgorithm">LegacyDeviceTokenAlgorithm</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegacyDeviceTokenAlgorithm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostLoyaltyPointsPerSalesLine name="PostLoyaltyPointsPerSalesLine">PostLoyaltyPointsPerSalesLine</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostLoyaltyPointsPerSalesLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BlockTransferBetweenDifferentLoyalty name="BlockTransferBetweenDifferentLoyalty">BlockTransferBetweenDifferentLoyalty</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockTransferBetweenDifferentLoyalty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableOmniChannelPayments name="EnableOmniChannelPayments">EnableOmniChannelPayments</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableOmniChannelPayments attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableFiscalIntegration name="EnableFiscalIntegration">EnableFiscalIntegration</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableFiscalIntegration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RecoListEnabled name="RecoListEnabled">RecoListEnabled</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoListEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RecoPersonalizationEnabled name="RecoPersonalizationEnabled">RecoPersonalizationEnabled</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoPersonalizationEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RecoListTrendingMaxAgeDays name="RecoListTrendingMaxAgeDays">RecoListTrendingMaxAgeDays</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoListTrendingMaxAgeDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RecoListTrendingTransactionsIntervalDays name="RecoListTrendingTransactionsIntervalDays">RecoListTrendingTransactionsIntervalDays</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoListTrendingTransactionsIntervalDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RecoListBestsellingTransactionsIntervalDays name="RecoListBestsellingTransactionsIntervalDays">RecoListBestsellingTransactionsIntervalDays</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoListBestsellingTransactionsIntervalDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableLocalStorageBackup name="EnableLocalStorageBackup">EnableLocalStorageBackup</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableLocalStorageBackup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseSalesReceiptAsDefaultReceiptTypeInJournal name="UseSalesReceiptAsDefaultReceiptTypeInJournal">UseSalesReceiptAsDefaultReceiptTypeInJournal</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSalesReceiptAsDefaultReceiptTypeInJournal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductAvailabilityJobPolicy name="ProductAvailabilityJobPolicy">ProductAvailabilityJobPolicy</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAvailabilityJobPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventoryAvailabilityCachePeriod name="InventoryAvailabilityCachePeriod">InventoryAvailabilityCachePeriod</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAvailabilityCachePeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventoryAvailabilitySumDeltaCachePeriod name="InventoryAvailabilitySumDeltaCachePeriod">InventoryAvailabilitySumDeltaCachePeriod</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAvailabilitySumDeltaCachePeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaskManagementInitialized name="TaskManagementInitialized">TaskManagementInitialized</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaskManagementInitialized attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidateCustomerToRedeemLoyalty name="ValidateCustomerToRedeemLoyalty">ValidateCustomerToRedeemLoyalty</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateCustomerToRedeemLoyalty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableAdvancedExternalGiftCard name="EnableAdvancedExternalGiftCard">EnableAdvancedExternalGiftCard</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableAdvancedExternalGiftCard attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_CatalogDefaultAttributeGroupRelationshipId name="Relationship_CatalogDefaultAttributeGroupRelationshipId">Relationship_CatalogDefaultAttributeGroupRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatalogDefaultAttributeGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.cdm.json/EcoResAttributeGroup</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CategoryDefaultAttributeGroupRelationshipId name="Relationship_CategoryDefaultAttributeGroupRelationshipId">Relationship_CategoryDefaultAttributeGroupRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CategoryDefaultAttributeGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.cdm.json/EcoResAttributeGroup</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomerDefaultAttributeGroupRelationshipId name="Relationship_CustomerDefaultAttributeGroupRelationshipId">Relationship_CustomerDefaultAttributeGroupRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomerDefaultAttributeGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.cdm.json/EcoResAttributeGroup</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExchangeRateTypeRelationshipId name="Relationship_ExchangeRateTypeRelationshipId">Relationship_ExchangeRateTypeRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExchangeRateTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/ExchangeRateType.md" target="_blank">/core/erp/Tables/Common/Currency/Group/ExchangeRateType.cdm.json/ExchangeRateType</a></td><td><a href="../../../Common/Currency/Group/ExchangeRateType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HtmlAttributeTypeRelationshipId name="Relationship_HtmlAttributeTypeRelationshipId">Relationship_HtmlAttributeTypeRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HtmlAttributeTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeType.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeType.cdm.json/EcoResAttributeType</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ImagesAttributeTypeRelationshipId name="Relationship_ImagesAttributeTypeRelationshipId">Relationship_ImagesAttributeTypeRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ImagesAttributeTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeType.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeType.cdm.json/EcoResAttributeType</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductDefaultAttributeGroupRelationshipId name="Relationship_ProductDefaultAttributeGroupRelationshipId">Relationship_ProductDefaultAttributeGroupRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductDefaultAttributeGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.cdm.json/EcoResAttributeGroup</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreTableRelationshipId name="Relationship_RetailStoreTableRelationshipId">Relationship_RetailStoreTableRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailStoreTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailStoreTable.cdm.json/RetailStoreTable</a></td><td><a href="../Main/RetailStoreTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionServiceProfileRelationshipId name="Relationship_RetailTransactionServiceProfileRelationshipId">Relationship_RetailTransactionServiceProfileRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionServiceProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailTransactionServiceProfile.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailTransactionServiceProfile.cdm.json/RetailTransactionServiceProfile</a></td><td><a href="RetailTransactionServiceProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VideosAttributeTypeRelationshipId name="Relationship_VideosAttributeTypeRelationshipId">Relationship_VideosAttributeTypeRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VideosAttributeTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeType.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeType.cdm.json/EcoResAttributeType</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkerDefaultAttributeGroupRelationshipId name="Relationship_WorkerDefaultAttributeGroupRelationshipId">Relationship_WorkerDefaultAttributeGroupRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkerDefaultAttributeGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.cdm.json/EcoResAttributeGroup</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultHardwareStationPackageRelationshipId name="Relationship_DefaultHardwareStationPackageRelationshipId">Relationship_DefaultHardwareStationPackageRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultHardwareStationPackageRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailSelfServicePackageInfo.cdm.json/RetailSelfServicePackageInfo</a></td><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultHardwarePeripheralSimulatorPackageRelationshipId name="Relationship_DefaultHardwarePeripheralSimulatorPackageRelationshipId">Relationship_DefaultHardwarePeripheralSimulatorPackageRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultHardwarePeripheralSimulatorPackageRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailSelfServicePackageInfo.cdm.json/RetailSelfServicePackageInfo</a></td><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultRetailStoreUnitPackageRelationshipId name="Relationship_DefaultRetailStoreUnitPackageRelationshipId">Relationship_DefaultRetailStoreUnitPackageRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultRetailStoreUnitPackageRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailSelfServicePackageInfo.cdm.json/RetailSelfServicePackageInfo</a></td><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultMPOSWindowsPhonePackageRelationshipId name="Relationship_DefaultMPOSWindowsPhonePackageRelationshipId">Relationship_DefaultMPOSWindowsPhonePackageRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultMPOSWindowsPhonePackageRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailSelfServicePackageInfo.cdm.json/RetailSelfServicePackageInfo</a></td><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultMPOSAndroidPackageRelationshipId name="Relationship_DefaultMPOSAndroidPackageRelationshipId">Relationship_DefaultMPOSAndroidPackageRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultMPOSAndroidPackageRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailSelfServicePackageInfo.cdm.json/RetailSelfServicePackageInfo</a></td><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultMPOSiOSPackageRelationshipId name="Relationship_DefaultMPOSiOSPackageRelationshipId">Relationship_DefaultMPOSiOSPackageRelationshipId</a>

First included in: Parameter/RetailSharedParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultMPOSiOSPackageRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailSelfServicePackageInfo.cdm.json/RetailSelfServicePackageInfo</a></td><td><a href="../Miscellaneous/RetailSelfServicePackageInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

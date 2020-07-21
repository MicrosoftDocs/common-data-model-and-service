---
title: smmSalesActivityCreationPolicyEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Sales activity creation policies in SalesAndMarketing(smmSalesActivityCreationPolicyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/smmSalesActivityCreationPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales activity creation policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WillBatchProcessingCreateActivities](#WillBatchProcessingCreateActivities)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultQuotationActivityCategory](#DefaultQuotationActivityCategory)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultQuotationActivityPhaseId](#DefaultQuotationActivityPhaseId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultQuotationActivityPurpose](#DefaultQuotationActivityPurpose)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultQuotationActivityTypeId](#DefaultQuotationActivityTypeId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[QuotationActivityCreationRule](#QuotationActivityCreationRule)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultCampaignFollowUpActivityCategory](#DefaultCampaignFollowUpActivityCategory)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultCampaignFollowUpActivityPhaseId](#DefaultCampaignFollowUpActivityPhaseId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultCampaignFollowUpActivityPurpose](#DefaultCampaignFollowUpActivityPurpose)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultCampaignFollowUpActivityTypeId](#DefaultCampaignFollowUpActivityTypeId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[CampaignFollowUpActivityCreationRule](#CampaignFollowUpActivityCreationRule)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultCampaignTargetActivityCategory](#DefaultCampaignTargetActivityCategory)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultCampaignTargetActivityPhaseId](#DefaultCampaignTargetActivityPhaseId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultCampaignTargetActivityPurpose](#DefaultCampaignTargetActivityPurpose)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultCampaignTargetActivityTypeId](#DefaultCampaignTargetActivityTypeId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[CampaignTargetActivityCreationRule](#CampaignTargetActivityCreationRule)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarketingCallListActivityCategory](#DefaultTelemarketingCallListActivityCategory)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarketingCallListActivityPhaseId](#DefaultTelemarketingCallListActivityPhaseId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarketingCallListActivityPurpose](#DefaultTelemarketingCallListActivityPurpose)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarketingCallListActivityTypeId](#DefaultTelemarketingCallListActivityTypeId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[TelemarketingCallListActivityCreationRule](#TelemarketingCallListActivityCreationRule)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarketingCallBackActivityCategory](#DefaultTelemarketingCallBackActivityCategory)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarketingCallBackActivityPhaseId](#DefaultTelemarketingCallBackActivityPhaseId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarketingCallBackActivityPurpose](#DefaultTelemarketingCallBackActivityPurpose)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarketingCallbackActivityTypeId](#DefaultTelemarketingCallbackActivityTypeId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[TelemarketingCallBackActivityCreationRule](#TelemarketingCallBackActivityCreationRule)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarkeringTargetActivityCategory](#DefaultTelemarkeringTargetActivityCategory)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarkeringTargetActivityPhaseId](#DefaultTelemarkeringTargetActivityPhaseId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarkeringTargetActivityPurpose](#DefaultTelemarkeringTargetActivityPurpose)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultTelemarkeringTargetActivityTypeId](#DefaultTelemarkeringTargetActivityTypeId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[TelemarkeringTargetActivityCreationRule](#TelemarkeringTargetActivityCreationRule)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultSalesCatalogRequestActivityCategory](#DefaultSalesCatalogRequestActivityCategory)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultSalesCatalogRequestActivityPhaseId](#DefaultSalesCatalogRequestActivityPhaseId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultSalesCatalogRequestActivityPurpose](#DefaultSalesCatalogRequestActivityPurpose)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultSalesCatalogRequestActivityTypeId](#DefaultSalesCatalogRequestActivityTypeId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[SalesCatalogRequestActivityCreationRule](#SalesCatalogRequestActivityCreationRule)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultSalesCatalogSentActivityCategory](#DefaultSalesCatalogSentActivityCategory)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultSalesCatalogSentActivityPhaseId](#DefaultSalesCatalogSentActivityPhaseId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultSalesCatalogSentActivityPurposeId](#DefaultSalesCatalogSentActivityPurposeId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[DefaultSalesCatalogSentActivityTypeId](#DefaultSalesCatalogSentActivityTypeId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[SalesCatalogSentActivityCreationRule](#SalesCatalogSentActivityCreationRule)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[BackingTable_smmParametersTableRelationshipId](#BackingTable_smmParametersTableRelationshipId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="smmSalesActivityCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmSalesActivityCreationPolicyEntity</a>|

### <a href=#WillBatchProcessingCreateActivities name="WillBatchProcessingCreateActivities">WillBatchProcessingCreateActivities</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillBatchProcessingCreateActivities attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultQuotationActivityCategory name="DefaultQuotationActivityCategory">DefaultQuotationActivityCategory</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultQuotationActivityCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultQuotationActivityPhaseId name="DefaultQuotationActivityPhaseId">DefaultQuotationActivityPhaseId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultQuotationActivityPhaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultQuotationActivityPurpose name="DefaultQuotationActivityPurpose">DefaultQuotationActivityPurpose</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultQuotationActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultQuotationActivityTypeId name="DefaultQuotationActivityTypeId">DefaultQuotationActivityTypeId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultQuotationActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationActivityCreationRule name="QuotationActivityCreationRule">QuotationActivityCreationRule</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationActivityCreationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCampaignFollowUpActivityCategory name="DefaultCampaignFollowUpActivityCategory">DefaultCampaignFollowUpActivityCategory</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCampaignFollowUpActivityCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCampaignFollowUpActivityPhaseId name="DefaultCampaignFollowUpActivityPhaseId">DefaultCampaignFollowUpActivityPhaseId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCampaignFollowUpActivityPhaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCampaignFollowUpActivityPurpose name="DefaultCampaignFollowUpActivityPurpose">DefaultCampaignFollowUpActivityPurpose</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCampaignFollowUpActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCampaignFollowUpActivityTypeId name="DefaultCampaignFollowUpActivityTypeId">DefaultCampaignFollowUpActivityTypeId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCampaignFollowUpActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignFollowUpActivityCreationRule name="CampaignFollowUpActivityCreationRule">CampaignFollowUpActivityCreationRule</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignFollowUpActivityCreationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCampaignTargetActivityCategory name="DefaultCampaignTargetActivityCategory">DefaultCampaignTargetActivityCategory</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCampaignTargetActivityCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCampaignTargetActivityPhaseId name="DefaultCampaignTargetActivityPhaseId">DefaultCampaignTargetActivityPhaseId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCampaignTargetActivityPhaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCampaignTargetActivityPurpose name="DefaultCampaignTargetActivityPurpose">DefaultCampaignTargetActivityPurpose</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCampaignTargetActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCampaignTargetActivityTypeId name="DefaultCampaignTargetActivityTypeId">DefaultCampaignTargetActivityTypeId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCampaignTargetActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignTargetActivityCreationRule name="CampaignTargetActivityCreationRule">CampaignTargetActivityCreationRule</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignTargetActivityCreationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarketingCallListActivityCategory name="DefaultTelemarketingCallListActivityCategory">DefaultTelemarketingCallListActivityCategory</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarketingCallListActivityCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarketingCallListActivityPhaseId name="DefaultTelemarketingCallListActivityPhaseId">DefaultTelemarketingCallListActivityPhaseId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarketingCallListActivityPhaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarketingCallListActivityPurpose name="DefaultTelemarketingCallListActivityPurpose">DefaultTelemarketingCallListActivityPurpose</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarketingCallListActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarketingCallListActivityTypeId name="DefaultTelemarketingCallListActivityTypeId">DefaultTelemarketingCallListActivityTypeId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarketingCallListActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TelemarketingCallListActivityCreationRule name="TelemarketingCallListActivityCreationRule">TelemarketingCallListActivityCreationRule</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TelemarketingCallListActivityCreationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarketingCallBackActivityCategory name="DefaultTelemarketingCallBackActivityCategory">DefaultTelemarketingCallBackActivityCategory</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarketingCallBackActivityCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarketingCallBackActivityPhaseId name="DefaultTelemarketingCallBackActivityPhaseId">DefaultTelemarketingCallBackActivityPhaseId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarketingCallBackActivityPhaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarketingCallBackActivityPurpose name="DefaultTelemarketingCallBackActivityPurpose">DefaultTelemarketingCallBackActivityPurpose</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarketingCallBackActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarketingCallbackActivityTypeId name="DefaultTelemarketingCallbackActivityTypeId">DefaultTelemarketingCallbackActivityTypeId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarketingCallbackActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TelemarketingCallBackActivityCreationRule name="TelemarketingCallBackActivityCreationRule">TelemarketingCallBackActivityCreationRule</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TelemarketingCallBackActivityCreationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarkeringTargetActivityCategory name="DefaultTelemarkeringTargetActivityCategory">DefaultTelemarkeringTargetActivityCategory</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarkeringTargetActivityCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarkeringTargetActivityPhaseId name="DefaultTelemarkeringTargetActivityPhaseId">DefaultTelemarkeringTargetActivityPhaseId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarkeringTargetActivityPhaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarkeringTargetActivityPurpose name="DefaultTelemarkeringTargetActivityPurpose">DefaultTelemarkeringTargetActivityPurpose</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarkeringTargetActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTelemarkeringTargetActivityTypeId name="DefaultTelemarkeringTargetActivityTypeId">DefaultTelemarkeringTargetActivityTypeId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTelemarkeringTargetActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TelemarkeringTargetActivityCreationRule name="TelemarkeringTargetActivityCreationRule">TelemarkeringTargetActivityCreationRule</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TelemarkeringTargetActivityCreationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesCatalogRequestActivityCategory name="DefaultSalesCatalogRequestActivityCategory">DefaultSalesCatalogRequestActivityCategory</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesCatalogRequestActivityCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesCatalogRequestActivityPhaseId name="DefaultSalesCatalogRequestActivityPhaseId">DefaultSalesCatalogRequestActivityPhaseId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesCatalogRequestActivityPhaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesCatalogRequestActivityPurpose name="DefaultSalesCatalogRequestActivityPurpose">DefaultSalesCatalogRequestActivityPurpose</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesCatalogRequestActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesCatalogRequestActivityTypeId name="DefaultSalesCatalogRequestActivityTypeId">DefaultSalesCatalogRequestActivityTypeId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesCatalogRequestActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCatalogRequestActivityCreationRule name="SalesCatalogRequestActivityCreationRule">SalesCatalogRequestActivityCreationRule</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCatalogRequestActivityCreationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesCatalogSentActivityCategory name="DefaultSalesCatalogSentActivityCategory">DefaultSalesCatalogSentActivityCategory</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesCatalogSentActivityCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesCatalogSentActivityPhaseId name="DefaultSalesCatalogSentActivityPhaseId">DefaultSalesCatalogSentActivityPhaseId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesCatalogSentActivityPhaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesCatalogSentActivityPurposeId name="DefaultSalesCatalogSentActivityPurposeId">DefaultSalesCatalogSentActivityPurposeId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesCatalogSentActivityPurposeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesCatalogSentActivityTypeId name="DefaultSalesCatalogSentActivityTypeId">DefaultSalesCatalogSentActivityTypeId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesCatalogSentActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCatalogSentActivityCreationRule name="SalesCatalogSentActivityCreationRule">SalesCatalogSentActivityCreationRule</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCatalogSentActivityCreationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_smmParametersTableRelationshipId name="BackingTable_smmParametersTableRelationshipId">BackingTable_smmParametersTableRelationshipId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_smmParametersTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/smmParametersTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/smmParametersTable.cdm.json/smmParametersTable</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/smmParametersTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/smmSalesActivityCreationPolicyEntity (this entity)  

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

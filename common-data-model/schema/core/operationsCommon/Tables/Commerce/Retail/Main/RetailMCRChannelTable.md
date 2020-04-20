---
title: RetailMCRChannelTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailMCRChannelTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Main/RetailMCRChannelTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailMCRChannelTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[CashOffice_RU](#CashOffice_RU)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[CategoryHierarchy](#CategoryHierarchy)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[ChannelTimeZone](#ChannelTimeZone)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[ChannelTimeZoneInfoId](#ChannelTimeZoneInfoId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[ChannelType](#ChannelType)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Currency](#Currency)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[DefaultCustAccount](#DefaultCustAccount)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[DefaultCustDataAreaId](#DefaultCustDataAreaId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[DefaultDimension](#DefaultDimension)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[EventNotificationProfileId](#EventNotificationProfileId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[inventLocation](#inventLocation)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[inventLocationDataAreaId](#inventLocationDataAreaId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[OMOperatingUnitID](#OMOperatingUnitID)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Payment](#Payment)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[PaymMode](#PaymMode)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[PriceIncludesSalesTax](#PriceIncludesSalesTax)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[StoreArea](#StoreArea)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[TransactionServiceProfile](#TransactionServiceProfile)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[DisplayTaxPerTaxComponent](#DisplayTaxPerTaxComponent)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[RetailChannelId](#RetailChannelId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[ManualAccept](#ManualAccept)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[RetailReturnPolicyChannel](#RetailReturnPolicyChannel)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[CalcExemptTaxesForPriceInclusive](#CalcExemptTaxesForPriceInclusive)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[InventSiteId](#InventSiteId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_CashOffice_RURelationshipId](#Relationship_CashOffice_RURelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_CustPaymModeTableRelationshipId](#Relationship_CustPaymModeTableRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_DimensionAttributeValueSetRelationshipId](#Relationship_DimensionAttributeValueSetRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_EcoResCategoryHierarchyRelationshipId](#Relationship_EcoResCategoryHierarchyRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_InventLocationRelationshipId](#Relationship_InventLocationRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_OMOperatingUnitRelationshipId](#Relationship_OMOperatingUnitRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_PaymTermRelationshipId](#Relationship_PaymTermRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_RetailEventNotificationProfileRelationshipId](#Relationship_RetailEventNotificationProfileRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_RetailTransactionServiceProfileRelationshipId](#Relationship_RetailTransactionServiceProfileRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_RetailReturnPolicyChannelRelationshipId](#Relationship_RetailReturnPolicyChannelRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[Relationship_InventSiteRelationshipId](#Relationship_InventSiteRelationshipId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[MCRCustomerCreditRetailInfocodeId](#MCRCustomerCreditRetailInfocodeId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[MCREnableDirectedSelling](#MCREnableDirectedSelling)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[MCREnableOrderCompletion](#MCREnableOrderCompletion)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[MCREnableOrderPriceControl](#MCREnableOrderPriceControl)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[MCRPriceOverrideRetailInfocodeId](#MCRPriceOverrideRetailInfocodeId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|
|[MCRReasonCodeRetailInfocodeId](#MCRReasonCodeRetailInfocodeId)||<a href="RetailMCRChannelTable.md" target="_blank">Main/RetailMCRChannelTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailMCRChannelTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CashOffice_RU name="CashOffice_RU">CashOffice_RU</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashOffice_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryHierarchy name="CategoryHierarchy">CategoryHierarchy</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchy attribute are listed below.</summary>

</details>

### <a href=#ChannelTimeZone name="ChannelTimeZone">ChannelTimeZone</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelTimeZone attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ChannelTimeZoneInfoId name="ChannelTimeZoneInfoId">ChannelTimeZoneInfoId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelTimeZoneInfoId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChannelType name="ChannelType">ChannelType</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustAccount name="DefaultCustAccount">DefaultCustAccount</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustDataAreaId name="DefaultCustDataAreaId">DefaultCustDataAreaId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EventNotificationProfileId name="EventNotificationProfileId">EventNotificationProfileId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventNotificationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#inventLocation name="inventLocation">inventLocation</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the inventLocation attribute are listed below.</summary>

</details>

### <a href=#inventLocationDataAreaId name="inventLocationDataAreaId">inventLocationDataAreaId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the inventLocationDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMOperatingUnitID name="OMOperatingUnitID">OMOperatingUnitID</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Payment name="Payment">Payment</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Payment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymMode name="PaymMode">PaymMode</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceIncludesSalesTax name="PriceIncludesSalesTax">PriceIncludesSalesTax</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceIncludesSalesTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StoreArea name="StoreArea">StoreArea</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreArea attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransactionServiceProfile name="TransactionServiceProfile">TransactionServiceProfile</a>

First included in: Main/RetailMCRChannelTable (this entity)  

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

### <a href=#DisplayTaxPerTaxComponent name="DisplayTaxPerTaxComponent">DisplayTaxPerTaxComponent</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayTaxPerTaxComponent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailChannelId name="RetailChannelId">RetailChannelId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelId attribute are listed below.</summary>

</details>

### <a href=#ManualAccept name="ManualAccept">ManualAccept</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualAccept attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailReturnPolicyChannel name="RetailReturnPolicyChannel">RetailReturnPolicyChannel</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailReturnPolicyChannel attribute are listed below.</summary>

</details>

### <a href=#CalcExemptTaxesForPriceInclusive name="CalcExemptTaxesForPriceInclusive">CalcExemptTaxesForPriceInclusive</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcExemptTaxesForPriceInclusive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventSiteId name="InventSiteId">InventSiteId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CashOffice_RURelationshipId name="Relationship_CashOffice_RURelationshipId">Relationship_CashOffice_RURelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashOffice_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/RCash/Main/RCashTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RCash/Main/RCashTable.cdm.json/RCashTable</a></td><td><a href="../../../Finance/RCash/Main/RCashTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustPaymModeTableRelationshipId name="Relationship_CustPaymModeTableRelationshipId">Relationship_CustPaymModeTableRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustPaymModeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/CustPaymModeTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/CustPaymModeTable.cdm.json/CustPaymModeTable</a></td><td><a href="../../../Finance/Bank/Group/CustPaymModeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeValueSetRelationshipId name="Relationship_DimensionAttributeValueSetRelationshipId">Relationship_DimensionAttributeValueSetRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResCategoryHierarchyRelationshipId name="Relationship_EcoResCategoryHierarchyRelationshipId">Relationship_EcoResCategoryHierarchyRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResCategoryHierarchyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchy.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchy.cdm.json/EcoResCategoryHierarchy</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventLocationRelationshipId name="Relationship_InventLocationRelationshipId">Relationship_InventLocationRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OMOperatingUnitRelationshipId name="Relationship_OMOperatingUnitRelationshipId">Relationship_OMOperatingUnitRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OMOperatingUnitRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/OMOperatingUnit.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/OMOperatingUnit.cdm.json/OMOperatingUnit</a></td><td><a href="../../../Common/GAB/Main/OMOperatingUnit.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymTermRelationshipId name="Relationship_PaymTermRelationshipId">Relationship_PaymTermRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymTermRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/PaymTerm.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymTerm.cdm.json/PaymTerm</a></td><td><a href="../../../Finance/Bank/Group/PaymTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailEventNotificationProfileRelationshipId name="Relationship_RetailEventNotificationProfileRelationshipId">Relationship_RetailEventNotificationProfileRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailEventNotificationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailEventNotificationProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailEventNotificationProfile.cdm.json/RetailEventNotificationProfile</a></td><td><a href="../Miscellaneous/RetailEventNotificationProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionServiceProfileRelationshipId name="Relationship_RetailTransactionServiceProfileRelationshipId">Relationship_RetailTransactionServiceProfileRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/RetailTransactionServiceProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Parameter/RetailTransactionServiceProfile.cdm.json/RetailTransactionServiceProfile</a></td><td><a href="../Parameter/RetailTransactionServiceProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailReturnPolicyChannelRelationshipId name="Relationship_RetailReturnPolicyChannelRelationshipId">Relationship_RetailReturnPolicyChannelRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailReturnPolicyChannelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/RetailReturnPolicyChannel.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Parameter/RetailReturnPolicyChannel.cdm.json/RetailReturnPolicyChannel</a></td><td><a href="../Parameter/RetailReturnPolicyChannel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventSiteRelationshipId name="Relationship_InventSiteRelationshipId">Relationship_InventSiteRelationshipId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventSiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventSite.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventSite.cdm.json/InventSite</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventSite.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCustomerCreditRetailInfocodeId name="MCRCustomerCreditRetailInfocodeId">MCRCustomerCreditRetailInfocodeId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCustomerCreditRetailInfocodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCREnableDirectedSelling name="MCREnableDirectedSelling">MCREnableDirectedSelling</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCREnableDirectedSelling attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCREnableOrderCompletion name="MCREnableOrderCompletion">MCREnableOrderCompletion</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCREnableOrderCompletion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCREnableOrderPriceControl name="MCREnableOrderPriceControl">MCREnableOrderPriceControl</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCREnableOrderPriceControl attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRPriceOverrideRetailInfocodeId name="MCRPriceOverrideRetailInfocodeId">MCRPriceOverrideRetailInfocodeId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRPriceOverrideRetailInfocodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRReasonCodeRetailInfocodeId name="MCRReasonCodeRetailInfocodeId">MCRReasonCodeRetailInfocodeId</a>

First included in: Main/RetailMCRChannelTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRReasonCodeRetailInfocodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

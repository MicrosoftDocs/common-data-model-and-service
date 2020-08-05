---
title: SalesDocumentDefaultsEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Sales type document default values in SalesAndMarketing(SalesDocumentDefaultsEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesDocumentDefaultsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales type document default values</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DefaultBillOfLadingCarrierName](#DefaultBillOfLadingCarrierName)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultBillOfLadingFreightChargeTerms](#DefaultBillOfLadingFreightChargeTerms)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultBillOfLadingFreightCountingRule](#DefaultBillOfLadingFreightCountingRule)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultBillOfLadingLanguageId](#DefaultBillOfLadingLanguageId)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultBillOfLadingFreightingParty](#DefaultBillOfLadingFreightingParty)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultBillOfLadingTrailerLoadingParty](#DefaultBillOfLadingTrailerLoadingParty)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultCreditNoteCustomerTransactionSettlementType](#DefaultCreditNoteCustomerTransactionSettlementType)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultEnterprisePortalSalesOrderOriginCode](#DefaultEnterprisePortalSalesOrderOriginCode)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultInventoryReservationMethod](#DefaultInventoryReservationMethod)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultReturnOrderValidityPeriodDays](#DefaultReturnOrderValidityPeriodDays)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultSalesOrderOriginCode](#DefaultSalesOrderOriginCode)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultSalesOrderPoolId](#DefaultSalesOrderPoolId)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultSalesOrderType](#DefaultSalesOrderType)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultSalesOrderValidityPeriodDays](#DefaultSalesOrderValidityPeriodDays)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultSalesQuotationFollowUpPeriodDays](#DefaultSalesQuotationFollowUpPeriodDays)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultSalesQuotationTypeId](#DefaultSalesQuotationTypeId)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[DefaultSalesQuotationValidityPeriodDays](#DefaultSalesQuotationValidityPeriodDays)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[WillAutomaticInventoryReservationConsiderBatchAttributesByDefault](#WillAutomaticInventoryReservationConsiderBatchAttributesByDefault)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[ExchangeRateDate](#ExchangeRateDate)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[IsDirectDeliveryChainCreationDeferred](#IsDirectDeliveryChainCreationDeferred)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[BackingTable_SalesParametersRelationshipId](#BackingTable_SalesParametersRelationshipId)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesDocumentDefaultsEntity.md" target="_blank">SalesAndMarketing/SalesDocumentDefaultsEntity</a>|

### <a href=#DefaultBillOfLadingCarrierName name="DefaultBillOfLadingCarrierName">DefaultBillOfLadingCarrierName</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBillOfLadingCarrierName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBillOfLadingFreightChargeTerms name="DefaultBillOfLadingFreightChargeTerms">DefaultBillOfLadingFreightChargeTerms</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBillOfLadingFreightChargeTerms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBillOfLadingFreightCountingRule name="DefaultBillOfLadingFreightCountingRule">DefaultBillOfLadingFreightCountingRule</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBillOfLadingFreightCountingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBillOfLadingLanguageId name="DefaultBillOfLadingLanguageId">DefaultBillOfLadingLanguageId</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBillOfLadingLanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBillOfLadingFreightingParty name="DefaultBillOfLadingFreightingParty">DefaultBillOfLadingFreightingParty</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBillOfLadingFreightingParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBillOfLadingTrailerLoadingParty name="DefaultBillOfLadingTrailerLoadingParty">DefaultBillOfLadingTrailerLoadingParty</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBillOfLadingTrailerLoadingParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCreditNoteCustomerTransactionSettlementType name="DefaultCreditNoteCustomerTransactionSettlementType">DefaultCreditNoteCustomerTransactionSettlementType</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCreditNoteCustomerTransactionSettlementType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultEnterprisePortalSalesOrderOriginCode name="DefaultEnterprisePortalSalesOrderOriginCode">DefaultEnterprisePortalSalesOrderOriginCode</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultEnterprisePortalSalesOrderOriginCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryReservationMethod name="DefaultInventoryReservationMethod">DefaultInventoryReservationMethod</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryReservationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReturnOrderValidityPeriodDays name="DefaultReturnOrderValidityPeriodDays">DefaultReturnOrderValidityPeriodDays</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReturnOrderValidityPeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesOrderOriginCode name="DefaultSalesOrderOriginCode">DefaultSalesOrderOriginCode</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesOrderOriginCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesOrderPoolId name="DefaultSalesOrderPoolId">DefaultSalesOrderPoolId</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesOrderPoolId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesOrderType name="DefaultSalesOrderType">DefaultSalesOrderType</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesOrderValidityPeriodDays name="DefaultSalesOrderValidityPeriodDays">DefaultSalesOrderValidityPeriodDays</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesOrderValidityPeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesQuotationFollowUpPeriodDays name="DefaultSalesQuotationFollowUpPeriodDays">DefaultSalesQuotationFollowUpPeriodDays</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesQuotationFollowUpPeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesQuotationTypeId name="DefaultSalesQuotationTypeId">DefaultSalesQuotationTypeId</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesQuotationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesQuotationValidityPeriodDays name="DefaultSalesQuotationValidityPeriodDays">DefaultSalesQuotationValidityPeriodDays</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesQuotationValidityPeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillAutomaticInventoryReservationConsiderBatchAttributesByDefault name="WillAutomaticInventoryReservationConsiderBatchAttributesByDefault">WillAutomaticInventoryReservationConsiderBatchAttributesByDefault</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillAutomaticInventoryReservationConsiderBatchAttributesByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateDate name="ExchangeRateDate">ExchangeRateDate</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDirectDeliveryChainCreationDeferred name="IsDirectDeliveryChainCreationDeferred">IsDirectDeliveryChainCreationDeferred</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDirectDeliveryChainCreationDeferred attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_SalesParametersRelationshipId name="BackingTable_SalesParametersRelationshipId">BackingTable_SalesParametersRelationshipId</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/SalesParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/SalesParameters.cdm.json/SalesParameters</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/SalesParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesDocumentDefaultsEntity (this entity)  

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

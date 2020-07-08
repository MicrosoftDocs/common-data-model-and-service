---
title: IntercompanyTradingPartnershipSalesValueMappingEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Intercompany sales value mappings in SalesAndMarketing(IntercompanyTradingPartnershipSalesValueMappingEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intercompany sales value mappings</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustomerLegalEntityId](#CustomerLegalEntityId)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[DeliveryModeCodeDefinition](#DeliveryModeCodeDefinition)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[ExternalDeliveryModeCode](#ExternalDeliveryModeCode)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[DeliveryTermsCodeDefinition](#DeliveryTermsCodeDefinition)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[ExternalDeliveryTermsCode](#ExternalDeliveryTermsCode)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[ChargeCodeDefinition](#ChargeCodeDefinition)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[ExternalChargeCode](#ExternalChargeCode)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[OrderReturnReasonCodeDefinition](#OrderReturnReasonCodeDefinition)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[ExternalOrderReturnReasonCode](#ExternalOrderReturnReasonCode)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[OrderReturnDispositionCodeDefinition](#OrderReturnDispositionCodeDefinition)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[ExternalOrderReturnDispositionCode](#ExternalOrderReturnDispositionCode)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[OrderInventoryProfileCodeDefinition](#OrderInventoryProfileCodeDefinition)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[ExternalOrderInventoryProfileCode](#ExternalOrderInventoryProfileCode)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[AgreementClassificationDefinition](#AgreementClassificationDefinition)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[ExternalAgreementClassificationCode](#ExternalAgreementClassificationCode)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[Relationship_IntercompanyTradingPartnershipEntityRelationshipId](#Relationship_IntercompanyTradingPartnershipEntityRelationshipId)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|
|[BackingTable_InterCompanyTradingPartnerRelationshipId](#BackingTable_InterCompanyTradingPartnerRelationshipId)||<a href="IntercompanyTradingPartnershipSalesValueMappingEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity</a>|

### <a href=#CustomerLegalEntityId name="CustomerLegalEntityId">CustomerLegalEntityId</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeCodeDefinition name="DeliveryModeCodeDefinition">DeliveryModeCodeDefinition</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryModeCodeDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalDeliveryModeCode name="ExternalDeliveryModeCode">ExternalDeliveryModeCode</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalDeliveryModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsCodeDefinition name="DeliveryTermsCodeDefinition">DeliveryTermsCodeDefinition</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTermsCodeDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalDeliveryTermsCode name="ExternalDeliveryTermsCode">ExternalDeliveryTermsCode</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalDeliveryTermsCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeCodeDefinition name="ChargeCodeDefinition">ChargeCodeDefinition</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCodeDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalChargeCode name="ExternalChargeCode">ExternalChargeCode</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalChargeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderReturnReasonCodeDefinition name="OrderReturnReasonCodeDefinition">OrderReturnReasonCodeDefinition</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderReturnReasonCodeDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalOrderReturnReasonCode name="ExternalOrderReturnReasonCode">ExternalOrderReturnReasonCode</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalOrderReturnReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderReturnDispositionCodeDefinition name="OrderReturnDispositionCodeDefinition">OrderReturnDispositionCodeDefinition</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderReturnDispositionCodeDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalOrderReturnDispositionCode name="ExternalOrderReturnDispositionCode">ExternalOrderReturnDispositionCode</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalOrderReturnDispositionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderInventoryProfileCodeDefinition name="OrderInventoryProfileCodeDefinition">OrderInventoryProfileCodeDefinition</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderInventoryProfileCodeDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalOrderInventoryProfileCode name="ExternalOrderInventoryProfileCode">ExternalOrderInventoryProfileCode</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalOrderInventoryProfileCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementClassificationDefinition name="AgreementClassificationDefinition">AgreementClassificationDefinition</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementClassificationDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalAgreementClassificationCode name="ExternalAgreementClassificationCode">ExternalAgreementClassificationCode</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalAgreementClassificationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntercompanyTradingPartnershipEntityRelationshipId name="Relationship_IntercompanyTradingPartnershipEntityRelationshipId">Relationship_IntercompanyTradingPartnershipEntityRelationshipId</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntercompanyTradingPartnershipEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InterCompanyTradingPartnerRelationshipId name="BackingTable_InterCompanyTradingPartnerRelationshipId">BackingTable_InterCompanyTradingPartnerRelationshipId</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InterCompanyTradingPartnerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/InterCompanyTradingPartner.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/InterCompanyTradingPartner.cdm.json/InterCompanyTradingPartner</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/InterCompanyTradingPartner.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

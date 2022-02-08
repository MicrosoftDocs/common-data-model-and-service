---
title: IntercompanyTradingPartnershipProcurementValueMappingEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Intercompany procurement value mappings in ProcurementAndSourcing(IntercompanyTradingPartnershipProcurementValueMappingEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intercompany procurement value mappings</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[VendorLegalEntityId](#VendorLegalEntityId)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[DeliveryModeCodeDefinition](#DeliveryModeCodeDefinition)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[ExternalDeliveryModeCode](#ExternalDeliveryModeCode)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[DeliveryTermsCodeDefinition](#DeliveryTermsCodeDefinition)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[ExternalDeliveryTermsCode](#ExternalDeliveryTermsCode)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[ChargeCodeDefinition](#ChargeCodeDefinition)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[ExternalChargeCode](#ExternalChargeCode)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[OrderReturnReasonCodeDefinition](#OrderReturnReasonCodeDefinition)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[ExternalOrderReturnReasonCode](#ExternalOrderReturnReasonCode)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[OrderReturnDispositionCodeDefinition](#OrderReturnDispositionCodeDefinition)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[ExternalOrderReturnDispositionCode](#ExternalOrderReturnDispositionCode)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[OrderInventoryProfileCodeDefinition](#OrderInventoryProfileCodeDefinition)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[ExternalOrderInventoryProfileCode](#ExternalOrderInventoryProfileCode)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[AgreementClassificationDefinition](#AgreementClassificationDefinition)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[ExternalAgreementClassificationCode](#ExternalAgreementClassificationCode)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[Relationship_IntercompanyTradingPartnershipEntityRelationshipId](#Relationship_IntercompanyTradingPartnershipEntityRelationshipId)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|
|[BackingTable_InterCompanyTradingPartnerRelationshipId](#BackingTable_InterCompanyTradingPartnerRelationshipId)||<a href="IntercompanyTradingPartnershipProcurementValueMappingEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity</a>|

### <a href=#VendorLegalEntityId name="VendorLegalEntityId">VendorLegalEntityId</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeCodeDefinition name="DeliveryModeCodeDefinition">DeliveryModeCodeDefinition</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementValueMappingEntity (this entity)  

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

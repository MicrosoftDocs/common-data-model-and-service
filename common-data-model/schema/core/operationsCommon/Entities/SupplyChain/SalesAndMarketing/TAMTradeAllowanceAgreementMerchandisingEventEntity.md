---
title: TAMTradeAllowanceAgreementMerchandisingEventEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Trade allowance agreement merchandising events in SalesAndMarketing(TAMTradeAllowanceAgreementMerchandisingEventEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trade allowance agreement merchandising events</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[EventDescription](#EventDescription)||<a href="TAMTradeAllowanceAgreementMerchandisingEventEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity</a>|
|[EventCostAmount](#EventCostAmount)||<a href="TAMTradeAllowanceAgreementMerchandisingEventEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity</a>|
|[StandardMerchandisingEventCategoryType](#StandardMerchandisingEventCategoryType)||<a href="TAMTradeAllowanceAgreementMerchandisingEventEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity</a>|
|[EventId](#EventId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity</a>|
|[MerchandisingEventCategoryName](#MerchandisingEventCategoryName)||<a href="TAMTradeAllowanceAgreementMerchandisingEventEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity</a>|
|[TradeAllowanceAgreementId](#TradeAllowanceAgreementId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="TAMTradeAllowanceAgreementMerchandisingEventEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity</a>|
|[Relationship_TradeAllowanceAgreementHeaderRelationshipId](#Relationship_TradeAllowanceAgreementHeaderRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity</a>|
|[BackingTable_TAMMerchandisingEventRelationshipId](#BackingTable_TAMMerchandisingEventRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity</a>|

### <a href=#EventDescription name="EventDescription">EventDescription</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EventCostAmount name="EventCostAmount">EventCostAmount</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event cost amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventCostAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Event cost amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandardMerchandisingEventCategoryType name="StandardMerchandisingEventCategoryType">StandardMerchandisingEventCategoryType</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Standard merchandising event category type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardMerchandisingEventCategoryType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Standard merchandising event category type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EventId name="EventId">EventId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MerchandisingEventCategoryName name="MerchandisingEventCategoryName">MerchandisingEventCategoryName</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MerchandisingEventCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAllowanceAgreementId name="TradeAllowanceAgreementId">TradeAllowanceAgreementId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAllowanceAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TradeAllowanceAgreementHeaderRelationshipId name="Relationship_TradeAllowanceAgreementHeaderRelationshipId">Relationship_TradeAllowanceAgreementHeaderRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TradeAllowanceAgreementHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_TAMMerchandisingEventRelationshipId name="BackingTable_TAMMerchandisingEventRelationshipId">BackingTable_TAMMerchandisingEventRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TAMMerchandisingEventRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/TAMMerchandisingEvent.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/TAMMerchandisingEvent.cdm.json/TAMMerchandisingEvent</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/TAMMerchandisingEvent.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventEntity (this entity)  

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

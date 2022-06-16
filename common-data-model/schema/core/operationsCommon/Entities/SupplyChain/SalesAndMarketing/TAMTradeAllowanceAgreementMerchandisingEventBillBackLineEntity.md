---
title: TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Trade allowance agreement merchandising event bill back lines in SalesAndMarketing(TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trade allowance agreement merchandising event bill back lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LineNumber](#LineNumber)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[RebateAgreementRefRecId](#RebateAgreementRefRecId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[BillBackAmountType](#BillBackAmountType)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[FromBillBackQuantity](#FromBillBackQuantity)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[ToBillBackQuantity](#ToBillBackQuantity)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[BillBackQuantityUnitSymbol](#BillBackQuantityUnitSymbol)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[BillBackAmount](#BillBackAmount)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[TradeAllowanceAgreementMerchandisingEventBillBackId](#TradeAllowanceAgreementMerchandisingEventBillBackId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[BillBackAmountCurrencyCode](#BillBackAmountCurrencyCode)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[TradeAllowanceAgreementId](#TradeAllowanceAgreementId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[TradeAllowanceAgreementMerchandisingEventId](#TradeAllowanceAgreementMerchandisingEventId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[Relationship_TradeAllowanceAgreementMerchandisingEventBillBackRelationshipId](#Relationship_TradeAllowanceAgreementMerchandisingEventBillBackRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[Relationship_UnitOfMeasureRelationshipId](#Relationship_UnitOfMeasureRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[Relationship_TradeAllowanceAgreementHeaderRelationshipId](#Relationship_TradeAllowanceAgreementHeaderRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[BackingTable_PdsRebateAgreementLineRelationshipId](#BackingTable_PdsRebateAgreementLineRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity</a>|

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateAgreementRefRecId name="RebateAgreementRefRecId">RebateAgreementRefRecId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateAgreementRefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillBackAmountType name="BillBackAmountType">BillBackAmountType</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillBackAmountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromBillBackQuantity name="FromBillBackQuantity">FromBillBackQuantity</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromBillBackQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToBillBackQuantity name="ToBillBackQuantity">ToBillBackQuantity</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToBillBackQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillBackQuantityUnitSymbol name="BillBackQuantityUnitSymbol">BillBackQuantityUnitSymbol</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillBackQuantityUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillBackAmount name="BillBackAmount">BillBackAmount</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillBackAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAllowanceAgreementMerchandisingEventBillBackId name="TradeAllowanceAgreementMerchandisingEventBillBackId">TradeAllowanceAgreementMerchandisingEventBillBackId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAllowanceAgreementMerchandisingEventBillBackId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillBackAmountCurrencyCode name="BillBackAmountCurrencyCode">BillBackAmountCurrencyCode</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillBackAmountCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAllowanceAgreementId name="TradeAllowanceAgreementId">TradeAllowanceAgreementId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

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

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

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

### <a href=#TradeAllowanceAgreementMerchandisingEventId name="TradeAllowanceAgreementMerchandisingEventId">TradeAllowanceAgreementMerchandisingEventId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAllowanceAgreementMerchandisingEventId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TradeAllowanceAgreementMerchandisingEventBillBackRelationshipId name="Relationship_TradeAllowanceAgreementMerchandisingEventBillBackRelationshipId">Relationship_TradeAllowanceAgreementMerchandisingEventBillBackRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TradeAllowanceAgreementMerchandisingEventBillBackRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnitOfMeasureRelationshipId name="Relationship_UnitOfMeasureRelationshipId">Relationship_UnitOfMeasureRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TradeAllowanceAgreementHeaderRelationshipId name="Relationship_TradeAllowanceAgreementHeaderRelationshipId">Relationship_TradeAllowanceAgreementHeaderRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

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

### <a href=#BackingTable_PdsRebateAgreementLineRelationshipId name="BackingTable_PdsRebateAgreementLineRelationshipId">BackingTable_PdsRebateAgreementLineRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PdsRebateAgreementLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetLine/PdsRebateAgreementLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/PdsRebateAgreementLine.cdm.json/PdsRebateAgreementLine</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetLine/PdsRebateAgreementLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventBillBackLineEntity (this entity)  

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

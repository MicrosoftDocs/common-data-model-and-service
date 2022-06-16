---
title: RetailReturnPolicyChannelPaymentMappingEntity in TransactionsAndOrders - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Payment mapping for channel return policies in TransactionsAndOrders(RetailReturnPolicyChannelPaymentMappingEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment mapping for channel return policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RetailReturnPolicyChannel](#RetailReturnPolicyChannel)||<a href="RetailReturnPolicyChannelPaymentMappingEntity.md" target="_blank">TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity</a>|
|[OriginalTenderTypeId](#OriginalTenderTypeId)||<a href="RetailReturnPolicyChannelPaymentMappingEntity.md" target="_blank">TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity</a>|
|[LineNumber](#LineNumber)||<a href="RetailReturnPolicyChannelPaymentMappingEntity.md" target="_blank">TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity</a>|
|[RetailReturnPolicyChannel_PolicyName](#RetailReturnPolicyChannel_PolicyName)||<a href="RetailReturnPolicyChannelPaymentMappingEntity.md" target="_blank">TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity</a>|
|[AllowedReturnTenderTypeId](#AllowedReturnTenderTypeId)||<a href="RetailReturnPolicyChannelPaymentMappingEntity.md" target="_blank">TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity</a>|
|[BackingTable_RetailReturnPolicyChannelPaymentMappingRelationshipId](#BackingTable_RetailReturnPolicyChannelPaymentMappingRelationshipId)||<a href="RetailReturnPolicyChannelPaymentMappingEntity.md" target="_blank">TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailReturnPolicyChannelPaymentMappingEntity.md" target="_blank">TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity</a>|

### <a href=#RetailReturnPolicyChannel name="RetailReturnPolicyChannel">RetailReturnPolicyChannel</a>

First included in: TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailReturnPolicyChannel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalTenderTypeId name="OriginalTenderTypeId">OriginalTenderTypeId</a>

First included in: TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalTenderTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity (this entity)  

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

### <a href=#RetailReturnPolicyChannel_PolicyName name="RetailReturnPolicyChannel_PolicyName">RetailReturnPolicyChannel_PolicyName</a>

First included in: TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailReturnPolicyChannel_PolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowedReturnTenderTypeId name="AllowedReturnTenderTypeId">AllowedReturnTenderTypeId</a>

First included in: TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedReturnTenderTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailReturnPolicyChannelPaymentMappingRelationshipId name="BackingTable_RetailReturnPolicyChannelPaymentMappingRelationshipId">BackingTable_RetailReturnPolicyChannelPaymentMappingRelationshipId</a>

First included in: TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailReturnPolicyChannelPaymentMappingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/TransactionsAndOrders/Parameter/RetailReturnPolicyChannelPaymentMapping.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Parameter/RetailReturnPolicyChannelPaymentMapping.cdm.json/RetailReturnPolicyChannelPaymentMapping</a></td><td><a href="../../../Tables/Commerce/TransactionsAndOrders/Parameter/RetailReturnPolicyChannelPaymentMapping.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: TransactionsAndOrders/RetailReturnPolicyChannelPaymentMappingEntity (this entity)  

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

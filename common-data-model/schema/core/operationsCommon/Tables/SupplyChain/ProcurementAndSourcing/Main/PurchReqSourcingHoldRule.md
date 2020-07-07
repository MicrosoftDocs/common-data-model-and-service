---
title: PurchReqSourcingHoldRule in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Purchase requisition to purchase order hold rule in Main

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReqSourcingHoldRule.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReqSourcingHoldRule/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase requisition to purchase order hold rule</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchReqSourcingHoldRule.md" target="_blank">Main/PurchReqSourcingHoldRule</a>|
|[EnableHoldByExternalCatalogItem](#EnableHoldByExternalCatalogItem)||<a href="PurchReqSourcingHoldRule.md" target="_blank">Main/PurchReqSourcingHoldRule</a>|
|[EnableHoldByInternalCatalogItem](#EnableHoldByInternalCatalogItem)||<a href="PurchReqSourcingHoldRule.md" target="_blank">Main/PurchReqSourcingHoldRule</a>|
|[EnableHoldByNonCatalogItem](#EnableHoldByNonCatalogItem)||<a href="PurchReqSourcingHoldRule.md" target="_blank">Main/PurchReqSourcingHoldRule</a>|
|[EnableHoldByPrePayment](#EnableHoldByPrePayment)||<a href="PurchReqSourcingHoldRule.md" target="_blank">Main/PurchReqSourcingHoldRule</a>|
|[EnableManualHold](#EnableManualHold)||<a href="PurchReqSourcingHoldRule.md" target="_blank">Main/PurchReqSourcingHoldRule</a>|
|[PolicyRule](#PolicyRule)||<a href="PurchReqSourcingHoldRule.md" target="_blank">Main/PurchReqSourcingHoldRule</a>|
|[IsFinancialDimensionMergeEnabled](#IsFinancialDimensionMergeEnabled)||<a href="PurchReqSourcingHoldRule.md" target="_blank">Main/PurchReqSourcingHoldRule</a>|
|[Relationship_PurchReqSourcingPolicyRuleRelationshipId](#Relationship_PurchReqSourcingPolicyRuleRelationshipId)||<a href="PurchReqSourcingHoldRule.md" target="_blank">Main/PurchReqSourcingHoldRule</a>|
|[Relationship_SysPolicyRuleRelationshipId](#Relationship_SysPolicyRuleRelationshipId)||<a href="PurchReqSourcingHoldRule.md" target="_blank">Main/PurchReqSourcingHoldRule</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/PurchReqSourcingHoldRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReqSourcingHoldRule/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EnableHoldByExternalCatalogItem name="EnableHoldByExternalCatalogItem">EnableHoldByExternalCatalogItem</a>

First included in: Main/PurchReqSourcingHoldRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Categories and vendors for external catalog items</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableHoldByExternalCatalogItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Categories and vendors for external catalog items</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EnableHoldByInternalCatalogItem name="EnableHoldByInternalCatalogItem">EnableHoldByInternalCatalogItem</a>

First included in: Main/PurchReqSourcingHoldRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Categories and vendors for internal catalog items</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableHoldByInternalCatalogItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Categories and vendors for internal catalog items</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EnableHoldByNonCatalogItem name="EnableHoldByNonCatalogItem">EnableHoldByNonCatalogItem</a>

First included in: Main/PurchReqSourcingHoldRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Categories and vendors for non-catalog items</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableHoldByNonCatalogItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Categories and vendors for non-catalog items</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EnableHoldByPrePayment name="EnableHoldByPrePayment">EnableHoldByPrePayment</a>

First included in: Main/PurchReqSourcingHoldRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>When the requisition is set up for prepayment</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableHoldByPrePayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>When the requisition is set up for prepayment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EnableManualHold name="EnableManualHold">EnableManualHold</a>

First included in: Main/PurchReqSourcingHoldRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableManualHold attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PolicyRule name="PolicyRule">PolicyRule</a>

First included in: Main/PurchReqSourcingHoldRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsFinancialDimensionMergeEnabled name="IsFinancialDimensionMergeEnabled">IsFinancialDimensionMergeEnabled</a>

First included in: Main/PurchReqSourcingHoldRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Merge financial dimensions from the vendor that was added after purchase requisition approval</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFinancialDimensionMergeEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Merge financial dimensions from the vendor that was added after purchase requisition approval</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_PurchReqSourcingPolicyRuleRelationshipId name="Relationship_PurchReqSourcingPolicyRuleRelationshipId">Relationship_PurchReqSourcingPolicyRuleRelationshipId</a>

First included in: Main/PurchReqSourcingHoldRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchReqSourcingPolicyRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/PurchReqSourcingPolicyRule.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchReqSourcingPolicyRule.cdm.json/PurchReqSourcingPolicyRule</a></td><td><a href="../Parameter/PurchReqSourcingPolicyRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysPolicyRuleRelationshipId name="Relationship_SysPolicyRuleRelationshipId">Relationship_SysPolicyRuleRelationshipId</a>

First included in: Main/PurchReqSourcingHoldRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysPolicyRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/Workflow/Main/SysPolicyRule.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Main/SysPolicyRule.cdm.json/SysPolicyRule</a></td><td><a href="../../../System/Workflow/Main/SysPolicyRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

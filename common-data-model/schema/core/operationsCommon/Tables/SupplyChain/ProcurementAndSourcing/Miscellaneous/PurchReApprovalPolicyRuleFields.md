---
title: PurchReApprovalPolicyRuleFields in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Purchase order re-approval policy fields in Miscellaneous(PurchReApprovalPolicyRuleFields)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Miscellaneous/PurchReApprovalPolicyRuleFields.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReApprovalPolicyRuleFields/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order re-approval policy fields</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchReApprovalPolicyRuleFields.md" target="_blank">Miscellaneous/PurchReApprovalPolicyRuleFields</a>|
|[PurchReApprovalPolicyRuleTable](#PurchReApprovalPolicyRuleTable)||<a href="PurchReApprovalPolicyRuleFields.md" target="_blank">Miscellaneous/PurchReApprovalPolicyRuleFields</a>|
|[RefFieldId](#RefFieldId)||<a href="PurchReApprovalPolicyRuleFields.md" target="_blank">Miscellaneous/PurchReApprovalPolicyRuleFields</a>|
|[RefTableId](#RefTableId)||<a href="PurchReApprovalPolicyRuleFields.md" target="_blank">Miscellaneous/PurchReApprovalPolicyRuleFields</a>|
|[Relationship_PurchReApprovalPolicyRuleTableRelationshipId](#Relationship_PurchReApprovalPolicyRuleTableRelationshipId)||<a href="PurchReApprovalPolicyRuleFields.md" target="_blank">Miscellaneous/PurchReApprovalPolicyRuleFields</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/PurchReApprovalPolicyRuleFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReApprovalPolicyRuleFields/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchReApprovalPolicyRuleTable name="PurchReApprovalPolicyRuleTable">PurchReApprovalPolicyRuleTable</a>

First included in: Miscellaneous/PurchReApprovalPolicyRuleFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchReApprovalPolicyRuleTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefFieldId name="RefFieldId">RefFieldId</a>

First included in: Miscellaneous/PurchReApprovalPolicyRuleFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: Miscellaneous/PurchReApprovalPolicyRuleFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_PurchReApprovalPolicyRuleTableRelationshipId name="Relationship_PurchReApprovalPolicyRuleTableRelationshipId">Relationship_PurchReApprovalPolicyRuleTableRelationshipId</a>

First included in: Miscellaneous/PurchReApprovalPolicyRuleFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchReApprovalPolicyRuleTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PurchReApprovalPolicyRuleTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReApprovalPolicyRuleTable.cdm.json/PurchReApprovalPolicyRuleTable</a></td><td><a href="../Main/PurchReApprovalPolicyRuleTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

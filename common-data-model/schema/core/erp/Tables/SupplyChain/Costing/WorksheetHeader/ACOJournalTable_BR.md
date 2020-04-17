---
title: ACOJournalTable_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# ACOJournalTable_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/Costing/WorksheetHeader/ACOJournalTable_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ACOJournalTable_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[BlockUserGroupId](#BlockUserGroupId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[BlockUserId](#BlockUserId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[DeletePostedLines](#DeletePostedLines)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[Description](#Description)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[DetailSummary](#DetailSummary)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[ExCostAmount](#ExCostAmount)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[JournalId](#JournalId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[JournalIdOriginal](#JournalIdOriginal)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[JournalNameId](#JournalNameId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[JournalType](#JournalType)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[NumberSequenceTable](#NumberSequenceTable)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[NumOfLines](#NumOfLines)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[Posted](#Posted)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[PostedDateTime](#PostedDateTime)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[PostedUserId](#PostedUserId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[SessionId](#SessionId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[SessionLoginDateTime](#SessionLoginDateTime)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[SystemBlocked](#SystemBlocked)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[TransDate](#TransDate)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[VoucherChange](#VoucherChange)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[VoucherDraw](#VoucherDraw)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[JournalUsedBy](#JournalUsedBy)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[Relationship_ACOJournalName_BRRelationshipId](#Relationship_ACOJournalName_BRRelationshipId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[Relationship_BlockUserGroupInfoRelationshipId](#Relationship_BlockUserGroupInfoRelationshipId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[Relationship_JournalErrorRelationshipId](#Relationship_JournalErrorRelationshipId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[Relationship_NumberSequenceTableRelationshipId](#Relationship_NumberSequenceTableRelationshipId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ACOJournalTable_BR.md" target="_blank">WorksheetHeader/ACOJournalTable_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ACOJournalTable_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BlockUserGroupId name="BlockUserGroupId">BlockUserGroupId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockUserGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BlockUserId name="BlockUserId">BlockUserId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeletePostedLines name="DeletePostedLines">DeletePostedLines</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeletePostedLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DetailSummary name="DetailSummary">DetailSummary</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DetailSummary attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExCostAmount name="ExCostAmount">ExCostAmount</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExCostAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalIdOriginal name="JournalIdOriginal">JournalIdOriginal</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalIdOriginal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNameId name="JournalNameId">JournalNameId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalType name="JournalType">JournalType</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#NumberSequenceTable name="NumberSequenceTable">NumberSequenceTable</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NumOfLines name="NumOfLines">NumOfLines</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumOfLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#PostedDateTime name="PostedDateTime">PostedDateTime</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#PostedUserId name="PostedUserId">PostedUserId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#SessionLoginDateTime name="SessionLoginDateTime">SessionLoginDateTime</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionLoginDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#SystemBlocked name="SystemBlocked">SystemBlocked</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemBlocked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#VoucherChange name="VoucherChange">VoucherChange</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherChange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VoucherDraw name="VoucherDraw">VoucherDraw</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherDraw attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalUsedBy name="JournalUsedBy">JournalUsedBy</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalUsedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ACOJournalName_BRRelationshipId name="Relationship_ACOJournalName_BRRelationshipId">Relationship_ACOJournalName_BRRelationshipId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ACOJournalName_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ACOJournalName_BR.md" target="_blank">/core/erp/Tables/SupplyChain/Costing/Group/ACOJournalName_BR.cdm.json/ACOJournalName_BR</a></td><td><a href="../Group/ACOJournalName_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BlockUserGroupInfoRelationshipId name="Relationship_BlockUserGroupInfoRelationshipId">Relationship_BlockUserGroupInfoRelationshipId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BlockUserGroupInfoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/UserGroupInfo.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Main/UserGroupInfo.cdm.json/UserGroupInfo</a></td><td><a href="../../../System/SystemAdministration/Main/UserGroupInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JournalErrorRelationshipId name="Relationship_JournalErrorRelationshipId">Relationship_JournalErrorRelationshipId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JournalErrorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/WorksheetLine/JournalError.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/WorksheetLine/JournalError.cdm.json/JournalError</a></td><td><a href="../../Inventory/WorksheetLine/JournalError.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_NumberSequenceTableRelationshipId name="Relationship_NumberSequenceTableRelationshipId">Relationship_NumberSequenceTableRelationshipId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/ACOJournalTable_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

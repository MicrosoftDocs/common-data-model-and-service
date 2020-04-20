---
title: EventInbox - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# EventInbox

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Framework/EventInbox.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EventInbox/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[AlertCreatedDateTime](#AlertCreatedDateTime)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[AlertedFor](#AlertedFor)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[AlertFieldId](#AlertFieldId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[AlertFieldLabel](#AlertFieldLabel)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[AlertInstanceRelationType](#AlertInstanceRelationType)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[AlertTableId](#AlertTableId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[CompanyId](#CompanyId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[Deleted](#Deleted)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[DueDateTime](#DueDateTime)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[EmailId](#EmailId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[EmailRecipient](#EmailRecipient)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[EmailTemplateId](#EmailTemplateId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[EnumType](#EnumType)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[EPDrillDown](#EPDrillDown)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[ExtendedDataType](#ExtendedDataType)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[GlobalRule](#GlobalRule)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[InboxId](#InboxId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[IsAggregated](#IsAggregated)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[IsRead](#IsRead)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[KeyFieldNameData](#KeyFieldNameData)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[KeyFieldNameList](#KeyFieldNameList)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[Message](#Message)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[NotificationSource](#NotificationSource)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[NotificationType](#NotificationType)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[ParentTableId](#ParentTableId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[RuleId](#RuleId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[SendEmail](#SendEmail)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[ShowPopup](#ShowPopup)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[Subject](#Subject)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[TypeId](#TypeId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[TypeTrigger](#TypeTrigger)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[UserId](#UserId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[Visible](#Visible)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[Relationship_EventRuleRelationshipId](#Relationship_EventRuleRelationshipId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[Relationship_SysEmailTableRelationshipId](#Relationship_SysEmailTableRelationshipId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|
|[Relationship_SysOutgoingEmailTableRelationshipId](#Relationship_SysOutgoingEmailTableRelationshipId)||<a href="EventInbox.md" target="_blank">Framework/EventInbox</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EventInbox/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AlertCreatedDateTime name="AlertCreatedDateTime">AlertCreatedDateTime</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlertCreatedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#AlertedFor name="AlertedFor">AlertedFor</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlertedFor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlertFieldId name="AlertFieldId">AlertFieldId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlertFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AlertFieldLabel name="AlertFieldLabel">AlertFieldLabel</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlertFieldLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlertInstanceRelationType name="AlertInstanceRelationType">AlertInstanceRelationType</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlertInstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AlertTableId name="AlertTableId">AlertTableId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlertTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#CompanyId name="CompanyId">CompanyId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Deleted name="Deleted">Deleted</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Deleted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DueDateTime name="DueDateTime">DueDateTime</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#EmailId name="EmailId">EmailId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EmailRecipient name="EmailRecipient">EmailRecipient</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailRecipient attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailTemplateId name="EmailTemplateId">EmailTemplateId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnumType name="EnumType">EnumType</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnumType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#EPDrillDown name="EPDrillDown">EPDrillDown</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPDrillDown attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExtendedDataType name="ExtendedDataType">ExtendedDataType</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtendedDataType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#GlobalRule name="GlobalRule">GlobalRule</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GlobalRule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#InboxId name="InboxId">InboxId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InboxId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsAggregated name="IsAggregated">IsAggregated</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAggregated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsRead name="IsRead">IsRead</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRead attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#KeyFieldNameData name="KeyFieldNameData">KeyFieldNameData</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyFieldNameData attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#KeyFieldNameList name="KeyFieldNameList">KeyFieldNameList</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyFieldNameList attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#Message name="Message">Message</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Message attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NotificationSource name="NotificationSource">NotificationSource</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotificationSource attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#NotificationType name="NotificationType">NotificationType</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotificationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ParentTableId name="ParentTableId">ParentTableId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#RuleId name="RuleId">RuleId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RuleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SendEmail name="SendEmail">SendEmail</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SendEmail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowPopup name="ShowPopup">ShowPopup</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowPopup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Subject name="Subject">Subject</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Subject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeId name="TypeId">TypeId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TypeTrigger name="TypeTrigger">TypeTrigger</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeTrigger attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UserId name="UserId">UserId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Visible name="Visible">Visible</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Visible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_EventRuleRelationshipId name="Relationship_EventRuleRelationshipId">Relationship_EventRuleRelationshipId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EventRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/EventRule.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/EventRule.cdm.json/EventRule</a></td><td><a href="../Main/EventRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysEmailTableRelationshipId name="Relationship_SysEmailTableRelationshipId">Relationship_SysEmailTableRelationshipId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysEmailTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/SysEmailTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailTable.cdm.json/SysEmailTable</a></td><td><a href="../Main/SysEmailTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysOutgoingEmailTableRelationshipId name="Relationship_SysOutgoingEmailTableRelationshipId">Relationship_SysOutgoingEmailTableRelationshipId</a>

First included in: Framework/EventInbox (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysOutgoingEmailTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/SysOutgoingEmailTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Transaction/SysOutgoingEmailTable.cdm.json/SysOutgoingEmailTable</a></td><td><a href="../Transaction/SysOutgoingEmailTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

---
title: SysUserInfo - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# SysUserInfo

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Main/SysUserInfo.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysUserInfo/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[compilerTarget](#compilerTarget)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[DefaultCountryRegion](#DefaultCountryRegion)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[docuHandlingActive](#docuHandlingActive)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[docuToolbarButtonActive](#docuToolbarButtonActive)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[Email](#Email)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[EventEmailAlertsWhen](#EventEmailAlertsWhen)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[EventPollFrequency](#EventPollFrequency)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[EventPopUpDisplayWhen](#EventPopUpDisplayWhen)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[EventPopUpLinkDestination](#EventPopUpLinkDestination)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[EventPopUps](#EventPopUps)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[EventWorkflowShowPopup](#EventWorkflowShowPopup)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[EventWorkflowTasksInClient](#EventWorkflowTasksInClient)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[EventWorkflowTasksInEmail](#EventWorkflowTasksInEmail)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[HelpMarkEmptyLinks](#HelpMarkEmptyLinks)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[HelpTheme](#HelpTheme)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[Id](#Id)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[Language](#Language)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[SqmEnabled](#SqmEnabled)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[SqmUserGuid](#SqmUserGuid)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[WorkflowLineItemNotificationFormat](#WorkflowLineItemNotificationFormat)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[Density](#Density)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[Theme](#Theme)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[StartPage](#StartPage)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[defaultExcelExportSite](#defaultExcelExportSite)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[defaultExcelExportPath](#defaultExcelExportPath)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[Mailer](#Mailer)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[AutomaticUrlUpdate](#AutomaticUrlUpdate)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[EnhancedTabSequence](#EnhancedTabSequence)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[TooltipOnFocus](#TooltipOnFocus)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[EventWorkflowTasksInActionCenter](#EventWorkflowTasksInActionCenter)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[NegativeAmountsInRed_CN](#NegativeAmountsInRed_CN)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[Relationship_LanguageTableRelationshipId](#Relationship_LanguageTableRelationshipId)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[Relationship_SysInetThemeTableRelationshipId](#Relationship_SysInetThemeTableRelationshipId)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|
|[Relationship_LogisticsAddressCountryRegionRelationshipId](#Relationship_LogisticsAddressCountryRegionRelationshipId)||<a href="SysUserInfo.md" target="_blank">Main/SysUserInfo</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysUserInfo/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#compilerTarget name="compilerTarget">compilerTarget</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the compilerTarget attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultCountryRegion name="DefaultCountryRegion">DefaultCountryRegion</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#docuHandlingActive name="docuHandlingActive">docuHandlingActive</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the docuHandlingActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#docuToolbarButtonActive name="docuToolbarButtonActive">docuToolbarButtonActive</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the docuToolbarButtonActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EventEmailAlertsWhen name="EventEmailAlertsWhen">EventEmailAlertsWhen</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventEmailAlertsWhen attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EventPollFrequency name="EventPollFrequency">EventPollFrequency</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventPollFrequency attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EventPopUpDisplayWhen name="EventPopUpDisplayWhen">EventPopUpDisplayWhen</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventPopUpDisplayWhen attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EventPopUpLinkDestination name="EventPopUpLinkDestination">EventPopUpLinkDestination</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventPopUpLinkDestination attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EventPopUps name="EventPopUps">EventPopUps</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventPopUps attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EventWorkflowShowPopup name="EventWorkflowShowPopup">EventWorkflowShowPopup</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventWorkflowShowPopup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EventWorkflowTasksInClient name="EventWorkflowTasksInClient">EventWorkflowTasksInClient</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventWorkflowTasksInClient attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EventWorkflowTasksInEmail name="EventWorkflowTasksInEmail">EventWorkflowTasksInEmail</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventWorkflowTasksInEmail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HelpMarkEmptyLinks name="HelpMarkEmptyLinks">HelpMarkEmptyLinks</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HelpMarkEmptyLinks attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HelpTheme name="HelpTheme">HelpTheme</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HelpTheme attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Id name="Id">Id</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Language name="Language">Language</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Language attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SqmEnabled name="SqmEnabled">SqmEnabled</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SqmEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SqmUserGuid name="SqmUserGuid">SqmUserGuid</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SqmUserGuid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowLineItemNotificationFormat name="WorkflowLineItemNotificationFormat">WorkflowLineItemNotificationFormat</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowLineItemNotificationFormat attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Density name="Density">Density</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Density attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Theme name="Theme">Theme</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Theme attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartPage name="StartPage">StartPage</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartPage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#defaultExcelExportSite name="defaultExcelExportSite">defaultExcelExportSite</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the defaultExcelExportSite attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#defaultExcelExportPath name="defaultExcelExportPath">defaultExcelExportPath</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the defaultExcelExportPath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Mailer name="Mailer">Mailer</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Mailer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutomaticUrlUpdate name="AutomaticUrlUpdate">AutomaticUrlUpdate</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticUrlUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnhancedTabSequence name="EnhancedTabSequence">EnhancedTabSequence</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnhancedTabSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TooltipOnFocus name="TooltipOnFocus">TooltipOnFocus</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TooltipOnFocus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EventWorkflowTasksInActionCenter name="EventWorkflowTasksInActionCenter">EventWorkflowTasksInActionCenter</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventWorkflowTasksInActionCenter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NegativeAmountsInRed_CN name="NegativeAmountsInRed_CN">NegativeAmountsInRed_CN</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NegativeAmountsInRed_CN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_LanguageTableRelationshipId name="Relationship_LanguageTableRelationshipId">Relationship_LanguageTableRelationshipId</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LanguageTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/LanguageTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/LanguageTable.cdm.json/LanguageTable</a></td><td><a href="../Group/LanguageTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysInetThemeTableRelationshipId name="Relationship_SysInetThemeTableRelationshipId">Relationship_SysInetThemeTableRelationshipId</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysInetThemeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SysInetThemeTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysInetThemeTable.cdm.json/SysInetThemeTable</a></td><td><a href="SysInetThemeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsAddressCountryRegionRelationshipId name="Relationship_LogisticsAddressCountryRegionRelationshipId">Relationship_LogisticsAddressCountryRegionRelationshipId</a>

First included in: Main/SysUserInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressCountryRegionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

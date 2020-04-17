---
title: JmgRegistrationSetup - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# JmgRegistrationSetup

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/ProductionControl/Parameter/JmgRegistrationSetup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JmgRegistrationSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[ActionPaneSetupID](#ActionPaneSetupID)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[DisableClose](#DisableClose)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[FeedbackStyle](#FeedbackStyle)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[IPCGridSetupID](#IPCGridSetupID)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[LockEmployee](#LockEmployee)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[ProdGridSetupID](#ProdGridSetupID)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[ProjGridSetupID](#ProjGridSetupID)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[SetupId](#SetupId)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[ShowCurrentActivities](#ShowCurrentActivities)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[ShowJobQueue](#ShowJobQueue)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[ShowLinks](#ShowLinks)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[ShowMessages](#ShowMessages)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[ShowPreview](#ShowPreview)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[ShowStatus](#ShowStatus)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[SignInStartPage](#SignInStartPage)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[SignOutFeedback](#SignOutFeedback)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[WrkCtrValidation](#WrkCtrValidation)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[Scanner](#Scanner)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[UseActualTimeOfRegistration](#UseActualTimeOfRegistration)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[EnableDevice](#EnableDevice)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[DefaultProdUnitFilter](#DefaultProdUnitFilter)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[DefaultResourceFilter](#DefaultResourceFilter)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[DefaultResourceGroupFilter](#DefaultResourceGroupFilter)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[EnableWorkerFilter](#EnableWorkerFilter)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[EnableSingleWorker](#EnableSingleWorker)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[GenerateLP](#GenerateLP)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[PrintLabel](#PrintLabel)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[DataAreaId](#DataAreaId)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[Relationship_JmgRegistrationActionPaneTableRelationshipId](#Relationship_JmgRegistrationActionPaneTableRelationshipId)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[Relationship_JmgRegistrationGridTable_IPCRelationshipId](#Relationship_JmgRegistrationGridTable_IPCRelationshipId)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[Relationship_JmgRegistrationGridTable_ProdRelationshipId](#Relationship_JmgRegistrationGridTable_ProdRelationshipId)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[Relationship_JmgRegistrationGridTable_ProjRelationshipId](#Relationship_JmgRegistrationGridTable_ProjRelationshipId)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[Relationship_ProdUnitTableRelationshipId](#Relationship_ProdUnitTableRelationshipId)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[Relationship_ResourceRelationshipId](#Relationship_ResourceRelationshipId)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[Relationship_ResourceGroupRelationshipId](#Relationship_ResourceGroupRelationshipId)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="JmgRegistrationSetup.md" target="_blank">Parameter/JmgRegistrationSetup</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JmgRegistrationSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActionPaneSetupID name="ActionPaneSetupID">ActionPaneSetupID</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionPaneSetupID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DisableClose name="DisableClose">DisableClose</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisableClose attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FeedbackStyle name="FeedbackStyle">FeedbackStyle</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeedbackStyle attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IPCGridSetupID name="IPCGridSetupID">IPCGridSetupID</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IPCGridSetupID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LockEmployee name="LockEmployee">LockEmployee</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LockEmployee attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProdGridSetupID name="ProdGridSetupID">ProdGridSetupID</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdGridSetupID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProjGridSetupID name="ProjGridSetupID">ProjGridSetupID</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjGridSetupID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SetupId name="SetupId">SetupId</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowCurrentActivities name="ShowCurrentActivities">ShowCurrentActivities</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowCurrentActivities attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowJobQueue name="ShowJobQueue">ShowJobQueue</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowJobQueue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowLinks name="ShowLinks">ShowLinks</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowLinks attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowMessages name="ShowMessages">ShowMessages</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowMessages attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowPreview name="ShowPreview">ShowPreview</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowPreview attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowStatus name="ShowStatus">ShowStatus</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SignInStartPage name="SignInStartPage">SignInStartPage</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignInStartPage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SignOutFeedback name="SignOutFeedback">SignOutFeedback</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignOutFeedback attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WrkCtrValidation name="WrkCtrValidation">WrkCtrValidation</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WrkCtrValidation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Scanner name="Scanner">Scanner</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scanner attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseActualTimeOfRegistration name="UseActualTimeOfRegistration">UseActualTimeOfRegistration</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseActualTimeOfRegistration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableDevice name="EnableDevice">EnableDevice</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableDevice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultProdUnitFilter name="DefaultProdUnitFilter">DefaultProdUnitFilter</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProdUnitFilter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultResourceFilter name="DefaultResourceFilter">DefaultResourceFilter</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultResourceFilter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultResourceGroupFilter name="DefaultResourceGroupFilter">DefaultResourceGroupFilter</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultResourceGroupFilter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableWorkerFilter name="EnableWorkerFilter">EnableWorkerFilter</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableWorkerFilter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableSingleWorker name="EnableSingleWorker">EnableSingleWorker</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableSingleWorker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#GenerateLP name="GenerateLP">GenerateLP</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenerateLP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintLabel name="PrintLabel">PrintLabel</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintLabel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

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

### <a href=#Relationship_JmgRegistrationActionPaneTableRelationshipId name="Relationship_JmgRegistrationActionPaneTableRelationshipId">Relationship_JmgRegistrationActionPaneTableRelationshipId</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JmgRegistrationActionPaneTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="JmgRegistrationActionPaneTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/Parameter/JmgRegistrationActionPaneTable.cdm.json/JmgRegistrationActionPaneTable</a></td><td><a href="JmgRegistrationActionPaneTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JmgRegistrationGridTable_IPCRelationshipId name="Relationship_JmgRegistrationGridTable_IPCRelationshipId">Relationship_JmgRegistrationGridTable_IPCRelationshipId</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JmgRegistrationGridTable_IPCRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="JmgRegistrationGridTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/Parameter/JmgRegistrationGridTable.cdm.json/JmgRegistrationGridTable</a></td><td><a href="JmgRegistrationGridTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JmgRegistrationGridTable_ProdRelationshipId name="Relationship_JmgRegistrationGridTable_ProdRelationshipId">Relationship_JmgRegistrationGridTable_ProdRelationshipId</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JmgRegistrationGridTable_ProdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="JmgRegistrationGridTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/Parameter/JmgRegistrationGridTable.cdm.json/JmgRegistrationGridTable</a></td><td><a href="JmgRegistrationGridTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JmgRegistrationGridTable_ProjRelationshipId name="Relationship_JmgRegistrationGridTable_ProjRelationshipId">Relationship_JmgRegistrationGridTable_ProjRelationshipId</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JmgRegistrationGridTable_ProjRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="JmgRegistrationGridTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/Parameter/JmgRegistrationGridTable.cdm.json/JmgRegistrationGridTable</a></td><td><a href="JmgRegistrationGridTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdUnitTableRelationshipId name="Relationship_ProdUnitTableRelationshipId">Relationship_ProdUnitTableRelationshipId</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdUnitTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProdUnitTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/Group/ProdUnitTable.cdm.json/ProdUnitTable</a></td><td><a href="../Group/ProdUnitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ResourceRelationshipId name="Relationship_ResourceRelationshipId">Relationship_ResourceRelationshipId</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ResourceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Main/WrkCtrTable.cdm.json/WrkCtrTable</a></td><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ResourceGroupRelationshipId name="Relationship_ResourceGroupRelationshipId">Relationship_ResourceGroupRelationshipId</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ResourceGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Main/WrkCtrTable.cdm.json/WrkCtrTable</a></td><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/JmgRegistrationSetup (this entity)  

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

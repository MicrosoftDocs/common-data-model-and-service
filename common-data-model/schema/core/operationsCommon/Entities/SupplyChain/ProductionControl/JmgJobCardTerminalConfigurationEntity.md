---
title: JmgJobCardTerminalConfigurationEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Job card terminal configurations in ProductionControl(JmgJobCardTerminalConfigurationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgJobCardTerminalConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Job card terminal configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[JobCardTerminalActionPaneConfigurationRecId](#JobCardTerminalActionPaneConfigurationRecId)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[JobCardTerminalIndirectActivitiesGridConfigurationRecId](#JobCardTerminalIndirectActivitiesGridConfigurationRecId)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[IsWorkerIdFieldDisabled](#IsWorkerIdFieldDisabled)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[JobCardTerminalProductionGridConfigurationRecId](#JobCardTerminalProductionGridConfigurationRecId)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[JobCardTerminalProjectGridConfigurationRecId](#JobCardTerminalProjectGridConfigurationRecId)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[ConfigurationId](#ConfigurationId)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[CurrentActivitiesFactBoxDisplayMode](#CurrentActivitiesFactBoxDisplayMode)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[MustWorkerSpecifyProductionAreaBeforeRegistration](#MustWorkerSpecifyProductionAreaBeforeRegistration)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[MessagesFactBoxDisplayMode](#MessagesFactBoxDisplayMode)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[PreviewPaneDisplayMode](#PreviewPaneDisplayMode)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[JobStatusFactBoxDisplayMode](#JobStatusFactBoxDisplayMode)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[SignInStartPage](#SignInStartPage)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[WillClockOutPromptWorkerForQuantity](#WillClockOutPromptWorkerForQuantity)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[WillRegistrationFormValidateScheduledJobList](#WillRegistrationFormValidateScheduledJobList)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[IsBarcodeScannerPrimaryInputDevice](#IsBarcodeScannerPrimaryInputDevice)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[IsActualRegistrationTimeUsed](#IsActualRegistrationTimeUsed)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[JobCardTerminalActionPaneConfigurationId](#JobCardTerminalActionPaneConfigurationId)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[JobCardTerminalIndirectActivitesGridConfigurationId](#JobCardTerminalIndirectActivitesGridConfigurationId)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[JobCardTerminalProductionGridConfigurationId](#JobCardTerminalProductionGridConfigurationId)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[JobCardTerminalProjectGridConfigurationId](#JobCardTerminalProjectGridConfigurationId)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[BackingTable_JmgRegistrationSetupRelationshipId](#BackingTable_JmgRegistrationSetupRelationshipId)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgJobCardTerminalConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardTerminalConfigurationEntity</a>|

### <a href=#JobCardTerminalActionPaneConfigurationRecId name="JobCardTerminalActionPaneConfigurationRecId">JobCardTerminalActionPaneConfigurationRecId</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobCardTerminalActionPaneConfigurationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobCardTerminalIndirectActivitiesGridConfigurationRecId name="JobCardTerminalIndirectActivitiesGridConfigurationRecId">JobCardTerminalIndirectActivitiesGridConfigurationRecId</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobCardTerminalIndirectActivitiesGridConfigurationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkerIdFieldDisabled name="IsWorkerIdFieldDisabled">IsWorkerIdFieldDisabled</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkerIdFieldDisabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobCardTerminalProductionGridConfigurationRecId name="JobCardTerminalProductionGridConfigurationRecId">JobCardTerminalProductionGridConfigurationRecId</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobCardTerminalProductionGridConfigurationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobCardTerminalProjectGridConfigurationRecId name="JobCardTerminalProjectGridConfigurationRecId">JobCardTerminalProjectGridConfigurationRecId</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobCardTerminalProjectGridConfigurationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfigurationId name="ConfigurationId">ConfigurationId</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentActivitiesFactBoxDisplayMode name="CurrentActivitiesFactBoxDisplayMode">CurrentActivitiesFactBoxDisplayMode</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentActivitiesFactBoxDisplayMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MustWorkerSpecifyProductionAreaBeforeRegistration name="MustWorkerSpecifyProductionAreaBeforeRegistration">MustWorkerSpecifyProductionAreaBeforeRegistration</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MustWorkerSpecifyProductionAreaBeforeRegistration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MessagesFactBoxDisplayMode name="MessagesFactBoxDisplayMode">MessagesFactBoxDisplayMode</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessagesFactBoxDisplayMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreviewPaneDisplayMode name="PreviewPaneDisplayMode">PreviewPaneDisplayMode</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreviewPaneDisplayMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobStatusFactBoxDisplayMode name="JobStatusFactBoxDisplayMode">JobStatusFactBoxDisplayMode</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobStatusFactBoxDisplayMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignInStartPage name="SignInStartPage">SignInStartPage</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignInStartPage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillClockOutPromptWorkerForQuantity name="WillClockOutPromptWorkerForQuantity">WillClockOutPromptWorkerForQuantity</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillClockOutPromptWorkerForQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRegistrationFormValidateScheduledJobList name="WillRegistrationFormValidateScheduledJobList">WillRegistrationFormValidateScheduledJobList</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRegistrationFormValidateScheduledJobList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBarcodeScannerPrimaryInputDevice name="IsBarcodeScannerPrimaryInputDevice">IsBarcodeScannerPrimaryInputDevice</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBarcodeScannerPrimaryInputDevice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActualRegistrationTimeUsed name="IsActualRegistrationTimeUsed">IsActualRegistrationTimeUsed</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActualRegistrationTimeUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobCardTerminalActionPaneConfigurationId name="JobCardTerminalActionPaneConfigurationId">JobCardTerminalActionPaneConfigurationId</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobCardTerminalActionPaneConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobCardTerminalIndirectActivitesGridConfigurationId name="JobCardTerminalIndirectActivitesGridConfigurationId">JobCardTerminalIndirectActivitesGridConfigurationId</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobCardTerminalIndirectActivitesGridConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobCardTerminalProductionGridConfigurationId name="JobCardTerminalProductionGridConfigurationId">JobCardTerminalProductionGridConfigurationId</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobCardTerminalProductionGridConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobCardTerminalProjectGridConfigurationId name="JobCardTerminalProjectGridConfigurationId">JobCardTerminalProjectGridConfigurationId</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobCardTerminalProjectGridConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_JmgRegistrationSetupRelationshipId name="BackingTable_JmgRegistrationSetupRelationshipId">BackingTable_JmgRegistrationSetupRelationshipId</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgRegistrationSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/JmgRegistrationSetup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Parameter/JmgRegistrationSetup.cdm.json/JmgRegistrationSetup</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/JmgRegistrationSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgJobCardTerminalConfigurationEntity (this entity)  

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

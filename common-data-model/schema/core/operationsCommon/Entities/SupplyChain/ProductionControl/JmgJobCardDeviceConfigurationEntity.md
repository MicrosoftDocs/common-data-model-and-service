---
title: JmgJobCardDeviceConfigurationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Job card device configurations

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgJobCardDeviceConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Job card device configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsWorkerIdFieldDisabled](#IsWorkerIdFieldDisabled)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|
|[ConfigurationId](#ConfigurationId)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|
|[WillClockOutPromptWorkerForQuantity](#WillClockOutPromptWorkerForQuantity)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|
|[IsBarcodeScannerPrimaryInputDevice](#IsBarcodeScannerPrimaryInputDevice)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|
|[IsActualRegistrationTimeUsed](#IsActualRegistrationTimeUsed)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|
|[DefaultProductionUnitIdFilter](#DefaultProductionUnitIdFilter)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|
|[DefaultOperationsResourceIdFilter](#DefaultOperationsResourceIdFilter)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|
|[DefaultOperationsResourceGroupIdFilter](#DefaultOperationsResourceGroupIdFilter)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|
|[ArePersonalFiltersAllowed](#ArePersonalFiltersAllowed)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|
|[IsSingleWorkerModeEnforced](#IsSingleWorkerModeEnforced)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|
|[BackingTable_JmgRegistrationSetupRelationshipId](#BackingTable_JmgRegistrationSetupRelationshipId)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgJobCardDeviceConfigurationEntity.md" target="_blank">ProductionControl/JmgJobCardDeviceConfigurationEntity</a>|

### <a href=#IsWorkerIdFieldDisabled name="IsWorkerIdFieldDisabled">IsWorkerIdFieldDisabled</a>

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

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

### <a href=#ConfigurationId name="ConfigurationId">ConfigurationId</a>

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

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

### <a href=#WillClockOutPromptWorkerForQuantity name="WillClockOutPromptWorkerForQuantity">WillClockOutPromptWorkerForQuantity</a>

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

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

### <a href=#IsBarcodeScannerPrimaryInputDevice name="IsBarcodeScannerPrimaryInputDevice">IsBarcodeScannerPrimaryInputDevice</a>

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

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

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

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

### <a href=#DefaultProductionUnitIdFilter name="DefaultProductionUnitIdFilter">DefaultProductionUnitIdFilter</a>

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProductionUnitIdFilter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOperationsResourceIdFilter name="DefaultOperationsResourceIdFilter">DefaultOperationsResourceIdFilter</a>

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOperationsResourceIdFilter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOperationsResourceGroupIdFilter name="DefaultOperationsResourceGroupIdFilter">DefaultOperationsResourceGroupIdFilter</a>

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOperationsResourceGroupIdFilter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePersonalFiltersAllowed name="ArePersonalFiltersAllowed">ArePersonalFiltersAllowed</a>

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePersonalFiltersAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSingleWorkerModeEnforced name="IsSingleWorkerModeEnforced">IsSingleWorkerModeEnforced</a>

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSingleWorkerModeEnforced attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_JmgRegistrationSetupRelationshipId name="BackingTable_JmgRegistrationSetupRelationshipId">BackingTable_JmgRegistrationSetupRelationshipId</a>

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

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

First included in: ProductionControl/JmgJobCardDeviceConfigurationEntity (this entity)  

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

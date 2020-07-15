---
title: GBTParametersEntity in SystemAdministration - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# GB/T 24589 parameters in SystemAdministration(GBTParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/SystemAdministration/GBTParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>GB/T 24589 parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AcquisitionLedgerDimension](#AcquisitionLedgerDimension)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[BalanceSheet](#BalanceSheet)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[CashflowAdditional](#CashflowAdditional)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[CashflowCodeFormat](#CashflowCodeFormat)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[CashFlowDimension](#CashFlowDimension)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[CashflowMajorSheet](#CashflowMajorSheet)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[ChangesOfOwnersEquity](#ChangesOfOwnersEquity)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[DepreciationLedgerDimension](#DepreciationLedgerDimension)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[DisposalLedgerDimension](#DisposalLedgerDimension)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[FixedAssetGroupCodeFormat](#FixedAssetGroupCodeFormat)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[IncomeSheet](#IncomeSheet)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[Industry](#Industry)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[key](#key)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[OrgNumber](#OrgNumber)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[OrgType](#OrgType)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[ERModelName](#ERModelName)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[AcquisitionLedgerDimensionDisplayValue](#AcquisitionLedgerDimensionDisplayValue)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[DepreciationLedgerDimensionDisplayValue](#DepreciationLedgerDimensionDisplayValue)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[DisposalLedgerDimensionDisplayValue](#DisposalLedgerDimensionDisplayValue)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[Relationship_AcquisitionLedgerDimensionCombinationRelationshipId](#Relationship_AcquisitionLedgerDimensionCombinationRelationshipId)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[Relationship_DepreciationLedgerDimensionCombinationRelationshipId](#Relationship_DepreciationLedgerDimensionCombinationRelationshipId)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[Relationship_DisposalLedgerDimensionCombinationRelationshipId](#Relationship_DisposalLedgerDimensionCombinationRelationshipId)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[BackingTable_GBTParameters_CNRelationshipId](#BackingTable_GBTParameters_CNRelationshipId)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="GBTParametersEntity.md" target="_blank">SystemAdministration/GBTParametersEntity</a>|

### <a href=#AcquisitionLedgerDimension name="AcquisitionLedgerDimension">AcquisitionLedgerDimension</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceSheet name="BalanceSheet">BalanceSheet</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashflowAdditional name="CashflowAdditional">CashflowAdditional</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashflowAdditional attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashflowCodeFormat name="CashflowCodeFormat">CashflowCodeFormat</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashflowCodeFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashFlowDimension name="CashFlowDimension">CashFlowDimension</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashFlowDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashflowMajorSheet name="CashflowMajorSheet">CashflowMajorSheet</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashflowMajorSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangesOfOwnersEquity name="ChangesOfOwnersEquity">ChangesOfOwnersEquity</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangesOfOwnersEquity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationLedgerDimension name="DepreciationLedgerDimension">DepreciationLedgerDimension</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisposalLedgerDimension name="DisposalLedgerDimension">DisposalLedgerDimension</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposalLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetGroupCodeFormat name="FixedAssetGroupCodeFormat">FixedAssetGroupCodeFormat</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetGroupCodeFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncomeSheet name="IncomeSheet">IncomeSheet</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomeSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Industry name="Industry">Industry</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Industry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#key name="key">key</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the key attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrgNumber name="OrgNumber">OrgNumber</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrgNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrgType name="OrgType">OrgType</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrgType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ERModelName name="ERModelName">ERModelName</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERModelName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcquisitionLedgerDimensionDisplayValue name="AcquisitionLedgerDimensionDisplayValue">AcquisitionLedgerDimensionDisplayValue</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationLedgerDimensionDisplayValue name="DepreciationLedgerDimensionDisplayValue">DepreciationLedgerDimensionDisplayValue</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisposalLedgerDimensionDisplayValue name="DisposalLedgerDimensionDisplayValue">DisposalLedgerDimensionDisplayValue</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposalLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AcquisitionLedgerDimensionCombinationRelationshipId name="Relationship_AcquisitionLedgerDimensionCombinationRelationshipId">Relationship_AcquisitionLedgerDimensionCombinationRelationshipId</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AcquisitionLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DepreciationLedgerDimensionCombinationRelationshipId name="Relationship_DepreciationLedgerDimensionCombinationRelationshipId">Relationship_DepreciationLedgerDimensionCombinationRelationshipId</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DepreciationLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DisposalLedgerDimensionCombinationRelationshipId name="Relationship_DisposalLedgerDimensionCombinationRelationshipId">Relationship_DisposalLedgerDimensionCombinationRelationshipId</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DisposalLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_GBTParameters_CNRelationshipId name="BackingTable_GBTParameters_CNRelationshipId">BackingTable_GBTParameters_CNRelationshipId</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_GBTParameters_CNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Parameter/GBTParameters_CN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Parameter/GBTParameters_CN.cdm.json/GBTParameters_CN</a></td><td><a href="../../../Tables/Finance/Tax/Parameter/GBTParameters_CN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SystemAdministration/GBTParametersEntity (this entity)  

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

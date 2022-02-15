---
title: LedgerAllocationEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Ledger allocation for main accounts in GeneralLedger(LedgerAllocationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerAllocationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger allocation for main accounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SourceAccount](#SourceAccount)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[FromMainAccountRecId](#FromMainAccountRecId)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[FromMainAccountLedgerChartOfAccountsRecId](#FromMainAccountLedgerChartOfAccountsRecId)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[MainAccountId](#MainAccountId)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[LineNumber](#LineNumber)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[AllocationPercentage](#AllocationPercentage)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[SourceSelectionCriteria](#SourceSelectionCriteria)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[SourceSelectionCriteriaDisplayValue](#SourceSelectionCriteriaDisplayValue)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[SourceSelectionCriteriaDimensions](#SourceSelectionCriteriaDimensions)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[SourceSelectionCriteriaDimensionsDisplayValue](#SourceSelectionCriteriaDimensionsDisplayValue)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[DestinationAccount](#DestinationAccount)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[DestinationAccountDisplayValue](#DestinationAccountDisplayValue)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[DestinationKeepSourceDimensions](#DestinationKeepSourceDimensions)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[DestinationKeepSourceDimensionsDisplayValue](#DestinationKeepSourceDimensionsDisplayValue)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[DestinationDimensions](#DestinationDimensions)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[DestinationDimensionsDisplayValue](#DestinationDimensionsDisplayValue)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[Relationship_SourceSelectionCriteriaDimensionsDimensionSetRelationshipId](#Relationship_SourceSelectionCriteriaDimensionsDimensionSetRelationshipId)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[Relationship_DestinationDimensionsDimensionSetRelationshipId](#Relationship_DestinationDimensionsDimensionSetRelationshipId)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[Relationship_DestinationAccountCombinationRelationshipId](#Relationship_DestinationAccountCombinationRelationshipId)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[BackingTable_LedgerAllocationRelationshipId](#BackingTable_LedgerAllocationRelationshipId)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerAllocationEntity.md" target="_blank">GeneralLedger/LedgerAllocationEntity</a>|

### <a href=#SourceAccount name="SourceAccount">SourceAccount</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromMainAccountRecId name="FromMainAccountRecId">FromMainAccountRecId</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromMainAccountRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromMainAccountLedgerChartOfAccountsRecId name="FromMainAccountLedgerChartOfAccountsRecId">FromMainAccountLedgerChartOfAccountsRecId</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromMainAccountLedgerChartOfAccountsRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountId name="MainAccountId">MainAccountId</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Source Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

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

### <a href=#AllocationPercentage name="AllocationPercentage">AllocationPercentage</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceSelectionCriteria name="SourceSelectionCriteria">SourceSelectionCriteria</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceSelectionCriteria attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceSelectionCriteriaDisplayValue name="SourceSelectionCriteriaDisplayValue">SourceSelectionCriteriaDisplayValue</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source selection criteria</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceSelectionCriteriaDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Source selection criteria</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceSelectionCriteriaDimensions name="SourceSelectionCriteriaDimensions">SourceSelectionCriteriaDimensions</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceSelectionCriteriaDimensions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceSelectionCriteriaDimensionsDisplayValue name="SourceSelectionCriteriaDimensionsDisplayValue">SourceSelectionCriteriaDimensionsDisplayValue</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source financial dimension values</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceSelectionCriteriaDimensionsDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Source financial dimension values</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationAccount name="DestinationAccount">DestinationAccount</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationAccountDisplayValue name="DestinationAccountDisplayValue">DestinationAccountDisplayValue</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Destination Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Destination Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationKeepSourceDimensions name="DestinationKeepSourceDimensions">DestinationKeepSourceDimensions</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationKeepSourceDimensions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationKeepSourceDimensionsDisplayValue name="DestinationKeepSourceDimensionsDisplayValue">DestinationKeepSourceDimensionsDisplayValue</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Destination keep source financial dimensions</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationKeepSourceDimensionsDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Destination keep source financial dimensions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationDimensions name="DestinationDimensions">DestinationDimensions</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationDimensions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationDimensionsDisplayValue name="DestinationDimensionsDisplayValue">DestinationDimensionsDisplayValue</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Destination financial dimension values</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationDimensionsDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Destination financial dimension values</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourceSelectionCriteriaDimensionsDimensionSetRelationshipId name="Relationship_SourceSelectionCriteriaDimensionsDimensionSetRelationshipId">Relationship_SourceSelectionCriteriaDimensionsDimensionSetRelationshipId</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceSelectionCriteriaDimensionsDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DestinationDimensionsDimensionSetRelationshipId name="Relationship_DestinationDimensionsDimensionSetRelationshipId">Relationship_DestinationDimensionsDimensionSetRelationshipId</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DestinationDimensionsDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DestinationAccountCombinationRelationshipId name="Relationship_DestinationAccountCombinationRelationshipId">Relationship_DestinationAccountCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DestinationAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_LedgerAllocationRelationshipId name="BackingTable_LedgerAllocationRelationshipId">BackingTable_LedgerAllocationRelationshipId</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerAllocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/LedgerAllocation.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/LedgerAllocation.cdm.json/LedgerAllocation</a></td><td><a href="../../../Tables/Finance/Ledger/Main/LedgerAllocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/LedgerAllocationEntity (this entity)  

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

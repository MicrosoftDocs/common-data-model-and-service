---
title: InventTestGroupMember - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Test group members

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventTestGroupMember.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTestGroupMember/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Test group members</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[AcceptableQualityLevel](#AcceptableQualityLevel)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[ActionOnFailure](#ActionOnFailure)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[CertificateOfAnalysis](#CertificateOfAnalysis)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[LowerLimit](#LowerLimit)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[LowerTolerance](#LowerTolerance)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[PdsBatchAttribId](#PdsBatchAttribId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[PdsTestResultValueDerivation](#PdsTestResultValueDerivation)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[PdsUpdateBatchAttributes](#PdsUpdateBatchAttributes)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[StandardValue](#StandardValue)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[TestGroupId](#TestGroupId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[TestId](#TestId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[TestInstrumentId](#TestInstrumentId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[TestSequence](#TestSequence)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[TestUnitId](#TestUnitId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[UpperLimit](#UpperLimit)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[UpperTolerance](#UpperTolerance)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[ValidFromDateTime](#ValidFromDateTime)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[ValidToDateTime](#ValidToDateTime)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[VariableId](#VariableId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[VariableOutcomeIdStandard](#VariableOutcomeIdStandard)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[DataAreaId](#DataAreaId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[Relationship_InventTestGroupRelationshipId](#Relationship_InventTestGroupRelationshipId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[Relationship_InventTestInstrumentRelationshipId](#Relationship_InventTestInstrumentRelationshipId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[Relationship_InventTestTableRelationshipId](#Relationship_InventTestTableRelationshipId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[Relationship_InventTestVariableRelationshipId](#Relationship_InventTestVariableRelationshipId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[Relationship_InventTestVariableOutcomeRelationshipId](#Relationship_InventTestVariableOutcomeRelationshipId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[Relationship_PdsBatchAttribRelationshipId](#Relationship_PdsBatchAttribRelationshipId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[Relationship_PdsBatchAttribEnumValuesRelationshipId](#Relationship_PdsBatchAttribEnumValuesRelationshipId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventTestGroupMember.md" target="_blank">Group/InventTestGroupMember</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTestGroupMember/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcceptableQualityLevel name="AcceptableQualityLevel">AcceptableQualityLevel</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptableQualityLevel attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ActionOnFailure name="ActionOnFailure">ActionOnFailure</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionOnFailure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CertificateOfAnalysis name="CertificateOfAnalysis">CertificateOfAnalysis</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateOfAnalysis attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LowerLimit name="LowerLimit">LowerLimit</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowerLimit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LowerTolerance name="LowerTolerance">LowerTolerance</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowerTolerance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsBatchAttribId name="PdsBatchAttribId">PdsBatchAttribId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsBatchAttribId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsTestResultValueDerivation name="PdsTestResultValueDerivation">PdsTestResultValueDerivation</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Test value determination</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsTestResultValueDerivation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Test value determination</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PdsUpdateBatchAttributes name="PdsUpdateBatchAttributes">PdsUpdateBatchAttributes</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsUpdateBatchAttributes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StandardValue name="StandardValue">StandardValue</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TestGroupId name="TestGroupId">TestGroupId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TestId name="TestId">TestId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TestInstrumentId name="TestInstrumentId">TestInstrumentId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestInstrumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TestSequence name="TestSequence">TestSequence</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TestUnitId name="TestUnitId">TestUnitId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpperLimit name="UpperLimit">UpperLimit</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpperLimit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UpperTolerance name="UpperTolerance">UpperTolerance</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpperTolerance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ValidFromDateTime name="ValidFromDateTime">ValidFromDateTime</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFromDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidToDateTime name="ValidToDateTime">ValidToDateTime</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidToDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#VariableId name="VariableId">VariableId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariableOutcomeIdStandard name="VariableOutcomeIdStandard">VariableOutcomeIdStandard</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariableOutcomeIdStandard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/InventTestGroupMember (this entity)  

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

### <a href=#Relationship_InventTestGroupRelationshipId name="Relationship_InventTestGroupRelationshipId">Relationship_InventTestGroupRelationshipId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventTestGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventTestGroup.cdm.json/InventTestGroup</a></td><td><a href="InventTestGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTestInstrumentRelationshipId name="Relationship_InventTestInstrumentRelationshipId">Relationship_InventTestInstrumentRelationshipId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestInstrumentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventTestInstrument.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventTestInstrument.cdm.json/InventTestInstrument</a></td><td><a href="InventTestInstrument.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTestTableRelationshipId name="Relationship_InventTestTableRelationshipId">Relationship_InventTestTableRelationshipId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventTestTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventTestTable.cdm.json/InventTestTable</a></td><td><a href="../Main/InventTestTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTestVariableRelationshipId name="Relationship_InventTestVariableRelationshipId">Relationship_InventTestVariableRelationshipId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestVariableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventTestVariable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventTestVariable.cdm.json/InventTestVariable</a></td><td><a href="../Main/InventTestVariable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTestVariableOutcomeRelationshipId name="Relationship_InventTestVariableOutcomeRelationshipId">Relationship_InventTestVariableOutcomeRelationshipId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestVariableOutcomeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventTestVariableOutcome.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventTestVariableOutcome.cdm.json/InventTestVariableOutcome</a></td><td><a href="../Main/InventTestVariableOutcome.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PdsBatchAttribRelationshipId name="Relationship_PdsBatchAttribRelationshipId">Relationship_PdsBatchAttribRelationshipId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsBatchAttribRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PdsBatchAttrib.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/PdsBatchAttrib.cdm.json/PdsBatchAttrib</a></td><td><a href="../Main/PdsBatchAttrib.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PdsBatchAttribEnumValuesRelationshipId name="Relationship_PdsBatchAttribEnumValuesRelationshipId">Relationship_PdsBatchAttribEnumValuesRelationshipId</a>

First included in: Group/InventTestGroupMember (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsBatchAttribEnumValuesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PdsBatchAttribEnumValues.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/PdsBatchAttribEnumValues.cdm.json/PdsBatchAttribEnumValues</a></td><td><a href="../Main/PdsBatchAttribEnumValues.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/InventTestGroupMember (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

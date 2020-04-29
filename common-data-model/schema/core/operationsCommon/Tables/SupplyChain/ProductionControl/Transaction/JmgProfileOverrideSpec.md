---
title: JmgProfileOverrideSpec - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Profile time override

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductionControl/Transaction/JmgProfileOverrideSpec.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JmgProfileOverrideSpec/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Profile time override</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[EndDay](#EndDay)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[EndTime](#EndTime)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[EventCode](#EventCode)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[LineNum](#LineNum)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[ProfileDate](#ProfileDate)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[ProfileType](#ProfileType)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[SecondaryProfileType](#SecondaryProfileType)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[StartDay](#StartDay)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[StartTime](#StartTime)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[ToleranceAfter](#ToleranceAfter)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[ToleranceAfterStart](#ToleranceAfterStart)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[ToleranceBefore](#ToleranceBefore)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[ToleranceBeforeEnd](#ToleranceBeforeEnd)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[Worker](#Worker)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[DataAreaId](#DataAreaId)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[Relationship_JmgProfileTypeTableRelationshipId](#Relationship_JmgProfileTypeTableRelationshipId)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[Relationship_JmgProfileTypeTable_SecondaryRelationshipId](#Relationship_JmgProfileTypeTable_SecondaryRelationshipId)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[Relationship_SwitchJmgIpcActivityRelationshipId](#Relationship_SwitchJmgIpcActivityRelationshipId)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="JmgProfileOverrideSpec.md" target="_blank">Transaction/JmgProfileOverrideSpec</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JmgProfileOverrideSpec/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EndDay name="EndDay">EndDay</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDay attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EndTime name="EndTime">EndTime</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End</td></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>End</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.time**  
</details>

### <a href=#EventCode name="EventCode">EventCode</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ProfileDate name="ProfileDate">ProfileDate</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ProfileType name="ProfileType">ProfileType</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SecondaryProfileType name="SecondaryProfileType">SecondaryProfileType</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Secondary</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryProfileType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Secondary</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#StartDay name="StartDay">StartDay</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDay attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartTime name="StartTime">StartTime</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start</td></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Start</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.time**  
</details>

### <a href=#ToleranceAfter name="ToleranceAfter">ToleranceAfter</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>T. after</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToleranceAfter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>T. after</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ToleranceAfterStart name="ToleranceAfterStart">ToleranceAfterStart</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToleranceAfterStart attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ToleranceBefore name="ToleranceBefore">ToleranceBefore</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>T. before</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToleranceBefore attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>T. before</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ToleranceBeforeEnd name="ToleranceBeforeEnd">ToleranceBeforeEnd</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToleranceBeforeEnd attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Worker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

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

### <a href=#Relationship_JmgProfileTypeTableRelationshipId name="Relationship_JmgProfileTypeTableRelationshipId">Relationship_JmgProfileTypeTableRelationshipId</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JmgProfileTypeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/JmgProfileTypeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Reference/JmgProfileTypeTable.cdm.json/JmgProfileTypeTable</a></td><td><a href="../Reference/JmgProfileTypeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JmgProfileTypeTable_SecondaryRelationshipId name="Relationship_JmgProfileTypeTable_SecondaryRelationshipId">Relationship_JmgProfileTypeTable_SecondaryRelationshipId</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JmgProfileTypeTable_SecondaryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/JmgProfileTypeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Reference/JmgProfileTypeTable.cdm.json/JmgProfileTypeTable</a></td><td><a href="../Reference/JmgProfileTypeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SwitchJmgIpcActivityRelationshipId name="Relationship_SwitchJmgIpcActivityRelationshipId">Relationship_SwitchJmgIpcActivityRelationshipId</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SwitchJmgIpcActivityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/JmgIpcActivity.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Reference/JmgIpcActivity.cdm.json/JmgIpcActivity</a></td><td><a href="../Reference/JmgIpcActivity.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/JmgProfileOverrideSpec (this entity)  

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

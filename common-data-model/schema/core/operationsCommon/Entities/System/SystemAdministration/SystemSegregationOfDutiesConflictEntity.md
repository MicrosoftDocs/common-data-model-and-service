---
title: SystemSegregationOfDutiesConflictEntity in SystemAdministration - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Security segregation of duties conflict in SystemAdministration(SystemSegregationOfDutiesConflictEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/SystemAdministration/SystemSegregationOfDutiesConflictEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Security segregation of duties conflict</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SegregationOfDutiesRule](#SegregationOfDutiesRule)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[SegregationOfDutiesRuleValidFrom](#SegregationOfDutiesRuleValidFrom)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[SegregationOfDutiesRuleValidTo](#SegregationOfDutiesRuleValidTo)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[SegregationOfDutiesRuleName](#SegregationOfDutiesRuleName)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[User](#User)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[ExistingRole](#ExistingRole)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[ExistingRoleIdentifier](#ExistingRoleIdentifier)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[ExistingRoleName](#ExistingRoleName)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[ExistingDuty](#ExistingDuty)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[ExistingDutyIdentifier](#ExistingDutyIdentifier)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[ExistingDutyName](#ExistingDutyName)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[NewRole](#NewRole)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[NewRoleIdentifier](#NewRoleIdentifier)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[NewRoleName](#NewRoleName)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[NewDuty](#NewDuty)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[NewDutyIdentifier](#NewDutyIdentifier)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[NewDutyName](#NewDutyName)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[AssignmentMode](#AssignmentMode)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[ReasonForOverride](#ReasonForOverride)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|
|[Resolution](#Resolution)||<a href="SystemSegregationOfDutiesConflictEntity.md" target="_blank">SystemAdministration/SystemSegregationOfDutiesConflictEntity</a>|

### <a href=#SegregationOfDutiesRule name="SegregationOfDutiesRule">SegregationOfDutiesRule</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegregationOfDutiesRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegregationOfDutiesRuleValidFrom name="SegregationOfDutiesRuleValidFrom">SegregationOfDutiesRuleValidFrom</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rule valid from</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegregationOfDutiesRuleValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rule valid from</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegregationOfDutiesRuleValidTo name="SegregationOfDutiesRuleValidTo">SegregationOfDutiesRuleValidTo</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rule valid to</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegregationOfDutiesRuleValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rule valid to</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegregationOfDutiesRuleName name="SegregationOfDutiesRuleName">SegregationOfDutiesRuleName</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rule name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegregationOfDutiesRuleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rule name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#User name="User">User</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the User attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExistingRole name="ExistingRole">ExistingRole</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExistingRole attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExistingRoleIdentifier name="ExistingRoleIdentifier">ExistingRoleIdentifier</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Existing role identifier</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExistingRoleIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Existing role identifier</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExistingRoleName name="ExistingRoleName">ExistingRoleName</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Existing role name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExistingRoleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Existing role name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExistingDuty name="ExistingDuty">ExistingDuty</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExistingDuty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExistingDutyIdentifier name="ExistingDutyIdentifier">ExistingDutyIdentifier</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Existing duty identifier</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExistingDutyIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Existing duty identifier</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExistingDutyName name="ExistingDutyName">ExistingDutyName</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Existing duty name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExistingDutyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Existing duty name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewRole name="NewRole">NewRole</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewRole attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewRoleIdentifier name="NewRoleIdentifier">NewRoleIdentifier</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>New role identifier</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewRoleIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>New role identifier</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewRoleName name="NewRoleName">NewRoleName</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>New role name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewRoleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>New role name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewDuty name="NewDuty">NewDuty</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewDuty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewDutyIdentifier name="NewDutyIdentifier">NewDutyIdentifier</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>New duty identifier</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewDutyIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>New duty identifier</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewDutyName name="NewDutyName">NewDutyName</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>New duty name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewDutyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>New duty name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssignmentMode name="AssignmentMode">AssignmentMode</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignmentMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonForOverride name="ReasonForOverride">ReasonForOverride</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonForOverride attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Resolution name="Resolution">Resolution</a>

First included in: SystemAdministration/SystemSegregationOfDutiesConflictEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Resolution attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

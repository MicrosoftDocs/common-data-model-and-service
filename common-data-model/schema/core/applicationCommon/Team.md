---
title: Team - Common Data Model | Microsoft Docs
description: This describes the Team entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Team

Collection of system users that routinely collaborate. Teams can be used to simplify record sharing and provide team members with common access to organization data when team members belong to different Business Units.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Team.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /Team  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[teamId](#teamId)|Unique identifier for the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[businessUnitId](#businessUnitId)|Unique identifier of the business unit with which the team is associated.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[name](#name)|Name of the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[description](#description)|Description of the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[emailAddress](#emailAddress)|Email address for the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[createdOn](#createdOn)|Date and time when the team was created.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[modifiedOn](#modifiedOn)|Date and time when the team was last modified.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[versionNumber](#versionNumber)|Version number of the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[administratorId](#administratorId)|Unique identifier of the user primary responsible for the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[isDefault](#isDefault)|Information about whether the team is a default business unit team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[yomiName](#yomiName)|Pronunciation of the full name of the team, written in phonetic hiragana or katakana characters.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[queueId](#queueId)|Unique identifier of the default queue for the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the team with respect to the base currency.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[teamType](#teamType)|Select the team type.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[teamType_display](#teamType_display)||<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[teamTemplateId](#teamTemplateId)|Shows the team template that is associated with the team.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[regardingObjectId](#regardingObjectId)|Choose the record that the team relates to.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[systemManaged](#systemManaged)|Select whether the team will be managed by the system.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[stageId](#stageId)|Shows the ID of the stage.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|
|[processId](#processId)|Shows the ID of the process.|<a href="Team.md" target="_blank">applicationCommon/Team</a>|

### <a href=#teamId name="teamId">teamId</a>

Unique identifier for the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Team</td></tr><tr><td>description</td><td>Unique identifier for the team.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>teamid</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization </td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#businessUnitId name="businessUnitId">businessUnitId</a>

Unique identifier of the business unit with which the team is associated.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit with which the team is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>businessunitid</td></tr></table>

### <a href=#name name="name">name</a>

Name of the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Team Name</td></tr><tr><td>description</td><td>Name of the team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#description name="description">description</a>

Description of the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

Email address for the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email</td></tr><tr><td>description</td><td>Email address for the team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the team was created.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the team was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the team was last modified.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the team was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version number</td></tr><tr><td>description</td><td>Version number of the team.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#administratorId name="administratorId">administratorId</a>

Unique identifier of the user primary responsible for the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Administrator</td></tr><tr><td>description</td><td>Unique identifier of the user primary responsible for the team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>administratorid</td></tr></table>

### <a href=#isDefault name="isDefault">isDefault</a>

Information about whether the team is a default business unit team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Default</td></tr><tr><td>description</td><td>Information about whether the team is a default business unit team.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isdefault</td></tr></table>

### <a href=#yomiName name="yomiName">yomiName</a>

Pronunciation of the full name of the team, written in phonetic hiragana or katakana characters.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Name</td></tr><tr><td>description</td><td>Pronunciation of the full name of the team, written in phonetic hiragana or katakana characters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yominame</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#queueId name="queueId">queueId</a>

Unique identifier of the default queue for the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Queue</td></tr><tr><td>description</td><td>Unique identifier of the default queue for the team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>queueid</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the team with respect to the base currency.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the team with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#teamType name="teamType">teamType</a>

Select the team type.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Team Type</td></tr><tr><td>description</td><td>Select the team type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>teamtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Owner</td><td>0</td></tr><tr><td>en</td><td>Access</td><td>1</td></tr></table></td></tr></table>

### <a href=#teamType_display name="teamType_display">teamType_display</a>

First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#teamTemplateId name="teamTemplateId">teamTemplateId</a>

Shows the team template that is associated with the team.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Team Template Identifier</td></tr><tr><td>description</td><td>Shows the team template that is associated with the team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>teamtemplateid</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Choose the record that the team relates to.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding Object Id</td></tr><tr><td>description</td><td>Choose the record that the team relates to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#systemManaged name="systemManaged">systemManaged</a>

Select whether the team will be managed by the system.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is System Managed</td></tr><tr><td>description</td><td>Select whether the team will be managed by the system.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>systemmanaged</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Shows the ID of the stage.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Shows the ID of the stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#processId name="processId">processId</a>

Shows the ID of the process.  
First included in: applicationCommon/Team (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Shows the ID of the process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

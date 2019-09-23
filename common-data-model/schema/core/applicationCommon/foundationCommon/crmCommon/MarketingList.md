---
title: MarketingList - Common Data Model | Microsoft Docs
description: Group of existing or potential customers created for a marketing campaign or other sales purposes.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Marketing List

Group of existing or potential customers created for a marketing campaign or other sales purposes.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/MarketingList.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/MarketingList  
- [/foundationCommon/crmCommon/solutions/marketing/MarketingList](solutions/marketing/MarketingList.md "/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/MarketingList.cdm.json/MarketingList")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[ownerId](#ownerId)|Owner Id|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[listId](#listId)|Unique identifier of the marketing list.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[listName](#listName)|Type a name for the marketing list so that it is identified correctly in lists.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[cost](#cost)|Type the cost of obtaining the marketing list.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[costBase](#costBase)|Value of the Cost in base currency.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[createdFromCode](#createdFromCode)|Select the type of members that this marketing list will contain: accounts, contacts, or leads. Each list can have only one member type and this value can't be changed after the marketing list is created.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[createdFromCode_display](#createdFromCode_display)||<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[description](#description)|Type additional information to describe the marketing list, such as the intended use or date of the last update.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[doNotSendOnOptOut](#doNotSendOnOptOut)|Select whether to override the opt-out settings on leads, contacts, and accounts for the members of the target marketing lists of the campaign activity. If No is selected, those who have chosen to opt out won't be excluded from the list. This means they will receive marketing materials.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[ignoreInactiveListMembers](#ignoreInactiveListMembers)|Select whether inactive accounts, contacts, or leads should be excluded from the campaign activity distribution when the marketing list is included in a campaign.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[lastUsedOn](#lastUsedOn)|Shows the date and time when the marketing list was last used in a campaign or in the creation of activities or opportunities.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[lockStatus](#lockStatus)|Select whether the marketing list is locked. If Yes is selected, no additional members can be added to the marketing list.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[memberCount](#memberCount)|Shows the sum of all members in the marketing list.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[memberType](#memberType)|Type of the members that can be stored in the marketing list.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[purpose](#purpose)|Type the intended use of the marketing list to identify its key segments, target offers, or business group.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[query](#query)|Query used for retrieving members of marketing list.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[source](#source)|Type the source of the marketing list, such as a third-party supplier or internal database.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[stateCode](#stateCode)|Shows whether the marketing list is active or inactive. Inactive marketing lists are read-only and can't be edited unless they are reactivated.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[stateCode_display](#stateCode_display)||<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[statusCode](#statusCode)|Select the marketing list's status.|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[statusCode_display](#statusCode_display)||<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|
|[type](#type)|Select whether you want the marketing list to be static or dynamic. The members in a static marketing list are unchanging. A dynamic marketing list is based on a dynamic query that retrieves the updated list of members|<a href="MarketingList.md" target="_blank">crmCommon/MarketingList</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#listId name="listId">listId</a>

Unique identifier of the marketing list.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>List</td></tr><tr><td>description</td><td>Unique identifier of the marketing list.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>listid</td></tr></table>

### <a href=#listName name="listName">listName</a>

Type a name for the marketing list so that it is identified correctly in lists.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a name for the marketing list so that it is identified correctly in lists.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>sourceName</td><td>listname</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#cost name="cost">cost</a>

Type the cost of obtaining the marketing list.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost</td></tr><tr><td>description</td><td>Type the cost of obtaining the marketing list.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>cost</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#costBase name="costBase">costBase</a>

Value of the Cost in base currency.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost (Base)</td></tr><tr><td>description</td><td>Value of the Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>cost_base</td></tr></table>

### <a href=#createdFromCode name="createdFromCode">createdFromCode</a>

Select the type of members that this marketing list will contain: accounts, contacts, or leads. Each list can have only one member type and this value can't be changed after the marketing list is created.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing List Member Type</td></tr><tr><td>description</td><td>Select the type of members that this marketing list will contain: accounts, contacts, or leads. Each list can have only one member type and this value can't be changed after the marketing list is created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>createdfromcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>1</td></tr><tr><td>en</td><td>Contact</td><td>2</td></tr><tr><td>en</td><td>Lead</td><td>4</td></tr></table></td></tr></table>

### <a href=#createdFromCode_display name="createdFromCode_display">createdFromCode_display</a>

First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the marketing list, such as the intended use or date of the last update.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the marketing list, such as the intended use or date of the last update.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#doNotSendOnOptOut name="doNotSendOnOptOut">doNotSendOnOptOut</a>

Select whether to override the opt-out settings on leads, contacts, and accounts for the members of the target marketing lists of the campaign activity. If No is selected, those who have chosen to opt out won't be excluded from the list. This means they will receive marketing materials.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exclude Members Who Opt Out</td></tr><tr><td>description</td><td>Select whether to override the opt-out settings on leads, contacts, and accounts for the members of the target marketing lists of the campaign activity. If No is selected, those who have chosen to opt out won't be excluded from the list. This means they will receive marketing materials.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotsendonoptout</td></tr></table>

### <a href=#ignoreInactiveListMembers name="ignoreInactiveListMembers">ignoreInactiveListMembers</a>

Select whether inactive accounts, contacts, or leads should be excluded from the campaign activity distribution when the marketing list is included in a campaign.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ignore Inactive List Members</td></tr><tr><td>description</td><td>Select whether inactive accounts, contacts, or leads should be excluded from the campaign activity distribution when the marketing list is included in a campaign.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ignoreinactivelistmembers</td></tr></table>

### <a href=#lastUsedOn name="lastUsedOn">lastUsedOn</a>

Shows the date and time when the marketing list was last used in a campaign or in the creation of activities or opportunities.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Used On</td></tr><tr><td>description</td><td>Shows the date and time when the marketing list was last used in a campaign or in the creation of activities or opportunities.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastusedon</td></tr></table>

### <a href=#lockStatus name="lockStatus">lockStatus</a>

Select whether the marketing list is locked. If Yes is selected, no additional members can be added to the marketing list.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Locked</td></tr><tr><td>description</td><td>Select whether the marketing list is locked. If Yes is selected, no additional members can be added to the marketing list.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lockstatus</td></tr></table>

### <a href=#memberCount name="memberCount">memberCount</a>

Shows the sum of all members in the marketing list.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Members Count</td></tr><tr><td>description</td><td>Shows the sum of all members in the marketing list.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>membercount</td></tr></table>

### <a href=#memberType name="memberType">memberType</a>

Type of the members that can be stored in the marketing list.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Member Type</td></tr><tr><td>description</td><td>Type of the members that can be stored in the marketing list.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>membertype</td></tr></table>

### <a href=#purpose name="purpose">purpose</a>

Type the intended use of the marketing list to identify its key segments, target offers, or business group.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purpose</td></tr><tr><td>description</td><td>Type the intended use of the marketing list to identify its key segments, target offers, or business group.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>512</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>purpose</td></tr></table>

### <a href=#query name="query">query</a>

Query used for retrieving members of marketing list.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Query</td></tr><tr><td>description</td><td>Query used for retrieving members of marketing list.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>query</td></tr></table>

### <a href=#source name="source">source</a>

Type the source of the marketing list, such as a third-party supplier or internal database.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source</td></tr><tr><td>description</td><td>Type the source of the marketing list, such as a third-party supplier or internal database.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>source</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the marketing list is active or inactive. Inactive marketing lists are read-only and can't be edited unless they are reactivated.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the marketing list is active or inactive. Inactive marketing lists are read-only and can't be edited unless they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the marketing list's status.  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the marketing list's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#type name="type">type</a>

Select whether you want the marketing list to be static or dynamic. The members in a static marketing list are unchanging. A dynamic marketing list is based on a dynamic query that retrieves the updated list of members  
First included in: crmCommon/MarketingList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Select whether you want the marketing list to be static or dynamic. The members in a static marketing list are unchanging. A dynamic marketing list is based on a dynamic query that retrieves the updated list of members</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>type</td></tr></table>

---
title: Pass - Common Data Model | Microsoft Docs
description: Information about passes.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Pass

Information about passes.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/Pass.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/Pass  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[passId](#passId)|Unique identifier for entity instances|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[stateCode](#stateCode)|Status of the Pass|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[stateCode_display](#stateCode_display)||<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[statusCode](#statusCode)|Reason for the status of the Pass|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[statusCode_display](#statusCode_display)||<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[name](#name)|The name of the custom entity.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[costPerUnit](#costPerUnit)||<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[costPerUnitBase](#costPerUnitBase)|Value of the Cost per unit in base currency.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[eventId](#eventId)|Unique identifier for Event associated with Pass.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[noOfPassesAllocated](#noOfPassesAllocated)|Number of passes allocated.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[noOfPassesSold](#noOfPassesSold)|Number of passes sold.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[passPrice](#passPrice)||<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[passPriceBase](#passPriceBase)|Value of the Pass Price in base currency.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[track](#track)|All Active  records|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[noOfPassesLeft](#noOfPassesLeft)|Number of passes left.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[totalCost](#totalCost)||<a href="Pass.md" target="_blank">eventManagement/Pass</a>|
|[totalcostBase](#totalcostBase)|Value of the Total cost in base currency.|<a href="Pass.md" target="_blank">eventManagement/Pass</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#passId name="passId">passId</a>

Unique identifier for entity instances  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pass</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_passid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Pass  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Pass</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Pass  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Pass</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

### <a href=#costPerUnit name="costPerUnit">costPerUnit</a>

First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost per unit</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_costperunit</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#costPerUnitBase name="costPerUnitBase">costPerUnitBase</a>

Value of the Cost per unit in base currency.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost per unit (Base)</td></tr><tr><td>description</td><td>Value of the Cost per unit in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_costperunit_base</td></tr></table>

### <a href=#eventId name="eventId">eventId</a>

Unique identifier for Event associated with Pass.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event</td></tr><tr><td>description</td><td>Unique identifier for Event associated with Pass.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventid</td></tr></table>

### <a href=#noOfPassesAllocated name="noOfPassesAllocated">noOfPassesAllocated</a>

Number of passes allocated.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>No of passes allocated</td></tr><tr><td>description</td><td>Number of passes allocated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_noofpassesallocated</td></tr></table>

### <a href=#noOfPassesSold name="noOfPassesSold">noOfPassesSold</a>

Number of passes sold.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>No of passes sold</td></tr><tr><td>description</td><td>Number of passes sold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_noofpassessold</td></tr></table>

### <a href=#passPrice name="passPrice">passPrice</a>

First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pass Price</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_passprice</td></tr></table>

### <a href=#passPriceBase name="passPriceBase">passPriceBase</a>

Value of the Pass Price in base currency.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pass Price (Base)</td></tr><tr><td>description</td><td>Value of the Pass Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_passprice_base</td></tr></table>

### <a href=#track name="track">track</a>

All Active  records  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Track</td></tr><tr><td>description</td><td>All Active  records</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_track</td></tr></table>

### <a href=#noOfPassesLeft name="noOfPassesLeft">noOfPassesLeft</a>

Number of passes left.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>No of passes left</td></tr><tr><td>description</td><td>Number of passes left.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_noofpassesleft</td></tr></table>

### <a href=#totalCost name="totalCost">totalCost</a>

First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total cost</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalcost</td></tr></table>

### <a href=#totalcostBase name="totalcostBase">totalcostBase</a>

Value of the Total cost in base currency.  
First included in: eventManagement/Pass (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total cost (Base)</td></tr><tr><td>description</td><td>Value of the Total cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalcost_base</td></tr></table>

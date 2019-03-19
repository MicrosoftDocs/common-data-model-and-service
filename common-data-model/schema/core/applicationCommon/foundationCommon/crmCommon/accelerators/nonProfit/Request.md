---
title: Request - Common Data Model | Microsoft Docs
description: This describes the Request entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Request

Represents a request from an individual or institution for funding or support. A request is more formal than an inquiry (LOI) and typically happens after an inquiry has already occurred.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Request.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/Request  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[requestId](#requestId)|Unique identifier for entity instances|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[stateCode](#stateCode)|Status of the Request|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[stateCode_display](#stateCode_display)||<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[statusCode](#statusCode)|Reason for the status of the Request|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[statusCode_display](#statusCode_display)||<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[name](#name)|The name of the custom entity.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[amountProjected](#amountProjected)|Projected amount to be received from awarding entity (as contrasted to amount requested and amount received).|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[amountprojectedBase](#amountprojectedBase)|Value of the Amount Projected in base currency.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[amountRecommended](#amountRecommended)|Recommended Award amount.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[amountrecommendedBase](#amountrecommendedBase)|Value of the Amount Recommended in base currency.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[amountRequested](#amountRequested)|Amount requested in proposal (as contrasted to amount expected and amount received).|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[amountrequestedBase](#amountrequestedBase)|Value of the Amount Requested in base currency.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[applicationID](#applicationID)|Internal ID for the Application.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[conflictofInterestDetail](#conflictofInterestDetail)|Description of a conflict of interest, if any.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[conflictofInterestStatus](#conflictofInterestStatus)|Indicates the type of conflict of interest, if any.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[conflictofInterestStatus_display](#conflictofInterestStatus_display)||<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[docketId](#docketId)|Docket|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[fiscalSponsorId](#fiscalSponsorId)|Fiscal Sponsor|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[initialApplicationChannel](#initialApplicationChannel)|Method by which the initial application was received.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[initialApplicationChannel_display](#initialApplicationChannel_display)||<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[leadId](#leadId)|Lead|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[purpose](#purpose)|Summary of the purpose of the Request proposal that is one-paragraph. Include what, where, when, and why.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[recipientId](#recipientId)||<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[renewalofAwardId](#renewalofAwardId)|Renewal Of Request|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[requestedDuration](#requestedDuration)|Requested duration of the Award in months|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[requestedStartDate](#requestedStartDate)|Date that funding is requested to begin|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[requestType](#requestType)|Type or Designation of Request|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[requestType_display](#requestType_display)||<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[requirements](#requirements)|Link to Request requirements|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[stage](#stage)|The stage the Request is currently in.|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[stage_display](#stage_display)||<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[submittedById](#submittedById)|Submitted By|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[submittedDate](#submittedDate)|Date the Request was received by the awarding organization|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[totalProjectBudget](#totalProjectBudget)|Total Project Budget, which may be in excess of a requested or awarded amount|<a href="Request.md" target="_blank">nonProfit/Request</a>|
|[totalprojectbudgetBase](#totalprojectbudgetBase)|Value of the Total Project Budget in base currency.|<a href="Request.md" target="_blank">nonProfit/Request</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#requestId name="requestId">requestId</a>

Unique identifier for entity instances  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Request</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_requestid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Request  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Request</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Request  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Request</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#amountProjected name="amountProjected">amountProjected</a>

Projected amount to be received from awarding entity (as contrasted to amount requested and amount received).  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Projected</td></tr><tr><td>description</td><td>Projected amount to be received from awarding entity (as contrasted to amount requested and amount received).</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountprojected</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountprojectedBase name="amountprojectedBase">amountprojectedBase</a>

Value of the Amount Projected in base currency.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Projected (Base)</td></tr><tr><td>description</td><td>Value of the Amount Projected in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountprojected_base</td></tr></table>

### <a href=#amountRecommended name="amountRecommended">amountRecommended</a>

Recommended Award amount.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Recommended</td></tr><tr><td>description</td><td>Recommended Award amount.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountrecommended</td></tr></table>

### <a href=#amountrecommendedBase name="amountrecommendedBase">amountrecommendedBase</a>

Value of the Amount Recommended in base currency.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Recommended (Base)</td></tr><tr><td>description</td><td>Value of the Amount Recommended in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountrecommended_base</td></tr></table>

### <a href=#amountRequested name="amountRequested">amountRequested</a>

Amount requested in proposal (as contrasted to amount expected and amount received).  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Requested</td></tr><tr><td>description</td><td>Amount requested in proposal (as contrasted to amount expected and amount received).</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountrequested</td></tr></table>

### <a href=#amountrequestedBase name="amountrequestedBase">amountrequestedBase</a>

Value of the Amount Requested in base currency.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Requested (Base)</td></tr><tr><td>description</td><td>Value of the Amount Requested in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountrequested_base</td></tr></table>

### <a href=#applicationID name="applicationID">applicationID</a>

Internal ID for the Application.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Application ID</td></tr><tr><td>description</td><td>Internal ID for the Application.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>15</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_applicationid</td></tr></table>

### <a href=#conflictofInterestDetail name="conflictofInterestDetail">conflictofInterestDetail</a>

Description of a conflict of interest, if any.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Conflict of Interest Detail</td></tr><tr><td>description</td><td>Description of a conflict of interest, if any.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_conflictofinterestdetail</td></tr></table>

### <a href=#conflictofInterestStatus name="conflictofInterestStatus">conflictofInterestStatus</a>

Indicates the type of conflict of interest, if any.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Conflict of Interest Status</td></tr><tr><td>description</td><td>Indicates the type of conflict of interest, if any.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_conflictofintereststatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Board Member</td><td>844060000</td></tr></table></td></tr></table>

### <a href=#conflictofInterestStatus_display name="conflictofInterestStatus_display">conflictofInterestStatus_display</a>

First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#docketId name="docketId">docketId</a>

Docket  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Docket</td></tr><tr><td>description</td><td>Docket</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_docketid</td></tr></table>

### <a href=#fiscalSponsorId name="fiscalSponsorId">fiscalSponsorId</a>

Fiscal Sponsor  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Sponsor</td></tr><tr><td>description</td><td>Fiscal Sponsor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_fiscalsponsorid</td></tr></table>

### <a href=#initialApplicationChannel name="initialApplicationChannel">initialApplicationChannel</a>

Method by which the initial application was received.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Initial Application Channel</td></tr><tr><td>description</td><td>Method by which the initial application was received.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_initialapplicationchannel</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>CommChannel</td><td>844060000</td></tr></table></td></tr></table>

### <a href=#initialApplicationChannel_display name="initialApplicationChannel_display">initialApplicationChannel_display</a>

First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#leadId name="leadId">leadId</a>

Lead  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead</td></tr><tr><td>description</td><td>Lead</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_leadid</td></tr></table>

### <a href=#purpose name="purpose">purpose</a>

Summary of the purpose of the Request proposal that is one-paragraph. Include what, where, when, and why.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purpose</td></tr><tr><td>description</td><td>Summary of the purpose of the Request proposal that is one-paragraph. Include what, where, when, and why.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_purpose</td></tr></table>

### <a href=#recipientId name="recipientId">recipientId</a>

First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_recipientid</td></tr></table>

### <a href=#renewalofAwardId name="renewalofAwardId">renewalofAwardId</a>

Renewal Of Request  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Renewal of Award</td></tr><tr><td>description</td><td>Renewal Of Request</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_renewalofawardid</td></tr></table>

### <a href=#requestedDuration name="requestedDuration">requestedDuration</a>

Requested duration of the Award in months  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requested Duration</td></tr><tr><td>description</td><td>Requested duration of the Award in months</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_requestedduration</td></tr></table>

### <a href=#requestedStartDate name="requestedStartDate">requestedStartDate</a>

Date that funding is requested to begin  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requested Start Date</td></tr><tr><td>description</td><td>Date that funding is requested to begin</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_requestedstartdate</td></tr></table>

### <a href=#requestType name="requestType">requestType</a>

Type or Designation of Request  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Request Type</td></tr><tr><td>description</td><td>Type or Designation of Request</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_requesttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>General</td><td>844060000</td></tr><tr><td>en</td><td>Project Support</td><td>844060001</td></tr></table></td></tr></table>

### <a href=#requestType_display name="requestType_display">requestType_display</a>

First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#requirements name="requirements">requirements</a>

Link to Request requirements  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirements</td></tr><tr><td>description</td><td>Link to Request requirements</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>512</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_requirements</td></tr></table>

### <a href=#stage name="stage">stage</a>

The stage the Request is currently in.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage</td></tr><tr><td>description</td><td>The stage the Request is currently in.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_stage</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Application Started</td><td>844060000</td></tr><tr><td>en</td><td>In Progress</td><td>844060001</td></tr><tr><td>en</td><td>Qualification</td><td>844060002</td></tr><tr><td>en</td><td>Prospecting</td><td>844060003</td></tr><tr><td>en</td><td>Submitted</td><td>844060004</td></tr><tr><td>en</td><td>Under Internal Review</td><td>844060005</td></tr><tr><td>en</td><td>Under Grant Committee Review</td><td>844060006</td></tr><tr><td>en</td><td>Notify Applicant of Decision</td><td>844060007</td></tr><tr><td>en</td><td>Awarded</td><td>844060008</td></tr><tr><td>en</td><td>Declined</td><td>844060009</td></tr><tr><td>en</td><td>Closed</td><td>844060010</td></tr><tr><td>en</td><td>Withdrawn</td><td>844060011</td></tr><tr><td>en</td><td>Proposal Re-Opened</td><td>844060012</td></tr></table></td></tr></table>

### <a href=#stage_display name="stage_display">stage_display</a>

First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#submittedById name="submittedById">submittedById</a>

Submitted By  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Submitted By</td></tr><tr><td>description</td><td>Submitted By</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_submittedbyid</td></tr></table>

### <a href=#submittedDate name="submittedDate">submittedDate</a>

Date the Request was received by the awarding organization  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Submitted Date</td></tr><tr><td>description</td><td>Date the Request was received by the awarding organization</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_submitteddate</td></tr></table>

### <a href=#totalProjectBudget name="totalProjectBudget">totalProjectBudget</a>

Total Project Budget, which may be in excess of a requested or awarded amount  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Project Budget</td></tr><tr><td>description</td><td>Total Project Budget, which may be in excess of a requested or awarded amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalprojectbudget</td></tr></table>

### <a href=#totalprojectbudgetBase name="totalprojectbudgetBase">totalprojectbudgetBase</a>

Value of the Total Project Budget in base currency.  
First included in: nonProfit/Request (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Project Budget (Base)</td></tr><tr><td>description</td><td>Value of the Total Project Budget in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalprojectbudget_base</td></tr></table>

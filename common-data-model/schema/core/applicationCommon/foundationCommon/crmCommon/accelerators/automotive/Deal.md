---
title: Deal - Common Data Model | Microsoft Docs
description: This describes the Deal entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Deal

Business proposal for the sale of one or more vehicle or device, including optional trade-ins, add-ons and financial terms.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/Deal.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/Deal  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[actualCost](#actualCost)|Cost of the deal.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[actualCostBase](#actualCostBase)|Value of the actual cost in base currency.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[actualRevenue](#actualRevenue)|Revenue gained from the deal.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[actualrevenue_Base](#actualrevenue_Base)|Value of the actual revenue in base currency.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[businessOperationId](#businessOperationId)|Department/team at dealership responsible for the deal.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[commissionAmount](#commissionAmount)|The amount of commission paid out for this deal.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[commissionAmountBase](#commissionAmountBase)|Value of the commission amount in base currency.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[dealFileId](#dealFileId)|The file location of this deal.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[dealId](#dealId)|Unique identifier for entity instances|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[dealNumber](#dealNumber)|Unique number of the deal.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[dealStatus](#dealStatus)|Status of the deal (scenario, offer or deal).|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[dealStatus_display](#dealStatus_display)||<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[description](#description)|Description of the deal.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[estimatedCost](#estimatedCost)|What the deal is expected to cost.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[estimatedCostBase](#estimatedCostBase)|Value of the estimated cost in base currency.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[estimatedRevenue](#estimatedRevenue)|How much revenue the deal is expected to make.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[estimatedRevenueBase](#estimatedRevenueBase)|Value of the estimated revenue in base currency.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[name](#name)|Name of the deal.|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[stateCode](#stateCode)|Status of the Deal|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[stateCode_display](#stateCode_display)||<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[statusCode](#statusCode)|Reason for the status of the Deal|<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[statusCode_display](#statusCode_display)||<a href="Deal.md" target="_blank">automotive/Deal</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Deal.md" target="_blank">automotive/Deal</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#actualCost name="actualCost">actualCost</a>

Cost of the deal.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Cost</td></tr><tr><td>description</td><td>Cost of the deal.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_actualcost</td></tr></table>

### <a href=#actualCostBase name="actualCostBase">actualCostBase</a>

Value of the actual cost in base currency.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Cost (Base)</td></tr><tr><td>description</td><td>Value of the actual cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_actualcost_base</td></tr></table>

### <a href=#actualRevenue name="actualRevenue">actualRevenue</a>

Revenue gained from the deal.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Revenue</td></tr><tr><td>description</td><td>Revenue gained from the deal.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_actualrevenue</td></tr></table>

### <a href=#actualrevenue_Base name="actualrevenue_Base">actualrevenue_Base</a>

Value of the actual revenue in base currency.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Revenue (Base)</td></tr><tr><td>description</td><td>Value of the actual revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_actualrevenue_base</td></tr></table>

### <a href=#businessOperationId name="businessOperationId">businessOperationId</a>

Department/team at dealership responsible for the deal.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Operation</td></tr><tr><td>description</td><td>Department/team at dealership responsible for the deal.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_businessoperationid</td></tr></table>

### <a href=#commissionAmount name="commissionAmount">commissionAmount</a>

The amount of commission paid out for this deal.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commission Amount</td></tr><tr><td>description</td><td>The amount of commission paid out for this deal.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_commissionamount</td></tr></table>

### <a href=#commissionAmountBase name="commissionAmountBase">commissionAmountBase</a>

Value of the commission amount in base currency.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commission Amount (Base)</td></tr><tr><td>description</td><td>Value of the commission amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_commissionamount_base</td></tr></table>

### <a href=#dealFileId name="dealFileId">dealFileId</a>

The file location of this deal.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deal File</td></tr><tr><td>description</td><td>The file location of this deal.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_dealfileid</td></tr></table>

### <a href=#dealId name="dealId">dealId</a>

Unique identifier for entity instances  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deal</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_dealid</td></tr></table>

### <a href=#dealNumber name="dealNumber">dealNumber</a>

Unique number of the deal.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deal Number</td></tr><tr><td>description</td><td>Unique number of the deal.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_dealnumber</td></tr></table>

### <a href=#dealStatus name="dealStatus">dealStatus</a>

Status of the deal (scenario, offer or deal).  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deal Status</td></tr><tr><td>description</td><td>Status of the deal (scenario, offer or deal).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_dealstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#dealStatus_display name="dealStatus_display">dealStatus_display</a>

First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Description of the deal.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the deal.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_description</td></tr></table>

### <a href=#estimatedCost name="estimatedCost">estimatedCost</a>

What the deal is expected to cost.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Cost</td></tr><tr><td>description</td><td>What the deal is expected to cost.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_estimatedcost</td></tr></table>

### <a href=#estimatedCostBase name="estimatedCostBase">estimatedCostBase</a>

Value of the estimated cost in base currency.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Cost (Base)</td></tr><tr><td>description</td><td>Value of the estimated cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_estimatedcost_base</td></tr></table>

### <a href=#estimatedRevenue name="estimatedRevenue">estimatedRevenue</a>

How much revenue the deal is expected to make.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Revenue</td></tr><tr><td>description</td><td>How much revenue the deal is expected to make.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_estimatedrevenue</td></tr></table>

### <a href=#estimatedRevenueBase name="estimatedRevenueBase">estimatedRevenueBase</a>

Value of the estimated revenue in base currency.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Revenue (Base)</td></tr><tr><td>description</td><td>Value of the estimated revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_estimatedrevenue_base</td></tr></table>

### <a href=#name name="name">name</a>

Name of the deal.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the deal.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Deal  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Deal</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Deal  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Deal</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>972230000</td><td>0</td></tr><tr><td>en</td><td>Signed</td><td>972230001</td><td>0</td></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Expired</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>972230002</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: automotive/Deal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

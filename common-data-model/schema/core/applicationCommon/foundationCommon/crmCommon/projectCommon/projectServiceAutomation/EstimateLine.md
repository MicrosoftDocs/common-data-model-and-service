---
title: EstimateLine - Common Data Model | Microsoft Docs
description: Estimates on a per day timescale.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Estimate Line

Estimates on a per day timescale.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/EstimateLine.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/EstimateLine  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[ownerId](#ownerId)|Owner Id|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[estimateLineId](#estimateLineId)|Shows the entity instances.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[stateCode](#stateCode)|Status of the Estimate Line|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[stateCode_display](#stateCode_display)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[statusCode](#statusCode)|Reason for the status of the Estimate Line|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[statusCode_display](#statusCode_display)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[description](#description)|Type the name of the custom entity.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[accountCustomer](#accountCustomer)|Shows the customer for the estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[accountingDate](#accountingDate)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[accountVendor](#accountVendor)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[amount](#amount)|Shows the amount on the estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[amountMethod](#amountMethod)|Shows the calculation method used to determine the amount on the estimate line. |<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[amountMethod_display](#amountMethod_display)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[basisAmount](#basisAmount)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[basisAmountBase](#basisAmountBase)|Value of the Basis Amount in base currency.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[basisPrice](#basisPrice)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[basisPriceBase](#basisPriceBase)|Value of the Basis Price in base currency.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[basisQuantity](#basisQuantity)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[billingType](#billingType)|Shows whether this estimate line is charged to the customer. |<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[billingType_display](#billingType_display)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[bookableResource](#bookableResource)|Shows the bookable resource for which estimates are generated.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[contactCustomer](#contactCustomer)|Shows the name of the customer contact.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[contactVendor](#contactVendor)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[customerType](#customerType)|Select the type of customer.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[customerType_display](#customerType_display)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[documentDate](#documentDate)|Shows the transaction date of the estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[endDateTime](#endDateTime)|Enter the end date and time.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[estimate](#estimate)|Shows the name of the estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[estimatePerDayLines](#estimatePerDayLines)|Stores the estimate per day detail lines.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[exchangeRateDate](#exchangeRateDate)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[numberOfResources](#numberOfResources)|Shows the estimate of the number of resources intended to be staffed for this task.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[percent](#percent)|Shows the percent for the estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[price](#price)|Shows the price for this estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[priceBase](#priceBase)|Value of the Price in base currency.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[priceList](#priceList)|Shows the price list used in this estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[product](#product)|Select the product.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[project](#project)|Shows the project for this estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[quantity](#quantity)|Enter the estimated quantity of work, cost, and sales.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[resourceCategory](#resourceCategory)|Shows the role of this resource on the estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[resourceOrganizationalUnitId](#resourceOrganizationalUnitId)|Select the organizational unit at the time the estimate line was registered of the resource who should perform the work.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[startDateTime](#startDateTime)|Shows the start date and time for the task for this estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[task](#task)|Shows the task related to this estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[transactionCategory](#transactionCategory)|Select the type of transaction.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[transactionClassification](#transactionClassification)|Shows the transaction classification for this estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[transactionClassification_display](#transactionClassification_display)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[transactionTypeCode](#transactionTypeCode)|Shows the transaction type for this estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[transactionTypeCode_display](#transactionTypeCode_display)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[unit](#unit)|Shows the unit of measurement for this estimate line.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[unitSchedule](#unitSchedule)|Select the unit of measure for the estimate quantity.|<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[vendorType](#vendorType)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|
|[vendorType_display](#vendorType_display)||<a href="EstimateLine.md" target="_blank">projectServiceAutomation/EstimateLine</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#estimateLineId name="estimateLineId">estimateLineId</a>

Shows the entity instances.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimate Line</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_estimatelineid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Estimate Line  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Estimate Line</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Estimate Line  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Estimate Line</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>450</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#accountCustomer name="accountCustomer">accountCustomer</a>

Shows the customer for the estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>Shows the customer for the estimate line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountcustomer</td></tr></table>

### <a href=#accountingDate name="accountingDate">accountingDate</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accounting Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountingdate</td></tr></table>

### <a href=#accountVendor name="accountVendor">accountVendor</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountvendor</td></tr></table>

### <a href=#amount name="amount">amount</a>

Shows the amount on the estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>Shows the amount on the estimate line.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_base</td></tr></table>

### <a href=#amountMethod name="amountMethod">amountMethod</a>

Shows the calculation method used to determine the amount on the estimate line.   
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Method</td></tr><tr><td>description</td><td>Shows the calculation method used to determine the amount on the estimate line. </td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amountmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Multiply Quantity By Price</td><td>192350000</td></tr><tr><td>en</td><td>Fixed Price</td><td>192350001</td></tr><tr><td>en</td><td>Multiply Basis Quantity By Price</td><td>192350002</td></tr><tr><td>en</td><td>Multiply Basis Amount By Percent</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#amountMethod_display name="amountMethod_display">amountMethod_display</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#basisAmount name="basisAmount">basisAmount</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisamount</td></tr></table>

### <a href=#basisAmountBase name="basisAmountBase">basisAmountBase</a>

Value of the Basis Amount in base currency.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Amount (Base)</td></tr><tr><td>description</td><td>Value of the Basis Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisamount_base</td></tr></table>

### <a href=#basisPrice name="basisPrice">basisPrice</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Price</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisprice</td></tr></table>

### <a href=#basisPriceBase name="basisPriceBase">basisPriceBase</a>

Value of the Basis Price in base currency.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Price (Base)</td></tr><tr><td>description</td><td>Value of the Basis Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisprice_base</td></tr></table>

### <a href=#basisQuantity name="basisQuantity">basisQuantity</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisquantity</td></tr></table>

### <a href=#billingType name="billingType">billingType</a>

Shows whether this estimate line is charged to the customer.   
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Type</td></tr><tr><td>description</td><td>Shows whether this estimate line is charged to the customer. </td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Non Chargeable</td><td>192350000</td></tr><tr><td>en</td><td>Chargeable</td><td>192350001</td></tr><tr><td>en</td><td>Complimentary</td><td>192350002</td></tr><tr><td>en</td><td>Not Available</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#billingType_display name="billingType_display">billingType_display</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

Shows the bookable resource for which estimates are generated.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource</td></tr><tr><td>description</td><td>Shows the bookable resource for which estimates are generated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#contactCustomer name="contactCustomer">contactCustomer</a>

Shows the name of the customer contact.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>Shows the name of the customer contact.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contactcustomer</td></tr></table>

### <a href=#contactVendor name="contactVendor">contactVendor</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contactvendor</td></tr></table>

### <a href=#customerType name="customerType">customerType</a>

Select the type of customer.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>Select the type of customer.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#customerType_display name="customerType_display">customerType_display</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#documentDate name="documentDate">documentDate</a>

Shows the transaction date of the estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document Date</td></tr><tr><td>description</td><td>Shows the transaction date of the estimate line.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_documentdate</td></tr></table>

### <a href=#endDateTime name="endDateTime">endDateTime</a>

Enter the end date and time.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date/Time</td></tr><tr><td>description</td><td>Enter the end date and time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_enddatetime</td></tr></table>

### <a href=#estimate name="estimate">estimate</a>

Shows the name of the estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimate</td></tr><tr><td>description</td><td>Shows the name of the estimate line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estimate</td></tr></table>

### <a href=#estimatePerDayLines name="estimatePerDayLines">estimatePerDayLines</a>

Stores the estimate per day detail lines.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimate Per Day Lines</td></tr><tr><td>description</td><td>Stores the estimate per day detail lines.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estimateperdaylines</td></tr></table>

### <a href=#exchangeRateDate name="exchangeRateDate">exchangeRateDate</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_exchangeratedate</td></tr></table>

### <a href=#numberOfResources name="numberOfResources">numberOfResources</a>

Shows the estimate of the number of resources intended to be staffed for this task.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of resources</td></tr><tr><td>description</td><td>Shows the estimate of the number of resources intended to be staffed for this task.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_numberofresources</td></tr></table>

### <a href=#percent name="percent">percent</a>

Shows the percent for the estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percent</td></tr><tr><td>description</td><td>Shows the percent for the estimate line.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_percent</td></tr></table>

### <a href=#price name="price">price</a>

Shows the price for this estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price</td></tr><tr><td>description</td><td>Shows the price for this estimate line.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price</td></tr></table>

### <a href=#priceBase name="priceBase">priceBase</a>

Value of the Price in base currency.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price (Base)</td></tr><tr><td>description</td><td>Value of the Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price_base</td></tr></table>

### <a href=#priceList name="priceList">priceList</a>

Shows the price list used in this estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Shows the price list used in this estimate line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pricelist</td></tr></table>

### <a href=#product name="product">product</a>

Select the product.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>Select the product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_product</td></tr></table>

### <a href=#project name="project">project</a>

Shows the project for this estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Shows the project for this estimate line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Enter the estimated quantity of work, cost, and sales.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Enter the estimated quantity of work, cost, and sales.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quantity</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Shows the role of this resource on the estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>description</td><td>Shows the role of this resource on the estimate line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#resourceOrganizationalUnitId name="resourceOrganizationalUnitId">resourceOrganizationalUnitId</a>

Select the organizational unit at the time the estimate line was registered of the resource who should perform the work.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resourcing Unit</td></tr><tr><td>description</td><td>Select the organizational unit at the time the estimate line was registered of the resource who should perform the work.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourceorganizationalunitid</td></tr></table>

### <a href=#startDateTime name="startDateTime">startDateTime</a>

Shows the start date and time for the task for this estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date/Time</td></tr><tr><td>description</td><td>Shows the start date and time for the task for this estimate line.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_startdatetime</td></tr></table>

### <a href=#task name="task">task</a>

Shows the task related to this estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Task</td></tr><tr><td>description</td><td>Shows the task related to this estimate line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_task</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

Select the type of transaction.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Select the type of transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>

### <a href=#transactionClassification name="transactionClassification">transactionClassification</a>

Shows the transaction classification for this estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Class</td></tr><tr><td>description</td><td>Shows the transaction classification for this estimate line.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactionclassification</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time</td><td>192350000</td></tr><tr><td>en</td><td>Expense</td><td>192350001</td></tr><tr><td>en</td><td>Material</td><td>192350002</td></tr><tr><td>en</td><td>Milestone</td><td>192350003</td></tr><tr><td>en</td><td>Fee</td><td>192350004</td></tr><tr><td>en</td><td>Tax</td><td>690970002</td></tr></table></td></tr></table>

### <a href=#transactionClassification_display name="transactionClassification_display">transactionClassification_display</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionTypeCode name="transactionTypeCode">transactionTypeCode</a>

Shows the transaction type for this estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Type</td></tr><tr><td>description</td><td>Shows the transaction type for this estimate line.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactiontypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Cost</td><td>192350000</td></tr><tr><td>en</td><td>Project Contract</td><td>192350004</td></tr><tr><td>en</td><td>Unbilled Sales</td><td>192350005</td></tr><tr><td>en</td><td>Billed Sales</td><td>192350006</td></tr><tr><td>en</td><td>Resourcing Unit Cost</td><td>192350007</td></tr><tr><td>en</td><td>Inter-Organizational Sales</td><td>192350008</td></tr></table></td></tr></table>

### <a href=#transactionTypeCode_display name="transactionTypeCode_display">transactionTypeCode_display</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#unit name="unit">unit</a>

Shows the unit of measurement for this estimate line.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Shows the unit of measurement for this estimate line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unit</td></tr></table>

### <a href=#unitSchedule name="unitSchedule">unitSchedule</a>

Select the unit of measure for the estimate quantity.  
First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit Schedule</td></tr><tr><td>description</td><td>Select the unit of measure for the estimate quantity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unitschedule</td></tr></table>

### <a href=#vendorType name="vendorType">vendorType</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_vendortype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#vendorType_display name="vendorType_display">vendorType_display</a>

First included in: projectServiceAutomation/EstimateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

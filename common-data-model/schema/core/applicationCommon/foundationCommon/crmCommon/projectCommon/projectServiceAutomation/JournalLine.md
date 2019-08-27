---
title: JournalLine - Common Data Model | Microsoft Docs
description: Unposted business transaction line details.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Journal Line

Unposted business transaction line details.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/JournalLine.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/JournalLine  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[ownerId](#ownerId)|Owner Id|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[journalLineId](#journalLineId)|Unique identifier for entity instances|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[stateCode](#stateCode)|Status of the Journal Line|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[stateCode_display](#stateCode_display)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[statusCode](#statusCode)|Reason for the status of the Journal Line|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[statusCode_display](#statusCode_display)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[description](#description)|The name of the custom entity.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[accountCustomer](#accountCustomer)|Shows the customer for the journal line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[accountingDate](#accountingDate)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[accountVendor](#accountVendor)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[amount](#amount)|Shows the amount of the journal line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[amountMethod](#amountMethod)|Select the calculation method for the amount.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[amountMethod_display](#amountMethod_display)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[basisAmount](#basisAmount)|Enter the basis amount of the journal line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[basisAmountBase](#basisAmountBase)|Value of the Basis Amount in base currency.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[basisPrice](#basisPrice)|Enter the basis price of the journal line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[basisPriceBase](#basisPriceBase)|Value of the Basis Price in base currency.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[basisQuantity](#basisQuantity)|Enter the basis quantity of the journal line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[billingStatus](#billingStatus)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[billingStatus_display](#billingStatus_display)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[billingType](#billingType)|Select the billing type for the journal line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[billingType_display](#billingType_display)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[bookableResource](#bookableResource)|Shows the resource.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[contactCustomer](#contactCustomer)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[contactVendor](#contactVendor)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[contractingUnit](#contractingUnit)|Unique identifier for Organizational Unit associated with Journal Line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[customerType](#customerType)|Shows the type of customer.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[customerType_display](#customerType_display)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[documentDate](#documentDate)|Enter the transaction date of the journal line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[endDateTime](#endDateTime)|Enter the end date and time.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[exchangeRateDate](#exchangeRateDate)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[externalDescription](#externalDescription)|The external description of the journal line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[isPosted](#isPosted)|Shows whether the journal has been submitted.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[journal](#journal)|Shows the name of the journal.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[percent](#percent)|Enter the percent.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[price](#price)|Enter the price.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[priceBase](#priceBase)|Value of the Price in base currency.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[priceList](#priceList)|Shows the price list used for the journal line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[product](#product)|Select the product.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[project](#project)|Select the project.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[quantity](#quantity)|Enter the quantity.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[resourceCategory](#resourceCategory)|Select the resource role.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[resourceOrganizationalUnitId](#resourceOrganizationalUnitId)|Organizational unit at the time the entry was registered of the resource who performed the work.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[salesContract](#salesContract)|Shows the project contract.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[salesContractLine](#salesContractLine)|(Deprecated) Shows the project contract line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[salesContractLineId](#salesContractLineId)|Unique identifier for Project Contract Line associated with Journal Line.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[startDateTime](#startDateTime)|Enter the start date and time.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[task](#task)|Select the project task.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[transactionCategory](#transactionCategory)|Select the transaction category.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[transactionClassification](#transactionClassification)|Select the transaction class.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[transactionClassification_display](#transactionClassification_display)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[transactionTypeCode](#transactionTypeCode)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[transactionTypeCode_display](#transactionTypeCode_display)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[unit](#unit)|Shows the unit of measurement.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[unitSchedule](#unitSchedule)|Shows the unit schedule.|<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[vendorType](#vendorType)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|
|[vendorType_display](#vendorType_display)||<a href="JournalLine.md" target="_blank">projectServiceAutomation/JournalLine</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#journalLineId name="journalLineId">journalLineId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Journal Line</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_journallineid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Journal Line  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Journal Line</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Journal Line  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Journal Line</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

The name of the custom entity.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#accountCustomer name="accountCustomer">accountCustomer</a>

Shows the customer for the journal line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>Shows the customer for the journal line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountcustomer</td></tr></table>

### <a href=#accountingDate name="accountingDate">accountingDate</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accounting Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountingdate</td></tr></table>

### <a href=#accountVendor name="accountVendor">accountVendor</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountvendor</td></tr></table>

### <a href=#amount name="amount">amount</a>

Shows the amount of the journal line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>Shows the amount of the journal line.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_base</td></tr></table>

### <a href=#amountMethod name="amountMethod">amountMethod</a>

Select the calculation method for the amount.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Method</td></tr><tr><td>description</td><td>Select the calculation method for the amount.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amountmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Multiply Quantity By Price</td><td>192350000</td></tr><tr><td>en</td><td>Fixed Price</td><td>192350001</td></tr><tr><td>en</td><td>Multiply Basis Quantity By Price</td><td>192350002</td></tr><tr><td>en</td><td>Multiply Basis Amount By Percent</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#amountMethod_display name="amountMethod_display">amountMethod_display</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#basisAmount name="basisAmount">basisAmount</a>

Enter the basis amount of the journal line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Amount</td></tr><tr><td>description</td><td>Enter the basis amount of the journal line.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisamount</td></tr></table>

### <a href=#basisAmountBase name="basisAmountBase">basisAmountBase</a>

Value of the Basis Amount in base currency.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Amount (Base)</td></tr><tr><td>description</td><td>Value of the Basis Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisamount_base</td></tr></table>

### <a href=#basisPrice name="basisPrice">basisPrice</a>

Enter the basis price of the journal line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Price</td></tr><tr><td>description</td><td>Enter the basis price of the journal line.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisprice</td></tr></table>

### <a href=#basisPriceBase name="basisPriceBase">basisPriceBase</a>

Value of the Basis Price in base currency.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Price (Base)</td></tr><tr><td>description</td><td>Value of the Basis Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisprice_base</td></tr></table>

### <a href=#basisQuantity name="basisQuantity">basisQuantity</a>

Enter the basis quantity of the journal line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Quantity</td></tr><tr><td>description</td><td>Enter the basis quantity of the journal line.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisquantity</td></tr></table>

### <a href=#billingStatus name="billingStatus">billingStatus</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Ready to Invoice</td><td>192350004</td></tr><tr><td>en</td><td>Unbilled Sales Created</td><td>192350000</td></tr><tr><td>en</td><td>Customer Invoice Created</td><td>192350001</td></tr><tr><td>en</td><td>Customer Invoice Posted</td><td>192350002</td></tr><tr><td>en</td><td>Canceled</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#billingStatus_display name="billingStatus_display">billingStatus_display</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#billingType name="billingType">billingType</a>

Select the billing type for the journal line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Type</td></tr><tr><td>description</td><td>Select the billing type for the journal line.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Non Chargeable</td><td>192350000</td></tr><tr><td>en</td><td>Chargeable</td><td>192350001</td></tr><tr><td>en</td><td>Complimentary</td><td>192350002</td></tr><tr><td>en</td><td>Not Available</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#billingType_display name="billingType_display">billingType_display</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

Shows the resource.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource</td></tr><tr><td>description</td><td>Shows the resource.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#contactCustomer name="contactCustomer">contactCustomer</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contactcustomer</td></tr></table>

### <a href=#contactVendor name="contactVendor">contactVendor</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contactvendor</td></tr></table>

### <a href=#contractingUnit name="contractingUnit">contractingUnit</a>

Unique identifier for Organizational Unit associated with Journal Line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contracting Unit</td></tr><tr><td>description</td><td>Unique identifier for Organizational Unit associated with Journal Line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractorganizationalunitid</td></tr></table>

### <a href=#customerType name="customerType">customerType</a>

Shows the type of customer.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>Shows the type of customer.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#customerType_display name="customerType_display">customerType_display</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#documentDate name="documentDate">documentDate</a>

Enter the transaction date of the journal line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document Date</td></tr><tr><td>description</td><td>Enter the transaction date of the journal line.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_documentdate</td></tr></table>

### <a href=#endDateTime name="endDateTime">endDateTime</a>

Enter the end date and time.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date/Time</td></tr><tr><td>description</td><td>Enter the end date and time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_enddatetime</td></tr></table>

### <a href=#exchangeRateDate name="exchangeRateDate">exchangeRateDate</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_exchangeratedate</td></tr></table>

### <a href=#externalDescription name="externalDescription">externalDescription</a>

The external description of the journal line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Description</td></tr><tr><td>description</td><td>The external description of the journal line.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_externaldescription</td></tr></table>

### <a href=#isPosted name="isPosted">isPosted</a>

Shows whether the journal has been submitted.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Posted</td></tr><tr><td>description</td><td>Shows whether the journal has been submitted.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_isposted</td></tr></table>

### <a href=#journal name="journal">journal</a>

Shows the name of the journal.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Journal</td></tr><tr><td>description</td><td>Shows the name of the journal.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_journal</td></tr></table>

### <a href=#percent name="percent">percent</a>

Enter the percent.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percent</td></tr><tr><td>description</td><td>Enter the percent.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_percent</td></tr></table>

### <a href=#price name="price">price</a>

Enter the price.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price</td></tr><tr><td>description</td><td>Enter the price.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price</td></tr></table>

### <a href=#priceBase name="priceBase">priceBase</a>

Value of the Price in base currency.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price (Base)</td></tr><tr><td>description</td><td>Value of the Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price_base</td></tr></table>

### <a href=#priceList name="priceList">priceList</a>

Shows the price list used for the journal line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Shows the price list used for the journal line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pricelist</td></tr></table>

### <a href=#product name="product">product</a>

Select the product.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>Select the product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_product</td></tr></table>

### <a href=#project name="project">project</a>

Select the project.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Select the project.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Enter the quantity.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Enter the quantity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quantity</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Select the resource role.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>description</td><td>Select the resource role.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#resourceOrganizationalUnitId name="resourceOrganizationalUnitId">resourceOrganizationalUnitId</a>

Organizational unit at the time the entry was registered of the resource who performed the work.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resourcing Unit</td></tr><tr><td>description</td><td>Organizational unit at the time the entry was registered of the resource who performed the work.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourceorganizationalunitid</td></tr></table>

### <a href=#salesContract name="salesContract">salesContract</a>

Shows the project contract.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract</td></tr><tr><td>description</td><td>Shows the project contract.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontract</td></tr></table>

### <a href=#salesContractLine name="salesContractLine">salesContractLine</a>

(Deprecated) Shows the project contract line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Project Contract Line</td></tr><tr><td>description</td><td>(Deprecated) Shows the project contract line.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontractline</td></tr></table>

### <a href=#salesContractLineId name="salesContractLineId">salesContractLineId</a>

Unique identifier for Project Contract Line associated with Journal Line.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract Line</td></tr><tr><td>description</td><td>Unique identifier for Project Contract Line associated with Journal Line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontractlineid</td></tr></table>

### <a href=#startDateTime name="startDateTime">startDateTime</a>

Enter the start date and time.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date/Time</td></tr><tr><td>description</td><td>Enter the start date and time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_startdatetime</td></tr></table>

### <a href=#task name="task">task</a>

Select the project task.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Task</td></tr><tr><td>description</td><td>Select the project task.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_task</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

Select the transaction category.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category</td></tr><tr><td>description</td><td>Select the transaction category.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>

### <a href=#transactionClassification name="transactionClassification">transactionClassification</a>

Select the transaction class.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Class</td></tr><tr><td>description</td><td>Select the transaction class.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactionclassification</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time</td><td>192350000</td></tr><tr><td>en</td><td>Expense</td><td>192350001</td></tr><tr><td>en</td><td>Material</td><td>192350002</td></tr><tr><td>en</td><td>Milestone</td><td>192350003</td></tr><tr><td>en</td><td>Fee</td><td>192350004</td></tr><tr><td>en</td><td>Tax</td><td>690970002</td></tr></table></td></tr></table>

### <a href=#transactionClassification_display name="transactionClassification_display">transactionClassification_display</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionTypeCode name="transactionTypeCode">transactionTypeCode</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactiontypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Cost</td><td>192350000</td></tr><tr><td>en</td><td>Project Contract</td><td>192350004</td></tr><tr><td>en</td><td>Unbilled Sales</td><td>192350005</td></tr><tr><td>en</td><td>Billed Sales</td><td>192350006</td></tr><tr><td>en</td><td>Resourcing Unit Cost</td><td>192350007</td></tr><tr><td>en</td><td>Inter-Organizational Sales</td><td>192350008</td></tr></table></td></tr></table>

### <a href=#transactionTypeCode_display name="transactionTypeCode_display">transactionTypeCode_display</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#unit name="unit">unit</a>

Shows the unit of measurement.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Shows the unit of measurement.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unit</td></tr></table>

### <a href=#unitSchedule name="unitSchedule">unitSchedule</a>

Shows the unit schedule.  
First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit Schedule</td></tr><tr><td>description</td><td>Shows the unit schedule.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unitschedule</td></tr></table>

### <a href=#vendorType name="vendorType">vendorType</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_vendortype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#vendorType_display name="vendorType_display">vendorType_display</a>

First included in: projectServiceAutomation/JournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

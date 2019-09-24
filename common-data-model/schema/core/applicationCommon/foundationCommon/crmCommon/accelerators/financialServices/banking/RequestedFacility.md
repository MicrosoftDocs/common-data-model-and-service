---
title: RequestedFacility - Common Data Model | Microsoft Docs
description: This describes the RequestedFacility entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Requested Facility

A requested facility represents a facility that is requested by a corporate customer applying for line of credit.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/financialServices/banking/RequestedFacility.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/financialServices/banking/RequestedFacility  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[ownerId](#ownerId)|Owner Id|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[amount](#amount)|The amount of the facility that customer is applying for under the requested line of credit such as the bank guarantee amount or term loan amount.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[companyId](#companyId)|The company that is requesting|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[fundingEvent](#fundingEvent)|Indication of when the client needs the funding of this facility to be done; immediately upon implementation of the line of credit, or at a later time.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[fundingEvent_display](#fundingEvent_display)||<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[interestRate](#interestRate)|The rate of interest applicable to the selected facility. The applicable rate must be fetched from the product catalog based on the requested amount.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[name](#name)|The name of the custom entity.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[opportunityId](#opportunityId)|Lookup to Opportunity|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[processingCharges](#processingCharges)|The processing charges applicable to the selected facility. The applicable rate must be fetched from the product catalog based on the requested amount.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[productId](#productId)|The facility that the corporate customer is requesting as part of the credit line application.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[purpose](#purpose)|The purpose of the facility requested under the credit line.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[requestedFacilityId](#requestedFacilityId)|Unique identifier for entity instances|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[deprecatedStageId](#deprecatedStageId)|Contains the id of the stage where the entity is located.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[stateCode](#stateCode)|Status of the Requested Facility|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[stateCode_display](#stateCode_display)||<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[statusCode](#statusCode)|Reason for the status of the Requested Facility|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[statusCode_display](#statusCode_display)||<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|
|[deprecatedTraversedPath](#deprecatedTraversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="RequestedFacility.md" target="_blank">banking/RequestedFacility</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amount name="amount">amount</a>

The amount of the facility that customer is applying for under the requested line of credit such as the bank guarantee amount or term loan amount.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>The amount of the facility that customer is applying for under the requested line of credit such as the bank guarantee amount or term loan amount.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_amount</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_amount_base</td></tr></table>

### <a href=#companyId name="companyId">companyId</a>

The company that is requesting  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company</td></tr><tr><td>description</td><td>The company that is requesting</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_companyid</td></tr></table>

### <a href=#fundingEvent name="fundingEvent">fundingEvent</a>

Indication of when the client needs the funding of this facility to be done; immediately upon implementation of the line of credit, or at a later time.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Funding Event</td></tr><tr><td>description</td><td>Indication of when the client needs the funding of this facility to be done; immediately upon implementation of the line of credit, or at a later time.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_fundingevent</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#fundingEvent_display name="fundingEvent_display">fundingEvent_display</a>

First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#interestRate name="interestRate">interestRate</a>

The rate of interest applicable to the selected facility. The applicable rate must be fetched from the product catalog based on the requested amount.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interest Rate</td></tr><tr><td>description</td><td>The rate of interest applicable to the selected facility. The applicable rate must be fetched from the product catalog based on the requested amount.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_interestrate</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_name</td></tr></table>

### <a href=#opportunityId name="opportunityId">opportunityId</a>

Lookup to Opportunity  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity</td></tr><tr><td>description</td><td>Lookup to Opportunity</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_opportunityid</td></tr></table>

### <a href=#processingCharges name="processingCharges">processingCharges</a>

The processing charges applicable to the selected facility. The applicable rate must be fetched from the product catalog based on the requested amount.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Processing Charges</td></tr><tr><td>description</td><td>The processing charges applicable to the selected facility. The applicable rate must be fetched from the product catalog based on the requested amount.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_processingcharges</td></tr></table>

### <a href=#productId name="productId">productId</a>

The facility that the corporate customer is requesting as part of the credit line application.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>The facility that the corporate customer is requesting as part of the credit line application.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_productid</td></tr></table>

### <a href=#purpose name="purpose">purpose</a>

The purpose of the facility requested under the credit line.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purpose</td></tr><tr><td>description</td><td>The purpose of the facility requested under the credit line.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_purpose</td></tr></table>

### <a href=#requestedFacilityId name="requestedFacilityId">requestedFacilityId</a>

Unique identifier for entity instances  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requested Facility</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_requestedfacilityid</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#deprecatedStageId name="deprecatedStageId">deprecatedStageId</a>

Contains the id of the stage where the entity is located.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Requested Facility  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Requested Facility</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Requested Facility  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Requested Facility</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#deprecatedTraversedPath name="deprecatedTraversedPath">deprecatedTraversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: banking/RequestedFacility (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

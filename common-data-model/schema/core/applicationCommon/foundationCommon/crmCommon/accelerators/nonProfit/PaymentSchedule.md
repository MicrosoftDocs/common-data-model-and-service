---
title: PaymentSchedule - Common Data Model | Microsoft Docs
description: This describes the PaymentSchedule entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Payment Schedule

A gift transaction can be a one-time payment or a recurring payment (ie, monthly/sustainer giving). In addition, it can be a pledge (ie, promise) of a future payment or a current/received payment.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/PaymentSchedule.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/PaymentSchedule  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[ownerId](#ownerId)|Owner Id|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[paymentScheduleId](#paymentScheduleId)|Unique identifier for entity instances|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[stateCode](#stateCode)|Status of the Payment Schedule|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[stateCode_display](#stateCode_display)||<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[statusCode](#statusCode)|Reason for the status of the Payment Schedule|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[statusCode_display](#statusCode_display)||<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[name](#name)||<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[firstPaymentDate](#firstPaymentDate)|Date of first payment|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[frequency](#frequency)|iCal compliant recurrence field|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[frequency_display](#frequency_display)||<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[frequencyInterval](#frequencyInterval)|iCal compliant recurrence field|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[lastPaymentDate](#lastPaymentDate)|The date by which the payment schedule is expected to be fully paid.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[nextPaymentAmount](#nextPaymentAmount)||<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[nextPaymentAmountBase](#nextPaymentAmountBase)|Value of the Next Payment Amount in base currency.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[nextPaymentDate](#nextPaymentDate)||<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[numberOfPayments](#numberOfPayments)||<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[omtSchedDefaultHardCreditToCustomer](#omtSchedDefaultHardCreditToCustomer)||<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[paymentScheduleDonorCommitmentId](#paymentScheduleDonorCommitmentId)|Donor Commitment|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[receiptOnAccountId](#receiptOnAccountId)|Receipt on Account|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[recurringAmount](#recurringAmount)|This will include both the Base and Donor Currencies|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[recurringamountBase](#recurringamountBase)|Value of the Recurring Amount in base currency.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[totalAmount](#totalAmount)|This will include both the Base and Donor Currencies|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|
|[totalamountBase](#totalamountBase)|Value of the Total Amount in base currency.|<a href="PaymentSchedule.md" target="_blank">nonProfit/PaymentSchedule</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#paymentScheduleId name="paymentScheduleId">paymentScheduleId</a>

Unique identifier for entity instances  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Schedule</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_paymentscheduleid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Payment Schedule  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Payment Schedule</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Payment Schedule  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Payment Schedule</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#firstPaymentDate name="firstPaymentDate">firstPaymentDate</a>

Date of first payment  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Payment Date</td></tr><tr><td>description</td><td>Date of first payment</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_firstpaymentdate</td></tr></table>

### <a href=#frequency name="frequency">frequency</a>

iCal compliant recurrence field  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Frequency</td></tr><tr><td>description</td><td>iCal compliant recurrence field</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_frequency</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>RecurrenceFrequency</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#frequency_display name="frequency_display">frequency_display</a>

First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#frequencyInterval name="frequencyInterval">frequencyInterval</a>

iCal compliant recurrence field  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Frequency Interval</td></tr><tr><td>description</td><td>iCal compliant recurrence field</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_frequencyinterval</td></tr></table>

### <a href=#lastPaymentDate name="lastPaymentDate">lastPaymentDate</a>

The date by which the payment schedule is expected to be fully paid.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Payment Date</td></tr><tr><td>description</td><td>The date by which the payment schedule is expected to be fully paid.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_lastpaymentdate</td></tr></table>

### <a href=#nextPaymentAmount name="nextPaymentAmount">nextPaymentAmount</a>

First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Payment Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_nextpaymentamount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#nextPaymentAmountBase name="nextPaymentAmountBase">nextPaymentAmountBase</a>

Value of the Next Payment Amount in base currency.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Payment Amount (Base)</td></tr><tr><td>description</td><td>Value of the Next Payment Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_nextpaymentamount_base</td></tr></table>

### <a href=#nextPaymentDate name="nextPaymentDate">nextPaymentDate</a>

First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Payment Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_nextpaymentdate</td></tr></table>

### <a href=#numberOfPayments name="numberOfPayments">numberOfPayments</a>

First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of Payments</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_numberofpayments</td></tr></table>

### <a href=#omtSchedDefaultHardCreditToCustomer name="omtSchedDefaultHardCreditToCustomer">omtSchedDefaultHardCreditToCustomer</a>

First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Hard Credit To Customer</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_omtsched_defaulthardcredittocustomer</td></tr></table>

### <a href=#paymentScheduleDonorCommitmentId name="paymentScheduleDonorCommitmentId">paymentScheduleDonorCommitmentId</a>

Donor Commitment  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Donor Commitment</td></tr><tr><td>description</td><td>Donor Commitment</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_paymentschedule_donorcommitmentid</td></tr></table>

### <a href=#receiptOnAccountId name="receiptOnAccountId">receiptOnAccountId</a>

Receipt on Account  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receipt on Account</td></tr><tr><td>description</td><td>Receipt on Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_receiptonaccountid</td></tr></table>

### <a href=#recurringAmount name="recurringAmount">recurringAmount</a>

This will include both the Base and Donor Currencies  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurring Amount</td></tr><tr><td>description</td><td>This will include both the Base and Donor Currencies</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_recurringamount</td></tr></table>

### <a href=#recurringamountBase name="recurringamountBase">recurringamountBase</a>

Value of the Recurring Amount in base currency.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurring Amount (Base)</td></tr><tr><td>description</td><td>Value of the Recurring Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_recurringamount_base</td></tr></table>

### <a href=#totalAmount name="totalAmount">totalAmount</a>

This will include both the Base and Donor Currencies  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount</td></tr><tr><td>description</td><td>This will include both the Base and Donor Currencies</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalamount</td></tr></table>

### <a href=#totalamountBase name="totalamountBase">totalamountBase</a>

Value of the Total Amount in base currency.  
First included in: nonProfit/PaymentSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalamount_base</td></tr></table>

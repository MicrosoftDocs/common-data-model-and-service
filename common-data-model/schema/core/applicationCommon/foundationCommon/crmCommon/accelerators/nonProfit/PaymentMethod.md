---
title: PaymentMethod - Common Data Model | Microsoft Docs
description: Payment Method is a placeholder entity for customizations that may be supported by an application.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Payment Method

Payment Method is a placeholder entity for customizations that may be supported by an application.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/PaymentMethod.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/PaymentMethod  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[ownerId](#ownerId)|Owner Id|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[paymentMethodId](#paymentMethodId)|Unique identifier for entity instances|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[stateCode](#stateCode)|Status of the Payment Method|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[stateCode_display](#stateCode_display)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[statusCode](#statusCode)|Reason for the status of the Payment Method|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[statusCode_display](#statusCode_display)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[name](#name)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[comments](#comments)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[contactId](#contactId)|Unique identifier for Contact associated with Payment Method.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[isDefault](#isDefault)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[lastAuthenticationStatus](#lastAuthenticationStatus)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[lastAuthenticationStatus_display](#lastAuthenticationStatus_display)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[lastAuthenticationStatusDate](#lastAuthenticationStatusDate)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[lastAuthenticationStatusDetail](#lastAuthenticationStatusDetail)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[lastAuthenticationStatusTechnicalDetail](#lastAuthenticationStatusTechnicalDetail)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[paymentScheduleId](#paymentScheduleId)|Unique identifier for Payment Schedule associated with Payment Method.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[payorId](#payorId)|Payor Account|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[transactionId](#transactionId)|Unique identifier for Transaction associated with Payment Method.|<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[type](#type)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|
|[type_display](#type_display)||<a href="PaymentMethod.md" target="_blank">nonProfit/PaymentMethod</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#paymentMethodId name="paymentMethodId">paymentMethodId</a>

Unique identifier for entity instances  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Method</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_paymentmethodid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Payment Method  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Payment Method</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Payment Method  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Payment Method</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#comments name="comments">comments</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comments</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_comments</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Unique identifier for Contact associated with Payment Method.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Unique identifier for Contact associated with Payment Method.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_contactid</td></tr></table>

### <a href=#isDefault name="isDefault">isDefault</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Default</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_isdefault</td></tr></table>

### <a href=#lastAuthenticationStatus name="lastAuthenticationStatus">lastAuthenticationStatus</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Authentication Status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_lastauthenticationstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>PaymentMethodStatus</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#lastAuthenticationStatus_display name="lastAuthenticationStatus_display">lastAuthenticationStatus_display</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#lastAuthenticationStatusDate name="lastAuthenticationStatusDate">lastAuthenticationStatusDate</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Authentication Status Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_lastauthenticationstatusdate</td></tr></table>

### <a href=#lastAuthenticationStatusDetail name="lastAuthenticationStatusDetail">lastAuthenticationStatusDetail</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Authentication Status Detail</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>120</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_lastauthenticationstatusdetail</td></tr></table>

### <a href=#lastAuthenticationStatusTechnicalDetail name="lastAuthenticationStatusTechnicalDetail">lastAuthenticationStatusTechnicalDetail</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Authentication Status Technical Detail</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_lastauthenticationstatustechnicaldetail</td></tr></table>

### <a href=#paymentScheduleId name="paymentScheduleId">paymentScheduleId</a>

Unique identifier for Payment Schedule associated with Payment Method.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Schedule</td></tr><tr><td>description</td><td>Unique identifier for Payment Schedule associated with Payment Method.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_paymentscheduleid</td></tr></table>

### <a href=#payorId name="payorId">payorId</a>

Payor Account  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payor Account</td></tr><tr><td>description</td><td>Payor Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_payorid</td></tr></table>

### <a href=#transactionId name="transactionId">transactionId</a>

Unique identifier for Transaction associated with Payment Method.  
First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction</td></tr><tr><td>description</td><td>Unique identifier for Transaction associated with Payment Method.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_transactionid</td></tr></table>

### <a href=#type name="type">type</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>PaymentMethodType</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: nonProfit/PaymentMethod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

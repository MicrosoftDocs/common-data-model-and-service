---
title: QuoteLineAnalyticsBreakdown - Common Data Model | Microsoft Docs
description: Reporting entity that is used to show quoted sales and estimated cost amounts by various dimensions.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Quote Line Analytics Breakdown

Reporting entity that is used to show quoted sales and estimated cost amounts by various dimensions.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/QuoteLineAnalyticsBreakdown.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/QuoteLineAnalyticsBreakdown  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[ownerId](#ownerId)|Owner Id|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[quoteLineAnalyticsBreakdownId](#quoteLineAnalyticsBreakdownId)|Unique identifier for entity instances|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[stateCode](#stateCode)|Status of the Quote Line Analytics Breakdown|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[stateCode_display](#stateCode_display)||<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[statusCode](#statusCode)|Reason for the status of the Quote Line Analytics Breakdown|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[statusCode_display](#statusCode_display)||<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[name](#name)|Type a description of the entity breakdown.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[amount](#amount)|Enter the amount on the quote line estimate.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[billingType](#billingType)|Select whether the quote line estimate will be charged to the customer. Valid values are Chargeable, Non-chargeable and Complimentary. Only chargeable transactions will affect the invoice totals.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[billingType_display](#billingType_display)||<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[endDateTime](#endDateTime)|Enter the estimated end date of the quote line estimate.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[price](#price)|Enter the unit price on the quote line estimate.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[priceBase](#priceBase)|Value of the Price in base currency.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[quote](#quote)|Select the quote that this quote line estimate belongs to.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[quoteLineDetail](#quoteLineDetail)|Select the quote line estimate.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[quoteLineScheduleOfValue](#quoteLineScheduleOfValue)|Shows the billing milestone for the quote line.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[resourceCategory](#resourceCategory)|Select the role that is estimated on the quote line.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[startDateTime](#startDateTime)|Enter the estimated start date of the quote line estimate.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[transactionCategory](#transactionCategory)|Select the category identified on the quote line estimate.|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[transactionClassification](#transactionClassification)|Transaction classification of  Project quote analytics|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[transactionClassification_display](#transactionClassification_display)||<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[transactionTypeCode](#transactionTypeCode)|Transaction type of the Project quote analytics|<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|
|[transactionTypeCode_display](#transactionTypeCode_display)||<a href="QuoteLineAnalyticsBreakdown.md" target="_blank">projectServiceAutomation/QuoteLineAnalyticsBreakdown</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#quoteLineAnalyticsBreakdownId name="quoteLineAnalyticsBreakdownId">quoteLineAnalyticsBreakdownId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Line Analytics Breakdown</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_quotelineanalyticsbreakdownid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Quote Line Analytics Breakdown  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Quote Line Analytics Breakdown</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Quote Line Analytics Breakdown  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Quote Line Analytics Breakdown</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Type a description of the entity breakdown.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a description of the entity breakdown.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#amount name="amount">amount</a>

Enter the amount on the quote line estimate.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>Enter the amount on the quote line estimate.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_base</td></tr></table>

### <a href=#billingType name="billingType">billingType</a>

Select whether the quote line estimate will be charged to the customer. Valid values are Chargeable, Non-chargeable and Complimentary. Only chargeable transactions will affect the invoice totals.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Type</td></tr><tr><td>description</td><td>Select whether the quote line estimate will be charged to the customer. Valid values are Chargeable, Non-chargeable and Complimentary. Only chargeable transactions will affect the invoice totals.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Non Chargeable</td><td>192350000</td></tr><tr><td>en</td><td>Chargeable</td><td>192350001</td></tr><tr><td>en</td><td>Complimentary</td><td>192350002</td></tr><tr><td>en</td><td>Not Available</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#billingType_display name="billingType_display">billingType_display</a>

First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#endDateTime name="endDateTime">endDateTime</a>

Enter the estimated end date of the quote line estimate.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date Time</td></tr><tr><td>description</td><td>Enter the estimated end date of the quote line estimate.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_enddatetime</td></tr></table>

### <a href=#price name="price">price</a>

Enter the unit price on the quote line estimate.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price</td></tr><tr><td>description</td><td>Enter the unit price on the quote line estimate.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price</td></tr></table>

### <a href=#priceBase name="priceBase">priceBase</a>

Value of the Price in base currency.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price (Base)</td></tr><tr><td>description</td><td>Value of the Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price_base</td></tr></table>

### <a href=#quote name="quote">quote</a>

Select the quote that this quote line estimate belongs to.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote</td></tr><tr><td>description</td><td>Select the quote that this quote line estimate belongs to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quote</td></tr></table>

### <a href=#quoteLineDetail name="quoteLineDetail">quoteLineDetail</a>

Select the quote line estimate.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Line Detail</td></tr><tr><td>description</td><td>Select the quote line estimate.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quotelinedetail</td></tr></table>

### <a href=#quoteLineScheduleOfValue name="quoteLineScheduleOfValue">quoteLineScheduleOfValue</a>

Shows the billing milestone for the quote line.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>QuoteLineScheduleOfValue</td></tr><tr><td>description</td><td>Shows the billing milestone for the quote line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quotelinescheduleofvalue</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Select the role that is estimated on the quote line.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>description</td><td>Select the role that is estimated on the quote line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#startDateTime name="startDateTime">startDateTime</a>

Enter the estimated start date of the quote line estimate.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date Time</td></tr><tr><td>description</td><td>Enter the estimated start date of the quote line estimate.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_startdatetime</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

Select the category identified on the quote line estimate.  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category</td></tr><tr><td>description</td><td>Select the category identified on the quote line estimate.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>

### <a href=#transactionClassification name="transactionClassification">transactionClassification</a>

Transaction classification of  Project quote analytics  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Class</td></tr><tr><td>description</td><td>Transaction classification of  Project quote analytics</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactionclassification</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time</td><td>192350000</td></tr><tr><td>en</td><td>Expense</td><td>192350001</td></tr><tr><td>en</td><td>Material</td><td>192350002</td></tr><tr><td>en</td><td>Milestone</td><td>192350003</td></tr><tr><td>en</td><td>Fee</td><td>192350004</td></tr><tr><td>en</td><td>Tax</td><td>690970002</td></tr></table></td></tr></table>

### <a href=#transactionClassification_display name="transactionClassification_display">transactionClassification_display</a>

First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionTypeCode name="transactionTypeCode">transactionTypeCode</a>

Transaction type of the Project quote analytics  
First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Type</td></tr><tr><td>description</td><td>Transaction type of the Project quote analytics</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactiontypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Cost</td><td>192350000</td></tr><tr><td>en</td><td>Project Contract</td><td>192350004</td></tr><tr><td>en</td><td>Unbilled Sales</td><td>192350005</td></tr><tr><td>en</td><td>Billed Sales</td><td>192350006</td></tr><tr><td>en</td><td>Resourcing Unit Cost</td><td>192350007</td></tr><tr><td>en</td><td>Inter-Organizational Sales</td><td>192350008</td></tr></table></td></tr></table>

### <a href=#transactionTypeCode_display name="transactionTypeCode_display">transactionTypeCode_display</a>

First included in: projectServiceAutomation/QuoteLineAnalyticsBreakdown (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

---
title: DesignationPlan - Common Data Model | Microsoft Docs
description: This describes the DesignationPlan entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Designation Plan

A line item attached to a Pledge, Payment Schedule, or Campaign indicating how associated payments should be designated.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/DesignationPlan.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/DesignationPlan  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[ownerId](#ownerId)|Owner Id|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[designationPlanId](#designationPlanId)|Unique identifier for entity instances|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[stateCode](#stateCode)|Status of the Designation Plan|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[stateCode_display](#stateCode_display)||<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[statusCode](#statusCode)|Reason for the status of the Designation Plan|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[statusCode_display](#statusCode_display)||<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[name](#name)||<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[amountOfPledgeMax](#amountOfPledgeMax)||<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[amountofpledgemaxBase](#amountofpledgemaxBase)|Value of the Amount Of Pledge Max in base currency.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[designationPlanCampaignId](#designationPlanCampaignId)|Campaign|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[designationPlanDesignationId](#designationPlanDesignationId)|Designation|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[designationPlanDonorCommitmentId](#designationPlanDonorCommitmentId)|Donor Commitment|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[designationPlanOpportunityId](#designationPlanOpportunityId)|Opportunity|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[designationPlanPaymentScheduleId](#designationPlanPaymentScheduleId)|Payment Schedule|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[numberOfPaymentsMax](#numberOfPaymentsMax)||<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[percentageOfPaymentsMax](#percentageOfPaymentsMax)||<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[percentageOfPledgeMax](#percentageOfPledgeMax)||<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[perPaymentMaxAmount](#perPaymentMaxAmount)||<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[perpaymentmaxamountBase](#perpaymentmaxamountBase)|Value of the Per Payment Max Amount in base currency.|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[perPaymentMaxPercent](#perPaymentMaxPercent)||<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[priorityOrder](#priorityOrder)|Applied when multiple line items might conflict (e.g. 90% vs $1000000)|<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[validFromDate](#validFromDate)||<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|
|[validToDate](#validToDate)||<a href="DesignationPlan.md" target="_blank">nonProfit/DesignationPlan</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#designationPlanId name="designationPlanId">designationPlanId</a>

Unique identifier for entity instances  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designation Plan</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_designationplanid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Designation Plan  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Designation Plan</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Designation Plan  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Designation Plan</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#amountOfPledgeMax name="amountOfPledgeMax">amountOfPledgeMax</a>

First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Of Pledge Max</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountofpledgemax</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountofpledgemaxBase name="amountofpledgemaxBase">amountofpledgemaxBase</a>

Value of the Amount Of Pledge Max in base currency.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Of Pledge Max (Base)</td></tr><tr><td>description</td><td>Value of the Amount Of Pledge Max in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountofpledgemax_base</td></tr></table>

### <a href=#designationPlanCampaignId name="designationPlanCampaignId">designationPlanCampaignId</a>

Campaign  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Campaign</td></tr><tr><td>description</td><td>Campaign</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designationplan_campaignid</td></tr></table>

### <a href=#designationPlanDesignationId name="designationPlanDesignationId">designationPlanDesignationId</a>

Designation  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designation</td></tr><tr><td>description</td><td>Designation</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designationplan_designationid</td></tr></table>

### <a href=#designationPlanDonorCommitmentId name="designationPlanDonorCommitmentId">designationPlanDonorCommitmentId</a>

Donor Commitment  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Donor Commitment</td></tr><tr><td>description</td><td>Donor Commitment</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designationplan_donorcommitmentid</td></tr></table>

### <a href=#designationPlanOpportunityId name="designationPlanOpportunityId">designationPlanOpportunityId</a>

Opportunity  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity</td></tr><tr><td>description</td><td>Opportunity</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designationplan_opportunityid</td></tr></table>

### <a href=#designationPlanPaymentScheduleId name="designationPlanPaymentScheduleId">designationPlanPaymentScheduleId</a>

Payment Schedule  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Schedule</td></tr><tr><td>description</td><td>Payment Schedule</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designationplan_paymentscheduleid</td></tr></table>

### <a href=#numberOfPaymentsMax name="numberOfPaymentsMax">numberOfPaymentsMax</a>

First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number Of Payments Max</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_numberofpaymentsmax</td></tr></table>

### <a href=#percentageOfPaymentsMax name="percentageOfPaymentsMax">percentageOfPaymentsMax</a>

First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage Of Payments Max</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_percentageofpaymentsmax</td></tr></table>

### <a href=#percentageOfPledgeMax name="percentageOfPledgeMax">percentageOfPledgeMax</a>

First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage Of Pledge Max</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_percentageofpledgemax</td></tr></table>

### <a href=#perPaymentMaxAmount name="perPaymentMaxAmount">perPaymentMaxAmount</a>

First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Per Payment Max Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_perpaymentmaxamount</td></tr></table>

### <a href=#perpaymentmaxamountBase name="perpaymentmaxamountBase">perpaymentmaxamountBase</a>

Value of the Per Payment Max Amount in base currency.  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Per Payment Max Amount (Base)</td></tr><tr><td>description</td><td>Value of the Per Payment Max Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_perpaymentmaxamount_base</td></tr></table>

### <a href=#perPaymentMaxPercent name="perPaymentMaxPercent">perPaymentMaxPercent</a>

First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Per Payment Max Percent</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_perpaymentmaxpercent</td></tr></table>

### <a href=#priorityOrder name="priorityOrder">priorityOrder</a>

Applied when multiple line items might conflict (e.g. 90% vs $1000000)  
First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority Order</td></tr><tr><td>description</td><td>Applied when multiple line items might conflict (e.g. 90% vs $1000000)</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_priorityorder</td></tr></table>

### <a href=#validFromDate name="validFromDate">validFromDate</a>

First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Valid From Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_validfromdate</td></tr></table>

### <a href=#validToDate name="validToDate">validToDate</a>

First included in: nonProfit/DesignationPlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Valid To Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_validtodate</td></tr></table>

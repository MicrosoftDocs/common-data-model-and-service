---
title: FinancingOpportunityDetail - Common Data Model | Microsoft Docs
description: Type of payment that forms part of a financing opportunity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Financing Opportunity Detail

Type of payment that forms part of a financing opportunity.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/FinancingOpportunityDetail.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/FinancingOpportunityDetail  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[ownerId](#ownerId)|Owner Id|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[amountLimit](#amountLimit)|The amount limit of the financing opportunity detail (max, min or exactly).|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[amountLimit_display](#amountLimit_display)||<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[amountType](#amountType)|The type for this financing opportunity detail (down payment, monthly or total).|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[amountType_display](#amountType_display)||<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[balanceType](#balanceType)|The type for the remaining balance (finance or residual).|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[balanceType_display](#balanceType_display)||<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[financingOpportunityDetailId](#financingOpportunityDetailId)|Unique identifier for entity instances|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[financingOpportunityId](#financingOpportunityId)|The parent financing opportunity for this financing opportunity detail record.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[name](#name)|Name of the financing opportunity detail.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[value](#value)|Amount of the financing opportunity detail.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[valueBase](#valueBase)|Value of the Value in base currency.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[stateCode](#stateCode)|Status of the Financing Opportunity Detail|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[stateCode_display](#stateCode_display)||<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[statusCode](#statusCode)|Reason for the status of the Financing Opportunity Detail|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[statusCode_display](#statusCode_display)||<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="FinancingOpportunityDetail.md" target="_blank">automotive/FinancingOpportunityDetail</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountLimit name="amountLimit">amountLimit</a>

The amount limit of the financing opportunity detail (max, min or exactly).  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Limit</td></tr><tr><td>description</td><td>The amount limit of the financing opportunity detail (max, min or exactly).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_amountlimit</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#amountLimit_display name="amountLimit_display">amountLimit_display</a>

First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#amountType name="amountType">amountType</a>

The type for this financing opportunity detail (down payment, monthly or total).  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Type</td></tr><tr><td>description</td><td>The type for this financing opportunity detail (down payment, monthly or total).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_amounttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#amountType_display name="amountType_display">amountType_display</a>

First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#balanceType name="balanceType">balanceType</a>

The type for the remaining balance (finance or residual).  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Balance Type</td></tr><tr><td>description</td><td>The type for the remaining balance (finance or residual).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_balancetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#balanceType_display name="balanceType_display">balanceType_display</a>

First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#financingOpportunityDetailId name="financingOpportunityDetailId">financingOpportunityDetailId</a>

Unique identifier for entity instances  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financing Opportunity Detail</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_financingopportunitydetailid</td></tr></table>

### <a href=#financingOpportunityId name="financingOpportunityId">financingOpportunityId</a>

The parent financing opportunity for this financing opportunity detail record.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financing Opportunity</td></tr><tr><td>description</td><td>The parent financing opportunity for this financing opportunity detail record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_financingopportunityid</td></tr></table>

### <a href=#name name="name">name</a>

Name of the financing opportunity detail.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the financing opportunity detail.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#value name="value">value</a>

Amount of the financing opportunity detail.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value</td></tr><tr><td>description</td><td>Amount of the financing opportunity detail.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_value</td></tr></table>

### <a href=#valueBase name="valueBase">valueBase</a>

Value of the Value in base currency.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value (Base)</td></tr><tr><td>description</td><td>Value of the Value in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_value_base</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Financing Opportunity Detail  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Financing Opportunity Detail</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Financing Opportunity Detail  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Financing Opportunity Detail</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: automotive/FinancingOpportunityDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

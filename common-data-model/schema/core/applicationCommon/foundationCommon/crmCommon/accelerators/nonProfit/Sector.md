---
title: Sector - Common Data Model | Microsoft Docs
description: Classification of the purpose of the Delivery Framework.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Sector

Classification of the purpose of the Delivery Framework.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Sector.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/Sector  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[sectorId](#sectorId)|Unique identifier for entity instances|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[stateCode](#stateCode)|Status of the Sector|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[stateCode_display](#stateCode_display)||<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[statusCode](#statusCode)|Reason for the status of the Sector|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[statusCode_display](#statusCode_display)||<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[name](#name)|The name of the custom entity.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[awardId](#awardId)|Unique identifier for Award associated with Sector.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[codeId](#codeId)|The code for the sector.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[deliveryFrameworkId](#deliveryFrameworkId)|Unique identifier for Delivery Framework associated with Sector.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[disbursementId](#disbursementId)|Unique identifier for Disbursement associated with Sector.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[donorCommitmentId](#donorCommitmentId)|Unique identifier for Donor Commitment associated with Sector.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[expenditureId](#expenditureId)|Unique identifier for Expenditure associated with Sector.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[percentage](#percentage)|Percentage of total commitments or total delivery framework budget to this item.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[relatedTo](#relatedTo)|Indicates the entity to which the sector is related.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[relatedTo_display](#relatedTo_display)||<a href="Sector.md" target="_blank">nonProfit/Sector</a>|
|[transactionId](#transactionId)|Unique identifier for Transaction associated with Sector.|<a href="Sector.md" target="_blank">nonProfit/Sector</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#sectorId name="sectorId">sectorId</a>

Unique identifier for entity instances  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sector</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msiati_sectorid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Sector  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Sector</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Sector  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Sector</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_name</td></tr></table>

### <a href=#awardId name="awardId">awardId</a>

Unique identifier for Award associated with Sector.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Award</td></tr><tr><td>description</td><td>Unique identifier for Award associated with Sector.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_awardid</td></tr></table>

### <a href=#codeId name="codeId">codeId</a>

The code for the sector.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>description</td><td>The code for the sector.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_codeid</td></tr></table>

### <a href=#deliveryFrameworkId name="deliveryFrameworkId">deliveryFrameworkId</a>

Unique identifier for Delivery Framework associated with Sector.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Framework</td></tr><tr><td>description</td><td>Unique identifier for Delivery Framework associated with Sector.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_deliveryframeworkid</td></tr></table>

### <a href=#disbursementId name="disbursementId">disbursementId</a>

Unique identifier for Disbursement associated with Sector.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disbursement</td></tr><tr><td>description</td><td>Unique identifier for Disbursement associated with Sector.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_disbursementid</td></tr></table>

### <a href=#donorCommitmentId name="donorCommitmentId">donorCommitmentId</a>

Unique identifier for Donor Commitment associated with Sector.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Donor Commitment</td></tr><tr><td>description</td><td>Unique identifier for Donor Commitment associated with Sector.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_donorcommitmentid</td></tr></table>

### <a href=#expenditureId name="expenditureId">expenditureId</a>

Unique identifier for Expenditure associated with Sector.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expenditure</td></tr><tr><td>description</td><td>Unique identifier for Expenditure associated with Sector.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_expenditureid</td></tr></table>

### <a href=#percentage name="percentage">percentage</a>

Percentage of total commitments or total delivery framework budget to this item.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage</td></tr><tr><td>description</td><td>Percentage of total commitments or total delivery framework budget to this item.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_percentage</td></tr></table>

### <a href=#relatedTo name="relatedTo">relatedTo</a>

Indicates the entity to which the sector is related.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related To</td></tr><tr><td>description</td><td>Indicates the entity to which the sector is related.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_relatedto</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Award</td><td>453490004</td></tr><tr><td>en</td><td>Delivery Framework</td><td>453490000</td></tr><tr><td>en</td><td>Disbursement</td><td>453490005</td></tr><tr><td>en</td><td>Donor Commitment</td><td>453490003</td></tr><tr><td>en</td><td>Expenditure</td><td>453490001</td></tr><tr><td>en</td><td>Transaction</td><td>453490002</td></tr></table></td></tr></table>

### <a href=#relatedTo_display name="relatedTo_display">relatedTo_display</a>

First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionId name="transactionId">transactionId</a>

Unique identifier for Transaction associated with Sector.  
First included in: nonProfit/Sector (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction</td></tr><tr><td>description</td><td>Unique identifier for Transaction associated with Sector.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_transactionid</td></tr></table>

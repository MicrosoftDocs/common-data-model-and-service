---
title: NarrativeTranslation - Common Data Model | Microsoft Docs
description: Allows the translation of different narrative elements for IATI reporting.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Narrative Translation

Allows the translation of different narrative elements for IATI reporting.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/NarrativeTranslation.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/NarrativeTranslation  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[ownerId](#ownerId)|Owner Id|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[narrativeTranslationId](#narrativeTranslationId)|Unique identifier for entity instances|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[stateCode](#stateCode)|Status of the Narrative Translation|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[stateCode_display](#stateCode_display)||<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[statusCode](#statusCode)|Reason for the status of the Narrative Translation|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[statusCode_display](#statusCode_display)||<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[name](#name)|The name of the custom entity.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[accountId](#accountId)|Unique identifier for Account associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[attribute](#attribute)||<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[msiatiAttribute_display](#msiatiAttribute_display)||<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[budgetId](#budgetId)|Unique identifier for Budget associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[conditionId](#conditionId)|Unique identifier for Condition associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[contactId](#contactId)|Unique identifier for Contact associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[deliveryFrameworkDescriptionId](#deliveryFrameworkDescriptionId)|Unique identifier for Delivery Framework Description associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[deliveryFrameworkId](#deliveryFrameworkId)|Unique identifier for Delivery Framework associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[disbursementId](#disbursementId)|Unique identifier for Disbursement associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[docuemntCountryId](#docuemntCountryId)|Unique identifier for Document Country associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[documentLinkId](#documentLinkId)|Unique identifier for Document Link associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[donorCommitmentId](#donorCommitmentId)|Unique identifier for Donor Commitment associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[entityName](#entityName)|Indicates the name of the entity|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[entityName_display](#entityName_display)||<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[expenditureId](#expenditureId)|Unique identifier for Expenditure associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[humanitarianScopeId](#humanitarianScopeId)|Unique identifier for Humanitarian Scope associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[indicatorId](#indicatorId)|Unique identifier for Indicator associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[indicatorValueId](#indicatorValueId)|Unique identifier for Indicator Value associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[languageId](#languageId)|Narrative languages|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[locationId](#locationId)|Unique identifier for Location associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[policyMakerId](#policyMakerId)|Unique identifier for Policy Marker associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[recipientCountryId](#recipientCountryId)|Unique identifier for Recipient Country associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[recipientRegionId](#recipientRegionId)|Unique identifier for Recipient Region associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[resultId](#resultId)|Unique identifier for Result associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[sectorId](#sectorId)|Unique identifier for Sector associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[tagId](#tagId)|Unique identifier for Tag associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[transactionId](#transactionId)|Unique identifier for Transaction associated with Narrative Translation.|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|
|[translation](#translation)|IATI's attribute translation|<a href="NarrativeTranslation.md" target="_blank">nonProfit/NarrativeTranslation</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#narrativeTranslationId name="narrativeTranslationId">narrativeTranslationId</a>

Unique identifier for entity instances  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Narrative Translation</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msiati_narrativetranslationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Narrative Translation  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Narrative Translation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Narrative Translation  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Narrative Translation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_name</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Unique identifier for Account associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_accountid</td></tr></table>

### <a href=#attribute name="attribute">attribute</a>

First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attribute</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_attribute</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Department</td><td>453490002</td></tr><tr><td>en</td><td>Full Name</td><td>453490003</td></tr><tr><td>en</td><td>Job Title</td><td>453490004</td></tr><tr><td>en</td><td>Address 1</td><td>453490005</td></tr><tr><td>en</td><td>Address 2</td><td>453490006</td></tr><tr><td>en</td><td>Address 3</td><td>453490007</td></tr><tr><td>en</td><td>Recipient Region Description</td><td>453490008</td></tr><tr><td>en</td><td>Recipient Country Description</td><td>453490009</td></tr><tr><td>en</td><td>Activity Location Description</td><td>453490010</td></tr><tr><td>en</td><td>Name</td><td>453490000</td></tr><tr><td>en</td><td>Description</td><td>453490001</td></tr></table></td></tr></table>

### <a href=#msiatiAttribute_display name="msiatiAttribute_display">msiatiAttribute_display</a>

First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#budgetId name="budgetId">budgetId</a>

Unique identifier for Budget associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget</td></tr><tr><td>description</td><td>Unique identifier for Budget associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_budgetid</td></tr></table>

### <a href=#conditionId name="conditionId">conditionId</a>

Unique identifier for Condition associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Condition</td></tr><tr><td>description</td><td>Unique identifier for Condition associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_conditionid</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Unique identifier for Contact associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Unique identifier for Contact associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_contactid</td></tr></table>

### <a href=#deliveryFrameworkDescriptionId name="deliveryFrameworkDescriptionId">deliveryFrameworkDescriptionId</a>

Unique identifier for Delivery Framework Description associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Framework Description</td></tr><tr><td>description</td><td>Unique identifier for Delivery Framework Description associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_deliveryframeworkdescriptionid</td></tr></table>

### <a href=#deliveryFrameworkId name="deliveryFrameworkId">deliveryFrameworkId</a>

Unique identifier for Delivery Framework associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Framework</td></tr><tr><td>description</td><td>Unique identifier for Delivery Framework associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_deliveryframeworkdid</td></tr></table>

### <a href=#disbursementId name="disbursementId">disbursementId</a>

Unique identifier for Disbursement associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disbursement</td></tr><tr><td>description</td><td>Unique identifier for Disbursement associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_disbursementid</td></tr></table>

### <a href=#docuemntCountryId name="docuemntCountryId">docuemntCountryId</a>

Unique identifier for Document Country associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document Country</td></tr><tr><td>description</td><td>Unique identifier for Document Country associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_docuemntcountryid</td></tr></table>

### <a href=#documentLinkId name="documentLinkId">documentLinkId</a>

Unique identifier for Document Link associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document Link</td></tr><tr><td>description</td><td>Unique identifier for Document Link associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_documentlinkid</td></tr></table>

### <a href=#donorCommitmentId name="donorCommitmentId">donorCommitmentId</a>

Unique identifier for Donor Commitment associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Donor Commitment</td></tr><tr><td>description</td><td>Unique identifier for Donor Commitment associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_donorcommitmentid</td></tr></table>

### <a href=#entityName name="entityName">entityName</a>

Indicates the name of the entity  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Name</td></tr><tr><td>description</td><td>Indicates the name of the entity</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_entityname</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>453490003</td></tr><tr><td>en</td><td>Budget</td><td>453490004</td></tr><tr><td>en</td><td>Condition</td><td>453490005</td></tr><tr><td>en</td><td>Contact</td><td>453490006</td></tr><tr><td>en</td><td>Delivery Framework</td><td>453490007</td></tr><tr><td>en</td><td>Delivery Framework Description</td><td>453490008</td></tr><tr><td>en</td><td>Disbursement</td><td>453490009</td></tr><tr><td>en</td><td>Document Country</td><td>453490010</td></tr><tr><td>en</td><td>Document Link</td><td>453490011</td></tr><tr><td>en</td><td>Donor Commitment</td><td>453490012</td></tr><tr><td>en</td><td>Expenditure</td><td>453490013</td></tr><tr><td>en</td><td>Humanitarian Scope</td><td>453490014</td></tr><tr><td>en</td><td>Indicator</td><td>453490015</td></tr><tr><td>en</td><td>Indicator Value</td><td>453490016</td></tr><tr><td>en</td><td>Policy Marker</td><td>453490017</td></tr><tr><td>en</td><td>Result</td><td>453490019</td></tr><tr><td>en</td><td>Sector</td><td>453490018</td></tr><tr><td>en</td><td>Tag</td><td>453490020</td></tr><tr><td>en</td><td>Transaction</td><td>453490021</td></tr><tr><td>en</td><td>Location</td><td>453490000</td></tr><tr><td>en</td><td>Recipient Country</td><td>453490001</td></tr><tr><td>en</td><td>Recipient Region</td><td>453490002</td></tr></table></td></tr></table>

### <a href=#entityName_display name="entityName_display">entityName_display</a>

First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#expenditureId name="expenditureId">expenditureId</a>

Unique identifier for Expenditure associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expenditure</td></tr><tr><td>description</td><td>Unique identifier for Expenditure associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_expenditureid</td></tr></table>

### <a href=#humanitarianScopeId name="humanitarianScopeId">humanitarianScopeId</a>

Unique identifier for Humanitarian Scope associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Humanitarian Scope</td></tr><tr><td>description</td><td>Unique identifier for Humanitarian Scope associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_humanitarianscopeid</td></tr></table>

### <a href=#indicatorId name="indicatorId">indicatorId</a>

Unique identifier for Indicator associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Indicator</td></tr><tr><td>description</td><td>Unique identifier for Indicator associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_indicatorid</td></tr></table>

### <a href=#indicatorValueId name="indicatorValueId">indicatorValueId</a>

Unique identifier for Indicator Value associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Indicator Value</td></tr><tr><td>description</td><td>Unique identifier for Indicator Value associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_indicatorvalueid</td></tr></table>

### <a href=#languageId name="languageId">languageId</a>

Narrative languages  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language</td></tr><tr><td>description</td><td>Narrative languages</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_languageid</td></tr></table>

### <a href=#locationId name="locationId">locationId</a>

Unique identifier for Location associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Location</td></tr><tr><td>description</td><td>Unique identifier for Location associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_locationid</td></tr></table>

### <a href=#policyMakerId name="policyMakerId">policyMakerId</a>

Unique identifier for Policy Marker associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Policy Maker</td></tr><tr><td>description</td><td>Unique identifier for Policy Marker associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_policymakerid</td></tr></table>

### <a href=#recipientCountryId name="recipientCountryId">recipientCountryId</a>

Unique identifier for Recipient Country associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Country</td></tr><tr><td>description</td><td>Unique identifier for Recipient Country associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientcountryid</td></tr></table>

### <a href=#recipientRegionId name="recipientRegionId">recipientRegionId</a>

Unique identifier for Recipient Region associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Region</td></tr><tr><td>description</td><td>Unique identifier for Recipient Region associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientregionid</td></tr></table>

### <a href=#resultId name="resultId">resultId</a>

Unique identifier for Result associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Result</td></tr><tr><td>description</td><td>Unique identifier for Result associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_resultid</td></tr></table>

### <a href=#sectorId name="sectorId">sectorId</a>

Unique identifier for Sector associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sector</td></tr><tr><td>description</td><td>Unique identifier for Sector associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_sectorid</td></tr></table>

### <a href=#tagId name="tagId">tagId</a>

Unique identifier for Tag associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tag</td></tr><tr><td>description</td><td>Unique identifier for Tag associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_tagid</td></tr></table>

### <a href=#transactionId name="transactionId">transactionId</a>

Unique identifier for Transaction associated with Narrative Translation.  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction</td></tr><tr><td>description</td><td>Unique identifier for Transaction associated with Narrative Translation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_transactionid</td></tr></table>

### <a href=#translation name="translation">translation</a>

IATI's attribute translation  
First included in: nonProfit/NarrativeTranslation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Translation</td></tr><tr><td>description</td><td>IATI's attribute translation</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_translation</td></tr></table>

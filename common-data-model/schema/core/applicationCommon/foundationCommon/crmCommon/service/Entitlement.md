---
title: Entitlement - Common Data Model | Microsoft Docs
description: Defines the amount and type of support a customer should receive.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Entitlement

Defines the amount and type of support a customer should receive.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/Entitlement.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/Entitlement  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[entitlementId](#entitlementId)|Unique identifier for entity instances|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[emailAddress](#emailAddress)|The primary email address for the entity.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[name](#name)|Type a meaningful name for the entitlement.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[allocationTypeCode](#allocationTypeCode)|Select the type of entitlement terms.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[allocationTypeCode_display](#allocationTypeCode_display)||<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[description](#description)|Type additional information to describe the Entitlement|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[decreaseRemainingOn](#decreaseRemainingOn)|Select whether to decrease the remaining terms when the case is created or when it is resolved.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[decreaseRemainingOn_display](#decreaseRemainingOn_display)||<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[endDate](#endDate)|Enter the date when the entitlement ends.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[entitlementTemplateId](#entitlementTemplateId)|Unique identifier for Entitlement Template associated with Entitlement.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[kbAccessLevel](#kbAccessLevel)|Select the access someone will have to the knowledge base on the portal.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[kbAccessLevel_display](#kbAccessLevel_display)||<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[remainingTerms](#remainingTerms)|Type the total number of entitlement terms that are left.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[restrictCaseCreation](#restrictCaseCreation)|Tells whether case creation is restricted based on entitlement terms.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) associated with the entitlement.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[startDate](#startDate)|Enter the date when the entitlement starts.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[stateCode](#stateCode)|For internal use only.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[stateCode_display](#stateCode_display)||<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[statusCode](#statusCode)|Select the reason code that explains the status of the entitlement.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[statusCode_display](#statusCode_display)||<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[totalTerms](#totalTerms)|Type the total number of entitlement terms.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[isDefault](#isDefault)|Shows whether this entitlement is the default one for the specified customer.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[accountId](#accountId)|Unique identifier for Account associated with Entitlement.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[contactId](#contactId)|Unique identifier for Contact associated with Entitlement.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the contact with respect to the base currency.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the contact.|<a href="Entitlement.md" target="_blank">service/Entitlement</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#entitlementId name="entitlementId">entitlementId</a>

Unique identifier for entity instances  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entitlement</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>entitlementid</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

The primary email address for the entity.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address</td></tr><tr><td>description</td><td>The primary email address for the entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#name name="name">name</a>

Type a meaningful name for the entitlement.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entitlement Name</td></tr><tr><td>description</td><td>Type a meaningful name for the entitlement.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#allocationTypeCode name="allocationTypeCode">allocationTypeCode</a>

Select the type of entitlement terms.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allocation Type</td></tr><tr><td>description</td><td>Select the type of entitlement terms.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>allocationtypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Number of cases</td><td>0</td></tr><tr><td>en</td><td>Number of hours</td><td>1</td></tr></table></td></tr></table>

### <a href=#allocationTypeCode_display name="allocationTypeCode_display">allocationTypeCode_display</a>

First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the Entitlement  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the Entitlement</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#decreaseRemainingOn name="decreaseRemainingOn">decreaseRemainingOn</a>

Select whether to decrease the remaining terms when the case is created or when it is resolved.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Decrease Remaining On</td></tr><tr><td>description</td><td>Select whether to decrease the remaining terms when the case is created or when it is resolved.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>decreaseremainingon</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Case Resolution</td><td>0</td></tr><tr><td>en</td><td>Case Creation</td><td>1</td></tr></table></td></tr></table>

### <a href=#decreaseRemainingOn_display name="decreaseRemainingOn_display">decreaseRemainingOn_display</a>

First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#endDate name="endDate">endDate</a>

Enter the date when the entitlement ends.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>description</td><td>Enter the date when the entitlement ends.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>enddate</td></tr></table>

### <a href=#entitlementTemplateId name="entitlementTemplateId">entitlementTemplateId</a>

Unique identifier for Entitlement Template associated with Entitlement.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entitlement Template</td></tr><tr><td>description</td><td>Unique identifier for Entitlement Template associated with Entitlement.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entitlementtemplateid</td></tr></table>

### <a href=#kbAccessLevel name="kbAccessLevel">kbAccessLevel</a>

Select the access someone will have to the knowledge base on the portal.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KB Access Level</td></tr><tr><td>description</td><td>Select the access someone will have to the knowledge base on the portal.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>kbaccesslevel</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Standard</td><td>0</td></tr><tr><td>en</td><td>Premium</td><td>1</td></tr><tr><td>en</td><td>None</td><td>2</td></tr></table></td></tr></table>

### <a href=#kbAccessLevel_display name="kbAccessLevel_display">kbAccessLevel_display</a>

First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#remainingTerms name="remainingTerms">remainingTerms</a>

Type the total number of entitlement terms that are left.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Terms</td></tr><tr><td>description</td><td>Type the total number of entitlement terms that are left.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>remainingterms</td></tr></table>

### <a href=#restrictCaseCreation name="restrictCaseCreation">restrictCaseCreation</a>

Tells whether case creation is restricted based on entitlement terms.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Restrict based on entitlement terms</td></tr><tr><td>description</td><td>Tells whether case creation is restricted based on entitlement terms.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>restrictcasecreation</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) associated with the entitlement.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) associated with the entitlement.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#startDate name="startDate">startDate</a>

Enter the date when the entitlement starts.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Enter the date when the entitlement starts.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>startdate</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

For internal use only.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>0</td></tr><tr><td>en</td><td>Active</td><td>1</td></tr><tr><td>en</td><td>Cancelled</td><td>2</td></tr><tr><td>en</td><td>Expired</td><td>3</td></tr><tr><td>en</td><td>Waiting</td><td>4</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the reason code that explains the status of the entitlement.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Code</td></tr><tr><td>description</td><td>Select the reason code that explains the status of the entitlement.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Active</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Cancelled</td><td>2</td><td>2</td></tr><tr><td>en</td><td>Expired</td><td>3</td><td>3</td></tr><tr><td>en</td><td>Waiting</td><td>1200</td><td>4</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#totalTerms name="totalTerms">totalTerms</a>

Type the total number of entitlement terms.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Terms</td></tr><tr><td>description</td><td>Type the total number of entitlement terms.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalterms</td></tr></table>

### <a href=#isDefault name="isDefault">isDefault</a>

Shows whether this entitlement is the default one for the specified customer.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Default</td></tr><tr><td>description</td><td>Shows whether this entitlement is the default one for the specified customer.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isdefault</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Unique identifier for Account associated with Entitlement.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Entitlement.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountid</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Unique identifier for Contact associated with Entitlement.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Unique identifier for Contact associated with Entitlement.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contactid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the contact with respect to the base currency.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the contact with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the contact.  
First included in: service/Entitlement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the contact.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

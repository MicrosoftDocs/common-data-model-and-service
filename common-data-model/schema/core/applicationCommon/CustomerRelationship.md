---
title: CustomerRelationship - Common Data Model | Microsoft Docs
description: Relationship between a customer and a partner in which either can be an account or contact.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Customer Relationship

Relationship between a customer and a partner in which either can be an account or contact.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/CustomerRelationship.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /CustomerRelationship  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[versionNumber](#versionNumber)||<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[createdOn](#createdOn)|Shows the date and time when the customer relationship was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[modifiedOn](#modifiedOn)|Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[customerRoleId](#customerRoleId)|Choose the primary party's role or nature of the relationship the customer has with the second party. The field is read-only until both parties have been selected. Administrators can configure role values under Business Management in the Settings area.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[customerRelationshipId](#customerRelationshipId)|Unique identifier of the customer relationship.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[ownerId](#ownerId)|Owner Id|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[partnerIdType](#partnerIdType)|The type of partner, either Account or Contact.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[partnerId](#partnerId)|Select the secondary account or contact involved in the customer relationship.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier of the business unit that owns the customer relationship.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[converseRelationshipId](#converseRelationshipId)|Unique identifier of the converse relationship of the customer relationship.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[partnerRoleId](#partnerRoleId)|Choose the secondary party's role or nature of the relationship the customer has with the primary party. The field is read-only until both parties have been selected. Administrators can configure role values under Business Management in the Settings area.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[customerRoleDescription](#customerRoleDescription)|Type additional information about the primary party's role in the customer relationship, such as the length or quality of the relationship.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[partnerRoleDescription](#partnerRoleDescription)|Type additional information about the secondary party's role in the customer relationship, such as the length or quality of the relationship.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[owningUser](#owningUser)|Unique identifier of the user who owns the customer relationship.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|
|[owningTeam](#owningTeam)|Unique identifier of the team who owns the customer relationship.|<a href="CustomerRelationship.md" target="_blank">applicationCommon/CustomerRelationship</a>|

### <a href=#versionNumber name="versionNumber">versionNumber</a>

First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Shows the date and time when the customer relationship was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Shows the date and time when the customer relationship was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#customerRoleId name="customerRoleId">customerRoleId</a>

Choose the primary party's role or nature of the relationship the customer has with the second party. The field is read-only until both parties have been selected. Administrators can configure role values under Business Management in the Settings area.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role 1</td></tr><tr><td>description</td><td>Choose the primary party's role or nature of the relationship the customer has with the second party. The field is read-only until both parties have been selected. Administrators can configure role values under Business Management in the Settings area.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerroleid</td></tr></table>

### <a href=#customerRelationshipId name="customerRelationshipId">customerRelationshipId</a>

Unique identifier of the customer relationship.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Relationship</td></tr><tr><td>description</td><td>Unique identifier of the customer relationship.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>customerrelationshipid</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#partnerIdType name="partnerIdType">partnerIdType</a>

The type of partner, either Account or Contact.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Partner Type</td></tr><tr><td>description</td><td>The type of partner, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>partneridtype</td></tr></table>

### <a href=#partnerId name="partnerId">partnerId</a>

Select the secondary account or contact involved in the customer relationship.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Party 2</td></tr><tr><td>description</td><td>Select the secondary account or contact involved in the customer relationship.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>partnerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier of the business unit that owns the customer relationship.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit that owns the customer relationship.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#converseRelationshipId name="converseRelationshipId">converseRelationshipId</a>

Unique identifier of the converse relationship of the customer relationship.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Converse Relationship</td></tr><tr><td>description</td><td>Unique identifier of the converse relationship of the customer relationship.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>converserelationshipid</td></tr></table>

### <a href=#partnerRoleId name="partnerRoleId">partnerRoleId</a>

Choose the secondary party's role or nature of the relationship the customer has with the primary party. The field is read-only until both parties have been selected. Administrators can configure role values under Business Management in the Settings area.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role 2</td></tr><tr><td>description</td><td>Choose the secondary party's role or nature of the relationship the customer has with the primary party. The field is read-only until both parties have been selected. Administrators can configure role values under Business Management in the Settings area.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>partnerroleid</td></tr></table>

### <a href=#customerRoleDescription name="customerRoleDescription">customerRoleDescription</a>

Type additional information about the primary party's role in the customer relationship, such as the length or quality of the relationship.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description 1</td></tr><tr><td>description</td><td>Type additional information about the primary party's role in the customer relationship, such as the length or quality of the relationship.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerroledescription</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#partnerRoleDescription name="partnerRoleDescription">partnerRoleDescription</a>

Type additional information about the secondary party's role in the customer relationship, such as the length or quality of the relationship.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description 2</td></tr><tr><td>description</td><td>Type additional information about the secondary party's role in the customer relationship, such as the length or quality of the relationship.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>partnerroledescription</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user who owns the customer relationship.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user who owns the customer relationship.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier of the team who owns the customer relationship.  
First included in: applicationCommon/CustomerRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier of the team who owns the customer relationship.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

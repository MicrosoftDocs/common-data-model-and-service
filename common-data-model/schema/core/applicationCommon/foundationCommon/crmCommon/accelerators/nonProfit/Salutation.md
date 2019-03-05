---
title: Salutation - Common Data Model | Microsoft Docs
description: This describes the Salutation entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Salutation

The way a donor or prospect is commonly addressed via written communication (lhard-copy letters, emails, etc.).  It is typical for nonprofits and foundations to address major donors by different salutations depending on the scenario.  A Medical Doctor could be addressed as "Doctor" when the organization reaches out regarding in-country field volunteerism the person performs.  On the other hand, the same individual might be referred to as Mrs. Smith as part of her household being solicited for a major gift.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Salutation.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/Salutation  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[salutationId](#salutationId)|Unique identifier for entity instances|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[stateCode](#stateCode)|Status of the Salutation|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[stateCode_display](#stateCode_display)||<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[statusCode](#statusCode)|Reason for the status of the Salutation|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[statusCode_display](#statusCode_display)||<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[name](#name)||<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[addressLabelLine1](#addressLabelLine1)|The first line of the address label when printing an envelope
>Mr John Smith
Mrs Wilma Smith
1234 Main Street
Anytown, USA 11111|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[addressLabelLine2](#addressLabelLine2)|This is the 2nd line of the envelope usually the 2nd person in the household if applicable
Mr John Smith
>Mrs Wilma Smith
1234 Main Street
Anytown, USA 11111|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[addressLabelLine3](#addressLabelLine3)|This is the 3rd line of the address which could be an Organization name or a C/O
Mr John Smith
Mrs Wilma Smith c/o Anytown Company
1234 Main Street
Anytown, USA 11111|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[communicationMethod](#communicationMethod)|Indicates that this Salutation should be applied when the Customer is contacted via the indicated communication channel|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[communicationMethod_display](#communicationMethod_display)||<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[constituentType](#constituentType)|Indicates that this Salutation should be applied when the Customer is contacted in their capacity as the indicated ConstituentType|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[constituentType_display](#constituentType_display)||<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[firstName](#firstName)|First Name|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[fullName](#fullName)|Full Name|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[insideSalutation](#insideSalutation)|This is the information that appears after the word Dear on the letter sent to the donor.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[isPreferred](#isPreferred)|Indicates that this Salutation may be applied by business logic when matches on other selection criteria (Comm. method, Account, Constituent Type) are not found.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[lastName](#lastName)|Last Name|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[middleName](#middleName)|Middle Name|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[onBehalfOfAccount](#onBehalfOfAccount)|Indicates that this Salutation should be applied when the Customer is contacted in the capacity of their role on the indicated Account.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[salutationCustomer](#salutationCustomer)||<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[suffix](#suffix)|Suffix|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[suffix_display](#suffix_display)||<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[title](#title)|Prefix|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[title_display](#title_display)||<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[type](#type)|Indicates that this Salutation should be applied when the Customer is contacted for the indicated category of mailing or acknowledgement.|<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|
|[type_display](#type_display)||<a href="Salutation.md" target="_blank">nonProfit/Salutation</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#salutationId name="salutationId">salutationId</a>

Unique identifier for entity instances  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Salutation</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_salutationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Salutation  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Salutation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Salutation  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Salutation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#addressLabelLine1 name="addressLabelLine1">addressLabelLine1</a>

The first line of the address label when printing an envelope
>Mr John Smith
Mrs Wilma Smith
1234 Main Street
Anytown, USA 11111  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Label Line 1</td></tr><tr><td>description</td><td>The first line of the address label when printing an envelope
>Mr John Smith
Mrs Wilma Smith
1234 Main Street
Anytown, USA 11111</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_addresslabelline1</td></tr></table>

### <a href=#addressLabelLine2 name="addressLabelLine2">addressLabelLine2</a>

This is the 2nd line of the envelope usually the 2nd person in the household if applicable
Mr John Smith
>Mrs Wilma Smith
1234 Main Street
Anytown, USA 11111  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Label Line 2</td></tr><tr><td>description</td><td>This is the 2nd line of the envelope usually the 2nd person in the household if applicable
Mr John Smith
>Mrs Wilma Smith
1234 Main Street
Anytown, USA 11111</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_addresslabelline2</td></tr></table>

### <a href=#addressLabelLine3 name="addressLabelLine3">addressLabelLine3</a>

This is the 3rd line of the address which could be an Organization name or a C/O
Mr John Smith
Mrs Wilma Smith c/o Anytown Company
1234 Main Street
Anytown, USA 11111  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Label Line 3</td></tr><tr><td>description</td><td>This is the 3rd line of the address which could be an Organization name or a C/O
Mr John Smith
Mrs Wilma Smith c/o Anytown Company
1234 Main Street
Anytown, USA 11111</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_addresslabelline3</td></tr></table>

### <a href=#communicationMethod name="communicationMethod">communicationMethod</a>

Indicates that this Salutation should be applied when the Customer is contacted via the indicated communication channel  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Communication Method</td></tr><tr><td>description</td><td>Indicates that this Salutation should be applied when the Customer is contacted via the indicated communication channel</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_communicationmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>CommChannel</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#communicationMethod_display name="communicationMethod_display">communicationMethod_display</a>

First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#constituentType name="constituentType">constituentType</a>

Indicates that this Salutation should be applied when the Customer is contacted in their capacity as the indicated ConstituentType  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Constituent Type</td></tr><tr><td>description</td><td>Indicates that this Salutation should be applied when the Customer is contacted in their capacity as the indicated ConstituentType</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_constituenttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>ConstituentTypeOption</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#constituentType_display name="constituentType_display">constituentType_display</a>

First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#firstName name="firstName">firstName</a>

First Name  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Name</td></tr><tr><td>description</td><td>First Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_firstname</td></tr></table>

### <a href=#fullName name="fullName">fullName</a>

Full Name  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Full Name</td></tr><tr><td>description</td><td>Full Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_fullname</td></tr></table>

### <a href=#insideSalutation name="insideSalutation">insideSalutation</a>

This is the information that appears after the word Dear on the letter sent to the donor.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inside Salutation</td></tr><tr><td>description</td><td>This is the information that appears after the word Dear on the letter sent to the donor.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insidesalutation</td></tr></table>

### <a href=#isPreferred name="isPreferred">isPreferred</a>

Indicates that this Salutation may be applied by business logic when matches on other selection criteria (Comm. method, Account, Constituent Type) are not found.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred</td></tr><tr><td>description</td><td>Indicates that this Salutation may be applied by business logic when matches on other selection criteria (Comm. method, Account, Constituent Type) are not found.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_ispreferred</td></tr></table>

### <a href=#lastName name="lastName">lastName</a>

Last Name  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Name</td></tr><tr><td>description</td><td>Last Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_lastname</td></tr></table>

### <a href=#middleName name="middleName">middleName</a>

Middle Name  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Middle Name</td></tr><tr><td>description</td><td>Middle Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_middlename</td></tr></table>

### <a href=#onBehalfOfAccount name="onBehalfOfAccount">onBehalfOfAccount</a>

Indicates that this Salutation should be applied when the Customer is contacted in the capacity of their role on the indicated Account.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Behalf Of Account</td></tr><tr><td>description</td><td>Indicates that this Salutation should be applied when the Customer is contacted in the capacity of their role on the indicated Account.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_onbehalfofaccount</td></tr></table>

### <a href=#salutationCustomer name="salutationCustomer">salutationCustomer</a>

First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_salutation_customer</td></tr></table>

### <a href=#suffix name="suffix">suffix</a>

Suffix  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Suffix</td></tr><tr><td>description</td><td>Suffix</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_suffix</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Jr.
Sr.</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#suffix_display name="suffix_display">suffix_display</a>

First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#title name="title">title</a>

Prefix  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Prefix</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_title</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Mr.
Mrs.
Dr.
Prof.
Ms.</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#title_display name="title_display">title_display</a>

First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#type name="type">type</a>

Indicates that this Salutation should be applied when the Customer is contacted for the indicated category of mailing or acknowledgement.  
First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Indicates that this Salutation should be applied when the Customer is contacted for the indicated category of mailing or acknowledgement.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Abbreviated</td><td>100000000</td></tr><tr><td>en</td><td>Annual Report Listing</td><td>100000001</td></tr><tr><td>en</td><td>Campaign Listing</td><td>100000002</td></tr><tr><td>en</td><td>Donor Wall recognition</td><td>100000003</td></tr><tr><td>en</td><td>Expanded in Detail</td><td>100000004</td></tr><tr><td>en</td><td>Formal Name</td><td>100000005</td></tr><tr><td>en</td><td>Informal Name</td><td>100000006</td></tr><tr><td>en</td><td>Major Donor Correspondence</td><td>100000007</td></tr><tr><td>en</td><td>Name Tag at Meeting Event</td><td>100000008</td></tr><tr><td>en</td><td>Other</td><td>100000009</td></tr><tr><td>en</td><td>Public Tribute</td><td>100000010</td></tr><tr><td>en</td><td>Tax Statement</td><td>100000011</td></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: nonProfit/Salutation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

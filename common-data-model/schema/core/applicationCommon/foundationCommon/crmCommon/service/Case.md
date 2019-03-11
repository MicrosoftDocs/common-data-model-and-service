---
title: Case - Common Data Model | Microsoft Docs
description: Service request case associated with a contract.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Case

Service request case associated with a contract.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/Case  
- [/foundationCommon/crmCommon/solutions/portals/Case](../solutions/portals/Case.md "/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Case.md" target="_blank">service/Case</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Case.md" target="_blank">service/Case</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Case.md" target="_blank">service/Case</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Case.md" target="_blank">service/Case</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Case.md" target="_blank">service/Case</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Case.md" target="_blank">service/Case</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Case.md" target="_blank">service/Case</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Case.md" target="_blank">service/Case</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Case.md" target="_blank">service/Case</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Case.md" target="_blank">service/Case</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Case.md" target="_blank">service/Case</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Case.md" target="_blank">service/Case</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Case.md" target="_blank">service/Case</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Case.md" target="_blank">service/Case</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Case.md" target="_blank">service/Case</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Case.md" target="_blank">service/Case</a>|
|[incidentId](#incidentId)|Unique identifier of the case.|<a href="Case.md" target="_blank">service/Case</a>|
|[emailAddress](#emailAddress)|The primary email address for the entity.|<a href="Case.md" target="_blank">service/Case</a>|
|[title](#title)|Type a subject or descriptive name, such as the request, issue, or company name, to identify the case in Microsoft Dynamics 365 views.|<a href="Case.md" target="_blank">service/Case</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="Case.md" target="_blank">service/Case</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="Case.md" target="_blank">service/Case</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="Case.md" target="_blank">service/Case</a>|
|[activitiesComplete](#activitiesComplete)|This attribute is used for Sample Service Business Processes.|<a href="Case.md" target="_blank">service/Case</a>|
|[actualServiceUnits](#actualServiceUnits)|Type the number of service units that were actually required to resolve the case.|<a href="Case.md" target="_blank">service/Case</a>|
|[billedServiceUnits](#billedServiceUnits)|Type the number of service units that were billed to the customer for the case.|<a href="Case.md" target="_blank">service/Case</a>|
|[blockedProfile](#blockedProfile)|Details whether the profile is blocked or not.|<a href="Case.md" target="_blank">service/Case</a>|
|[caseOriginCode](#caseOriginCode)|Select how contact about the case was originated, such as email, phone, or web, for use in reporting and analysis.|<a href="Case.md" target="_blank">service/Case</a>|
|[caseOriginCode_display](#caseOriginCode_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[caseTypeCode](#caseTypeCode)|Select the type of case to identify the incident for use in case routing and analysis.|<a href="Case.md" target="_blank">service/Case</a>|
|[caseTypeCode_display](#caseTypeCode_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[checkEmail](#checkEmail)|This attribute is used for Sample Service Business Processes.|<a href="Case.md" target="_blank">service/Case</a>|
|[contractDetailId](#contractDetailId)|Choose the contract line that the case should be logged under to make sure the customer is charged correctly.|<a href="Case.md" target="_blank">service/Case</a>|
|[contractId](#contractId)|Choose the service contract that the case should be logged under to make sure the customer is eligible for support services.|<a href="Case.md" target="_blank">service/Case</a>|
|[contractServiceLevelCode](#contractServiceLevelCode)|Select the service level for the case to make sure the case is handled correctly.|<a href="Case.md" target="_blank">service/Case</a>|
|[contractServiceLevelCode_display](#contractServiceLevelCode_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="Case.md" target="_blank">service/Case</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="Case.md" target="_blank">service/Case</a>|
|[customerSatisfactionCode](#customerSatisfactionCode)|Select the customer's level of satisfaction with the handling and resolution of the case.|<a href="Case.md" target="_blank">service/Case</a>|
|[customerSatisfactionCode_display](#customerSatisfactionCode_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[description](#description)|Type additional information to describe the case to assist the service team in reaching a resolution.|<a href="Case.md" target="_blank">service/Case</a>|
|[entitlementId](#entitlementId)|Choose the entitlement that is applicable for the case.|<a href="Case.md" target="_blank">service/Case</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the case record.|<a href="Case.md" target="_blank">service/Case</a>|
|[firstResponseSLAStatus](#firstResponseSLAStatus)|Shows the status of the initial response time for the case according to the terms of the SLA.|<a href="Case.md" target="_blank">service/Case</a>|
|[firstResponseSLAStatus_display](#firstResponseSLAStatus_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[followupBy](#followupBy)|Enter the date by which a customer service representative has to follow up with the customer on this case.|<a href="Case.md" target="_blank">service/Case</a>|
|[followUpTaskCreated](#followUpTaskCreated)|This attribute is used for Sample Service Business Processes.|<a href="Case.md" target="_blank">service/Case</a>|
|[incidentStageCode](#incidentStageCode)|Select the current stage of the service process for the case to assist service team members when they review or transfer a case.|<a href="Case.md" target="_blank">service/Case</a>|
|[incidentStageCode_display](#incidentStageCode_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[isDecrementing](#isDecrementing)|For system use only.|<a href="Case.md" target="_blank">service/Case</a>|
|[kbArticleId](#kbArticleId)|Choose the article that contains additional information or a resolution for the case, for reference during research or follow up with the customer.|<a href="Case.md" target="_blank">service/Case</a>|
|[messageTypeCode](#messageTypeCode)|Shows whether the post originated as a public or private message.|<a href="Case.md" target="_blank">service/Case</a>|
|[messageTypeCode_display](#messageTypeCode_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[priorityCode](#priorityCode)|Select the priority so that preferred customers or critical issues are handled quickly.|<a href="Case.md" target="_blank">service/Case</a>|
|[priorityCode_display](#priorityCode_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[productId](#productId)|Choose the product associated with the case to identify warranty, service, or other product issues and be able to report the number of incidents for each product.|<a href="Case.md" target="_blank">service/Case</a>|
|[productSerialNumber](#productSerialNumber)|Type the serial number of the product that is associated with this case, so that the number of cases per product can be reported.|<a href="Case.md" target="_blank">service/Case</a>|
|[existingCase](#existingCase)|Select an existing case for the customer that has been populated. For internal use only.|<a href="Case.md" target="_blank">service/Case</a>|
|[resolveBySLAStatus](#resolveBySLAStatus)|Shows the status of the resolution time for the case according to the terms of the SLA.|<a href="Case.md" target="_blank">service/Case</a>|
|[resolveBySLAStatus_display](#resolveBySLAStatus_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[responsibleContactId](#responsibleContactId)|Choose an additional customer contact who can also help resolve the case.|<a href="Case.md" target="_blank">service/Case</a>|
|[sentimentValue](#sentimentValue)|Value derived after assessing words commonly associated with a negative, neutral, or positive sentiment that occurs in a social post. Sentiment information can also be reported as numeric values.|<a href="Case.md" target="_blank">service/Case</a>|
|[influenceScore](#influenceScore)|Will contain the Influencer score coming from NetBreeze.|<a href="Case.md" target="_blank">service/Case</a>|
|[serviceStage](#serviceStage)|Select the stage, in the case resolution process, that the case is in.|<a href="Case.md" target="_blank">service/Case</a>|
|[serviceStage_display](#serviceStage_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[severityCode](#severityCode)|Select the severity of this case to indicate the incident's impact on the customer's business.|<a href="Case.md" target="_blank">service/Case</a>|
|[severityCode_display](#severityCode_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this case. This field is for internal use only.|<a href="Case.md" target="_blank">service/Case</a>|
|[socialProfileId](#socialProfileId)|Unique identifier of the social profile with which the case is associated.|<a href="Case.md" target="_blank">service/Case</a>|
|[stateCode](#stateCode)|Shows whether the case is active, resolved, or canceled. Resolved and canceled cases are read-only and can't be edited unless they are reactivated.|<a href="Case.md" target="_blank">service/Case</a>|
|[stateCode_display](#stateCode_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[statusCode](#statusCode)|Select the case's status.|<a href="Case.md" target="_blank">service/Case</a>|
|[statusCode_display](#statusCode_display)||<a href="Case.md" target="_blank">service/Case</a>|
|[subjectId](#subjectId)|Choose the subject for the case, such as catalog request or product complaint, so customer service managers can identify frequent requests or problem areas. Administrators can configure subjects under Business Management in the Settings area.|<a href="Case.md" target="_blank">service/Case</a>|
|[ticketNumber](#ticketNumber)|Shows the case number for customer reference and searching capabilities. This cannot be modified.|<a href="Case.md" target="_blank">service/Case</a>|
|[masterId](#masterId)|Choose the primary case the current case was merged into.|<a href="Case.md" target="_blank">service/Case</a>|
|[parentCaseId](#parentCaseId)|Choose the parent case for a case.|<a href="Case.md" target="_blank">service/Case</a>|
|[numberOfChildIncidents](#numberOfChildIncidents)|Number of child incidents associated with the incident.|<a href="Case.md" target="_blank">service/Case</a>|
|[merged](#merged)|Tells whether the incident has been merged with another incident.|<a href="Case.md" target="_blank">service/Case</a>|
|[routeCase](#routeCase)|Tells whether the incident has been routed to queue or not.|<a href="Case.md" target="_blank">service/Case</a>|
|[resolveBy](#resolveBy)|Enter the date by when the case must be resolved.|<a href="Case.md" target="_blank">service/Case</a>|
|[responseBy](#responseBy)|For internal use only.|<a href="Case.md" target="_blank">service/Case</a>|
|[customerContacted](#customerContacted)|Tells whether customer service representative has contacted the customer or not.|<a href="Case.md" target="_blank">service/Case</a>|
|[firstResponseSent](#firstResponseSent)|Indicates if the first response has been sent.|<a href="Case.md" target="_blank">service/Case</a>|
|[isEscalated](#isEscalated)|Indicates if the case has been escalated.|<a href="Case.md" target="_blank">service/Case</a>|
|[escalatedOn](#escalatedOn)|Indicates the date and time when the case was escalated.|<a href="Case.md" target="_blank">service/Case</a>|
|[primaryContactId](#primaryContactId)|Select a primary contact for this case.|<a href="Case.md" target="_blank">service/Case</a>|
|[onHoldTime](#onHoldTime)|Shows the duration in minutes for which the case was on hold.|<a href="Case.md" target="_blank">service/Case</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date time stamp of the last on hold time.|<a href="Case.md" target="_blank">service/Case</a>|
|[resolveByKPIId](#resolveByKPIId)|For internal use only.|<a href="Case.md" target="_blank">service/Case</a>|
|[firstResponseByKPIId](#firstResponseByKPIId)|For internal use only.|<a href="Case.md" target="_blank">service/Case</a>|
|[decrementEntitlementTerm](#decrementEntitlementTerm)|Shows whether terms of the associated entitlement should be decremented or not.|<a href="Case.md" target="_blank">service/Case</a>|
|[entityImageId](#entityImageId)||<a href="Case.md" target="_blank">service/Case</a>|
|[accountId](#accountId)|Unique identifier of the account with which the case is associated.|<a href="Case.md" target="_blank">service/Case</a>|
|[contactId](#contactId)|Unique identifier of the contact associated with the case.|<a href="Case.md" target="_blank">service/Case</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="Case.md" target="_blank">service/Case</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="Case.md" target="_blank">service/Case</a>|
|[createdByExternalParty](#createdByExternalParty)|Shows the external party who created the record.|<a href="Case.md" target="_blank">service/Case</a>|
|[modifiedByExternalParty](#modifiedByExternalParty)|Shows the external party who modified the record.|<a href="Case.md" target="_blank">service/Case</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#incidentId name="incidentId">incidentId</a>

Unique identifier of the case.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Case</td></tr><tr><td>description</td><td>Unique identifier of the case.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>incidentid</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

The primary email address for the entity.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address</td></tr><tr><td>description</td><td>The primary email address for the entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#title name="title">title</a>

Type a subject or descriptive name, such as the request, issue, or company name, to identify the case in Microsoft Dynamics 365 views.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Case Title</td></tr><tr><td>description</td><td>Type a subject or descriptive name, such as the request, issue, or company name, to identify the case in Microsoft Dynamics 365 views.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#activitiesComplete name="activitiesComplete">activitiesComplete</a>

This attribute is used for Sample Service Business Processes.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activities Complete</td></tr><tr><td>description</td><td>This attribute is used for Sample Service Business Processes.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>activitiescomplete</td></tr></table>

### <a href=#actualServiceUnits name="actualServiceUnits">actualServiceUnits</a>

Type the number of service units that were actually required to resolve the case.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Service Units</td></tr><tr><td>description</td><td>Type the number of service units that were actually required to resolve the case.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualserviceunits</td></tr></table>

### <a href=#billedServiceUnits name="billedServiceUnits">billedServiceUnits</a>

Type the number of service units that were billed to the customer for the case.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billed Service Units</td></tr><tr><td>description</td><td>Type the number of service units that were billed to the customer for the case.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billedserviceunits</td></tr></table>

### <a href=#blockedProfile name="blockedProfile">blockedProfile</a>

Details whether the profile is blocked or not.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Blocked Profile</td></tr><tr><td>description</td><td>Details whether the profile is blocked or not.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>blockedprofile</td></tr></table>

### <a href=#caseOriginCode name="caseOriginCode">caseOriginCode</a>

Select how contact about the case was originated, such as email, phone, or web, for use in reporting and analysis.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Origin</td></tr><tr><td>description</td><td>Select how contact about the case was originated, such as email, phone, or web, for use in reporting and analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>caseorigincode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Phone</td><td>1</td></tr><tr><td>en</td><td>Email</td><td>2</td></tr><tr><td>en</td><td>Web</td><td>3</td></tr><tr><td>en</td><td>Facebook</td><td>2483</td></tr><tr><td>en</td><td>Twitter</td><td>3986</td></tr></table></td></tr></table>

### <a href=#caseOriginCode_display name="caseOriginCode_display">caseOriginCode_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#caseTypeCode name="caseTypeCode">caseTypeCode</a>

Select the type of case to identify the incident for use in case routing and analysis.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Case Type</td></tr><tr><td>description</td><td>Select the type of case to identify the incident for use in case routing and analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>casetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Question</td><td>1</td></tr><tr><td>en</td><td>Problem</td><td>2</td></tr><tr><td>en</td><td>Request</td><td>3</td></tr></table></td></tr></table>

### <a href=#caseTypeCode_display name="caseTypeCode_display">caseTypeCode_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#checkEmail name="checkEmail">checkEmail</a>

This attribute is used for Sample Service Business Processes.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check Email</td></tr><tr><td>description</td><td>This attribute is used for Sample Service Business Processes.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>checkemail</td></tr></table>

### <a href=#contractDetailId name="contractDetailId">contractDetailId</a>

Choose the contract line that the case should be logged under to make sure the customer is charged correctly.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Line</td></tr><tr><td>description</td><td>Choose the contract line that the case should be logged under to make sure the customer is charged correctly.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contractdetailid</td></tr></table>

### <a href=#contractId name="contractId">contractId</a>

Choose the service contract that the case should be logged under to make sure the customer is eligible for support services.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract</td></tr><tr><td>description</td><td>Choose the service contract that the case should be logged under to make sure the customer is eligible for support services.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contractid</td></tr></table>

### <a href=#contractServiceLevelCode name="contractServiceLevelCode">contractServiceLevelCode</a>

Select the service level for the case to make sure the case is handled correctly.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service Level</td></tr><tr><td>description</td><td>Select the service level for the case to make sure the case is handled correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contractservicelevelcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Gold</td><td>1</td></tr><tr><td>en</td><td>Silver</td><td>2</td></tr><tr><td>en</td><td>Bronze</td><td>3</td></tr></table></td></tr></table>

### <a href=#contractServiceLevelCode_display name="contractServiceLevelCode_display">contractServiceLevelCode_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#customerSatisfactionCode name="customerSatisfactionCode">customerSatisfactionCode</a>

Select the customer's level of satisfaction with the handling and resolution of the case.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Satisfaction</td></tr><tr><td>description</td><td>Select the customer's level of satisfaction with the handling and resolution of the case.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customersatisfactioncode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Very Satisfied</td><td>5</td></tr><tr><td>en</td><td>Satisfied</td><td>4</td></tr><tr><td>en</td><td>Neutral</td><td>3</td></tr><tr><td>en</td><td>Dissatisfied</td><td>2</td></tr><tr><td>en</td><td>Very Dissatisfied</td><td>1</td></tr></table></td></tr></table>

### <a href=#customerSatisfactionCode_display name="customerSatisfactionCode_display">customerSatisfactionCode_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the case to assist the service team in reaching a resolution.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the case to assist the service team in reaching a resolution.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#entitlementId name="entitlementId">entitlementId</a>

Choose the entitlement that is applicable for the case.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entitlement</td></tr><tr><td>description</td><td>Choose the entitlement that is applicable for the case.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entitlementid</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the case record.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the case record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#firstResponseSLAStatus name="firstResponseSLAStatus">firstResponseSLAStatus</a>

Shows the status of the initial response time for the case according to the terms of the SLA.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Response SLA Status</td></tr><tr><td>description</td><td>Shows the status of the initial response time for the case according to the terms of the SLA.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>firstresponseslastatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>In Progress</td><td>1</td></tr><tr><td>en</td><td>Nearing Noncompliance</td><td>2</td></tr><tr><td>en</td><td>Succeeded</td><td>3</td></tr><tr><td>en</td><td>Noncompliant</td><td>4</td></tr></table></td></tr></table>

### <a href=#firstResponseSLAStatus_display name="firstResponseSLAStatus_display">firstResponseSLAStatus_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#followupBy name="followupBy">followupBy</a>

Enter the date by which a customer service representative has to follow up with the customer on this case.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Follow Up By</td></tr><tr><td>description</td><td>Enter the date by which a customer service representative has to follow up with the customer on this case.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>followupby</td></tr></table>

### <a href=#followUpTaskCreated name="followUpTaskCreated">followUpTaskCreated</a>

This attribute is used for Sample Service Business Processes.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Follow up Task Created</td></tr><tr><td>description</td><td>This attribute is used for Sample Service Business Processes.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>followuptaskcreated</td></tr></table>

### <a href=#incidentStageCode name="incidentStageCode">incidentStageCode</a>

Select the current stage of the service process for the case to assist service team members when they review or transfer a case.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Case Stage</td></tr><tr><td>description</td><td>Select the current stage of the service process for the case to assist service team members when they review or transfer a case.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>incidentstagecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#incidentStageCode_display name="incidentStageCode_display">incidentStageCode_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isDecrementing name="isDecrementing">isDecrementing</a>

For system use only.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Decrementing</td></tr><tr><td>description</td><td>For system use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isdecrementing</td></tr></table>

### <a href=#kbArticleId name="kbArticleId">kbArticleId</a>

Choose the article that contains additional information or a resolution for the case, for reference during research or follow up with the customer.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Knowledge Base Article</td></tr><tr><td>description</td><td>Choose the article that contains additional information or a resolution for the case, for reference during research or follow up with the customer.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>kbarticleid</td></tr></table>

### <a href=#messageTypeCode name="messageTypeCode">messageTypeCode</a>

Shows whether the post originated as a public or private message.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Received As</td></tr><tr><td>description</td><td>Shows whether the post originated as a public or private message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>messagetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#messageTypeCode_display name="messageTypeCode_display">messageTypeCode_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Select the priority so that preferred customers or critical issues are handled quickly.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Select the priority so that preferred customers or critical issues are handled quickly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>High</td><td>1</td></tr><tr><td>en</td><td>Normal</td><td>2</td></tr><tr><td>en</td><td>Low</td><td>3</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#productId name="productId">productId</a>

Choose the product associated with the case to identify warranty, service, or other product issues and be able to report the number of incidents for each product.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>Choose the product associated with the case to identify warranty, service, or other product issues and be able to report the number of incidents for each product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productid</td></tr></table>

### <a href=#productSerialNumber name="productSerialNumber">productSerialNumber</a>

Type the serial number of the product that is associated with this case, so that the number of cases per product can be reported.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Serial Number</td></tr><tr><td>description</td><td>Type the serial number of the product that is associated with this case, so that the number of cases per product can be reported.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productserialnumber</td></tr></table>

### <a href=#existingCase name="existingCase">existingCase</a>

Select an existing case for the customer that has been populated. For internal use only.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Existing Case</td></tr><tr><td>description</td><td>Select an existing case for the customer that has been populated. For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>existingcase</td></tr></table>

### <a href=#resolveBySLAStatus name="resolveBySLAStatus">resolveBySLAStatus</a>

Shows the status of the resolution time for the case according to the terms of the SLA.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resolve By SLA Status</td></tr><tr><td>description</td><td>Shows the status of the resolution time for the case according to the terms of the SLA.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resolvebyslastatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>In Progress</td><td>1</td></tr><tr><td>en</td><td>Nearing Noncompliance</td><td>2</td></tr><tr><td>en</td><td>Succeeded</td><td>3</td></tr><tr><td>en</td><td>Noncompliant</td><td>4</td></tr></table></td></tr></table>

### <a href=#resolveBySLAStatus_display name="resolveBySLAStatus_display">resolveBySLAStatus_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#responsibleContactId name="responsibleContactId">responsibleContactId</a>

Choose an additional customer contact who can also help resolve the case.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Responsible Contact</td></tr><tr><td>description</td><td>Choose an additional customer contact who can also help resolve the case.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>responsiblecontactid</td></tr></table>

### <a href=#sentimentValue name="sentimentValue">sentimentValue</a>

Value derived after assessing words commonly associated with a negative, neutral, or positive sentiment that occurs in a social post. Sentiment information can also be reported as numeric values.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sentiment Value</td></tr><tr><td>description</td><td>Value derived after assessing words commonly associated with a negative, neutral, or positive sentiment that occurs in a social post. Sentiment information can also be reported as numeric values.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sentimentvalue</td></tr></table>

### <a href=#influenceScore name="influenceScore">influenceScore</a>

Will contain the Influencer score coming from NetBreeze.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Influence Score</td></tr><tr><td>description</td><td>Will contain the Influencer score coming from NetBreeze.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>influencescore</td></tr></table>

### <a href=#serviceStage name="serviceStage">serviceStage</a>

Select the stage, in the case resolution process, that the case is in.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service Stage</td></tr><tr><td>description</td><td>Select the stage, in the case resolution process, that the case is in.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>servicestage</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Identify</td><td>0</td></tr><tr><td>en</td><td>Research</td><td>1</td></tr><tr><td>en</td><td>Resolve</td><td>2</td></tr></table></td></tr></table>

### <a href=#serviceStage_display name="serviceStage_display">serviceStage_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#severityCode name="severityCode">severityCode</a>

Select the severity of this case to indicate the incident's impact on the customer's business.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Severity</td></tr><tr><td>description</td><td>Select the severity of this case to indicate the incident's impact on the customer's business.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>severitycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#severityCode_display name="severityCode_display">severityCode_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this case. This field is for internal use only.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this case. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#socialProfileId name="socialProfileId">socialProfileId</a>

Unique identifier of the social profile with which the case is associated.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Profile</td></tr><tr><td>description</td><td>Unique identifier of the social profile with which the case is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>socialprofileid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the case is active, resolved, or canceled. Resolved and canceled cases are read-only and can't be edited unless they are reactivated.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the case is active, resolved, or canceled. Resolved and canceled cases are read-only and can't be edited unless they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Resolved</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the case's status.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the case's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Problem Solved</td><td>5</td><td>1</td></tr><tr><td>en</td><td>Information Provided</td><td>1000</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>6</td><td>2</td></tr><tr><td>en</td><td>Merged</td><td>2000</td><td>2</td></tr><tr><td>en</td><td>In Progress</td><td>1</td><td>0</td></tr><tr><td>en</td><td>On Hold</td><td>2</td><td>0</td></tr><tr><td>en</td><td>Waiting for Details</td><td>3</td><td>0</td></tr><tr><td>en</td><td>Researching</td><td>4</td><td>0</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectId name="subjectId">subjectId</a>

Choose the subject for the case, such as catalog request or product complaint, so customer service managers can identify frequent requests or problem areas. Administrators can configure subjects under Business Management in the Settings area.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Choose the subject for the case, such as catalog request or product complaint, so customer service managers can identify frequent requests or problem areas. Administrators can configure subjects under Business Management in the Settings area.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subjectid</td></tr></table>

### <a href=#ticketNumber name="ticketNumber">ticketNumber</a>

Shows the case number for customer reference and searching capabilities. This cannot be modified.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Case Number</td></tr><tr><td>description</td><td>Shows the case number for customer reference and searching capabilities. This cannot be modified.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ticketnumber</td></tr></table>

### <a href=#masterId name="masterId">masterId</a>

Choose the primary case the current case was merged into.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Master Case</td></tr><tr><td>description</td><td>Choose the primary case the current case was merged into.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>masterid</td></tr></table>

### <a href=#parentCaseId name="parentCaseId">parentCaseId</a>

Choose the parent case for a case.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Case</td></tr><tr><td>description</td><td>Choose the parent case for a case.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentcaseid</td></tr></table>

### <a href=#numberOfChildIncidents name="numberOfChildIncidents">numberOfChildIncidents</a>

Number of child incidents associated with the incident.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Child Cases</td></tr><tr><td>description</td><td>Number of child incidents associated with the incident.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>numberofchildincidents</td></tr></table>

### <a href=#merged name="merged">merged</a>

Tells whether the incident has been merged with another incident.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Internal Use Only</td></tr><tr><td>description</td><td>Tells whether the incident has been merged with another incident.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>merged</td></tr></table>

### <a href=#routeCase name="routeCase">routeCase</a>

Tells whether the incident has been routed to queue or not.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Route Case</td></tr><tr><td>description</td><td>Tells whether the incident has been routed to queue or not.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>routecase</td></tr></table>

### <a href=#resolveBy name="resolveBy">resolveBy</a>

Enter the date by when the case must be resolved.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resolve By</td></tr><tr><td>description</td><td>Enter the date by when the case must be resolved.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resolveby</td></tr></table>

### <a href=#responseBy name="responseBy">responseBy</a>

For internal use only.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Response By</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>responseby</td></tr></table>

### <a href=#customerContacted name="customerContacted">customerContacted</a>

Tells whether customer service representative has contacted the customer or not.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Contacted</td></tr><tr><td>description</td><td>Tells whether customer service representative has contacted the customer or not.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customercontacted</td></tr></table>

### <a href=#firstResponseSent name="firstResponseSent">firstResponseSent</a>

Indicates if the first response has been sent.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Response Sent</td></tr><tr><td>description</td><td>Indicates if the first response has been sent.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>firstresponsesent</td></tr></table>

### <a href=#isEscalated name="isEscalated">isEscalated</a>

Indicates if the case has been escalated.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Escalated</td></tr><tr><td>description</td><td>Indicates if the case has been escalated.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isescalated</td></tr></table>

### <a href=#escalatedOn name="escalatedOn">escalatedOn</a>

Indicates the date and time when the case was escalated.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Escalated On</td></tr><tr><td>description</td><td>Indicates the date and time when the case was escalated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>escalatedon</td></tr></table>

### <a href=#primaryContactId name="primaryContactId">primaryContactId</a>

Select a primary contact for this case.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Select a primary contact for this case.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primarycontactid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows the duration in minutes for which the case was on hold.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows the duration in minutes for which the case was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date time stamp of the last on hold time.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#resolveByKPIId name="resolveByKPIId">resolveByKPIId</a>

For internal use only.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resolve By KPI</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resolvebykpiid</td></tr></table>

### <a href=#firstResponseByKPIId name="firstResponseByKPIId">firstResponseByKPIId</a>

For internal use only.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Response By KPI</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>firstresponsebykpiid</td></tr></table>

### <a href=#decrementEntitlementTerm name="decrementEntitlementTerm">decrementEntitlementTerm</a>

Shows whether terms of the associated entitlement should be decremented or not.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Decrement Entitlement Terms</td></tr><tr><td>description</td><td>Shows whether terms of the associated entitlement should be decremented or not.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>decremententitlementterm</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Unique identifier of the account with which the case is associated.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier of the account with which the case is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountid</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Unique identifier of the contact associated with the case.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Unique identifier of the contact associated with the case.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contactid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#createdByExternalParty name="createdByExternalParty">createdByExternalParty</a>

Shows the external party who created the record.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdbyexternalparty</td></tr></table>

### <a href=#modifiedByExternalParty name="modifiedByExternalParty">modifiedByExternalParty</a>

Shows the external party who modified the record.  
First included in: service/Case (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedbyexternalparty</td></tr></table>

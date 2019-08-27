---
title: Campaign - Common Data Model | Microsoft Docs
description: This describes the Campaign entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Campaign

Container for campaign activities and responses, sales literature, products, and lists to create, plan, execute, and track the results of a specific marketing campaign through its life.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/Campaign.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/Campaign  
- [/foundationCommon/crmCommon/accelerators/nonProfit/Campaign](accelerators/nonProfit/Campaign.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Campaign.cdm.json/Campaign")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[campaignId](#campaignId)|Unique identifier of the campaign.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[emailAddress](#emailAddress)|The primary email address for the entity.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[name](#name)|Type a name for the campaign so that it is identified correctly in lists.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[actualEnd](#actualEnd)|Enter the date when the campaign was closed or completed.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[actualStart](#actualStart)|Enter the actual start date and time for the campaign.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[budgetedCost](#budgetedCost)|Type the amount budgeted for the campaign to define a limit for how much you can spend.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[budgetedCostBase](#budgetedCostBase)|Value of the Budget Allocated in base currency.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[codeName](#codeName)|Type a number or other tracking code to identify the campaign. If no value is entered, a code will be generated automatically.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[description](#description)|Type additional information to describe the campaign, such as the products or services offered or the targeted audience.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[expectedResponse](#expectedResponse)|Type the expected response rate for the campaign as a full number between 0 and 100.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[expectedRevenue](#expectedRevenue)|Type the expected revenue for the campaign for return on investment projections and post-campaign reporting.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[expectedRevenueBase](#expectedRevenueBase)|Value of the Estimated Revenue in base currency.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[isTemplate](#isTemplate)|Select whether the campaign is a template that can be copied when you create future campaigns.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[message](#message)|Type the promotional message or marketing copy for the campaign.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[objective](#objective)|Type the objective of the campaign, including products, services, discounts, and pricing.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[otherCost](#otherCost)|Type the sum of any miscellaneous campaign costs not included in the campaign activities to make sure the actual cost of the campaign is calculated correctly.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[otherCostBase](#otherCostBase)|Value of the Miscellaneous Costs in base currency.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[promotionCodeName](#promotionCodeName)|Type a promotional code to track sales related to the campaign or allow customers to redeem a discount offer.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[proposedEnd](#proposedEnd)|Enter the date when the campaign is scheduled to end.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[proposedStart](#proposedStart)|Enter the date when the campaign is scheduled to start.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[stateCode](#stateCode)|Shows the status of the campaign. By default, campaigns are active and can't be deactivated.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[stateCode_display](#stateCode_display)||<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[statusCode](#statusCode)|Select the campaign's status.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[statusCode_display](#statusCode_display)||<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[totalActualCost](#totalActualCost)|Shows the sum of the amounts entered in the Total Cost of Campaign Activities and Miscellaneous Costs fields.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[totalActualCostBase](#totalActualCostBase)|Value of the Total Cost of Campaign in base currency.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[totalCampaignActivityActualCost](#totalCampaignActivityActualCost)|Shows the sum of the values entered in the Actual Cost field on all campaign activities related to the campaign.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[totalCampaignActivityActualCostBase](#totalCampaignActivityActualCostBase)|Value of the Total Cost of Campaign Activities in base currency.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[typeCode](#typeCode)|Select the type of the campaign.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[typeCode_display](#typeCode_display)||<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[priceListId](#priceListId)|Choose the price list associated with this item to make sure the products associated with the campaign are offered at the correct prices.|<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|
|[entityImageId](#entityImageId)||<a href="Campaign.md" target="_blank">crmCommon/Campaign</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#campaignId name="campaignId">campaignId</a>

Unique identifier of the campaign.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Campaign</td></tr><tr><td>description</td><td>Unique identifier of the campaign.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>campaignid</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

The primary email address for the entity.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address</td></tr><tr><td>description</td><td>The primary email address for the entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#name name="name">name</a>

Type a name for the campaign so that it is identified correctly in lists.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a name for the campaign so that it is identified correctly in lists.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Enter the date when the campaign was closed or completed.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End Date</td></tr><tr><td>description</td><td>Enter the date when the campaign was closed or completed.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualend</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Enter the actual start date and time for the campaign.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start Date</td></tr><tr><td>description</td><td>Enter the actual start date and time for the campaign.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstart</td></tr></table>

### <a href=#budgetedCost name="budgetedCost">budgetedCost</a>

Type the amount budgeted for the campaign to define a limit for how much you can spend.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Allocated</td></tr><tr><td>description</td><td>Type the amount budgeted for the campaign to define a limit for how much you can spend.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>budgetedcost</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#budgetedCostBase name="budgetedCostBase">budgetedCostBase</a>

Value of the Budget Allocated in base currency.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Allocated (Base)</td></tr><tr><td>description</td><td>Value of the Budget Allocated in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>budgetedcost_base</td></tr></table>

### <a href=#codeName name="codeName">codeName</a>

Type a number or other tracking code to identify the campaign. If no value is entered, a code will be generated automatically.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Campaign Code</td></tr><tr><td>description</td><td>Type a number or other tracking code to identify the campaign. If no value is entered, a code will be generated automatically.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>codename</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the campaign, such as the products or services offered or the targeted audience.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the campaign, such as the products or services offered or the targeted audience.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#expectedResponse name="expectedResponse">expectedResponse</a>

Type the expected response rate for the campaign as a full number between 0 and 100.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Response Percentage</td></tr><tr><td>description</td><td>Type the expected response rate for the campaign as a full number between 0 and 100.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>expectedresponse</td></tr></table>

### <a href=#expectedRevenue name="expectedRevenue">expectedRevenue</a>

Type the expected revenue for the campaign for return on investment projections and post-campaign reporting.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Revenue</td></tr><tr><td>description</td><td>Type the expected revenue for the campaign for return on investment projections and post-campaign reporting.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>expectedrevenue</td></tr></table>

### <a href=#expectedRevenueBase name="expectedRevenueBase">expectedRevenueBase</a>

Value of the Estimated Revenue in base currency.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Revenue (Base)</td></tr><tr><td>description</td><td>Value of the Estimated Revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>expectedrevenue_base</td></tr></table>

### <a href=#isTemplate name="isTemplate">isTemplate</a>

Select whether the campaign is a template that can be copied when you create future campaigns.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Template</td></tr><tr><td>description</td><td>Select whether the campaign is a template that can be copied when you create future campaigns.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>istemplate</td></tr></table>

### <a href=#message name="message">message</a>

Type the promotional message or marketing copy for the campaign.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Message</td></tr><tr><td>description</td><td>Type the promotional message or marketing copy for the campaign.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>message</td></tr></table>

### <a href=#objective name="objective">objective</a>

Type the objective of the campaign, including products, services, discounts, and pricing.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offer</td></tr><tr><td>description</td><td>Type the objective of the campaign, including products, services, discounts, and pricing.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>objective</td></tr></table>

### <a href=#otherCost name="otherCost">otherCost</a>

Type the sum of any miscellaneous campaign costs not included in the campaign activities to make sure the actual cost of the campaign is calculated correctly.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Miscellaneous Costs</td></tr><tr><td>description</td><td>Type the sum of any miscellaneous campaign costs not included in the campaign activities to make sure the actual cost of the campaign is calculated correctly.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>othercost</td></tr></table>

### <a href=#otherCostBase name="otherCostBase">otherCostBase</a>

Value of the Miscellaneous Costs in base currency.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Miscellaneous Costs (Base)</td></tr><tr><td>description</td><td>Value of the Miscellaneous Costs in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>othercost_base</td></tr></table>

### <a href=#promotionCodeName name="promotionCodeName">promotionCodeName</a>

Type a promotional code to track sales related to the campaign or allow customers to redeem a discount offer.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Promotion Code</td></tr><tr><td>description</td><td>Type a promotional code to track sales related to the campaign or allow customers to redeem a discount offer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>promotioncodename</td></tr></table>

### <a href=#proposedEnd name="proposedEnd">proposedEnd</a>

Enter the date when the campaign is scheduled to end.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Proposed End Date</td></tr><tr><td>description</td><td>Enter the date when the campaign is scheduled to end.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>proposedend</td></tr></table>

### <a href=#proposedStart name="proposedStart">proposedStart</a>

Enter the date when the campaign is scheduled to start.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Proposed Start Date</td></tr><tr><td>description</td><td>Enter the date when the campaign is scheduled to start.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>proposedstart</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows the status of the campaign. By default, campaigns are active and can't be deactivated.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows the status of the campaign. By default, campaigns are active and can't be deactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the campaign's status.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the campaign's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Proposed</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Ready To Launch</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Launched</td><td>2</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>3</td><td>0</td></tr><tr><td>en</td><td>Canceled</td><td>4</td><td>0</td></tr><tr><td>en</td><td>Suspended</td><td>5</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>6</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#totalActualCost name="totalActualCost">totalActualCost</a>

Shows the sum of the amounts entered in the Total Cost of Campaign Activities and Miscellaneous Costs fields.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Cost of Campaign</td></tr><tr><td>description</td><td>Shows the sum of the amounts entered in the Total Cost of Campaign Activities and Miscellaneous Costs fields.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalactualcost</td></tr></table>

### <a href=#totalActualCostBase name="totalActualCostBase">totalActualCostBase</a>

Value of the Total Cost of Campaign in base currency.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Cost of Campaign (Base)</td></tr><tr><td>description</td><td>Value of the Total Cost of Campaign in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalactualcost_base</td></tr></table>

### <a href=#totalCampaignActivityActualCost name="totalCampaignActivityActualCost">totalCampaignActivityActualCost</a>

Shows the sum of the values entered in the Actual Cost field on all campaign activities related to the campaign.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Cost of Campaign Activities</td></tr><tr><td>description</td><td>Shows the sum of the values entered in the Actual Cost field on all campaign activities related to the campaign.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalcampaignactivityactualcost</td></tr></table>

### <a href=#totalCampaignActivityActualCostBase name="totalCampaignActivityActualCostBase">totalCampaignActivityActualCostBase</a>

Value of the Total Cost of Campaign Activities in base currency.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Cost of Campaign Activities (Base)</td></tr><tr><td>description</td><td>Value of the Total Cost of Campaign Activities in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalcampaignactivityactualcost_base</td></tr></table>

### <a href=#typeCode name="typeCode">typeCode</a>

Select the type of the campaign.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Campaign Type</td></tr><tr><td>description</td><td>Select the type of the campaign.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>typecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Advertisement</td><td>1</td></tr><tr><td>en</td><td>Direct Marketing</td><td>2</td></tr><tr><td>en</td><td>Event</td><td>3</td></tr><tr><td>en</td><td>Co-branding</td><td>4</td></tr><tr><td>en</td><td>Other</td><td>5</td></tr></table></td></tr></table>

### <a href=#typeCode_display name="typeCode_display">typeCode_display</a>

First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#priceListId name="priceListId">priceListId</a>

Choose the price list associated with this item to make sure the products associated with the campaign are offered at the correct prices.  
First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Choose the price list associated with this item to make sure the products associated with the campaign are offered at the correct prices.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricelistid</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: crmCommon/Campaign (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

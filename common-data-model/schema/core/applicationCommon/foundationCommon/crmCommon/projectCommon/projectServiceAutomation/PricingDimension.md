---
title: PricingDimension - Common Data Model | Microsoft Docs
description: This describes the PricingDimension entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Pricing Dimension

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/PricingDimension.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/PricingDimension  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[ownerId](#ownerId)|Owner Id|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[dimensionId](#dimensionId)|Unique identifier for entity instances|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[stateCode](#stateCode)|Status of the Pricing Dimension|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[stateCode_display](#stateCode_display)||<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[statusCode](#statusCode)|Reason for the status of the Pricing Dimension|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[statusCode_display](#statusCode_display)||<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[name](#name)|Name of the Dimension to be used in pricing calculations.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[applicableToCost](#applicableToCost)|Determines if this pricing dimension is applicable for Cost price.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[applicableToPurchase](#applicableToPurchase)|Determines if this pricing dimension is applicable for Purchase price.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[applicableToSales](#applicableToSales)|Determines if this pricing dimension is applicable for Sales price.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[costPriority](#costPriority)|Determines priority of the pricing dimension when resolving for Cost price.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[purchasePriority](#purchasePriority)|Determines priority of the pricing dimension when resolving for Purchase price.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[salesPriority](#salesPriority)|Determines priority of the pricing dimension when resolving for Sales price.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[type](#type)|Type determines if the dimension is to be used for retrieving the final per unit price or to retrieve a markup that is to be applied on a base price.|<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|
|[type_display](#type_display)||<a href="PricingDimension.md" target="_blank">projectServiceAutomation/PricingDimension</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#dimensionId name="dimensionId">dimensionId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pricing Dimension</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_dimensionid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Pricing Dimension  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Pricing Dimension</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Pricing Dimension  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Pricing Dimension</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Name of the Dimension to be used in pricing calculations.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dimension Name</td></tr><tr><td>description</td><td>Name of the Dimension to be used in pricing calculations.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#applicableToCost name="applicableToCost">applicableToCost</a>

Determines if this pricing dimension is applicable for Cost price.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Applicable To Cost</td></tr><tr><td>description</td><td>Determines if this pricing dimension is applicable for Cost price.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_applicabletocost</td></tr></table>

### <a href=#applicableToPurchase name="applicableToPurchase">applicableToPurchase</a>

Determines if this pricing dimension is applicable for Purchase price.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Applicable To Purchase</td></tr><tr><td>description</td><td>Determines if this pricing dimension is applicable for Purchase price.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_applicabletopurchase</td></tr></table>

### <a href=#applicableToSales name="applicableToSales">applicableToSales</a>

Determines if this pricing dimension is applicable for Sales price.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Applicable To Sales</td></tr><tr><td>description</td><td>Determines if this pricing dimension is applicable for Sales price.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_applicabletosales</td></tr></table>

### <a href=#costPriority name="costPriority">costPriority</a>

Determines priority of the pricing dimension when resolving for Cost price.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Priority</td></tr><tr><td>description</td><td>Determines priority of the pricing dimension when resolving for Cost price.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costpriority</td></tr></table>

### <a href=#purchasePriority name="purchasePriority">purchasePriority</a>

Determines priority of the pricing dimension when resolving for Purchase price.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase Priority</td></tr><tr><td>description</td><td>Determines priority of the pricing dimension when resolving for Purchase price.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_purchasepriority</td></tr></table>

### <a href=#salesPriority name="salesPriority">salesPriority</a>

Determines priority of the pricing dimension when resolving for Sales price.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Priority</td></tr><tr><td>description</td><td>Determines priority of the pricing dimension when resolving for Sales price.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salespriority</td></tr></table>

### <a href=#type name="type">type</a>

Type determines if the dimension is to be used for retrieving the final per unit price or to retrieve a markup that is to be applied on a base price.  
First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Type determines if the dimension is to be used for retrieving the final per unit price or to retrieve a markup that is to be applied on a base price.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Amount-based</td><td>192350000</td></tr><tr><td>en</td><td>Markup-based</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: projectServiceAutomation/PricingDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

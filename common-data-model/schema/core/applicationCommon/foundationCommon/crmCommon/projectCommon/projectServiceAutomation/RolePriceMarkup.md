---
title: RolePriceMarkup - Common Data Model | Microsoft Docs
description: List of markups for prices by role on a price list.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Role Price Markup

List of markups for prices by role on a price list.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/RolePriceMarkup.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/RolePriceMarkup  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[resourcecategorymarkuppricelevelId](#resourcecategorymarkuppricelevelId)|Unique identifier for entity instances|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[stateCode](#stateCode)|Status of the Role Price Markup|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[stateCode_display](#stateCode_display)||<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[statusCode](#statusCode)|Reason for the status of the Role Price Markup|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[statusCode_display](#statusCode_display)||<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[description](#description)|The name of the custom entity.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[bookableResource](#bookableResource)|Select the bookable resource that the price is being set for.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[resourcingUnit](#resourcingUnit)|Select the organizational unit of the resource performing the work.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[percent](#percent)|Enter the markup percent over base price. This field is relevant only when the price calculation method selected is "Markup percentage".|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[priceCalculation](#priceCalculation)|Select the price calculation method to determine the price.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[priceCalculation_display](#priceCalculation_display)||<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[priceList](#priceList)|Select the price list to which this price list item is being added.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[resourceCategory](#resourceCategory)|Select the role that the price is being set for.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|
|[transactionCategory](#transactionCategory)|Select the transaction category that the price is being set for.|<a href="RolePriceMarkup.md" target="_blank">projectServiceAutomation/RolePriceMarkup</a>|

### <a href=#resourcecategorymarkuppricelevelId name="resourcecategorymarkuppricelevelId">resourcecategorymarkuppricelevelId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role Price Markup</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategorymarkuppricelevelid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Role Price Markup  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Role Price Markup</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Role Price Markup  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Role Price Markup</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#description name="description">description</a>

The name of the custom entity.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

Select the bookable resource that the price is being set for.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource</td></tr><tr><td>description</td><td>Select the bookable resource that the price is being set for.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#resourcingUnit name="resourcingUnit">resourcingUnit</a>

Select the organizational unit of the resource performing the work.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resourcing Unit</td></tr><tr><td>description</td><td>Select the organizational unit of the resource performing the work.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_organizationalunit</td></tr></table>

### <a href=#percent name="percent">percent</a>

Enter the markup percent over base price. This field is relevant only when the price calculation method selected is "Markup percentage".  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percent</td></tr><tr><td>description</td><td>Enter the markup percent over base price. This field is relevant only when the price calculation method selected is "Markup percentage".</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_percent</td></tr></table>

### <a href=#priceCalculation name="priceCalculation">priceCalculation</a>

Select the price calculation method to determine the price.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Calculation</td></tr><tr><td>description</td><td>Select the price calculation method to determine the price.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pricecalculation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Price per unit</td><td>192350000</td></tr><tr><td>en</td><td>At cost</td><td>192350001</td></tr><tr><td>en</td><td>Markup percentage</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#priceCalculation_display name="priceCalculation_display">priceCalculation_display</a>

First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#priceList name="priceList">priceList</a>

Select the price list to which this price list item is being added.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Select the price list to which this price list item is being added.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pricelist</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Select the role that the price is being set for.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>description</td><td>Select the role that the price is being set for.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

Select the transaction category that the price is being set for.  
First included in: projectServiceAutomation/RolePriceMarkup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category</td></tr><tr><td>description</td><td>Select the transaction category that the price is being set for.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>

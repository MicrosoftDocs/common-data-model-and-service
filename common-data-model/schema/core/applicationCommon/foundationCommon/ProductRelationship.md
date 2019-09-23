---
title: ProductRelationship - Common Data Model | Microsoft Docs
description: This describes the ProductRelationship entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Product Relationship

Information about the selling relationship between two products, including the relationship type, such as up-sell, cross-sell, substitute, or accessory.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/ProductRelationship.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/ProductRelationship  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[productSubstituteId](#productSubstituteId)|Shows the unique identifier of the product relationship.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[name](#name)|name|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[productId](#productId)|Shows the product that the relationship is defined for.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[salesRelationshipType](#salesRelationshipType)|Select the type of the product relationship.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[salesRelationshipType_display](#salesRelationshipType_display)||<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[stateCode](#stateCode)|Select the product relationship's status.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[stateCode_display](#stateCode_display)||<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[statusCode](#statusCode)|Shows whether the product relationship is active or inactive.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[statusCode_display](#statusCode_display)||<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[substitutedProductId](#substitutedProductId)|Select the related product that the relationship needs to be defined for.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[direction](#direction)|Select whether the relationship is unidirectional or bidirectional.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[direction_display](#direction_display)||<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the record.|<a href="ProductRelationship.md" target="_blank">foundationCommon/ProductRelationship</a>|

### <a href=#productSubstituteId name="productSubstituteId">productSubstituteId</a>

Shows the unique identifier of the product relationship.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product Relationship ID</td></tr><tr><td>description</td><td>Shows the unique identifier of the product relationship.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>productsubstituteid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

name  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>name</td></tr><tr><td>description</td><td>name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#productId name="productId">productId</a>

Shows the product that the relationship is defined for.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>Shows the product that the relationship is defined for.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>productid</td></tr></table>

### <a href=#salesRelationshipType name="salesRelationshipType">salesRelationshipType</a>

Select the type of the product relationship.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Relationship Type</td></tr><tr><td>description</td><td>Select the type of the product relationship.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>salesrelationshiptype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Up-sell</td><td>0</td></tr><tr><td>en</td><td>Cross-sell</td><td>1</td></tr><tr><td>en</td><td>Accessory</td><td>2</td></tr><tr><td>en</td><td>Substitute</td><td>3</td></tr></table></td></tr></table>

### <a href=#salesRelationshipType_display name="salesRelationshipType_display">salesRelationshipType_display</a>

First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Select the product relationship's status.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Select the product relationship's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Shows whether the product relationship is active or inactive.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Shows whether the product relationship is active or inactive.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#substitutedProductId name="substitutedProductId">substitutedProductId</a>

Select the related product that the relationship needs to be defined for.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related Product</td></tr><tr><td>description</td><td>Select the related product that the relationship needs to be defined for.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>substitutedproductid</td></tr></table>

### <a href=#direction name="direction">direction</a>

Select whether the relationship is unidirectional or bidirectional.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Direction</td></tr><tr><td>description</td><td>Select whether the relationship is unidirectional or bidirectional.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>direction</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Uni-Directional</td><td>0</td></tr><tr><td>en</td><td>Bi-Directional</td><td>1</td></tr></table></td></tr></table>

### <a href=#direction_display name="direction_display">direction_display</a>

First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the record.  
First included in: foundationCommon/ProductRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

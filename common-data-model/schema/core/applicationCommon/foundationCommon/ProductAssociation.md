---
title: ProductAssociation - Common Data Model | Microsoft Docs
description: Instance of a product added to a bundle or kit.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Product Association

Instance of a product added to a bundle or kit.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/ProductAssociation.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/ProductAssociation  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[productAssociationId](#productAssociationId)|Shows the unique identifier of the product association.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[associatedProduct](#associatedProduct)|Select a product to add to the bundle or kit.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[productId](#productId)|Select a bundle or a kit.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[quantity](#quantity)|Type the quantity of the products added to the bundle or kit.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[productIsRequired](#productIsRequired)|Select whether the associated product is required or optional.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[productIsRequired_display](#productIsRequired_display)||<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[uoMId](#uoMId)|Shows the unit of the product association.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[stateCode](#stateCode)|Shows whether the associated product is active or inactive.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[stateCode_display](#stateCode_display)||<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[statusCode](#statusCode)|Select the associated product's status.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[statusCode_display](#statusCode_display)||<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[propertyCustomizationStatus](#propertyCustomizationStatus)|Shows whether the item has properties that can be customized.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[propertyCustomizationStatus_display](#propertyCustomizationStatus_display)||<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the record.|<a href="ProductAssociation.md" target="_blank">foundationCommon/ProductAssociation</a>|

### <a href=#productAssociationId name="productAssociationId">productAssociationId</a>

Shows the unique identifier of the product association.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product Association ID</td></tr><tr><td>description</td><td>Shows the unique identifier of the product association.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>productassociationid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#associatedProduct name="associatedProduct">associatedProduct</a>

Select a product to add to the bundle or kit.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Associated Product</td></tr><tr><td>description</td><td>Select a product to add to the bundle or kit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>associatedproduct</td></tr></table>

### <a href=#productId name="productId">productId</a>

Select a bundle or a kit.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>Select a bundle or a kit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>productid</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Type the quantity of the products added to the bundle or kit.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Type the quantity of the products added to the bundle or kit.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quantity</td></tr></table>

### <a href=#productIsRequired name="productIsRequired">productIsRequired</a>

Select whether the associated product is required or optional.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required</td></tr><tr><td>description</td><td>Select whether the associated product is required or optional.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productisrequired</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Optional</td><td>0</td></tr><tr><td>en</td><td>Required</td><td>1</td></tr></table></td></tr></table>

### <a href=#productIsRequired_display name="productIsRequired_display">productIsRequired_display</a>

First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#uoMId name="uoMId">uoMId</a>

Shows the unit of the product association.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Shows the unit of the product association.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>uomid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the associated product is active or inactive.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the associated product is active or inactive.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr><tr><td>en</td><td>Draft</td><td>2</td></tr><tr><td>en</td><td>Under Revision</td><td>3</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the associated product's status.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the associated product's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Draft</td><td>0</td><td>2</td></tr><tr><td>en</td><td>DraftActive</td><td>3</td><td>3</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#propertyCustomizationStatus name="propertyCustomizationStatus">propertyCustomizationStatus</a>

Shows whether the item has properties that can be customized.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property Customization</td></tr><tr><td>description</td><td>Shows whether the item has properties that can be customized.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>propertycustomizationstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Available</td><td>0</td></tr><tr><td>en</td><td>Available</td><td>1</td></tr></table></td></tr></table>

### <a href=#propertyCustomizationStatus_display name="propertyCustomizationStatus_display">propertyCustomizationStatus_display</a>

First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the record.  
First included in: foundationCommon/ProductAssociation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

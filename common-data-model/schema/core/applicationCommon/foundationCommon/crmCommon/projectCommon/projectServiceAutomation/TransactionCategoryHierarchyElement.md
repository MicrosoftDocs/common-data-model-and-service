---
title: TransactionCategoryHierarchyElement - Common Data Model | Microsoft Docs
description: Hierarchical relationship of the transaction category with a root node.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Transaction Category Hierarchy Element

Hierarchical relationship of the transaction category with a root node.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/TransactionCategoryHierarchyElement.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/TransactionCategoryHierarchyElement  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[transactionCategoryHierarchyElementId](#transactionCategoryHierarchyElementId)|Unique identifier for entity instances|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[stateCode](#stateCode)|Status of the Transaction Category Hierarchy Element|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[stateCode_display](#stateCode_display)||<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[statusCode](#statusCode)|Reason for the status of the Transaction Category Hierarchy Element|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[statusCode_display](#statusCode_display)||<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[name](#name)|The name of the custom entity.|<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[childCategory](#childCategory)||<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|
|[parentCategory](#parentCategory)||<a href="TransactionCategoryHierarchyElement.md" target="_blank">projectServiceAutomation/TransactionCategoryHierarchyElement</a>|

### <a href=#transactionCategoryHierarchyElementId name="transactionCategoryHierarchyElementId">transactionCategoryHierarchyElementId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category Hierarchy Element</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategoryhierarchyelementid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Transaction Category Hierarchy Element  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Transaction Category Hierarchy Element</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Transaction Category Hierarchy Element  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Transaction Category Hierarchy Element</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#childCategory name="childCategory">childCategory</a>

First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Child Category</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_childcategory</td></tr></table>

### <a href=#parentCategory name="parentCategory">parentCategory</a>

First included in: projectServiceAutomation/TransactionCategoryHierarchyElement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Category</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_parentcategory</td></tr></table>

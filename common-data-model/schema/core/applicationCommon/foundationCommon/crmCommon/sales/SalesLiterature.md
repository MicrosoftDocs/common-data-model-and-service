---
title: SalesLiterature - Common Data Model | Microsoft Docs
description: Storage of sales literature, which may contain one or more documents.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Sales Literature

Storage of sales literature, which may contain one or more documents.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/sales/SalesLiterature.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/sales/SalesLiterature  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[salesLiteratureId](#salesLiteratureId)|Unique identifier of the sales literature.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[name](#name)|Type a descriptive title for the sales literature.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[description](#description)|Type additional information to describe the sales literature, such as the intended audience or primary messages.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[employeeContactId](#employeeContactId)|Choose the user who is responsible for maintaining or updating the sales literature.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[expirationDate](#expirationDate)|Enter the expiration date or last day the sales literature can be distributed.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[hasAttachments](#hasAttachments)|Tells whether the sales literature has one or more attachments.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[isCustomerViewable](#isCustomerViewable)|Select whether the sales literature can be distributed to prospects and customers or is for internal use only.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[keyWords](#keyWords)|Type one or more topics or keywords that can be used to search for the sales literature.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[literatureTypeCode](#literatureTypeCode)|Select a category or type to help others identify the intended use of the sales literature.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[literatureTypeCode_display](#literatureTypeCode_display)||<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[subjectId](#subjectId)|Choose the subject for the sales literature to relate the item to a product or business group. Administrators can configure subjects under Business Management in the Settings area.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[entityImageId](#entityImageId)||<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="SalesLiterature.md" target="_blank">sales/SalesLiterature</a>|

### <a href=#salesLiteratureId name="salesLiteratureId">salesLiteratureId</a>

Unique identifier of the sales literature.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Literature</td></tr><tr><td>description</td><td>Unique identifier of the sales literature.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>salesliteratureid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Type a descriptive title for the sales literature.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Type a descriptive title for the sales literature.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the sales literature, such as the intended audience or primary messages.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the sales literature, such as the intended audience or primary messages.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#employeeContactId name="employeeContactId">employeeContactId</a>

Choose the user who is responsible for maintaining or updating the sales literature.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employee Contact</td></tr><tr><td>description</td><td>Choose the user who is responsible for maintaining or updating the sales literature.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>employeecontactid</td></tr></table>

### <a href=#expirationDate name="expirationDate">expirationDate</a>

Enter the expiration date or last day the sales literature can be distributed.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expiration Date</td></tr><tr><td>description</td><td>Enter the expiration date or last day the sales literature can be distributed.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>expirationdate</td></tr></table>

### <a href=#hasAttachments name="hasAttachments">hasAttachments</a>

Tells whether the sales literature has one or more attachments.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has Attachments</td></tr><tr><td>description</td><td>Tells whether the sales literature has one or more attachments.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>hasattachments</td></tr></table>

### <a href=#isCustomerViewable name="isCustomerViewable">isCustomerViewable</a>

Select whether the sales literature can be distributed to prospects and customers or is for internal use only.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Viewable</td></tr><tr><td>description</td><td>Select whether the sales literature can be distributed to prospects and customers or is for internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>iscustomerviewable</td></tr></table>

### <a href=#keyWords name="keyWords">keyWords</a>

Type one or more topics or keywords that can be used to search for the sales literature.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Key Words</td></tr><tr><td>description</td><td>Type one or more topics or keywords that can be used to search for the sales literature.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>keywords</td></tr></table>

### <a href=#literatureTypeCode name="literatureTypeCode">literatureTypeCode</a>

Select a category or type to help others identify the intended use of the sales literature.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Select a category or type to help others identify the intended use of the sales literature.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>literaturetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Presentation</td><td>0</td></tr><tr><td>en</td><td>Product Sheet</td><td>1</td></tr><tr><td>en</td><td>Policies And Procedures</td><td>2</td></tr><tr><td>en</td><td>Sales Literature</td><td>3</td></tr><tr><td>en</td><td>Spreadsheets</td><td>4</td></tr><tr><td>en</td><td>News</td><td>5</td></tr><tr><td>en</td><td>Bulletins</td><td>6</td></tr><tr><td>en</td><td>Price Sheets</td><td>7</td></tr><tr><td>en</td><td>Manuals</td><td>8</td></tr><tr><td>en</td><td>Company Background</td><td>9</td></tr><tr><td>en</td><td>Marketing Collateral</td><td>100001</td></tr></table></td></tr></table>

### <a href=#literatureTypeCode_display name="literatureTypeCode_display">literatureTypeCode_display</a>

First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectId name="subjectId">subjectId</a>

Choose the subject for the sales literature to relate the item to a product or business group. Administrators can configure subjects under Business Management in the Settings area.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Choose the subject for the sales literature to relate the item to a product or business group. Administrators can configure subjects under Business Management in the Settings area.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subjectid</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: sales/SalesLiterature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

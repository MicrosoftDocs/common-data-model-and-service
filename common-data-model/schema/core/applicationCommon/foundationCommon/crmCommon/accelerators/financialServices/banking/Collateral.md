---
title: Collateral - Common Data Model | Microsoft Docs
description: This describes the Collateral entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Collateral

Collateral entity represents the collateral information related to a commercial loan product that the customer holds with the bank.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/financialServices/banking/Collateral.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/financialServices/banking/Collateral  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[collateralId](#collateralId)|Unique identifier for entity instances|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[collateralType](#collateralType)|Type of collateral provided by the client as security against the loan.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[collateralType_display](#collateralType_display)||<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[collateralValue](#collateralValue)|The value of the collateral as per the evaluation done.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[collateralValueBase](#collateralValueBase)|Value of the Collateral Value in base currency.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[coverage](#coverage)|The amount of the loan that is secured/covered by the specified collateral.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[dateOfValuation](#dateOfValuation)|The date on which the collateral was evaluated/appraised.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[description](#description)|Description of the collateral.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[evaluatedBy](#evaluatedBy)|The name of the firm that evaluated/appraised the collateral.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[financialProductId](#financialProductId)|Reference to the loan product for which the collateral is defined.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[name](#name)|The name of the custom entity.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[nextDateOfValuation](#nextDateOfValuation)|The date on which the collateral needs to be re-evaluated.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[deprecatedStageId](#deprecatedStageId)|Contains the id of the stage where the entity is located.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[stateCode](#stateCode)|Status of the Collateral|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[stateCode_display](#stateCode_display)||<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[statusCode](#statusCode)|Reason for the status of the Collateral|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[statusCode_display](#statusCode_display)||<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|
|[deprecatedTraversedPath](#deprecatedTraversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="Collateral.md" target="_blank">banking/Collateral</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#collateralId name="collateralId">collateralId</a>

Unique identifier for entity instances  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Collateral</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_collateralid</td></tr></table>

### <a href=#collateralType name="collateralType">collateralType</a>

Type of collateral provided by the client as security against the loan.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Collateral Type</td></tr><tr><td>description</td><td>Type of collateral provided by the client as security against the loan.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_collateraltype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#collateralType_display name="collateralType_display">collateralType_display</a>

First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#collateralValue name="collateralValue">collateralValue</a>

The value of the collateral as per the evaluation done.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Collateral Value</td></tr><tr><td>description</td><td>The value of the collateral as per the evaluation done.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_collateralvalue</td></tr></table>

### <a href=#collateralValueBase name="collateralValueBase">collateralValueBase</a>

Value of the Collateral Value in base currency.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Collateral Value (Base)</td></tr><tr><td>description</td><td>Value of the Collateral Value in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_collateralvalue_base</td></tr></table>

### <a href=#coverage name="coverage">coverage</a>

The amount of the loan that is secured/covered by the specified collateral.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Coverage</td></tr><tr><td>description</td><td>The amount of the loan that is secured/covered by the specified collateral.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_coverage</td></tr></table>

### <a href=#dateOfValuation name="dateOfValuation">dateOfValuation</a>

The date on which the collateral was evaluated/appraised.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date of Valuation</td></tr><tr><td>description</td><td>The date on which the collateral was evaluated/appraised.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_dateofvaluation</td></tr></table>

### <a href=#description name="description">description</a>

Description of the collateral.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the collateral.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_description</td></tr></table>

### <a href=#evaluatedBy name="evaluatedBy">evaluatedBy</a>

The name of the firm that evaluated/appraised the collateral.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Evaluated by</td></tr><tr><td>description</td><td>The name of the firm that evaluated/appraised the collateral.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_evaluatedby</td></tr></table>

### <a href=#financialProductId name="financialProductId">financialProductId</a>

Reference to the loan product for which the collateral is defined.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financial Product</td></tr><tr><td>description</td><td>Reference to the loan product for which the collateral is defined.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_financialproductid</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_name</td></tr></table>

### <a href=#nextDateOfValuation name="nextDateOfValuation">nextDateOfValuation</a>

The date on which the collateral needs to be re-evaluated.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Date of Valuation</td></tr><tr><td>description</td><td>The date on which the collateral needs to be re-evaluated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_nextdateofvaluation</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#deprecatedStageId name="deprecatedStageId">deprecatedStageId</a>

Contains the id of the stage where the entity is located.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Collateral  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Collateral</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Collateral  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Collateral</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#deprecatedTraversedPath name="deprecatedTraversedPath">deprecatedTraversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: banking/Collateral (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

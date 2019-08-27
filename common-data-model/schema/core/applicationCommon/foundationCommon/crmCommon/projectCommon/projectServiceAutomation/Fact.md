---
title: Fact - Common Data Model | Microsoft Docs
description: Aggregated fact entity for actual transactions.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Fact

Aggregated fact entity for actual transactions.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Fact.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Fact  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[factId](#factId)|Unique identifier for entity instances|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[stateCode](#stateCode)|Status of the Fact|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[stateCode_display](#stateCode_display)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[statusCode](#statusCode)|Reason for the status of the Fact|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[statusCode_display](#statusCode_display)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[name](#name)|The name of the custom entity.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[accountCustomer](#accountCustomer)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[accountVendor](#accountVendor)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actChargeableBilledSalesAmount](#actChargeableBilledSalesAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actChargeableBilledSalesAmountBase](#actChargeableBilledSalesAmountBase)|Value of the Actual Chargeable Billed Sales Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actChargeableBilledSalesQuantity](#actChargeableBilledSalesQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actChargeableCostAmount](#actChargeableCostAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actChargeableCostAmountBase](#actChargeableCostAmountBase)|Value of the Actual Chargeable Cost Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actChargeableCostQuantity](#actChargeableCostQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actChargeableUnbilledSalesAmount](#actChargeableUnbilledSalesAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actChargeableUnbilledSalesAmountBase](#actChargeableUnbilledSalesAmountBase)|Value of the Actual Chargeable Unbilled Sales Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actChargeableUnbilledSalesQuantity](#actChargeableUnbilledSalesQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNoChargeBilledSalesAmount](#actNoChargeBilledSalesAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNoChargeBilledSalesAmountBase](#actNoChargeBilledSalesAmountBase)|Value of the Actual No Charge Billed Sales Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNoChargeBilledSalesQuantity](#actNoChargeBilledSalesQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNoChargeCostAmount](#actNoChargeCostAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNoChargeCostAmountBase](#actNoChargeCostAmountBase)|Value of the Actual No Charge Cost Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNoChargeCostQuantity](#actNoChargeCostQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNoChargeUnbilledSalesAmount](#actNoChargeUnbilledSalesAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNoChargeUnbilledSalesAmountBase](#actNoChargeUnbilledSalesAmountBase)|Value of the Actual No Charge Unbilled Sales Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNoChargeUnbilledSalesQuantity](#actNoChargeUnbilledSalesQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNonChargeableCostAmount](#actNonChargeableCostAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNonChargeableCostAmountBase](#actNonChargeableCostAmountBase)|Value of the Actual Non Chargeable Cost Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNonChargeableCostQuantity](#actNonChargeableCostQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNonChargeableUnbilledSalesAmount](#actNonChargeableUnbilledSalesAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNonChargeableUnbilledSalesAmountBase](#actNonChargeableUnbilledSalesAmountBase)|Value of the Actual Non Chargeable Unbilled Sales Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[actNonChargeableUnbilledSalesQuantity](#actNonChargeableUnbilledSalesQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[bookableResource](#bookableResource)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[contactCustomer](#contactCustomer)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[contactVendor](#contactVendor)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[customerType](#customerType)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[customerType_display](#customerType_display)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[documentDate](#documentDate)|Enter the transaction date of the business event.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[endDate](#endDate)|Enter the end date for this transaction.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estChargeableBilledSalesAmount](#estChargeableBilledSalesAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estChargeableBilledSalesAmountBase](#estChargeableBilledSalesAmountBase)|Value of the Estimated Chargeable Billed Sales Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estChargeableBilledSalesQuantity](#estChargeableBilledSalesQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estChargeableCostAmount](#estChargeableCostAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estChargeableCostAmountBase](#estChargeableCostAmountBase)|Value of the Estimated Chargeable Cost Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estChargeableCostQuantity](#estChargeableCostQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estChargeableUnbilledSalesAmount](#estChargeableUnbilledSalesAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estChargeableUnbilledSalesAmountBase](#estChargeableUnbilledSalesAmountBase)|Value of the Estimated Chargeable Unbilled Sales Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estChargeableUnbilledSalesQuantity](#estChargeableUnbilledSalesQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estimate](#estimate)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estimateLineId](#estimateLineId)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNoChargeBilledSalesAmount](#estNoChargeBilledSalesAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNoChargeBilledSalesAmountBase](#estNoChargeBilledSalesAmountBase)|Value of the Estimated No Charge Billed Sales Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNoChargeBilledSalesQuantity](#estNoChargeBilledSalesQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNoChargeCostAmount](#estNoChargeCostAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNoChargeCostAmountBase](#estNoChargeCostAmountBase)|Value of the Estimated No Charge Cost Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNoChargeCostQuantity](#estNoChargeCostQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNoChargeUnbilledSalesAmount](#estNoChargeUnbilledSalesAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNoChargeUnbilledSalesAmountBase](#estNoChargeUnbilledSalesAmountBase)|Value of the Estimated No Charge Unbilled Sales Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNoChargeUnbilledSalesQuantity](#estNoChargeUnbilledSalesQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNonChargeableCostAmount](#estNonChargeableCostAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNonChargeableCostAmountBase](#estNonChargeableCostAmountBase)|Value of the Estimated Non Chargeable Cost Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNonChargeableCostQuantity](#estNonChargeableCostQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNonChargeableUnbilledSalesAmount](#estNonChargeableUnbilledSalesAmount)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNonChargeableUnbilledSalesAmountBase](#estNonChargeableUnbilledSalesAmountBase)|Value of the Estimated Non Chargeable Unbilled Sales Amount in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[estNonChargeableUnbilledSalesQuantity](#estNonChargeableUnbilledSalesQuantity)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[factType](#factType)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[factType_display](#factType_display)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[product](#product)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[project](#project)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[resourceCategory](#resourceCategory)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[salesContract](#salesContract)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[salesContractLine](#salesContractLine)|(Deprecated)|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[salesContractLineId](#salesContractLineId)|Unique identifier for Project Contract Line associated with Fact.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[startDate](#startDate)|Enter the start date.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[task](#task)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[transactionCategory](#transactionCategory)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[transactionClassification](#transactionClassification)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[transactionClassification_display](#transactionClassification_display)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[vendorType](#vendorType)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[vendorType_display](#vendorType_display)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[earnedRevenue](#earnedRevenue)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[earnedRevenueBase](#earnedRevenueBase)|Value of the Earned Revenue in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[grossMargin](#grossMargin)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[grossMarginBase](#grossMarginBase)|Value of the Gross Margin in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[totalCost](#totalCost)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[totalCostBase](#totalCostBase)|Value of the Total Cost in base currency.|<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|
|[totalHours](#totalHours)||<a href="Fact.md" target="_blank">projectServiceAutomation/Fact</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#factId name="factId">factId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fact</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_factid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Fact  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Fact</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Fact  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Fact</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#accountCustomer name="accountCustomer">accountCustomer</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountcustomer</td></tr></table>

### <a href=#accountVendor name="accountVendor">accountVendor</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountvendor</td></tr></table>

### <a href=#actChargeableBilledSalesAmount name="actChargeableBilledSalesAmount">actChargeableBilledSalesAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Chargeable Billed Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actchargeablebilledsalesamount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#actChargeableBilledSalesAmountBase name="actChargeableBilledSalesAmountBase">actChargeableBilledSalesAmountBase</a>

Value of the Actual Chargeable Billed Sales Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Chargeable Billed Sales Amount (Base)</td></tr><tr><td>description</td><td>Value of the Actual Chargeable Billed Sales Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actchargeablebilledsalesamount_base</td></tr></table>

### <a href=#actChargeableBilledSalesQuantity name="actChargeableBilledSalesQuantity">actChargeableBilledSalesQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Chargeable Billed Sales Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actchargeablebilledsalesquantity</td></tr></table>

### <a href=#actChargeableCostAmount name="actChargeableCostAmount">actChargeableCostAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Chargeable Cost Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actchargeablecostamount</td></tr></table>

### <a href=#actChargeableCostAmountBase name="actChargeableCostAmountBase">actChargeableCostAmountBase</a>

Value of the Actual Chargeable Cost Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Chargeable Cost Amount (Base)</td></tr><tr><td>description</td><td>Value of the Actual Chargeable Cost Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actchargeablecostamount_base</td></tr></table>

### <a href=#actChargeableCostQuantity name="actChargeableCostQuantity">actChargeableCostQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Chargeable Cost Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actchargeablecostquantity</td></tr></table>

### <a href=#actChargeableUnbilledSalesAmount name="actChargeableUnbilledSalesAmount">actChargeableUnbilledSalesAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Chargeable Unbilled Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actchargeableunbilledsalesamount</td></tr></table>

### <a href=#actChargeableUnbilledSalesAmountBase name="actChargeableUnbilledSalesAmountBase">actChargeableUnbilledSalesAmountBase</a>

Value of the Actual Chargeable Unbilled Sales Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Chargeable Unbilled Sales Amount (Base)</td></tr><tr><td>description</td><td>Value of the Actual Chargeable Unbilled Sales Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actchargeableunbilledsalesamount_base</td></tr></table>

### <a href=#actChargeableUnbilledSalesQuantity name="actChargeableUnbilledSalesQuantity">actChargeableUnbilledSalesQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Chargeable Unbilled Sales Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actchargeableunbilledsalesquantity</td></tr></table>

### <a href=#actNoChargeBilledSalesAmount name="actNoChargeBilledSalesAmount">actNoChargeBilledSalesAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual No Charge Billed Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnochargebilledsalesamount</td></tr></table>

### <a href=#actNoChargeBilledSalesAmountBase name="actNoChargeBilledSalesAmountBase">actNoChargeBilledSalesAmountBase</a>

Value of the Actual No Charge Billed Sales Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual No Charge Billed Sales Amount (Base)</td></tr><tr><td>description</td><td>Value of the Actual No Charge Billed Sales Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnochargebilledsalesamount_base</td></tr></table>

### <a href=#actNoChargeBilledSalesQuantity name="actNoChargeBilledSalesQuantity">actNoChargeBilledSalesQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual No Charge Billed Sales Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnochargebilledsalesquantity</td></tr></table>

### <a href=#actNoChargeCostAmount name="actNoChargeCostAmount">actNoChargeCostAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual No Charge Cost Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnochargecostamount</td></tr></table>

### <a href=#actNoChargeCostAmountBase name="actNoChargeCostAmountBase">actNoChargeCostAmountBase</a>

Value of the Actual No Charge Cost Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual No Charge Cost Amount (Base)</td></tr><tr><td>description</td><td>Value of the Actual No Charge Cost Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnochargecostamount_base</td></tr></table>

### <a href=#actNoChargeCostQuantity name="actNoChargeCostQuantity">actNoChargeCostQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual No Charge Cost Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnochargecostquantity</td></tr></table>

### <a href=#actNoChargeUnbilledSalesAmount name="actNoChargeUnbilledSalesAmount">actNoChargeUnbilledSalesAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual No Charge Unbilled Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnochargeunbilledsalesamount</td></tr></table>

### <a href=#actNoChargeUnbilledSalesAmountBase name="actNoChargeUnbilledSalesAmountBase">actNoChargeUnbilledSalesAmountBase</a>

Value of the Actual No Charge Unbilled Sales Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual No Charge Unbilled Sales Amount (Base)</td></tr><tr><td>description</td><td>Value of the Actual No Charge Unbilled Sales Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnochargeunbilledsalesamount_base</td></tr></table>

### <a href=#actNoChargeUnbilledSalesQuantity name="actNoChargeUnbilledSalesQuantity">actNoChargeUnbilledSalesQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual No Charge Unbilled Sales Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnochargeunbilledsalesquantity</td></tr></table>

### <a href=#actNonChargeableCostAmount name="actNonChargeableCostAmount">actNonChargeableCostAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Non Chargeable Cost Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnonchargeablecostamount</td></tr></table>

### <a href=#actNonChargeableCostAmountBase name="actNonChargeableCostAmountBase">actNonChargeableCostAmountBase</a>

Value of the Actual Non Chargeable Cost Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Non Chargeable Cost Amount (Base)</td></tr><tr><td>description</td><td>Value of the Actual Non Chargeable Cost Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnonchargeablecostamount_base</td></tr></table>

### <a href=#actNonChargeableCostQuantity name="actNonChargeableCostQuantity">actNonChargeableCostQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Non Chargeable Cost Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnonchargeablecostquantity</td></tr></table>

### <a href=#actNonChargeableUnbilledSalesAmount name="actNonChargeableUnbilledSalesAmount">actNonChargeableUnbilledSalesAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Non Chargeable Unbilled Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnonchargeableunbilledsalesamount</td></tr></table>

### <a href=#actNonChargeableUnbilledSalesAmountBase name="actNonChargeableUnbilledSalesAmountBase">actNonChargeableUnbilledSalesAmountBase</a>

Value of the Actual Non Chargeable Unbilled Sales Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Non Chargeable Unbilled Sales Amount (Base)</td></tr><tr><td>description</td><td>Value of the Actual Non Chargeable Unbilled Sales Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnonchargeableunbilledsalesamount_base</td></tr></table>

### <a href=#actNonChargeableUnbilledSalesQuantity name="actNonChargeableUnbilledSalesQuantity">actNonChargeableUnbilledSalesQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Non Chargeable Unbilled Sales Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actnonchargeableunbilledsalesquantity</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#contactCustomer name="contactCustomer">contactCustomer</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contactcustomer</td></tr></table>

### <a href=#contactVendor name="contactVendor">contactVendor</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contactvendor</td></tr></table>

### <a href=#customerType name="customerType">customerType</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#customerType_display name="customerType_display">customerType_display</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#documentDate name="documentDate">documentDate</a>

Enter the transaction date of the business event.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document Date</td></tr><tr><td>description</td><td>Enter the transaction date of the business event.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_documentdate</td></tr></table>

### <a href=#endDate name="endDate">endDate</a>

Enter the end date for this transaction.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>description</td><td>Enter the end date for this transaction.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_enddate</td></tr></table>

### <a href=#estChargeableBilledSalesAmount name="estChargeableBilledSalesAmount">estChargeableBilledSalesAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Chargeable Billed Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estchargeablebilledsalesamount</td></tr></table>

### <a href=#estChargeableBilledSalesAmountBase name="estChargeableBilledSalesAmountBase">estChargeableBilledSalesAmountBase</a>

Value of the Estimated Chargeable Billed Sales Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Chargeable Billed Sales Amount (Base)</td></tr><tr><td>description</td><td>Value of the Estimated Chargeable Billed Sales Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estchargeablebilledsalesamount_base</td></tr></table>

### <a href=#estChargeableBilledSalesQuantity name="estChargeableBilledSalesQuantity">estChargeableBilledSalesQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Chargeable Billed Sales Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estchargeablebilledsalesquantity</td></tr></table>

### <a href=#estChargeableCostAmount name="estChargeableCostAmount">estChargeableCostAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Chargeable Cost Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estchargeablecostamount</td></tr></table>

### <a href=#estChargeableCostAmountBase name="estChargeableCostAmountBase">estChargeableCostAmountBase</a>

Value of the Estimated Chargeable Cost Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Chargeable Cost Amount (Base)</td></tr><tr><td>description</td><td>Value of the Estimated Chargeable Cost Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estchargeablecostamount_base</td></tr></table>

### <a href=#estChargeableCostQuantity name="estChargeableCostQuantity">estChargeableCostQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Chargeable Cost Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estchargeablecostquantity</td></tr></table>

### <a href=#estChargeableUnbilledSalesAmount name="estChargeableUnbilledSalesAmount">estChargeableUnbilledSalesAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Chargeable Unbilled Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estchargeableunbilledsalesamount</td></tr></table>

### <a href=#estChargeableUnbilledSalesAmountBase name="estChargeableUnbilledSalesAmountBase">estChargeableUnbilledSalesAmountBase</a>

Value of the Estimated Chargeable Unbilled Sales Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Chargeable Unbilled Sales Amount (Base)</td></tr><tr><td>description</td><td>Value of the Estimated Chargeable Unbilled Sales Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estchargeableunbilledsalesamount_base</td></tr></table>

### <a href=#estChargeableUnbilledSalesQuantity name="estChargeableUnbilledSalesQuantity">estChargeableUnbilledSalesQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Chargeable Unbilled Sales Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estchargeableunbilledsalesquantity</td></tr></table>

### <a href=#estimate name="estimate">estimate</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimate</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estimate</td></tr></table>

### <a href=#estimateLineId name="estimateLineId">estimateLineId</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimate Line</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estimatelineid</td></tr></table>

### <a href=#estNoChargeBilledSalesAmount name="estNoChargeBilledSalesAmount">estNoChargeBilledSalesAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated No Charge Billed Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnochargebilledsalesamount</td></tr></table>

### <a href=#estNoChargeBilledSalesAmountBase name="estNoChargeBilledSalesAmountBase">estNoChargeBilledSalesAmountBase</a>

Value of the Estimated No Charge Billed Sales Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated No Charge Billed Sales Amount (Base)</td></tr><tr><td>description</td><td>Value of the Estimated No Charge Billed Sales Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnochargebilledsalesamount_base</td></tr></table>

### <a href=#estNoChargeBilledSalesQuantity name="estNoChargeBilledSalesQuantity">estNoChargeBilledSalesQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated No Charge Billed Sales Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnochargebilledsalesquantity</td></tr></table>

### <a href=#estNoChargeCostAmount name="estNoChargeCostAmount">estNoChargeCostAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated No Charge Cost Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnochargecostamount</td></tr></table>

### <a href=#estNoChargeCostAmountBase name="estNoChargeCostAmountBase">estNoChargeCostAmountBase</a>

Value of the Estimated No Charge Cost Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated No Charge Cost Amount (Base)</td></tr><tr><td>description</td><td>Value of the Estimated No Charge Cost Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnochargecostamount_base</td></tr></table>

### <a href=#estNoChargeCostQuantity name="estNoChargeCostQuantity">estNoChargeCostQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated No Charge Cost Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnochargecostquantity</td></tr></table>

### <a href=#estNoChargeUnbilledSalesAmount name="estNoChargeUnbilledSalesAmount">estNoChargeUnbilledSalesAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated No Charge Unbilled Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnochargeunbilledsalesamount</td></tr></table>

### <a href=#estNoChargeUnbilledSalesAmountBase name="estNoChargeUnbilledSalesAmountBase">estNoChargeUnbilledSalesAmountBase</a>

Value of the Estimated No Charge Unbilled Sales Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated No Charge Unbilled Sales Amount (Base)</td></tr><tr><td>description</td><td>Value of the Estimated No Charge Unbilled Sales Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnochargeunbilledsalesamount_base</td></tr></table>

### <a href=#estNoChargeUnbilledSalesQuantity name="estNoChargeUnbilledSalesQuantity">estNoChargeUnbilledSalesQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated No Charge Unbilled Sales Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnochargeunbilledsalesquantity</td></tr></table>

### <a href=#estNonChargeableCostAmount name="estNonChargeableCostAmount">estNonChargeableCostAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Non Chargeable Cost Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnonchargeablecostamount</td></tr></table>

### <a href=#estNonChargeableCostAmountBase name="estNonChargeableCostAmountBase">estNonChargeableCostAmountBase</a>

Value of the Estimated Non Chargeable Cost Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Non Chargeable Cost Amount (Base)</td></tr><tr><td>description</td><td>Value of the Estimated Non Chargeable Cost Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnonchargeablecostamount_base</td></tr></table>

### <a href=#estNonChargeableCostQuantity name="estNonChargeableCostQuantity">estNonChargeableCostQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Non Chargeable Cost Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnonchargeablecostquantity</td></tr></table>

### <a href=#estNonChargeableUnbilledSalesAmount name="estNonChargeableUnbilledSalesAmount">estNonChargeableUnbilledSalesAmount</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Non Chargeable Unbilled Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnonchargeableunbilledsalesamount</td></tr></table>

### <a href=#estNonChargeableUnbilledSalesAmountBase name="estNonChargeableUnbilledSalesAmountBase">estNonChargeableUnbilledSalesAmountBase</a>

Value of the Estimated Non Chargeable Unbilled Sales Amount in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Non Chargeable Unbilled Sales Amount (Base)</td></tr><tr><td>description</td><td>Value of the Estimated Non Chargeable Unbilled Sales Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnonchargeableunbilledsalesamount_base</td></tr></table>

### <a href=#estNonChargeableUnbilledSalesQuantity name="estNonChargeableUnbilledSalesQuantity">estNonChargeableUnbilledSalesQuantity</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Non Chargeable Unbilled Sales Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estnonchargeableunbilledsalesquantity</td></tr></table>

### <a href=#factType name="factType">factType</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fact Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_facttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Actual</td><td>192350000</td></tr><tr><td>en</td><td>Estimate</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#factType_display name="factType_display">factType_display</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#product name="product">product</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_product</td></tr></table>

### <a href=#project name="project">project</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#salesContract name="salesContract">salesContract</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontract</td></tr></table>

### <a href=#salesContractLine name="salesContractLine">salesContractLine</a>

(Deprecated)  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Project Contract Line</td></tr><tr><td>description</td><td>(Deprecated)</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontractline</td></tr></table>

### <a href=#salesContractLineId name="salesContractLineId">salesContractLineId</a>

Unique identifier for Project Contract Line associated with Fact.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract Line</td></tr><tr><td>description</td><td>Unique identifier for Project Contract Line associated with Fact.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontractlineid</td></tr></table>

### <a href=#startDate name="startDate">startDate</a>

Enter the start date.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Enter the start date.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_startdate</td></tr></table>

### <a href=#task name="task">task</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Task</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_task</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>

### <a href=#transactionClassification name="transactionClassification">transactionClassification</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Classification</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactionclassification</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time</td><td>192350000</td></tr><tr><td>en</td><td>Expense</td><td>192350001</td></tr><tr><td>en</td><td>Material</td><td>192350002</td></tr><tr><td>en</td><td>Milestone</td><td>192350003</td></tr><tr><td>en</td><td>Fee</td><td>192350004</td></tr><tr><td>en</td><td>Tax</td><td>690970002</td></tr></table></td></tr></table>

### <a href=#transactionClassification_display name="transactionClassification_display">transactionClassification_display</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#vendorType name="vendorType">vendorType</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_vendortype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#vendorType_display name="vendorType_display">vendorType_display</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#earnedRevenue name="earnedRevenue">earnedRevenue</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Earned Revenue</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_earnedrevenue</td></tr></table>

### <a href=#earnedRevenueBase name="earnedRevenueBase">earnedRevenueBase</a>

Value of the Earned Revenue in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Earned Revenue (Base)</td></tr><tr><td>description</td><td>Value of the Earned Revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_earnedrevenue_base</td></tr></table>

### <a href=#grossMargin name="grossMargin">grossMargin</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Gross Margin</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_grossmargin</td></tr></table>

### <a href=#grossMarginBase name="grossMarginBase">grossMarginBase</a>

Value of the Gross Margin in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Gross Margin (Base)</td></tr><tr><td>description</td><td>Value of the Gross Margin in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_grossmargin_base</td></tr></table>

### <a href=#totalCost name="totalCost">totalCost</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Cost</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalcost</td></tr></table>

### <a href=#totalCostBase name="totalCostBase">totalCostBase</a>

Value of the Total Cost in base currency.  
First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Cost (Base)</td></tr><tr><td>description</td><td>Value of the Total Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalcost_base</td></tr></table>

### <a href=#totalHours name="totalHours">totalHours</a>

First included in: projectServiceAutomation/Fact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Hours</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalhours</td></tr></table>

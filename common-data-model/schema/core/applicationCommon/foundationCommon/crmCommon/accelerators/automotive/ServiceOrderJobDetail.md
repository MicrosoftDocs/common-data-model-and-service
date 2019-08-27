---
title: ServiceOrderJobDetail - Common Data Model | Microsoft Docs
description: Record of time, material or other information relating to the execution of a given service order job.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Service Order Job Detail

Record of time, material or other information relating to the execution of a given service order job.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/ServiceOrderJobDetail.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/ServiceOrderJobDetail  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[actualQuantity](#actualQuantity)|Actual number of item used in the service order for this job.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[amount](#amount)|The amount of this item.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[amountBase](#amountBase)|Value of the amount in base currency.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[businessOperationId](#businessOperationId)|Department/team at the service workshop responsible for service  job including this item.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[description](#description)|Description of the service order job detail.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[deviceWarrantyId](#deviceWarrantyId)|Specific automobile warranty for which this service job detail applies.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[discount](#discount)|Amount of discount applied to service job detail.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[discountBase](#discountBase)|Value of the Discount in base currency.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[estimatedAmount](#estimatedAmount)|Estimated cost of the service job detail.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[estimatedAmountBase](#estimatedAmountBase)|Value of the Estimated Amount in base currency.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[expectedQuantity](#expectedQuantity)|Estimated quantity of this item needed for the service job detail.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[itemName](#itemName)|Name of the item being used for this service job detail.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[name](#name)|Name of the service order job detail.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[operationCodeId](#operationCodeId)|Operation code associated to this service job detail. |<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[paySubtype](#paySubtype)|Sub type of the pay type associated to this service job detail.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[payType](#payType)|Who is paying for this service job (customer, OEM warranty, 3rd party warranty or dealer).|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[payType_display](#payType_display)||<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[projectName](#projectName)|The name of this service job project.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[salesPrice](#salesPrice)|The sales price for this item.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[salesPriceBase](#salesPriceBase)|Value of the Sales Price in base currency.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[serviceContractId](#serviceContractId)|The service contract associated to this service order job detail.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[serviceOrderId](#serviceOrderId)|The parent service order for this service order job detail.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[serviceOrderJobDetailId](#serviceOrderJobDetailId)|Unique identifier for entity instances|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[serviceOrderJobId](#serviceOrderJobId)|The parent service order job for this service order job detail.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[subcontractorAccountId](#subcontractorAccountId)|The subcontractor hired for this part of the service job.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[subcontractorPurchaseOrder](#subcontractorPurchaseOrder)|Purchase order for the subcontractor hired for this part of the service job.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[technicianId](#technicianId)|Service technician who carries out this part of the service job.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[type](#type)|Type of service job detail (operation, material, expense or subcontract).|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[type_display](#type_display)||<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[stateCode](#stateCode)|Status of the Service Order Job Detail|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[stateCode_display](#stateCode_display)||<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[statusCode](#statusCode)|Reason for the status of the Service Order Job Detail|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[statusCode_display](#statusCode_display)||<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="ServiceOrderJobDetail.md" target="_blank">automotive/ServiceOrderJobDetail</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#actualQuantity name="actualQuantity">actualQuantity</a>

Actual number of item used in the service order for this job.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Quantity</td></tr><tr><td>description</td><td>Actual number of item used in the service order for this job.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msauto_actualquantity</td></tr></table>

### <a href=#amount name="amount">amount</a>

The amount of this item.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>The amount of this item.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_amount</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the amount in base currency.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_amount_base</td></tr></table>

### <a href=#businessOperationId name="businessOperationId">businessOperationId</a>

Department/team at the service workshop responsible for service  job including this item.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Operation</td></tr><tr><td>description</td><td>Department/team at the service workshop responsible for service  job including this item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_businessoperationid</td></tr></table>

### <a href=#description name="description">description</a>

Description of the service order job detail.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the service order job detail.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_description</td></tr></table>

### <a href=#deviceWarrantyId name="deviceWarrantyId">deviceWarrantyId</a>

Specific automobile warranty for which this service job detail applies.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Warranty</td></tr><tr><td>description</td><td>Specific automobile warranty for which this service job detail applies.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicewarrantyid</td></tr></table>

### <a href=#discount name="discount">discount</a>

Amount of discount applied to service job detail.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount</td></tr><tr><td>description</td><td>Amount of discount applied to service job detail.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_discount</td></tr></table>

### <a href=#discountBase name="discountBase">discountBase</a>

Value of the Discount in base currency.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount (Base)</td></tr><tr><td>description</td><td>Value of the Discount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_discount_base</td></tr></table>

### <a href=#estimatedAmount name="estimatedAmount">estimatedAmount</a>

Estimated cost of the service job detail.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Amount</td></tr><tr><td>description</td><td>Estimated cost of the service job detail.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_estimatedamount</td></tr></table>

### <a href=#estimatedAmountBase name="estimatedAmountBase">estimatedAmountBase</a>

Value of the Estimated Amount in base currency.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Amount (Base)</td></tr><tr><td>description</td><td>Value of the Estimated Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_estimatedamount_base</td></tr></table>

### <a href=#expectedQuantity name="expectedQuantity">expectedQuantity</a>

Estimated quantity of this item needed for the service job detail.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Quantity</td></tr><tr><td>description</td><td>Estimated quantity of this item needed for the service job detail.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msauto_expectedquantity</td></tr></table>

### <a href=#itemName name="itemName">itemName</a>

Name of the item being used for this service job detail.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item Name</td></tr><tr><td>description</td><td>Name of the item being used for this service job detail.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_itemname</td></tr></table>

### <a href=#name name="name">name</a>

Name of the service order job detail.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the service order job detail.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#operationCodeId name="operationCodeId">operationCodeId</a>

Operation code associated to this service job detail.   
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operation Code</td></tr><tr><td>description</td><td>Operation code associated to this service job detail. </td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_operationcodeid</td></tr></table>

### <a href=#paySubtype name="paySubtype">paySubtype</a>

Sub type of the pay type associated to this service job detail.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pay Subtype</td></tr><tr><td>description</td><td>Sub type of the pay type associated to this service job detail.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_paysubtype</td></tr></table>

### <a href=#payType name="payType">payType</a>

Who is paying for this service job (customer, OEM warranty, 3rd party warranty or dealer).  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pay Type</td></tr><tr><td>description</td><td>Who is paying for this service job (customer, OEM warranty, 3rd party warranty or dealer).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_paytype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#payType_display name="payType_display">payType_display</a>

First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#projectName name="projectName">projectName</a>

The name of this service job project.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Name</td></tr><tr><td>description</td><td>The name of this service job project.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_projectname</td></tr></table>

### <a href=#salesPrice name="salesPrice">salesPrice</a>

The sales price for this item.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Price</td></tr><tr><td>description</td><td>The sales price for this item.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_salesprice</td></tr></table>

### <a href=#salesPriceBase name="salesPriceBase">salesPriceBase</a>

Value of the Sales Price in base currency.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Price (Base)</td></tr><tr><td>description</td><td>Value of the Sales Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_salesprice_base</td></tr></table>

### <a href=#serviceContractId name="serviceContractId">serviceContractId</a>

The service contract associated to this service order job detail.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service Contract</td></tr><tr><td>description</td><td>The service contract associated to this service order job detail.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_servicecontractid</td></tr></table>

### <a href=#serviceOrderId name="serviceOrderId">serviceOrderId</a>

The parent service order for this service order job detail.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service Order</td></tr><tr><td>description</td><td>The parent service order for this service order job detail.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_serviceorderid</td></tr></table>

### <a href=#serviceOrderJobDetailId name="serviceOrderJobDetailId">serviceOrderJobDetailId</a>

Unique identifier for entity instances  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service Order Job Detail</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_serviceorderjobdetailid</td></tr></table>

### <a href=#serviceOrderJobId name="serviceOrderJobId">serviceOrderJobId</a>

The parent service order job for this service order job detail.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service Order Job</td></tr><tr><td>description</td><td>The parent service order job for this service order job detail.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_serviceorderjobid</td></tr></table>

### <a href=#subcontractorAccountId name="subcontractorAccountId">subcontractorAccountId</a>

The subcontractor hired for this part of the service job.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subcontractor Account</td></tr><tr><td>description</td><td>The subcontractor hired for this part of the service job.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_subcontractoraccountid</td></tr></table>

### <a href=#subcontractorPurchaseOrder name="subcontractorPurchaseOrder">subcontractorPurchaseOrder</a>

Purchase order for the subcontractor hired for this part of the service job.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subcontractor Purchase Order</td></tr><tr><td>description</td><td>Purchase order for the subcontractor hired for this part of the service job.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_subcontractorpurchaseorder</td></tr></table>

### <a href=#technicianId name="technicianId">technicianId</a>

Service technician who carries out this part of the service job.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Technician</td></tr><tr><td>description</td><td>Service technician who carries out this part of the service job.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_technicianid</td></tr></table>

### <a href=#type name="type">type</a>

Type of service job detail (operation, material, expense or subcontract).  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Type of service job detail (operation, material, expense or subcontract).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Service Order Job Detail  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Service Order Job Detail</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Service Order Job Detail  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Service Order Job Detail</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: automotive/ServiceOrderJobDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

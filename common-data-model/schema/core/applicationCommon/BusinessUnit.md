---
title: BusinessUnit - Common Data Model | Microsoft Docs
description: Business, division, or department in the Microsoft Dynamics 365 database.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Business Unit

Business, division, or department in the Microsoft Dynamics 365 database.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/BusinessUnit.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /BusinessUnit  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[businessUnitId](#businessUnitId)|Unique identifier of the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[name](#name)|Name of the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[description](#description)|Description of the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[divisionName](#divisionName)|Name of the division to which the business unit belongs.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[fileAsName](#fileAsName)|Alternative name under which the business unit can be filed.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[tickerSymbol](#tickerSymbol)|Stock exchange ticker symbol for the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[stockExchange](#stockExchange)|Stock exchange on which the business is listed.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[UTCOffset](#UTCOffset)|UTC offset for the business unit. This is the difference between local time and standard Coordinated Universal Time.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[createdOn](#createdOn)|Date and time when the business unit was created.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[modifiedOn](#modifiedOn)|Date and time when the business unit was last modified.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[creditLimit](#creditLimit)|Credit limit for the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[costCenter](#costCenter)|Name of the business unit cost center.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[webSiteUrl](#webSiteUrl)|Website URL for the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[ftpSiteUrl](#ftpSiteUrl)|FTP site URL for the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[emailAddress](#emailAddress)|Email address for the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[inheritanceMask](#inheritanceMask)|Inheritance mask for the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[workflowSuspended](#workflowSuspended)|Information about whether workflow or sales process rules have been suspended.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[parentBusinessUnitId](#parentBusinessUnitId)|Unique identifier for the parent business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[isDisabled](#isDisabled)|Information about whether the business unit is enabled or disabled.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[disabledReason](#disabledReason)|Reason for disabling the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[versionNumber](#versionNumber)|Version number of the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1AddressId](#address1AddressId)|Unique identifier for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1AddressTypeCode](#address1AddressTypeCode)|Type of address for address 1, such as billing, shipping, or primary address.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1AddressTypeCode_display](#address1AddressTypeCode_display)||<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1Name](#address1Name)|Name to enter for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1Line1](#address1Line1)|First line for entering address 1 information.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1Line2](#address1Line2)|Second line for entering address 1 information.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1Line3](#address1Line3)|Third line for entering address 1 information.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1City](#address1City)|City name for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1StateOrProvince](#address1StateOrProvince)|State or province for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1County](#address1County)|County name for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1Country](#address1Country)|Country/region name for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1PostOfficeBox](#address1PostOfficeBox)|Post office box number for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1PostalCode](#address1PostalCode)|ZIP Code or postal code for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1UTCOffset](#address1UTCOffset)|UTC offset for address 1. This is the difference between local time and standard Coordinated Universal Time.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1UPSZone](#address1UPSZone)|United Parcel Service (UPS) zone for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1Latitude](#address1Latitude)|Latitude for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1Telephone1](#address1Telephone1)|First telephone number associated with address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1Longitude](#address1Longitude)|Longitude for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1ShippingMethodCode](#address1ShippingMethodCode)|Method of shipment for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1ShippingMethodCode_display](#address1ShippingMethodCode_display)||<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1Telephone2](#address1Telephone2)|Second telephone number associated with address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1Telephone3](#address1Telephone3)|Third telephone number associated with address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address1Fax](#address1Fax)|Fax number for address 1.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2AddressId](#address2AddressId)|Unique identifier for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2AddressTypeCode](#address2AddressTypeCode)|Type of address for address 2, such as billing, shipping, or primary address.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2AddressTypeCode_display](#address2AddressTypeCode_display)||<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2Name](#address2Name)|Name to enter for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2Line1](#address2Line1)|First line for entering address 2 information.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2Line2](#address2Line2)|Second line for entering address 2 information.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2Line3](#address2Line3)|Third line for entering address 2 information.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2City](#address2City)|City name for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2StateOrProvince](#address2StateOrProvince)|State or province for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2County](#address2County)|County name for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2Country](#address2Country)|Country/region name for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2PostOfficeBox](#address2PostOfficeBox)|Post office box number for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2PostalCode](#address2PostalCode)|ZIP Code or postal code for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2UTCOffset](#address2UTCOffset)|UTC offset for address 2. This is the difference between local time and standard Coordinated Universal Time.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2UPSZone](#address2UPSZone)|United Parcel Service (UPS) zone for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2Latitude](#address2Latitude)|Latitude for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2Telephone1](#address2Telephone1)|First telephone number associated with address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2Longitude](#address2Longitude)|Longitude for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2ShippingMethodCode](#address2ShippingMethodCode)|Method of shipment for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2ShippingMethodCode_display](#address2ShippingMethodCode_display)||<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2Telephone2](#address2Telephone2)|Second telephone number associated with address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2Telephone3](#address2Telephone3)|Third telephone number associated with address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[address2Fax](#address2Fax)|Fax number for address 2.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[picture](#picture)|Picture or diagram of the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[calendarId](#calendarId)|Fiscal calendar associated with the business unit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the businessunit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the businessunit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the businessunit.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the businessunit with respect to the base currency.|<a href="BusinessUnit.md" target="_blank">applicationCommon/BusinessUnit</a>|

### <a href=#businessUnitId name="businessUnitId">businessUnitId</a>

Unique identifier of the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>businessunitid</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the business unit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#name name="name">name</a>

Name of the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the business unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#description name="description">description</a>

Description of the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the business unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#divisionName name="divisionName">divisionName</a>

Name of the division to which the business unit belongs.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Division</td></tr><tr><td>description</td><td>Name of the division to which the business unit belongs.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>divisionname</td></tr></table>

### <a href=#fileAsName name="fileAsName">fileAsName</a>

Alternative name under which the business unit can be filed.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>File as Name</td></tr><tr><td>description</td><td>Alternative name under which the business unit can be filed.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fileasname</td></tr></table>

### <a href=#tickerSymbol name="tickerSymbol">tickerSymbol</a>

Stock exchange ticker symbol for the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ticker Symbol</td></tr><tr><td>description</td><td>Stock exchange ticker symbol for the business unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>tickersymbol</td></tr></table>

### <a href=#stockExchange name="stockExchange">stockExchange</a>

Stock exchange on which the business is listed.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stock Exchange</td></tr><tr><td>description</td><td>Stock exchange on which the business is listed.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stockexchange</td></tr></table>

### <a href=#UTCOffset name="UTCOffset">UTCOffset</a>

UTC offset for the business unit. This is the difference between local time and standard Coordinated Universal Time.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Offset</td></tr><tr><td>description</td><td>UTC offset for the business unit. This is the difference between local time and standard Coordinated Universal Time.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcoffset</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the business unit was created.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the business unit was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the business unit was last modified.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the business unit was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#creditLimit name="creditLimit">creditLimit</a>

Credit limit for the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit Limit</td></tr><tr><td>description</td><td>Credit limit for the business unit.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>creditlimit</td></tr></table>

### <a href=#costCenter name="costCenter">costCenter</a>

Name of the business unit cost center.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Center</td></tr><tr><td>description</td><td>Name of the business unit cost center.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>costcenter</td></tr></table>

### <a href=#webSiteUrl name="webSiteUrl">webSiteUrl</a>

Website URL for the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Website URL for the business unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>websiteurl</td></tr></table>

### <a href=#ftpSiteUrl name="ftpSiteUrl">ftpSiteUrl</a>

FTP site URL for the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>FTP Site</td></tr><tr><td>description</td><td>FTP site URL for the business unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ftpsiteurl</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

Email address for the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email</td></tr><tr><td>description</td><td>Email address for the business unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#inheritanceMask name="inheritanceMask">inheritanceMask</a>

Inheritance mask for the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inheritance Mask</td></tr><tr><td>description</td><td>Inheritance mask for the business unit.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inheritancemask</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the business unit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the business unit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#workflowSuspended name="workflowSuspended">workflowSuspended</a>

Information about whether workflow or sales process rules have been suspended.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Workflow Suspended</td></tr><tr><td>description</td><td>Information about whether workflow or sales process rules have been suspended.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>workflowsuspended</td></tr></table>

### <a href=#parentBusinessUnitId name="parentBusinessUnitId">parentBusinessUnitId</a>

Unique identifier for the parent business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Business</td></tr><tr><td>description</td><td>Unique identifier for the parent business unit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentbusinessunitid</td></tr></table>

### <a href=#isDisabled name="isDisabled">isDisabled</a>

Information about whether the business unit is enabled or disabled.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Disabled</td></tr><tr><td>description</td><td>Information about whether the business unit is enabled or disabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isdisabled</td></tr></table>

### <a href=#disabledReason name="disabledReason">disabledReason</a>

Reason for disabling the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disable Reason</td></tr><tr><td>description</td><td>Reason for disabling the business unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>disabledreason</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version number</td></tr><tr><td>description</td><td>Version number of the business unit.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#address1AddressId name="address1AddressId">address1AddressId</a>

Unique identifier for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: ID</td></tr><tr><td>description</td><td>Unique identifier for address 1.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_addressid</td></tr></table>

### <a href=#address1AddressTypeCode name="address1AddressTypeCode">address1AddressTypeCode</a>

Type of address for address 1, such as billing, shipping, or primary address.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Address Type</td></tr><tr><td>description</td><td>Type of address for address 1, such as billing, shipping, or primary address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address1AddressTypeCode_display name="address1AddressTypeCode_display">address1AddressTypeCode_display</a>

First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1Name name="address1Name">address1Name</a>

Name to enter for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Name</td></tr><tr><td>description</td><td>Name to enter for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_name</td></tr></table>

### <a href=#address1Line1 name="address1Line1">address1Line1</a>

First line for entering address 1 information.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Street 1</td></tr><tr><td>description</td><td>First line for entering address 1 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line1</td></tr></table>

### <a href=#address1Line2 name="address1Line2">address1Line2</a>

Second line for entering address 1 information.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Street 2</td></tr><tr><td>description</td><td>Second line for entering address 1 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line2</td></tr></table>

### <a href=#address1Line3 name="address1Line3">address1Line3</a>

Third line for entering address 1 information.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Street 3</td></tr><tr><td>description</td><td>Third line for entering address 1 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line3</td></tr></table>

### <a href=#address1City name="address1City">address1City</a>

City name for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To City</td></tr><tr><td>description</td><td>City name for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_city</td></tr></table>

### <a href=#address1StateOrProvince name="address1StateOrProvince">address1StateOrProvince</a>

State or province for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To State/Province</td></tr><tr><td>description</td><td>State or province for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_stateorprovince</td></tr></table>

### <a href=#address1County name="address1County">address1County</a>

County name for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: County</td></tr><tr><td>description</td><td>County name for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_county</td></tr></table>

### <a href=#address1Country name="address1Country">address1Country</a>

Country/region name for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Country/Region</td></tr><tr><td>description</td><td>Country/region name for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_country</td></tr></table>

### <a href=#address1PostOfficeBox name="address1PostOfficeBox">address1PostOfficeBox</a>

Post office box number for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Post Office Box</td></tr><tr><td>description</td><td>Post office box number for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_postofficebox</td></tr></table>

### <a href=#address1PostalCode name="address1PostalCode">address1PostalCode</a>

ZIP Code or postal code for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To ZIP/Postal Code</td></tr><tr><td>description</td><td>ZIP Code or postal code for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_postalcode</td></tr></table>

### <a href=#address1UTCOffset name="address1UTCOffset">address1UTCOffset</a>

UTC offset for address 1. This is the difference between local time and standard Coordinated Universal Time.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: UTC Offset</td></tr><tr><td>description</td><td>UTC offset for address 1. This is the difference between local time and standard Coordinated Universal Time.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_utcoffset</td></tr></table>

### <a href=#address1UPSZone name="address1UPSZone">address1UPSZone</a>

United Parcel Service (UPS) zone for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: UPS Zone</td></tr><tr><td>description</td><td>United Parcel Service (UPS) zone for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_upszone</td></tr></table>

### <a href=#address1Latitude name="address1Latitude">address1Latitude</a>

Latitude for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Latitude</td></tr><tr><td>description</td><td>Latitude for address 1.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_latitude</td></tr></table>

### <a href=#address1Telephone1 name="address1Telephone1">address1Telephone1</a>

First telephone number associated with address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Phone</td></tr><tr><td>description</td><td>First telephone number associated with address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone1</td></tr></table>

### <a href=#address1Longitude name="address1Longitude">address1Longitude</a>

Longitude for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Longitude</td></tr><tr><td>description</td><td>Longitude for address 1.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_longitude</td></tr></table>

### <a href=#address1ShippingMethodCode name="address1ShippingMethodCode">address1ShippingMethodCode</a>

Method of shipment for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Shipping Method</td></tr><tr><td>description</td><td>Method of shipment for address 1.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address1ShippingMethodCode_display name="address1ShippingMethodCode_display">address1ShippingMethodCode_display</a>

First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1Telephone2 name="address1Telephone2">address1Telephone2</a>

Second telephone number associated with address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other Phone</td></tr><tr><td>description</td><td>Second telephone number associated with address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone2</td></tr></table>

### <a href=#address1Telephone3 name="address1Telephone3">address1Telephone3</a>

Third telephone number associated with address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Telephone 3</td></tr><tr><td>description</td><td>Third telephone number associated with address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone3</td></tr></table>

### <a href=#address1Fax name="address1Fax">address1Fax</a>

Fax number for address 1.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Fax</td></tr><tr><td>description</td><td>Fax number for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_fax</td></tr></table>

### <a href=#address2AddressId name="address2AddressId">address2AddressId</a>

Unique identifier for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: ID</td></tr><tr><td>description</td><td>Unique identifier for address 2.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_addressid</td></tr></table>

### <a href=#address2AddressTypeCode name="address2AddressTypeCode">address2AddressTypeCode</a>

Type of address for address 2, such as billing, shipping, or primary address.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Address Type</td></tr><tr><td>description</td><td>Type of address for address 2, such as billing, shipping, or primary address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address2AddressTypeCode_display name="address2AddressTypeCode_display">address2AddressTypeCode_display</a>

First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2Name name="address2Name">address2Name</a>

Name to enter for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Name</td></tr><tr><td>description</td><td>Name to enter for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_name</td></tr></table>

### <a href=#address2Line1 name="address2Line1">address2Line1</a>

First line for entering address 2 information.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 1</td></tr><tr><td>description</td><td>First line for entering address 2 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line1</td></tr></table>

### <a href=#address2Line2 name="address2Line2">address2Line2</a>

Second line for entering address 2 information.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 2</td></tr><tr><td>description</td><td>Second line for entering address 2 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line2</td></tr></table>

### <a href=#address2Line3 name="address2Line3">address2Line3</a>

Third line for entering address 2 information.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 3</td></tr><tr><td>description</td><td>Third line for entering address 2 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line3</td></tr></table>

### <a href=#address2City name="address2City">address2City</a>

City name for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To City</td></tr><tr><td>description</td><td>City name for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_city</td></tr></table>

### <a href=#address2StateOrProvince name="address2StateOrProvince">address2StateOrProvince</a>

State or province for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To State/Province</td></tr><tr><td>description</td><td>State or province for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_stateorprovince</td></tr></table>

### <a href=#address2County name="address2County">address2County</a>

County name for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: County</td></tr><tr><td>description</td><td>County name for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_county</td></tr></table>

### <a href=#address2Country name="address2Country">address2Country</a>

Country/region name for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Country/Region</td></tr><tr><td>description</td><td>Country/region name for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_country</td></tr></table>

### <a href=#address2PostOfficeBox name="address2PostOfficeBox">address2PostOfficeBox</a>

Post office box number for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Post Office Box</td></tr><tr><td>description</td><td>Post office box number for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_postofficebox</td></tr></table>

### <a href=#address2PostalCode name="address2PostalCode">address2PostalCode</a>

ZIP Code or postal code for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To ZIP/Postal Code</td></tr><tr><td>description</td><td>ZIP Code or postal code for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_postalcode</td></tr></table>

### <a href=#address2UTCOffset name="address2UTCOffset">address2UTCOffset</a>

UTC offset for address 2. This is the difference between local time and standard Coordinated Universal Time.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: UTC Offset</td></tr><tr><td>description</td><td>UTC offset for address 2. This is the difference between local time and standard Coordinated Universal Time.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_utcoffset</td></tr></table>

### <a href=#address2UPSZone name="address2UPSZone">address2UPSZone</a>

United Parcel Service (UPS) zone for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: UPS Zone</td></tr><tr><td>description</td><td>United Parcel Service (UPS) zone for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_upszone</td></tr></table>

### <a href=#address2Latitude name="address2Latitude">address2Latitude</a>

Latitude for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Latitude</td></tr><tr><td>description</td><td>Latitude for address 2.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_latitude</td></tr></table>

### <a href=#address2Telephone1 name="address2Telephone1">address2Telephone1</a>

First telephone number associated with address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 1</td></tr><tr><td>description</td><td>First telephone number associated with address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone1</td></tr></table>

### <a href=#address2Longitude name="address2Longitude">address2Longitude</a>

Longitude for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Longitude</td></tr><tr><td>description</td><td>Longitude for address 2.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_longitude</td></tr></table>

### <a href=#address2ShippingMethodCode name="address2ShippingMethodCode">address2ShippingMethodCode</a>

Method of shipment for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Shipping Method</td></tr><tr><td>description</td><td>Method of shipment for address 2.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address2ShippingMethodCode_display name="address2ShippingMethodCode_display">address2ShippingMethodCode_display</a>

First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2Telephone2 name="address2Telephone2">address2Telephone2</a>

Second telephone number associated with address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 2</td></tr><tr><td>description</td><td>Second telephone number associated with address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone2</td></tr></table>

### <a href=#address2Telephone3 name="address2Telephone3">address2Telephone3</a>

Third telephone number associated with address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 3</td></tr><tr><td>description</td><td>Third telephone number associated with address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone3</td></tr></table>

### <a href=#address2Fax name="address2Fax">address2Fax</a>

Fax number for address 2.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Fax</td></tr><tr><td>description</td><td>Fax number for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_fax</td></tr></table>

### <a href=#picture name="picture">picture</a>

Picture or diagram of the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Picture</td></tr><tr><td>description</td><td>Picture or diagram of the business unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>picture</td></tr></table>

### <a href=#calendarId name="calendarId">calendarId</a>

Fiscal calendar associated with the business unit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calendar</td></tr><tr><td>description</td><td>Fiscal calendar associated with the business unit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>calendarid</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the businessunit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the businessunit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the businessunit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the businessunit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the businessunit.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the businessunit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the businessunit with respect to the base currency.  
First included in: applicationCommon/BusinessUnit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the businessunit with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

---
title: LeadAddress - Common Data Model | Microsoft Docs
description: Address information for a lead.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Lead Address

Address information for a lead.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/LeadAddress.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/LeadAddress  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[leadAddressId](#leadAddressId)|Unique identifier of the lead address.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[createdOn](#createdOn)|Date and time when the lead address was created.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the lead address.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[modifiedOn](#modifiedOn)|Date and time when the lead address was last modified.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the lead address.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the leadaddress.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the leadaddress.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[name](#name)|Name used to identify the lead address.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[addressNumber](#addressNumber)|Information about the address for the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[addressTypeCode](#addressTypeCode)|Type of address for the lead address.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[addressTypeCode_display](#addressTypeCode_display)||<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[city](#city)|City name in the address for the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[composite](#composite)|Shows the complete address.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[country](#country)|Country/region name in the address for the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[county](#county)|County name in the address for the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[fax](#fax)|Fax number for the address for the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[latitude](#latitude)|Latitude for the address for the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[line1](#line1)|First line for entering address information.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[line2](#line2)|Second line for entering address information.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[line3](#line3)|Third line for entering address information.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[longitude](#longitude)|Longitude for the address for the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[parentId](#parentId)|Unique identifier of the parent object with which the lead address is associated.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[postalCode](#postalCode)|ZIP Code or postal code in the address for the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[postOfficeBox](#postOfficeBox)|Post office box number in the address for the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[shippingMethodCode](#shippingMethodCode)|Method of shipment for the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[shippingMethodCode_display](#shippingMethodCode_display)||<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[stateOrProvince](#stateOrProvince)|State or province in the address for the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[telephone1](#telephone1)|First telephone number for the lead address.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[telephone2](#telephone2)|Second telephone number for the lead address.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[telephone3](#telephone3)|Third telephone number for the lead address.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[UPSZone](#UPSZone)|United Parcel Service (UPS) zone for the address of the lead.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[UTCOffset](#UTCOffset)|UTC offset for the lead address. This is the difference between local time and standard Coordinated Universal Time.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the leadaddress with respect to the base currency.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the leadaddress.|<a href="LeadAddress.md" target="_blank">crmCommon/LeadAddress</a>|

### <a href=#leadAddressId name="leadAddressId">leadAddressId</a>

Unique identifier of the lead address.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>description</td><td>Unique identifier of the lead address.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>leadaddressid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the lead address was created.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the lead address was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the lead address.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the lead address.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the lead address was last modified.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the lead address was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the lead address.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the lead address.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the leadaddress.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the leadaddress.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the leadaddress.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the leadaddress.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Name used to identify the lead address.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Name</td></tr><tr><td>description</td><td>Name used to identify the lead address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#addressNumber name="addressNumber">addressNumber</a>

Information about the address for the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Number</td></tr><tr><td>description</td><td>Information about the address for the lead.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addressnumber</td></tr></table>

### <a href=#addressTypeCode name="addressTypeCode">addressTypeCode</a>

Type of address for the lead address.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Type</td></tr><tr><td>description</td><td>Type of address for the lead address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#addressTypeCode_display name="addressTypeCode_display">addressTypeCode_display</a>

First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#city name="city">city</a>

City name in the address for the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City name in the address for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>city</td></tr></table>

### <a href=#composite name="composite">composite</a>

Shows the complete address.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>description</td><td>Shows the complete address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>composite</td></tr></table>

### <a href=#country name="country">country</a>

Country/region name in the address for the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Country/region name in the address for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>country</td></tr></table>

### <a href=#county name="county">county</a>

County name in the address for the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>County</td></tr><tr><td>description</td><td>County name in the address for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>county</td></tr></table>

### <a href=#fax name="fax">fax</a>

Fax number for the address for the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Fax number for the address for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fax</td></tr></table>

### <a href=#latitude name="latitude">latitude</a>

Latitude for the address for the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Latitude</td></tr><tr><td>description</td><td>Latitude for the address for the lead.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>latitude</td></tr></table>

### <a href=#line1 name="line1">line1</a>

First line for entering address information.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 1</td></tr><tr><td>description</td><td>First line for entering address information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line1</td></tr></table>

### <a href=#line2 name="line2">line2</a>

Second line for entering address information.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 2</td></tr><tr><td>description</td><td>Second line for entering address information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line2</td></tr></table>

### <a href=#line3 name="line3">line3</a>

Third line for entering address information.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 3</td></tr><tr><td>description</td><td>Third line for entering address information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line3</td></tr></table>

### <a href=#longitude name="longitude">longitude</a>

Longitude for the address for the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Longitude</td></tr><tr><td>description</td><td>Longitude for the address for the lead.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>longitude</td></tr></table>

### <a href=#parentId name="parentId">parentId</a>

Unique identifier of the parent object with which the lead address is associated.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent</td></tr><tr><td>description</td><td>Unique identifier of the parent object with which the lead address is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>parentid</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

ZIP Code or postal code in the address for the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ZIP/Postal Code</td></tr><tr><td>description</td><td>ZIP Code or postal code in the address for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postalcode</td></tr></table>

### <a href=#postOfficeBox name="postOfficeBox">postOfficeBox</a>

Post office box number in the address for the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Office Box</td></tr><tr><td>description</td><td>Post office box number in the address for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postofficebox</td></tr></table>

### <a href=#shippingMethodCode name="shippingMethodCode">shippingMethodCode</a>

Method of shipment for the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Method of shipment for the lead.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#shippingMethodCode_display name="shippingMethodCode_display">shippingMethodCode_display</a>

First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateOrProvince name="stateOrProvince">stateOrProvince</a>

State or province in the address for the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>State or province in the address for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stateorprovince</td></tr></table>

### <a href=#telephone1 name="telephone1">telephone1</a>

First telephone number for the lead address.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Phone</td></tr><tr><td>description</td><td>First telephone number for the lead address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone1</td></tr></table>

### <a href=#telephone2 name="telephone2">telephone2</a>

Second telephone number for the lead address.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Phone 2</td></tr><tr><td>description</td><td>Second telephone number for the lead address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone2</td></tr></table>

### <a href=#telephone3 name="telephone3">telephone3</a>

Third telephone number for the lead address.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 3</td></tr><tr><td>description</td><td>Third telephone number for the lead address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone3</td></tr></table>

### <a href=#UPSZone name="UPSZone">UPSZone</a>

United Parcel Service (UPS) zone for the address of the lead.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UPS Zone</td></tr><tr><td>description</td><td>United Parcel Service (UPS) zone for the address of the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>upszone</td></tr></table>

### <a href=#UTCOffset name="UTCOffset">UTCOffset</a>

UTC offset for the lead address. This is the difference between local time and standard Coordinated Universal Time.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Offset</td></tr><tr><td>description</td><td>UTC offset for the lead address. This is the difference between local time and standard Coordinated Universal Time.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcoffset</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the leadaddress with respect to the base currency.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the leadaddress with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the leadaddress.  
First included in: crmCommon/LeadAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the leadaddress.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

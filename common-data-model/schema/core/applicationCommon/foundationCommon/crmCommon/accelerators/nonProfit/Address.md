---
title: Address - Common Data Model | Microsoft Docs
description: Address and shipping information. Used to store additional addresses for an account or a contact.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Address

Address and shipping information. Used to store additional addresses for an account or a contact.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Address.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/Address](../../../../Address.md "/core/applicationCommon/Address.cdm.json/Address")  
- [/foundationCommon/crmCommon/accelerators/education/higherEducation/Address](../education/higherEducation/Address.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/education/higherEducation/Address.cdm.json/Address")  
- [/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Address](../healthCare/electronicMedicalRecords/Address.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Address.cdm.json/Address")  
- /foundationCommon/crmCommon/accelerators/nonProfit/Address  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[parentIdTypeCode](#parentIdTypeCode)|The name of the entity linked by parentId|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[parentId](#parentId)|Choose the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[customerAddressId](#customerAddressId)|Unique identifier of the customer address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[addressNumber](#addressNumber)|Shows the number of the address, to indicate whether the address is the primary, secondary, or other address for the customer.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[objectTypeCode](#objectTypeCode)|Shows the type code of the customer record to indicate whether the address belongs to a customer account or contact.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[objectTypeCode_display](#objectTypeCode_display)||<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[addressTypeCode](#addressTypeCode)|Select the address type, such as primary or billing.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[addressTypeCode_display](#addressTypeCode_display)||<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[name](#name)|Type a descriptive name for the customer's address, such as Corporate Headquarters.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[primaryContactName](#primaryContactName)|Type the name of the primary contact person for the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[line1](#line1)|Type the first line of the customer's address to help identify the location.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[line2](#line2)|Type the second line of the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[line3](#line3)|Type the third line of the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[city](#city)|Type the city for the customer's address to help identify the location.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[stateOrProvince](#stateOrProvince)|Type the state or province of the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[county](#county)|Type the county for the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[country](#country)|Type the country or region for the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[postOfficeBox](#postOfficeBox)|Type the post office box number of the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[postalCode](#postalCode)|Type the ZIP Code or postal code for the address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[UTCOffset](#UTCOffset)|Select the time zone for the address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[freightTermsCode](#freightTermsCode)|Select the freight terms to make sure shipping charges are processed correctly.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[freightTermsCode_display](#freightTermsCode_display)||<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[UPSZone](#UPSZone)|Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[latitude](#latitude)|Type the latitude value for the customer's address, for use in mapping and other applications.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[telephone1](#telephone1)|Type the primary phone number for the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[longitude](#longitude)|Type the longitude value for the customer's address, for use in mapping and other applications.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[shippingMethodCode](#shippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[shippingMethodCode_display](#shippingMethodCode_display)||<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[telephone2](#telephone2)|Type a second phone number for the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[telephone3](#telephone3)|Type a third phone number for the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[fax](#fax)|Type the fax number associated with the customer's address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[versionNumber](#versionNumber)|Version number of the customer address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[createdOn](#createdOn)|Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[modifiedOn](#modifiedOn)|Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Shows the business unit that the record owner belongs to.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[owningUser](#owningUser)|Unique identifier of the user who owns the customer address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[composite](#composite)|Shows the complete address.|<a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>|
|[endDate](#endDate)|Effective end date of the address and related contact info|<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[isUspsValidated](#isUspsValidated)||<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[isvalidated](#isvalidated)|Indicates the address has been validated.|<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[region](#region)|Indicates the region of the world that the address is located.|<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[region_display](#region_display)||<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[seasonalEndDay](#seasonalEndDay)|Annual end day (of month) of the address and related contact info|<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[seasonalEndDay_display](#seasonalEndDay_display)||<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[seasonalEndMonth](#seasonalEndMonth)|Annual end month of the address and related contact info|<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[seasonalEndMonth_display](#seasonalEndMonth_display)||<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[seasonalStartDay](#seasonalStartDay)|Annual start day (of month) of the address and related contact info|<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[seasonalStartDay_display](#seasonalStartDay_display)||<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[seasonalStartMonth](#seasonalStartMonth)|Annual start month of the address and related contact info|<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[seasonalStartMonth_display](#seasonalStartMonth_display)||<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[startDate](#startDate)|Effective start date of the address and related contact info|<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[telephone1TypeCode](#telephone1TypeCode)||<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[telephone1TypeCode_display](#telephone1TypeCode_display)||<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[telephone2TypeCode](#telephone2TypeCode)||<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[telephone2TypeCode_display](#telephone2TypeCode_display)||<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[telephone3TypeCode](#telephone3TypeCode)||<a href="Address.md" target="_blank">nonProfit/Address</a>|
|[telephone3TypeCode_display](#telephone3TypeCode_display)||<a href="Address.md" target="_blank">nonProfit/Address</a>|

### <a href=#parentIdTypeCode name="parentIdTypeCode">parentIdTypeCode</a>

The name of the entity linked by parentId  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>parentId Type</td></tr><tr><td>description</td><td>The name of the entity linked by parentId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>parentidtypecode</td></tr></table>

### <a href=#parentId name="parentId">parentId</a>

Choose the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent</td></tr><tr><td>description</td><td>Choose the customer's address.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>parentid</td></tr></table>

### <a href=#customerAddressId name="customerAddressId">customerAddressId</a>

Unique identifier of the customer address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>description</td><td>Unique identifier of the customer address.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>customeraddressid</td></tr></table>

### <a href=#addressNumber name="addressNumber">addressNumber</a>

Shows the number of the address, to indicate whether the address is the primary, secondary, or other address for the customer.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Number</td></tr><tr><td>description</td><td>Shows the number of the address, to indicate whether the address is the primary, secondary, or other address for the customer.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addressnumber</td></tr></table>

### <a href=#objectTypeCode name="objectTypeCode">objectTypeCode</a>

Shows the type code of the customer record to indicate whether the address belongs to a customer account or contact.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Object Type </td></tr><tr><td>description</td><td>Shows the type code of the customer record to indicate whether the address belongs to a customer account or contact.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>objecttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>1</td></tr><tr><td>en</td><td>Contact</td><td>2</td></tr></table></td></tr></table>

### <a href=#objectTypeCode_display name="objectTypeCode_display">objectTypeCode_display</a>

First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#addressTypeCode name="addressTypeCode">addressTypeCode</a>

Select the address type, such as primary or billing.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Type</td></tr><tr><td>description</td><td>Select the address type, such as primary or billing.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Bill To</td><td>1</td></tr><tr><td>en</td><td>Ship To</td><td>2</td></tr><tr><td>en</td><td>Primary</td><td>3</td></tr><tr><td>en</td><td>Other</td><td>4</td></tr></table></td></tr></table>

### <a href=#addressTypeCode_display name="addressTypeCode_display">addressTypeCode_display</a>

First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Type a descriptive name for the customer's address, such as Corporate Headquarters.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Name</td></tr><tr><td>description</td><td>Type a descriptive name for the customer's address, such as Corporate Headquarters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#primaryContactName name="primaryContactName">primaryContactName</a>

Type the name of the primary contact person for the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Contact</td></tr><tr><td>description</td><td>Type the name of the primary contact person for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primarycontactname</td></tr></table>

### <a href=#line1 name="line1">line1</a>

Type the first line of the customer's address to help identify the location.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line1</td></tr></table>

### <a href=#line2 name="line2">line2</a>

Type the second line of the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line2</td></tr></table>

### <a href=#line3 name="line3">line3</a>

Type the third line of the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 3</td></tr><tr><td>description</td><td>Type the third line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line3</td></tr></table>

### <a href=#city name="city">city</a>

Type the city for the customer's address to help identify the location.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>Type the city for the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>city</td></tr></table>

### <a href=#stateOrProvince name="stateOrProvince">stateOrProvince</a>

Type the state or province of the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>Type the state or province of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stateorprovince</td></tr></table>

### <a href=#county name="county">county</a>

Type the county for the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>County</td></tr><tr><td>description</td><td>Type the county for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>county</td></tr></table>

### <a href=#country name="country">country</a>

Type the country or region for the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>country</td></tr></table>

### <a href=#postOfficeBox name="postOfficeBox">postOfficeBox</a>

Type the post office box number of the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Office Box</td></tr><tr><td>description</td><td>Type the post office box number of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postofficebox</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

Type the ZIP Code or postal code for the address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postalcode</td></tr></table>

### <a href=#UTCOffset name="UTCOffset">UTCOffset</a>

Select the time zone for the address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Offset</td></tr><tr><td>description</td><td>Select the time zone for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcoffset</td></tr></table>

### <a href=#freightTermsCode name="freightTermsCode">freightTermsCode</a>

Select the freight terms to make sure shipping charges are processed correctly.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping charges are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FOB</td><td>1</td></tr><tr><td>en</td><td>No Charge</td><td>2</td></tr></table></td></tr></table>

### <a href=#freightTermsCode_display name="freightTermsCode_display">freightTermsCode_display</a>

First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#UPSZone name="UPSZone">UPSZone</a>

Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UPS Zone</td></tr><tr><td>description</td><td>Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>upszone</td></tr></table>

### <a href=#latitude name="latitude">latitude</a>

Type the latitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Latitude</td></tr><tr><td>description</td><td>Type the latitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>latitude</td></tr></table>

### <a href=#telephone1 name="telephone1">telephone1</a>

Type the primary phone number for the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Phone</td></tr><tr><td>description</td><td>Type the primary phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone1</td></tr></table>

### <a href=#longitude name="longitude">longitude</a>

Type the longitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Longitude</td></tr><tr><td>description</td><td>Type the longitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>longitude</td></tr></table>

### <a href=#shippingMethodCode name="shippingMethodCode">shippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Airborne</td><td>1</td></tr><tr><td>en</td><td>DHL</td><td>2</td></tr><tr><td>en</td><td>FedEx</td><td>3</td></tr><tr><td>en</td><td>UPS</td><td>4</td></tr><tr><td>en</td><td>Postal Mail</td><td>5</td></tr><tr><td>en</td><td>Full Load</td><td>6</td></tr><tr><td>en</td><td>Will Call</td><td>7</td></tr></table></td></tr></table>

### <a href=#shippingMethodCode_display name="shippingMethodCode_display">shippingMethodCode_display</a>

First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#telephone2 name="telephone2">telephone2</a>

Type a second phone number for the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Phone 2</td></tr><tr><td>description</td><td>Type a second phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone2</td></tr></table>

### <a href=#telephone3 name="telephone3">telephone3</a>

Type a third phone number for the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone3</td></tr></table>

### <a href=#fax name="fax">fax</a>

Type the fax number associated with the customer's address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Type the fax number associated with the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fax</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the customer address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the customer address.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Shows the business unit that the record owner belongs to.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Shows the business unit that the record owner belongs to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user who owns the customer address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Unique identifier of the user who owns the customer address.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#composite name="composite">composite</a>

Shows the complete address.  
First included in: <a href="../../../../Address.md" target="_blank">applicationCommon/Address</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>description</td><td>Shows the complete address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>composite</td></tr></table>

### <a href=#endDate name="endDate">endDate</a>

Effective end date of the address and related contact info  
First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>description</td><td>Effective end date of the address and related contact info</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_enddate</td></tr></table>

### <a href=#isUspsValidated name="isUspsValidated">isUspsValidated</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>USPS Validated</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_isuspsvalidated</td></tr></table>

### <a href=#isvalidated name="isvalidated">isvalidated</a>

Indicates the address has been validated.  
First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Validated</td></tr><tr><td>description</td><td>Indicates the address has been validated.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_isvalidated</td></tr></table>

### <a href=#region name="region">region</a>

Indicates the region of the world that the address is located.  
First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Region</td></tr><tr><td>description</td><td>Indicates the region of the world that the address is located.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_region</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Region</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#region_display name="region_display">region_display</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#seasonalEndDay name="seasonalEndDay">seasonalEndDay</a>

Annual end day (of month) of the address and related contact info  
First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Seasonal End Day</td></tr><tr><td>description</td><td>Annual end day (of month) of the address and related contact info</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_seasonalendday</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>DaysOfMonth</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#seasonalEndDay_display name="seasonalEndDay_display">seasonalEndDay_display</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#seasonalEndMonth name="seasonalEndMonth">seasonalEndMonth</a>

Annual end month of the address and related contact info  
First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Seasonal End Month</td></tr><tr><td>description</td><td>Annual end month of the address and related contact info</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_seasonalendmonth</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>MonthNames</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#seasonalEndMonth_display name="seasonalEndMonth_display">seasonalEndMonth_display</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#seasonalStartDay name="seasonalStartDay">seasonalStartDay</a>

Annual start day (of month) of the address and related contact info  
First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Seasonal Start Day</td></tr><tr><td>description</td><td>Annual start day (of month) of the address and related contact info</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_seasonalstartday</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>DaysOfMonth</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#seasonalStartDay_display name="seasonalStartDay_display">seasonalStartDay_display</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#seasonalStartMonth name="seasonalStartMonth">seasonalStartMonth</a>

Annual start month of the address and related contact info  
First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Seasonal Start Month</td></tr><tr><td>description</td><td>Annual start month of the address and related contact info</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_seasonalstartmonth</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>MonthNames</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#seasonalStartMonth_display name="seasonalStartMonth_display">seasonalStartMonth_display</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#startDate name="startDate">startDate</a>

Effective start date of the address and related contact info  
First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Effective start date of the address and related contact info</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_startdate</td></tr></table>

### <a href=#telephone1TypeCode name="telephone1TypeCode">telephone1TypeCode</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 1 Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_telephone1typecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Home</td><td>100000000</td></tr><tr><td>en</td><td>Office</td><td>100000001</td></tr><tr><td>en</td><td>Mobile</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#telephone1TypeCode_display name="telephone1TypeCode_display">telephone1TypeCode_display</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#telephone2TypeCode name="telephone2TypeCode">telephone2TypeCode</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 2 Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_telephone2typecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Home</td><td>100000000</td></tr><tr><td>en</td><td>Office</td><td>100000001</td></tr><tr><td>en</td><td>Mobile</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#telephone2TypeCode_display name="telephone2TypeCode_display">telephone2TypeCode_display</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#telephone3TypeCode name="telephone3TypeCode">telephone3TypeCode</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 3 Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_telephone3typecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Home</td><td>100000000</td></tr><tr><td>en</td><td>Office</td><td>100000001</td></tr><tr><td>en</td><td>Mobile</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#telephone3TypeCode_display name="telephone3TypeCode_display">telephone3TypeCode_display</a>

First included in: nonProfit/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

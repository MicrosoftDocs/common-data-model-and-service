---
title: Address - Common Data Model | Microsoft Docs
description: Address and shipping information. Used to store additional addresses for an account or contact.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Address

Address and shipping information. Used to store additional addresses for an account or contact.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Address.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /Address  
- [/foundationCommon/crmCommon/accelerators/education/higherEducation/Address](foundationCommon/crmCommon/accelerators/education/higherEducation/Address.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/education/higherEducation/Address.cdm.json/Address")  
- [/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Address](foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Address.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Address.cdm.json/Address")  
- [/foundationCommon/crmCommon/accelerators/nonProfit/Address](foundationCommon/crmCommon/accelerators/nonProfit/Address.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Address.cdm.json/Address")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[parentIdTypeCode](#parentIdTypeCode)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[parentId](#parentId)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[customerAddressId](#customerAddressId)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[addressNumber](#addressNumber)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[objectTypeCode](#objectTypeCode)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[objectTypeCode_display](#objectTypeCode_display)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[addressTypeCode](#addressTypeCode)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[addressTypeCode_display](#addressTypeCode_display)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[name](#name)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[primaryContactName](#primaryContactName)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[line1](#line1)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[line2](#line2)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[line3](#line3)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[city](#city)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[stateOrProvince](#stateOrProvince)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[county](#county)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[country](#country)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[postOfficeBox](#postOfficeBox)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[postalCode](#postalCode)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[UTCOffset](#UTCOffset)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[freightTermsCode](#freightTermsCode)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[freightTermsCode_display](#freightTermsCode_display)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[UPSZone](#UPSZone)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[latitude](#latitude)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[telephone1](#telephone1)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[longitude](#longitude)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[shippingMethodCode](#shippingMethodCode)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[shippingMethodCode_display](#shippingMethodCode_display)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[telephone2](#telephone2)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[telephone3](#telephone3)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[fax](#fax)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[versionNumber](#versionNumber)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[createdBy](#createdBy)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[createdOn](#createdOn)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[modifiedBy](#modifiedBy)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[modifiedOn](#modifiedOn)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[owningBusinessUnit](#owningBusinessUnit)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[owningUser](#owningUser)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[importSequenceNumber](#importSequenceNumber)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[ownerIdType](#ownerIdType)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[ownerId](#ownerId)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[transactionCurrencyId](#transactionCurrencyId)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[exchangeRate](#exchangeRate)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|
|[composite](#composite)||<a href="Address.md" target="_blank">applicationCommon/Address</a>|

### <a href=#parentIdTypeCode name="parentIdTypeCode">parentIdTypeCode</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#parentId name="parentId">parentId</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr></table>

### <a href=#customerAddressId name="customerAddressId">customerAddressId</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr></table>

### <a href=#addressNumber name="addressNumber">addressNumber</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#objectTypeCode name="objectTypeCode">objectTypeCode</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>1</td></tr><tr><td>en</td><td>Contact</td><td>2</td></tr></table></td></tr></table>

### <a href=#objectTypeCode_display name="objectTypeCode_display">objectTypeCode_display</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#addressTypeCode name="addressTypeCode">addressTypeCode</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Bill To</td><td>1</td></tr><tr><td>en</td><td>Ship To</td><td>2</td></tr><tr><td>en</td><td>Primary</td><td>3</td></tr><tr><td>en</td><td>Other</td><td>4</td></tr></table></td></tr></table>

### <a href=#addressTypeCode_display name="addressTypeCode_display">addressTypeCode_display</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#primaryContactName name="primaryContactName">primaryContactName</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#line1 name="line1">line1</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#line2 name="line2">line2</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#line3 name="line3">line3</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#city name="city">city</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#stateOrProvince name="stateOrProvince">stateOrProvince</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#county name="county">county</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#country name="country">country</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#postOfficeBox name="postOfficeBox">postOfficeBox</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#UTCOffset name="UTCOffset">UTCOffset</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#freightTermsCode name="freightTermsCode">freightTermsCode</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FOB</td><td>1</td></tr><tr><td>en</td><td>No Charge</td><td>2</td></tr></table></td></tr></table>

### <a href=#freightTermsCode_display name="freightTermsCode_display">freightTermsCode_display</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#UPSZone name="UPSZone">UPSZone</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#latitude name="latitude">latitude</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#telephone1 name="telephone1">telephone1</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#longitude name="longitude">longitude</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#shippingMethodCode name="shippingMethodCode">shippingMethodCode</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Airborne</td><td>1</td></tr><tr><td>en</td><td>DHL</td><td>2</td></tr><tr><td>en</td><td>FedEx</td><td>3</td></tr><tr><td>en</td><td>UPS</td><td>4</td></tr><tr><td>en</td><td>Postal Mail</td><td>5</td></tr><tr><td>en</td><td>Full Load</td><td>6</td></tr><tr><td>en</td><td>Will Call</td><td>7</td></tr></table></td></tr></table>

### <a href=#shippingMethodCode_display name="shippingMethodCode_display">shippingMethodCode_display</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#telephone2 name="telephone2">telephone2</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#telephone3 name="telephone3">telephone3</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#fax name="fax">fax</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

### <a href=#composite name="composite">composite</a>

First included in: applicationCommon/Address (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

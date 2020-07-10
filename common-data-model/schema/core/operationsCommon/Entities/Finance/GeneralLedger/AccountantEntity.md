---
title: AccountantEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Accountants in GeneralLedger(AccountantEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/AccountantEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accountants</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CNPJ](#CNPJ)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[CPF](#CPF)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[CRCCountryRegionId](#CRCCountryRegionId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[CRCExpirationDate](#CRCExpirationDate)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[CRC](#CRC)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[CRCIssuerState](#CRCIssuerState)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AccountantName](#AccountantName)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AccountantLogisticsLocationPostalAddressIsPostalAddress](#AccountantLogisticsLocationPostalAddressIsPostalAddress)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AccountantLogisticsLocationPostalAddressIsPrimary](#AccountantLogisticsLocationPostalAddressIsPrimary)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AccountantLogisticsLocationPostalAddressRecId](#AccountantLogisticsLocationPostalAddressRecId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AccountantLogisticsLocationElectronicAddressIsPostalAddress](#AccountantLogisticsLocationElectronicAddressIsPostalAddress)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AccountantLogisticsLocationElectronicAddressRecId](#AccountantLogisticsLocationElectronicAddressRecId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[LogisticsLocationPostalAddressRecId](#LogisticsLocationPostalAddressRecId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[LogisticsLocationPostalAddressLocationId](#LogisticsLocationPostalAddressLocationId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[LogisticsLocationElectronicAddressRecId](#LogisticsLocationElectronicAddressRecId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[LogisticsLocationElectronicAddressLocationId](#LogisticsLocationElectronicAddressLocationId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[LogisticsPostalAddressValidFrom](#LogisticsPostalAddressValidFrom)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[LogisticsPostalAddressValidTo](#LogisticsPostalAddressValidTo)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[Address](#Address)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressBuildingCompliment](#AddressBuildingCompliment)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressCity](#AddressCity)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressCityRecId](#AddressCityRecId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressCountryRegionId](#AddressCountryRegionId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressCounty](#AddressCounty)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressDistrictId](#AddressDistrictId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressDistrict](#AddressDistrict)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressIsPrivate](#AddressIsPrivate)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressLocation](#AddressLocation)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressState](#AddressState)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressStreet](#AddressStreet)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressStreetNumber](#AddressStreetNumber)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressValidFrom](#AddressValidFrom)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressValidTo](#AddressValidTo)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressZipCode](#AddressZipCode)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressZipCodeRecId](#AddressZipCodeRecId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressCityName](#AddressCityName)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressDistrictName](#AddressDistrictName)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressZipCodeName](#AddressZipCodeName)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailCountryRegionCode](#EmailCountryRegionCode)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailDescription](#EmailDescription)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailIsInstantMessage](#EmailIsInstantMessage)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailIsPrimary](#EmailIsPrimary)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailIsPrivate](#EmailIsPrivate)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailLocation](#EmailLocation)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailLocator](#EmailLocator)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailLocatorExtension](#EmailLocatorExtension)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailPrivateForParty](#EmailPrivateForParty)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailType](#EmailType)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneCountryRegionCode](#PhoneCountryRegionCode)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneDescription](#PhoneDescription)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneIsInstantMessage](#PhoneIsInstantMessage)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneIsMobilePhone](#PhoneIsMobilePhone)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneIsPrimary](#PhoneIsPrimary)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneIsPrivate](#PhoneIsPrivate)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneLocation](#PhoneLocation)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneLocator](#PhoneLocator)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneLocatorExtension](#PhoneLocatorExtension)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhonePrivateForParty](#PhonePrivateForParty)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneType](#PhoneType)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[LogisticsAddressCityRecId](#LogisticsAddressCityRecId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressDescription](#AddressDescription)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressRole](#AddressRole)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AddressRoleLocationId](#AddressRoleLocationId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AccountantLogisticsLocationElectronicAddressLocation](#AccountantLogisticsLocationElectronicAddressLocation)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[AccountantLogisticsLocationElectronicAddressIsPrimary](#AccountantLogisticsLocationElectronicAddressIsPrimary)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailRoleLocationId](#EmailRoleLocationId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[EmailRole](#EmailRole)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneRole](#PhoneRole)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[PhoneRoleLocationId](#PhoneRoleLocationId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|
|[BackingTable_Accountant_BRRelationshipId](#BackingTable_Accountant_BRRelationshipId)||<a href="AccountantEntity.md" target="_blank">GeneralLedger/AccountantEntity</a>|

### <a href=#CNPJ name="CNPJ">CNPJ</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CNPJ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CPF name="CPF">CPF</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CRCCountryRegionId name="CRCCountryRegionId">CRCCountryRegionId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CRCCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CRCExpirationDate name="CRCExpirationDate">CRCExpirationDate</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CRCExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CRC name="CRC">CRC</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CRC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CRCIssuerState name="CRCIssuerState">CRCIssuerState</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CRCIssuerState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountantName name="AccountantName">AccountantName</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountantLogisticsLocationPostalAddressIsPostalAddress name="AccountantLogisticsLocationPostalAddressIsPostalAddress">AccountantLogisticsLocationPostalAddressIsPostalAddress</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantLogisticsLocationPostalAddressIsPostalAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountantLogisticsLocationPostalAddressIsPrimary name="AccountantLogisticsLocationPostalAddressIsPrimary">AccountantLogisticsLocationPostalAddressIsPrimary</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantLogisticsLocationPostalAddressIsPrimary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountantLogisticsLocationPostalAddressRecId name="AccountantLogisticsLocationPostalAddressRecId">AccountantLogisticsLocationPostalAddressRecId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantLogisticsLocationPostalAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountantLogisticsLocationElectronicAddressIsPostalAddress name="AccountantLogisticsLocationElectronicAddressIsPostalAddress">AccountantLogisticsLocationElectronicAddressIsPostalAddress</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantLogisticsLocationElectronicAddressIsPostalAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountantLogisticsLocationElectronicAddressRecId name="AccountantLogisticsLocationElectronicAddressRecId">AccountantLogisticsLocationElectronicAddressRecId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantLogisticsLocationElectronicAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsLocationPostalAddressRecId name="LogisticsLocationPostalAddressRecId">LogisticsLocationPostalAddressRecId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsLocationPostalAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsLocationPostalAddressLocationId name="LogisticsLocationPostalAddressLocationId">LogisticsLocationPostalAddressLocationId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsLocationPostalAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsLocationElectronicAddressRecId name="LogisticsLocationElectronicAddressRecId">LogisticsLocationElectronicAddressRecId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsLocationElectronicAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsLocationElectronicAddressLocationId name="LogisticsLocationElectronicAddressLocationId">LogisticsLocationElectronicAddressLocationId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsLocationElectronicAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalAddressValidFrom name="LogisticsPostalAddressValidFrom">LogisticsPostalAddressValidFrom</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsPostalAddressValidTo name="LogisticsPostalAddressValidTo">LogisticsPostalAddressValidTo</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Address name="Address">Address</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Address attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBuildingCompliment name="AddressBuildingCompliment">AddressBuildingCompliment</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCity name="AddressCity">AddressCity</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCityRecId name="AddressCityRecId">AddressCityRecId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCityRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountryRegionId name="AddressCountryRegionId">AddressCountryRegionId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCounty name="AddressCounty">AddressCounty</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDistrictId name="AddressDistrictId">AddressDistrictId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDistrictId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDistrict name="AddressDistrict">AddressDistrict</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDistrict attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressIsPrivate name="AddressIsPrivate">AddressIsPrivate</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocation name="AddressLocation">AddressLocation</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressState name="AddressState">AddressState</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreet name="AddressStreet">AddressStreet</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreetNumber name="AddressStreetNumber">AddressStreetNumber</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidFrom name="AddressValidFrom">AddressValidFrom</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidTo name="AddressValidTo">AddressValidTo</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressZipCode name="AddressZipCode">AddressZipCode</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressZipCodeRecId name="AddressZipCodeRecId">AddressZipCodeRecId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressZipCodeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCityName name="AddressCityName">AddressCityName</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDistrictName name="AddressDistrictName">AddressDistrictName</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressZipCodeName name="AddressZipCodeName">AddressZipCodeName</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressZipCodeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailCountryRegionCode name="EmailCountryRegionCode">EmailCountryRegionCode</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailCountryRegionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailDescription name="EmailDescription">EmailDescription</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailIsInstantMessage name="EmailIsInstantMessage">EmailIsInstantMessage</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailIsInstantMessage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailIsPrimary name="EmailIsPrimary">EmailIsPrimary</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailIsPrimary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailIsPrivate name="EmailIsPrivate">EmailIsPrivate</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailLocation name="EmailLocation">EmailLocation</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailLocator name="EmailLocator">EmailLocator</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailLocator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailLocatorExtension name="EmailLocatorExtension">EmailLocatorExtension</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailLocatorExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailPrivateForParty name="EmailPrivateForParty">EmailPrivateForParty</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailPrivateForParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailType name="EmailType">EmailType</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneCountryRegionCode name="PhoneCountryRegionCode">PhoneCountryRegionCode</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneCountryRegionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneDescription name="PhoneDescription">PhoneDescription</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneIsInstantMessage name="PhoneIsInstantMessage">PhoneIsInstantMessage</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneIsInstantMessage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneIsMobilePhone name="PhoneIsMobilePhone">PhoneIsMobilePhone</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneIsMobilePhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneIsPrimary name="PhoneIsPrimary">PhoneIsPrimary</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneIsPrimary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneIsPrivate name="PhoneIsPrivate">PhoneIsPrivate</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneLocation name="PhoneLocation">PhoneLocation</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneLocator name="PhoneLocator">PhoneLocator</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneLocator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneLocatorExtension name="PhoneLocatorExtension">PhoneLocatorExtension</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneLocatorExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhonePrivateForParty name="PhonePrivateForParty">PhonePrivateForParty</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhonePrivateForParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneType name="PhoneType">PhoneType</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsAddressCityRecId name="LogisticsAddressCityRecId">LogisticsAddressCityRecId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsAddressCityRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDescription name="AddressDescription">AddressDescription</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressRole name="AddressRole">AddressRole</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRole attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressRoleLocationId name="AddressRoleLocationId">AddressRoleLocationId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRoleLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountantLogisticsLocationElectronicAddressLocation name="AccountantLogisticsLocationElectronicAddressLocation">AccountantLogisticsLocationElectronicAddressLocation</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantLogisticsLocationElectronicAddressLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountantLogisticsLocationElectronicAddressIsPrimary name="AccountantLogisticsLocationElectronicAddressIsPrimary">AccountantLogisticsLocationElectronicAddressIsPrimary</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantLogisticsLocationElectronicAddressIsPrimary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailRoleLocationId name="EmailRoleLocationId">EmailRoleLocationId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailRoleLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailRole name="EmailRole">EmailRole</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailRole attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneRole name="PhoneRole">PhoneRole</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneRole attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneRoleLocationId name="PhoneRoleLocationId">PhoneRoleLocationId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneRoleLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_Accountant_BRRelationshipId name="BackingTable_Accountant_BRRelationshipId">BackingTable_Accountant_BRRelationshipId</a>

First included in: GeneralLedger/AccountantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_Accountant_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/Accountant_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/Accountant_BR.cdm.json/Accountant_BR</a></td><td><a href="../../../Tables/Finance/Ledger/Main/Accountant_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

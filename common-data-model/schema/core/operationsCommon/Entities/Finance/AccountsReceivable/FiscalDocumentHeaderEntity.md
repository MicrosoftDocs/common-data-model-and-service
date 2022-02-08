---
title: FiscalDocumentHeaderEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Fiscal document header entity in AccountsReceivable(FiscalDocumentHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/FiscalDocumentHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal document header entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FiscalDocumentNumber](#FiscalDocumentNumber)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Series](#Series)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[AccessKey](#AccessKey)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Model](#Model)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Specie](#Specie)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Direction](#Direction)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Status](#Status)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DocumentDate](#DocumentDate)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[PostedDate](#PostedDate)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[CancelAccountingDate](#CancelAccountingDate)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Issuer](#Issuer)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FiscalEstablishmentCNPJorCPF](#FiscalEstablishmentCNPJorCPF)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FiscalEstablishmentIE](#FiscalEstablishmentIE)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FiscalEstablishmentCCM](#FiscalEstablishmentCCM)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FiscalEstablishmentName](#FiscalEstablishmentName)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FiscalEstablishmentTaxSubstitutionRegistry](#FiscalEstablishmentTaxSubstitutionRegistry)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FiscalEstablishmentTelephone](#FiscalEstablishmentTelephone)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FiscalEstablishmentAddress](#FiscalEstablishmentAddress)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAccountType](#ThirdPartyAccountType)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAccount](#ThirdPartyAccount)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyName](#ThirdPartyName)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyCNPJorCPF](#ThirdPartyCNPJorCPF)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyIE](#ThirdPartyIE)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyCCM](#ThirdPartyCCM)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyTelephone](#ThirdPartyTelephone)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyFax](#ThirdPartyFax)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyEmailAccount](#ThirdPartyEmailAccount)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyForeignerId](#ThirdPartyForeignerId)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyIsICMSContributor](#ThirdPartyIsICMSContributor)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAddress](#ThirdPartyAddress)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAddressDescription](#ThirdPartyAddressDescription)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAddressStreet](#ThirdPartyAddressStreet)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAddressStreetNumber](#ThirdPartyAddressStreetNumber)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAddressBuildingCompliment](#ThirdPartyAddressBuildingCompliment)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAddressDistrictName](#ThirdPartyAddressDistrictName)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAddressCity](#ThirdPartyAddressCity)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAddressState](#ThirdPartyAddressState)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAddressCountryRegionId](#ThirdPartyAddressCountryRegionId)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAddressCountryRegionISOCode](#ThirdPartyAddressCountryRegionISOCode)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ThirdPartyAddressZipCode](#ThirdPartyAddressZipCode)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[TotalAmount](#TotalAmount)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[TotalFreight](#TotalFreight)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[TotalInsurance](#TotalInsurance)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[TotalOtherCharges](#TotalOtherCharges)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[TotalProductsAmount](#TotalProductsAmount)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[TotalServicesAmount](#TotalServicesAmount)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ComplementaryFiscalDocumentType](#ComplementaryFiscalDocumentType)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ComplementedFiscalDocument](#ComplementedFiscalDocument)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ComplementedFiscalDocumentNumber](#ComplementedFiscalDocumentNumber)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ComplementedFiscalDocumentSeries](#ComplementedFiscalDocumentSeries)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ComplementedFiscalDocumentDirection](#ComplementedFiscalDocumentDirection)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ComplementedFiscalDocumentStatus](#ComplementedFiscalDocumentStatus)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ComplementedFiscalDocumentFiscalEstablishmentId](#ComplementedFiscalDocumentFiscalEstablishmentId)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ComplementedFiscalDocumentThirdPartyCNPJorCPF](#ComplementedFiscalDocumentThirdPartyCNPJorCPF)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryCNPJorCPF](#DeliveryCNPJorCPF)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryIE](#DeliveryIE)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryAddress](#DeliveryAddress)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryAddressBuildingCompliment](#DeliveryAddressBuildingCompliment)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryAddressState](#DeliveryAddressState)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FreightChargeTerms](#FreightChargeTerms)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[DeliveryTerms](#DeliveryTerms)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ModeOfDelivery](#ModeOfDelivery)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[VehicleNumber](#VehicleNumber)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[VehicleStateRegistered](#VehicleStateRegistered)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[CTeType](#CTeType)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Carrier](#Carrier)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[CarrierName](#CarrierName)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[CarrierCNPJorCPF](#CarrierCNPJorCPF)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[CarrierIE](#CarrierIE)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[CarrierAddress](#CarrierAddress)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[CityWhereServicePerformed](#CityWhereServicePerformed)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[CityKeyWhereServicePerformed](#CityKeyWhereServicePerformed)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[CFPSCode](#CFPSCode)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ReasonComment](#ReasonComment)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ManualICMSSTTaxAmount](#ManualICMSSTTaxAmount)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ImportDeclaration](#ImportDeclaration)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[ImportDeclarationNumber](#ImportDeclarationNumber)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[NumericCode](#NumericCode)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[OperationDescription](#OperationDescription)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Brand](#Brand)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[PreviousVersion](#PreviousVersion)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Purpose](#Purpose)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Version](#Version)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FinalUser](#FinalUser)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FiscalDocumentDateTime](#FiscalDocumentDateTime)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FiscalDocumentDateTimeOffset](#FiscalDocumentDateTimeOffset)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[PresenceType](#PresenceType)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[TotalSUFRAMACOFINSDiscount](#TotalSUFRAMACOFINSDiscount)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[TotalSUFRAMAICMSDiscount](#TotalSUFRAMAICMSDiscount)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[TotalSUFRAMAPISDiscount](#TotalSUFRAMAPISDiscount)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[FiscalDocumentFormat](#FiscalDocumentFormat)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[PaymentDocumentType](#PaymentDocumentType)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[PaymentNumberOfInstallments](#PaymentNumberOfInstallments)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[PaymentAmount](#PaymentAmount)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[PaymentDueDate](#PaymentDueDate)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Voucher](#Voucher)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[BackingTable_FiscalDocument_BRRelationshipId](#BackingTable_FiscalDocument_BRRelationshipId)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="FiscalDocumentHeaderEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderEntity</a>|

### <a href=#FiscalDocumentNumber name="FiscalDocumentNumber">FiscalDocumentNumber</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Series name="Series">Series</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Series attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccessKey name="AccessKey">AccessKey</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccessKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Model name="Model">Model</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Model attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Specie name="Specie">Specie</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Specie attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Direction name="Direction">Direction</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Direction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostedDate name="PostedDate">PostedDate</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CancelAccountingDate name="CancelAccountingDate">CancelAccountingDate</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelAccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Issuer name="Issuer">Issuer</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Issuer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentCNPJorCPF name="FiscalEstablishmentCNPJorCPF">FiscalEstablishmentCNPJorCPF</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentCNPJorCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentIE name="FiscalEstablishmentIE">FiscalEstablishmentIE</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentIE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentCCM name="FiscalEstablishmentCCM">FiscalEstablishmentCCM</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentCCM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentName name="FiscalEstablishmentName">FiscalEstablishmentName</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentTaxSubstitutionRegistry name="FiscalEstablishmentTaxSubstitutionRegistry">FiscalEstablishmentTaxSubstitutionRegistry</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentTaxSubstitutionRegistry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentTelephone name="FiscalEstablishmentTelephone">FiscalEstablishmentTelephone</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentTelephone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentAddress name="FiscalEstablishmentAddress">FiscalEstablishmentAddress</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAccountType name="ThirdPartyAccountType">ThirdPartyAccountType</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party account type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party account type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAccount name="ThirdPartyAccount">ThirdPartyAccount</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyName name="ThirdPartyName">ThirdPartyName</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyCNPJorCPF name="ThirdPartyCNPJorCPF">ThirdPartyCNPJorCPF</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party CNPJ/CPF</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyCNPJorCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party CNPJ/CPF</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyIE name="ThirdPartyIE">ThirdPartyIE</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party IE</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyIE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party IE</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyCCM name="ThirdPartyCCM">ThirdPartyCCM</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party CCM</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyCCM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party CCM</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyTelephone name="ThirdPartyTelephone">ThirdPartyTelephone</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party telephone</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyTelephone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party telephone</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyFax name="ThirdPartyFax">ThirdPartyFax</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party fax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyFax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party fax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyEmailAccount name="ThirdPartyEmailAccount">ThirdPartyEmailAccount</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party email</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyEmailAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party email</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyForeignerId name="ThirdPartyForeignerId">ThirdPartyForeignerId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party Foreigner ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyForeignerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party Foreigner ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyIsICMSContributor name="ThirdPartyIsICMSContributor">ThirdPartyIsICMSContributor</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyIsICMSContributor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddress name="ThirdPartyAddress">ThirdPartyAddress</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressDescription name="ThirdPartyAddressDescription">ThirdPartyAddressDescription</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party address name or description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party address name or description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressStreet name="ThirdPartyAddressStreet">ThirdPartyAddressStreet</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party address street</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party address street</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressStreetNumber name="ThirdPartyAddressStreetNumber">ThirdPartyAddressStreetNumber</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party address street number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party address street number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressBuildingCompliment name="ThirdPartyAddressBuildingCompliment">ThirdPartyAddressBuildingCompliment</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party address building complement</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party address building complement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressDistrictName name="ThirdPartyAddressDistrictName">ThirdPartyAddressDistrictName</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party address district</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party address district</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressCity name="ThirdPartyAddressCity">ThirdPartyAddressCity</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party address city</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party address city</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressState name="ThirdPartyAddressState">ThirdPartyAddressState</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party address state</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party address state</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressCountryRegionId name="ThirdPartyAddressCountryRegionId">ThirdPartyAddressCountryRegionId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party address country/region</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party address country/region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressCountryRegionISOCode name="ThirdPartyAddressCountryRegionISOCode">ThirdPartyAddressCountryRegionISOCode</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyAddressZipCode name="ThirdPartyAddressZipCode">ThirdPartyAddressZipCode</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Third party address zip/postal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Third party address zip/postal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalAmount name="TotalAmount">TotalAmount</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalFreight name="TotalFreight">TotalFreight</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalFreight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalInsurance name="TotalInsurance">TotalInsurance</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalInsurance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalOtherCharges name="TotalOtherCharges">TotalOtherCharges</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalOtherCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalProductsAmount name="TotalProductsAmount">TotalProductsAmount</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalProductsAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalServicesAmount name="TotalServicesAmount">TotalServicesAmount</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalServicesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementaryFiscalDocumentType name="ComplementaryFiscalDocumentType">ComplementaryFiscalDocumentType</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementaryFiscalDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementedFiscalDocument name="ComplementedFiscalDocument">ComplementedFiscalDocument</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementedFiscalDocument attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementedFiscalDocumentNumber name="ComplementedFiscalDocumentNumber">ComplementedFiscalDocumentNumber</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Complemented fiscal document number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementedFiscalDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Complemented fiscal document number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementedFiscalDocumentSeries name="ComplementedFiscalDocumentSeries">ComplementedFiscalDocumentSeries</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Complemented fiscal document series</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementedFiscalDocumentSeries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Complemented fiscal document series</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementedFiscalDocumentDirection name="ComplementedFiscalDocumentDirection">ComplementedFiscalDocumentDirection</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Complemented fiscal document direction</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementedFiscalDocumentDirection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Complemented fiscal document direction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementedFiscalDocumentStatus name="ComplementedFiscalDocumentStatus">ComplementedFiscalDocumentStatus</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Complemented fiscal document status</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementedFiscalDocumentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Complemented fiscal document status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementedFiscalDocumentFiscalEstablishmentId name="ComplementedFiscalDocumentFiscalEstablishmentId">ComplementedFiscalDocumentFiscalEstablishmentId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Complemented fiscal document fiscal establishment ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementedFiscalDocumentFiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Complemented fiscal document fiscal establishment ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementedFiscalDocumentThirdPartyCNPJorCPF name="ComplementedFiscalDocumentThirdPartyCNPJorCPF">ComplementedFiscalDocumentThirdPartyCNPJorCPF</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Complemented fiscal document third party CNPJ/CPF</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementedFiscalDocumentThirdPartyCNPJorCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Complemented fiscal document third party CNPJ/CPF</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCNPJorCPF name="DeliveryCNPJorCPF">DeliveryCNPJorCPF</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery CNPJ/CPF</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCNPJorCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery CNPJ/CPF</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryIE name="DeliveryIE">DeliveryIE</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery IE</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryIE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery IE</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddress name="DeliveryAddress">DeliveryAddress</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDescription name="DeliveryAddressDescription">DeliveryAddressDescription</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address name or description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address name or description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreet name="DeliveryAddressStreet">DeliveryAddressStreet</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address street</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address street</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetNumber name="DeliveryAddressStreetNumber">DeliveryAddressStreetNumber</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address street number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address street number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressBuildingCompliment name="DeliveryAddressBuildingCompliment">DeliveryAddressBuildingCompliment</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address building complement</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address building complement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDistrictName name="DeliveryAddressDistrictName">DeliveryAddressDistrictName</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address district</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address district</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address city</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address city</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressState name="DeliveryAddressState">DeliveryAddressState</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address state</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address state</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionId name="DeliveryAddressCountryRegionId">DeliveryAddressCountryRegionId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address country/region</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address country/region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionISOCode name="DeliveryAddressCountryRegionISOCode">DeliveryAddressCountryRegionISOCode</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressZipCode name="DeliveryAddressZipCode">DeliveryAddressZipCode</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address zip/postal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address zip/postal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightChargeTerms name="FreightChargeTerms">FreightChargeTerms</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightChargeTerms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTerms name="DeliveryTerms">DeliveryTerms</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTerms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModeOfDelivery name="ModeOfDelivery">ModeOfDelivery</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModeOfDelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VehicleNumber name="VehicleNumber">VehicleNumber</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VehicleStateRegistered name="VehicleStateRegistered">VehicleStateRegistered</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vehicle state registered</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleStateRegistered attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vehicle state registered</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CTeType name="CTeType">CTeType</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CTeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Carrier name="Carrier">Carrier</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Carrier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierName name="CarrierName">CarrierName</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierCNPJorCPF name="CarrierCNPJorCPF">CarrierCNPJorCPF</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierCNPJorCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierIE name="CarrierIE">CarrierIE</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierIE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierAddress name="CarrierAddress">CarrierAddress</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CityWhereServicePerformed name="CityWhereServicePerformed">CityWhereServicePerformed</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CityWhereServicePerformed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CityKeyWhereServicePerformed name="CityKeyWhereServicePerformed">CityKeyWhereServicePerformed</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City key where service was performed</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CityKeyWhereServicePerformed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>City key where service was performed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFPSCode name="CFPSCode">CFPSCode</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFPSCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonComment name="ReasonComment">ReasonComment</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualICMSSTTaxAmount name="ManualICMSSTTaxAmount">ManualICMSSTTaxAmount</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualICMSSTTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImportDeclaration name="ImportDeclaration">ImportDeclaration</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImportDeclaration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImportDeclarationNumber name="ImportDeclarationNumber">ImportDeclarationNumber</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImportDeclarationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumericCode name="NumericCode">NumericCode</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumericCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationDescription name="OperationDescription">OperationDescription</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Brand name="Brand">Brand</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Brand attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreviousVersion name="PreviousVersion">PreviousVersion</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreviousVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Purpose name="Purpose">Purpose</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Version name="Version">Version</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Version attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinalUser name="FinalUser">FinalUser</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinalUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentDateTime name="FiscalDocumentDateTime">FiscalDocumentDateTime</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentDateTimeOffset name="FiscalDocumentDateTimeOffset">FiscalDocumentDateTimeOffset</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentDateTimeOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PresenceType name="PresenceType">PresenceType</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalSUFRAMACOFINSDiscount name="TotalSUFRAMACOFINSDiscount">TotalSUFRAMACOFINSDiscount</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalSUFRAMACOFINSDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalSUFRAMAICMSDiscount name="TotalSUFRAMAICMSDiscount">TotalSUFRAMAICMSDiscount</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalSUFRAMAICMSDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalSUFRAMAPISDiscount name="TotalSUFRAMAPISDiscount">TotalSUFRAMAPISDiscount</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalSUFRAMAPISDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentFormat name="FiscalDocumentFormat">FiscalDocumentFormat</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentDocumentType name="PaymentDocumentType">PaymentDocumentType</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentNumberOfInstallments name="PaymentNumberOfInstallments">PaymentNumberOfInstallments</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentNumberOfInstallments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentAmount name="PaymentAmount">PaymentAmount</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentDueDate name="PaymentDueDate">PaymentDueDate</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentDueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_FiscalDocument_BRRelationshipId name="BackingTable_FiscalDocument_BRRelationshipId">BackingTable_FiscalDocument_BRRelationshipId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FiscalDocument_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocument_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocument_BR.cdm.json/FiscalDocument_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocument_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

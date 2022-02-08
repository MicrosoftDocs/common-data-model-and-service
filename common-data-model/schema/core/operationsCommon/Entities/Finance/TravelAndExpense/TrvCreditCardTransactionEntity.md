---
title: TrvCreditCardTransactionEntity in TravelAndExpense - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Credit card transactions in TravelAndExpense(TrvCreditCardTransactionEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/TravelAndExpense/TrvCreditCardTransactionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit card transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Amount_CreditCardCurrency](#Amount_CreditCardCurrency)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[Amount_LocalCurrency](#Amount_LocalCurrency)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[BusinessName](#BusinessName)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CardNumber](#CardNumber)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CardNumberNIKS](#CardNumberNIKS)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CardType](#CardType)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CategoryCode](#CategoryCode)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CategoryCodesDescription](#CategoryCodesDescription)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CCTransUniqueID](#CCTransUniqueID)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CostType](#CostType)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[Country](#Country)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[EmpPayMethodRecId](#EmpPayMethodRecId)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[ExchCode_CreditCardCurrency](#ExchCode_CreditCardCurrency)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[ExchCode_LocalCurrency](#ExchCode_LocalCurrency)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[MerchantCategoryCode](#MerchantCategoryCode)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[Name](#Name)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[PaymentMethod](#PaymentMethod)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[Posted](#Posted)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[Reference](#Reference)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[Town](#Town)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TransactionDate](#TransactionDate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[Transferred](#Transferred)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TravelNo](#TravelNo)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[Worker](#Worker)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CarRentalCheckOutDate](#CarRentalCheckOutDate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CheckOutLocation](#CheckOutLocation)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[DailyRentalRate](#DailyRentalRate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[DaysRented](#DaysRented)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[MonthlyRentalRate](#MonthlyRentalRate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[RegularMileageCharges](#RegularMileageCharges)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[RenterName](#RenterName)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[ReservationNumber](#ReservationNumber)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[ReturnLocation](#ReturnLocation)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[ReturnDate](#ReturnDate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TotalMiles](#TotalMiles)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[VehicleClass](#VehicleClass)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[WeeklyRentalRate](#WeeklyRentalRate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[DepartureDate](#DepartureDate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[DomesticIndicator](#DomesticIndicator)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[ExchangeTicketNumber](#ExchangeTicketNumber)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[IssuingCarrier](#IssuingCarrier)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[NumberOfLegs](#NumberOfLegs)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[OriginalTicketNumber](#OriginalTicketNumber)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[PassengerName](#PassengerName)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TicketIssueDate](#TicketIssueDate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TravelAgencyCode](#TravelAgencyCode)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TravelAgencyInvoiceNumber](#TravelAgencyInvoiceNumber)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TravelAgencyName](#TravelAgencyName)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[ArrivalDate](#ArrivalDate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CarrierCode](#CarrierCode)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CityOfOrigin](#CityOfOrigin)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[DepartureTax](#DepartureTax)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[DestinationCity](#DestinationCity)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[FareAmount](#FareAmount)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[FeeAmount](#FeeAmount)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[FlightNumber](#FlightNumber)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TrvEnhancedTripLegDetail_ItineraryRecId](#TrvEnhancedTripLegDetail_ItineraryRecId)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[ServiceClass](#ServiceClass)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[StopOverCity](#StopOverCity)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TaxAmount](#TaxAmount)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TravelDate](#TravelDate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TripLegNumber](#TripLegNumber)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CheckInDate](#CheckInDate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CheckOutDate](#CheckOutDate)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[FolioNumber](#FolioNumber)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[GuestName](#GuestName)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[GuestNumber](#GuestNumber)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TotalRoomNights](#TotalRoomNights)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TotalRoomRent](#TotalRoomRent)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[TotalTaxAmount](#TotalTaxAmount)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[NoShowIndicator](#NoShowIndicator)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[CarRental_PBSRecid](#CarRental_PBSRecid)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[Itinerary_PBSRecid](#Itinerary_PBSRecid)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[Hotel_PBSRecid](#Hotel_PBSRecid)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[HashedCCNumber](#HashedCCNumber)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[BackingTable_TrvPBSMaindataRelationshipId](#BackingTable_TrvPBSMaindataRelationshipId)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TrvCreditCardTransactionEntity.md" target="_blank">TravelAndExpense/TrvCreditCardTransactionEntity</a>|

### <a href=#Amount_CreditCardCurrency name="Amount_CreditCardCurrency">Amount_CreditCardCurrency</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction amount</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount_CreditCardCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount_LocalCurrency name="Amount_LocalCurrency">Amount_LocalCurrency</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount in local currency</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount_LocalCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount in local currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessName name="BusinessName">BusinessName</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Merchant name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Merchant name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardNumber name="CardNumber">CardNumber</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardNumberNIKS name="CardNumberNIKS">CardNumberNIKS</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unique ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardNumberNIKS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardType name="CardType">CardType</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryCode name="CategoryCode">CategoryCode</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryCodesDescription name="CategoryCodesDescription">CategoryCodesDescription</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryCodesDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CCTransUniqueID name="CCTransUniqueID">CCTransUniqueID</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CCTransUniqueID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostType name="CostType">CostType</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Country name="Country">Country</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Country attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmpPayMethodRecId name="EmpPayMethodRecId">EmpPayMethodRecId</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmpPayMethodRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchCode_CreditCardCurrency name="ExchCode_CreditCardCurrency">ExchCode_CreditCardCurrency</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchCode_CreditCardCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchCode_LocalCurrency name="ExchCode_LocalCurrency">ExchCode_LocalCurrency</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Local currency code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchCode_LocalCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Local currency code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MerchantCategoryCode name="MerchantCategoryCode">MerchantCategoryCode</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MerchantCategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cardholder's name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cardholder's name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentMethod name="PaymentMethod">PaymentMethod</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Processed for payment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Processed for payment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reference name="Reference">Reference</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Town name="Town">Town</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Town attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transferred name="Transferred">Transferred</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction is added to expense report</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transferred attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction is added to expense report</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TravelNo name="TravelNo">TravelNo</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TravelNo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Worker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarRentalCheckOutDate name="CarRentalCheckOutDate">CarRentalCheckOutDate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarRentalCheckOutDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckOutLocation name="CheckOutLocation">CheckOutLocation</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckOutLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyRentalRate name="DailyRentalRate">DailyRentalRate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyRentalRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaysRented name="DaysRented">DaysRented</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysRented attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MonthlyRentalRate name="MonthlyRentalRate">MonthlyRentalRate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonthlyRentalRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegularMileageCharges name="RegularMileageCharges">RegularMileageCharges</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegularMileageCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RenterName name="RenterName">RenterName</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RenterName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservationNumber name="ReservationNumber">ReservationNumber</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnLocation name="ReturnLocation">ReturnLocation</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnDate name="ReturnDate">ReturnDate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalMiles name="TotalMiles">TotalMiles</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalMiles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VehicleClass name="VehicleClass">VehicleClass</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleClass attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WeeklyRentalRate name="WeeklyRentalRate">WeeklyRentalRate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WeeklyRentalRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepartureDate name="DepartureDate">DepartureDate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepartureDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DomesticIndicator name="DomesticIndicator">DomesticIndicator</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DomesticIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeTicketNumber name="ExchangeTicketNumber">ExchangeTicketNumber</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeTicketNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IssuingCarrier name="IssuingCarrier">IssuingCarrier</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssuingCarrier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfLegs name="NumberOfLegs">NumberOfLegs</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfLegs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalTicketNumber name="OriginalTicketNumber">OriginalTicketNumber</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalTicketNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PassengerName name="PassengerName">PassengerName</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassengerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TicketIssueDate name="TicketIssueDate">TicketIssueDate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TicketIssueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TravelAgencyCode name="TravelAgencyCode">TravelAgencyCode</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TravelAgencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TravelAgencyInvoiceNumber name="TravelAgencyInvoiceNumber">TravelAgencyInvoiceNumber</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TravelAgencyInvoiceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TravelAgencyName name="TravelAgencyName">TravelAgencyName</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TravelAgencyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArrivalDate name="ArrivalDate">ArrivalDate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArrivalDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierCode name="CarrierCode">CarrierCode</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CityOfOrigin name="CityOfOrigin">CityOfOrigin</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CityOfOrigin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepartureTax name="DepartureTax">DepartureTax</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepartureTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationCity name="DestinationCity">DestinationCity</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FareAmount name="FareAmount">FareAmount</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FareAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeAmount name="FeeAmount">FeeAmount</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FlightNumber name="FlightNumber">FlightNumber</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FlightNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrvEnhancedTripLegDetail_ItineraryRecId name="TrvEnhancedTripLegDetail_ItineraryRecId">TrvEnhancedTripLegDetail_ItineraryRecId</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrvEnhancedTripLegDetail_ItineraryRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceClass name="ServiceClass">ServiceClass</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceClass attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StopOverCity name="StopOverCity">StopOverCity</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StopOverCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TravelDate name="TravelDate">TravelDate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TravelDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TripLegNumber name="TripLegNumber">TripLegNumber</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TripLegNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckInDate name="CheckInDate">CheckInDate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckInDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckOutDate name="CheckOutDate">CheckOutDate</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckOutDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FolioNumber name="FolioNumber">FolioNumber</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FolioNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GuestName name="GuestName">GuestName</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuestName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GuestNumber name="GuestNumber">GuestNumber</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuestNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalRoomNights name="TotalRoomNights">TotalRoomNights</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRoomNights attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalRoomRent name="TotalRoomRent">TotalRoomRent</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRoomRent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalTaxAmount name="TotalTaxAmount">TotalTaxAmount</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NoShowIndicator name="NoShowIndicator">NoShowIndicator</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NoShowIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarRental_PBSRecid name="CarRental_PBSRecid">CarRental_PBSRecid</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarRental_PBSRecid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Itinerary_PBSRecid name="Itinerary_PBSRecid">Itinerary_PBSRecid</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Itinerary_PBSRecid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Hotel_PBSRecid name="Hotel_PBSRecid">Hotel_PBSRecid</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hotel_PBSRecid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HashedCCNumber name="HashedCCNumber">HashedCCNumber</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HashedCCNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TrvPBSMaindataRelationshipId name="BackingTable_TrvPBSMaindataRelationshipId">BackingTable_TrvPBSMaindataRelationshipId</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TrvPBSMaindataRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Expense/WorksheetLine/TrvPBSMaindata.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/WorksheetLine/TrvPBSMaindata.cdm.json/TrvPBSMaindata</a></td><td><a href="../../../Tables/Finance/Expense/WorksheetLine/TrvPBSMaindata.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: TravelAndExpense/TrvCreditCardTransactionEntity (this entity)  

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

---
title: PurchPurchaseAgreementLineFulfillmentEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Purchase agreement lines fulfillment in ProcurementAndSourcing(PurchPurchaseAgreementLineFulfillmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase agreement lines fulfillment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PurchaseAgreementLegalEntityId](#PurchaseAgreementLegalEntityId)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[PurchaseAgreementId](#PurchaseAgreementId)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[LineNumber](#LineNumber)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[CommittedQuantity](#CommittedQuantity)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[RemainingQuantity](#RemainingQuantity)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[ReleasedQuantity](#ReleasedQuantity)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[ReceivedQuantity](#ReceivedQuantity)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[InvoicedQuantity](#InvoicedQuantity)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[UnitSymbol](#UnitSymbol)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[CommittedCatchWeightQuantity](#CommittedCatchWeightQuantity)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[RemainingCatchWeightQuantity](#RemainingCatchWeightQuantity)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[ReleasedCatchWeightQuantity](#ReleasedCatchWeightQuantity)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[ReceivedCatchWeightQuantity](#ReceivedCatchWeightQuantity)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[InvoicedCatchWeightQuantity](#InvoicedCatchWeightQuantity)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[CommittedAmount](#CommittedAmount)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[RemainingAmount](#RemainingAmount)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[ReleasedAmount](#ReleasedAmount)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[ReceivedAmount](#ReceivedAmount)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[InvoicedAmount](#InvoicedAmount)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[Relationship_PurchaseAgreementLineV2RelationshipId](#Relationship_PurchaseAgreementLineV2RelationshipId)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[BackingTable_PurchPurchaseAgreementLineV2EntityRelationshipId](#BackingTable_PurchPurchaseAgreementLineV2EntityRelationshipId)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchPurchaseAgreementLineFulfillmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity</a>|

### <a href=#PurchaseAgreementLegalEntityId name="PurchaseAgreementLegalEntityId">PurchaseAgreementLegalEntityId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseAgreementLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseAgreementId name="PurchaseAgreementId">PurchaseAgreementId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommittedQuantity name="CommittedQuantity">CommittedQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommittedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingQuantity name="RemainingQuantity">RemainingQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remaining quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReleasedQuantity name="ReleasedQuantity">ReleasedQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Released quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleasedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Released quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivedQuantity name="ReceivedQuantity">ReceivedQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Received quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Received quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicedQuantity name="InvoicedQuantity">InvoicedQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoiced quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoiced quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitSymbol name="UnitSymbol">UnitSymbol</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommittedCatchWeightQuantity name="CommittedCatchWeightQuantity">CommittedCatchWeightQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommittedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingCatchWeightQuantity name="RemainingCatchWeightQuantity">RemainingCatchWeightQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining CW quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remaining CW quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReleasedCatchWeightQuantity name="ReleasedCatchWeightQuantity">ReleasedCatchWeightQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Released CW quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleasedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Released CW quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivedCatchWeightQuantity name="ReceivedCatchWeightQuantity">ReceivedCatchWeightQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Received CW quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Received CW quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicedCatchWeightQuantity name="InvoicedCatchWeightQuantity">InvoicedCatchWeightQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoiced CW quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicedCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoiced CW quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommittedAmount name="CommittedAmount">CommittedAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommittedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingAmount name="RemainingAmount">RemainingAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remaining amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReleasedAmount name="ReleasedAmount">ReleasedAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Released amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleasedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Released amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivedAmount name="ReceivedAmount">ReceivedAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Received amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Received amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicedAmount name="InvoicedAmount">InvoicedAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoiced amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoiced amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchaseAgreementLineV2RelationshipId name="Relationship_PurchaseAgreementLineV2RelationshipId">Relationship_PurchaseAgreementLineV2RelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseAgreementLineV2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchPurchaseAgreementLineV2EntityRelationshipId name="BackingTable_PurchPurchaseAgreementLineV2EntityRelationshipId">BackingTable_PurchPurchaseAgreementLineV2EntityRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchPurchaseAgreementLineV2EntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementLineFulfillmentEntity (this entity)  

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

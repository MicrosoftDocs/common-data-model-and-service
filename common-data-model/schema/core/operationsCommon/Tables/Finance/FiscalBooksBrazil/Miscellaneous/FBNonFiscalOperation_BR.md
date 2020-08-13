---
title: FBNonFiscalOperation_BR in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Non fiscal operations to be reported in SPED file in Miscellaneous(FBNonFiscalOperation_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBNonFiscalOperation_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBNonFiscalOperation_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Non fiscal operations to be reported in SPED file</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[AccountType](#AccountType)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[CreditSourceCode](#CreditSourceCode)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[Description](#Description)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[FBBookingPeriod_BR](#FBBookingPeriod_BR)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[FiscalEstablishmentDataArea](#FiscalEstablishmentDataArea)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[FiscalEstablishment_BR](#FiscalEstablishment_BR)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[LedgerDimension](#LedgerDimension)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[OffsetDefaultDimension](#OffsetDefaultDimension)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[OffsetLedgerDimension](#OffsetLedgerDimension)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[TotalAmount](#TotalAmount)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[TransDate](#TransDate)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[Voucher](#Voucher)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[FBEconomicActivityCode_BR](#FBEconomicActivityCode_BR)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[Relationship_FBBookingPeriod_BRRelationshipId](#Relationship_FBBookingPeriod_BRRelationshipId)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[Relationship_FiscalEstablishment_BRRelationshipId](#Relationship_FiscalEstablishment_BRRelationshipId)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[Relationship_LedgerDimensionRelationshipId](#Relationship_LedgerDimensionRelationshipId)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[Relationship_OffsetDefaultDimensionRelationshipId](#Relationship_OffsetDefaultDimensionRelationshipId)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[Relationship_OffsetLedgerDimensionRelationshipId](#Relationship_OffsetLedgerDimensionRelationshipId)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[Relationship_FBEconomicActivityCode_BRRelationshipId](#Relationship_FBEconomicActivityCode_BRRelationshipId)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|
|[Relationship_DimensionAttributeValueSetRelationshipId](#Relationship_DimensionAttributeValueSetRelationshipId)||<a href="FBNonFiscalOperation_BR.md" target="_blank">Miscellaneous/FBNonFiscalOperation_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBNonFiscalOperation_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditSourceCode name="CreditSourceCode">CreditSourceCode</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit source code</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditSourceCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit source code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FBBookingPeriod_BR name="FBBookingPeriod_BR">FBBookingPeriod_BR</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBBookingPeriod_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalEstablishmentDataArea name="FiscalEstablishmentDataArea">FiscalEstablishmentDataArea</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishment_BR name="FiscalEstablishment_BR">FiscalEstablishment_BR</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishment_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OffsetDefaultDimension name="OffsetDefaultDimension">OffsetDefaultDimension</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetDefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OffsetLedgerDimension name="OffsetLedgerDimension">OffsetLedgerDimension</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset account</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TotalAmount name="TotalAmount">TotalAmount</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posting date</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posting date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

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

### <a href=#FBEconomicActivityCode_BR name="FBEconomicActivityCode_BR">FBEconomicActivityCode_BR</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBEconomicActivityCode_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_FBBookingPeriod_BRRelationshipId name="Relationship_FBBookingPeriod_BRRelationshipId">Relationship_FBBookingPeriod_BRRelationshipId</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBBookingPeriod_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FBBookingPeriod_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBBookingPeriod_BR.cdm.json/FBBookingPeriod_BR</a></td><td><a href="../Transaction/FBBookingPeriod_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalEstablishment_BRRelationshipId name="Relationship_FiscalEstablishment_BRRelationshipId">Relationship_FiscalEstablishment_BRRelationshipId</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalEstablishment_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FiscalEstablishment_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FiscalEstablishment_BR.cdm.json/FiscalEstablishment_BR</a></td><td><a href="../Main/FiscalEstablishment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionRelationshipId name="Relationship_LedgerDimensionRelationshipId">Relationship_LedgerDimensionRelationshipId</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OffsetDefaultDimensionRelationshipId name="Relationship_OffsetDefaultDimensionRelationshipId">Relationship_OffsetDefaultDimensionRelationshipId</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetDefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OffsetLedgerDimensionRelationshipId name="Relationship_OffsetLedgerDimensionRelationshipId">Relationship_OffsetLedgerDimensionRelationshipId</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBEconomicActivityCode_BRRelationshipId name="Relationship_FBEconomicActivityCode_BRRelationshipId">Relationship_FBEconomicActivityCode_BRRelationshipId</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBEconomicActivityCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FBEconomicActivityCode_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBEconomicActivityCode_BR.cdm.json/FBEconomicActivityCode_BR</a></td><td><a href="FBEconomicActivityCode_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeValueSetRelationshipId name="Relationship_DimensionAttributeValueSetRelationshipId">Relationship_DimensionAttributeValueSetRelationshipId</a>

First included in: Miscellaneous/FBNonFiscalOperation_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

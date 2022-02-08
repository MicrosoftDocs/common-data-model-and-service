---
title: FBCIAPAssetTrans_OtherCredits_BR in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# CIAP Fixed asset transactions other credits in Miscellaneous(FBCIAPAssetTrans_OtherCredits_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBCIAPAssetTrans_OtherCredits_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CIAP Fixed asset transactions other credits</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBCIAPAssetTrans_OtherCredits_BR.md" target="_blank">Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR</a>|
|[FBCIAPAssetTrans_BR](#FBCIAPAssetTrans_BR)||<a href="FBCIAPAssetTrans_OtherCredits_BR.md" target="_blank">Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR</a>|
|[FromDate](#FromDate)||<a href="FBCIAPAssetTrans_OtherCredits_BR.md" target="_blank">Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR</a>|
|[InstallmentAmount](#InstallmentAmount)||<a href="FBCIAPAssetTrans_OtherCredits_BR.md" target="_blank">Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR</a>|
|[InstallmentNum](#InstallmentNum)||<a href="FBCIAPAssetTrans_OtherCredits_BR.md" target="_blank">Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR</a>|
|[ToDate](#ToDate)||<a href="FBCIAPAssetTrans_OtherCredits_BR.md" target="_blank">Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR</a>|
|[TotalOutgoingOperationsAmount](#TotalOutgoingOperationsAmount)||<a href="FBCIAPAssetTrans_OtherCredits_BR.md" target="_blank">Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR</a>|
|[TotalTaxableOutgoingAmount](#TotalTaxableOutgoingAmount)||<a href="FBCIAPAssetTrans_OtherCredits_BR.md" target="_blank">Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR</a>|
|[Relationship_FBCIAPAssetTrans_BRRelationshipId](#Relationship_FBCIAPAssetTrans_BRRelationshipId)||<a href="FBCIAPAssetTrans_OtherCredits_BR.md" target="_blank">Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBCIAPAssetTrans_OtherCredits_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBCIAPAssetTrans_BR name="FBCIAPAssetTrans_BR">FBCIAPAssetTrans_BR</a>

First included in: Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBCIAPAssetTrans_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#InstallmentAmount name="InstallmentAmount">InstallmentAmount</a>

First included in: Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Installment amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstallmentAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Installment amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InstallmentNum name="InstallmentNum">InstallmentNum</a>

First included in: Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Installment number</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstallmentNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Installment number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TotalOutgoingOperationsAmount name="TotalOutgoingOperationsAmount">TotalOutgoingOperationsAmount</a>

First included in: Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total outgoing transactions amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalOutgoingOperationsAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total outgoing transactions amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalTaxableOutgoingAmount name="TotalTaxableOutgoingAmount">TotalTaxableOutgoingAmount</a>

First included in: Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable outgoing transactions amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalTaxableOutgoingAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable outgoing transactions amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Relationship_FBCIAPAssetTrans_BRRelationshipId name="Relationship_FBCIAPAssetTrans_BRRelationshipId">Relationship_FBCIAPAssetTrans_BRRelationshipId</a>

First included in: Miscellaneous/FBCIAPAssetTrans_OtherCredits_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBCIAPAssetTrans_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FBCIAPAssetTrans_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBCIAPAssetTrans_BR.cdm.json/FBCIAPAssetTrans_BR</a></td><td><a href="../Transaction/FBCIAPAssetTrans_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

---
title: TrvPBSMaindata - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# TrvPBSMaindata

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Expense/WorksheetLine/TrvPBSMaindata.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TrvPBSMaindata/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[AmountCurr](#AmountCurr)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[AmountLocal](#AmountLocal)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[BusinessName](#BusinessName)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[CardNumber](#CardNumber)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[CardNumberNIKS](#CardNumberNIKS)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[CardType](#CardType)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[CatCode](#CatCode)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[CatCodesDesc](#CatCodesDesc)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[CCTransUniqueID](#CCTransUniqueID)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[CostType](#CostType)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Country](#Country)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[EmpPayMethodRecId](#EmpPayMethodRecId)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[ExchCode](#ExchCode)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[ExchCodeLocal](#ExchCodeLocal)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[MerchantCategoryCode](#MerchantCategoryCode)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Name](#Name)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Paymethod](#Paymethod)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Posted](#Posted)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Reference](#Reference)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Town](#Town)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[TransDate](#TransDate)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Transferred](#Transferred)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[TravelNo](#TravelNo)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[UserField1](#UserField1)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[UserField2](#UserField2)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[UserField3](#UserField3)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[UserField4](#UserField4)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[UserField5](#UserField5)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[UserField6](#UserField6)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[UserField7](#UserField7)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[UserField8](#UserField8)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[UserField9](#UserField9)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[UserFieldLong](#UserFieldLong)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Worker](#Worker)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[DataAreaId](#DataAreaId)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Relationship_CostTypeRelationshipId](#Relationship_CostTypeRelationshipId)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Relationship_EmpPaymethodRelationshipId](#Relationship_EmpPaymethodRelationshipId)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Relationship_LocalCurrencyRelationshipId](#Relationship_LocalCurrencyRelationshipId)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Relationship_TrvExpTableRelationshipId](#Relationship_TrvExpTableRelationshipId)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Relationship_TrvPaymethodRelationshipId](#Relationship_TrvPaymethodRelationshipId)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TrvPBSMaindata.md" target="_blank">WorksheetLine/TrvPBSMaindata</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TrvPBSMaindata/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountCurr name="AmountCurr">AmountCurr</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCurr attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountLocal name="AmountLocal">AmountLocal</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLocal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BusinessName name="BusinessName">BusinessName</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardNumber name="CardNumber">CardNumber</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

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

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardNumberNIKS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardType name="CardType">CardType</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

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

### <a href=#CatCode name="CatCode">CatCode</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatCodesDesc name="CatCodesDesc">CatCodesDesc</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatCodesDesc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CCTransUniqueID name="CCTransUniqueID">CCTransUniqueID</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

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

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Country name="Country">Country</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Country attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmpPayMethodRecId name="EmpPayMethodRecId">EmpPayMethodRecId</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmpPayMethodRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExchCode name="ExchCode">ExchCode</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchCodeLocal name="ExchCodeLocal">ExchCodeLocal</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchCodeLocal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MerchantCategoryCode name="MerchantCategoryCode">MerchantCategoryCode</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MerchantCategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Paymethod name="Paymethod">Paymethod</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Paymethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Reference name="Reference">Reference</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Town name="Town">Town</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Town attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Transferred name="Transferred">Transferred</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transferred attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TravelNo name="TravelNo">TravelNo</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TravelNo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserField1 name="UserField1">UserField1</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserField1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserField2 name="UserField2">UserField2</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserField2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserField3 name="UserField3">UserField3</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserField3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserField4 name="UserField4">UserField4</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserField4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserField5 name="UserField5">UserField5</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserField5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserField6 name="UserField6">UserField6</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserField6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserField7 name="UserField7">UserField7</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserField7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserField8 name="UserField8">UserField8</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserField8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserField9 name="UserField9">UserField9</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserField9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserFieldLong name="UserFieldLong">UserFieldLong</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserFieldLong attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Worker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CostTypeRelationshipId name="Relationship_CostTypeRelationshipId">Relationship_CostTypeRelationshipId</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CostTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/TrvCostType.md" target="_blank">/core/erp/Tables/Finance/Expense/Reference/TrvCostType.cdm.json/TrvCostType</a></td><td><a href="../Reference/TrvCostType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EmpPaymethodRelationshipId name="Relationship_EmpPaymethodRelationshipId">Relationship_EmpPaymethodRelationshipId</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EmpPaymethodRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/TrvEmpPaymethod.md" target="_blank">/core/erp/Tables/Finance/Expense/Reference/TrvEmpPaymethod.cdm.json/TrvEmpPaymethod</a></td><td><a href="../Reference/TrvEmpPaymethod.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LocalCurrencyRelationshipId name="Relationship_LocalCurrencyRelationshipId">Relationship_LocalCurrencyRelationshipId</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LocalCurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TrvExpTableRelationshipId name="Relationship_TrvExpTableRelationshipId">Relationship_TrvExpTableRelationshipId</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TrvExpTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/TrvExpTable.md" target="_blank">/core/erp/Tables/Finance/Expense/WorksheetHeader/TrvExpTable.cdm.json/TrvExpTable</a></td><td><a href="../WorksheetHeader/TrvExpTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TrvPaymethodRelationshipId name="Relationship_TrvPaymethodRelationshipId">Relationship_TrvPaymethodRelationshipId</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TrvPaymethodRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/TrvPayMethod.md" target="_blank">/core/erp/Tables/Finance/Expense/Reference/TrvPayMethod.cdm.json/TrvPayMethod</a></td><td><a href="../Reference/TrvPayMethod.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/TrvPBSMaindata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

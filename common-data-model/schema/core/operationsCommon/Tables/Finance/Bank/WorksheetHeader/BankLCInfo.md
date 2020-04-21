---
title: BankLCInfo - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# BankLCInfo

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Bank/WorksheetHeader/BankLCInfo.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankLCInfo/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[BankLC](#BankLC)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[Charges](#Charges)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[ConfirmationInstruction](#ConfirmationInstruction)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[Deferreddays](#Deferreddays)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[DescriptionOfGoods](#DescriptionOfGoods)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[DestinationPort](#DestinationPort)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[DocumentsRequired](#DocumentsRequired)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[Draft](#Draft)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[IncoTerms](#IncoTerms)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[LatestShipmentDateTime](#LatestShipmentDateTime)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[PartialShipment](#PartialShipment)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[PeriodOfPresentation](#PeriodOfPresentation)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[PortofLoading](#PortofLoading)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[Remarks](#Remarks)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[SpecialInstructions](#SpecialInstructions)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[TransShipment](#TransShipment)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[DataAreaId](#DataAreaId)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[Relationship_BankLCRelationshipId](#Relationship_BankLCRelationshipId)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="BankLCInfo.md" target="_blank">WorksheetHeader/BankLCInfo</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankLCInfo/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankLC name="BankLC">BankLC</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankLC attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Charges name="Charges">Charges</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Charges attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ConfirmationInstruction name="ConfirmationInstruction">ConfirmationInstruction</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmationInstruction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Deferreddays name="Deferreddays">Deferreddays</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Deferreddays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DescriptionOfGoods name="DescriptionOfGoods">DescriptionOfGoods</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DescriptionOfGoods attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationPort name="DestinationPort">DestinationPort</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationPort attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentsRequired name="DocumentsRequired">DocumentsRequired</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentsRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Draft name="Draft">Draft</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Draft attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IncoTerms name="IncoTerms">IncoTerms</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncoTerms attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LatestShipmentDateTime name="LatestShipmentDateTime">LatestShipmentDateTime</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LatestShipmentDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PartialShipment name="PartialShipment">PartialShipment</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartialShipment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PeriodOfPresentation name="PeriodOfPresentation">PeriodOfPresentation</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodOfPresentation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PortofLoading name="PortofLoading">PortofLoading</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PortofLoading attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Remarks name="Remarks">Remarks</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Remarks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialInstructions name="SpecialInstructions">SpecialInstructions</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialInstructions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransShipment name="TransShipment">TransShipment</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransShipment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

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

### <a href=#Relationship_BankLCRelationshipId name="Relationship_BankLCRelationshipId">Relationship_BankLCRelationshipId</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankLCRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankLC.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetHeader/BankLC.cdm.json/BankLC</a></td><td><a href="BankLC.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/BankLCInfo (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

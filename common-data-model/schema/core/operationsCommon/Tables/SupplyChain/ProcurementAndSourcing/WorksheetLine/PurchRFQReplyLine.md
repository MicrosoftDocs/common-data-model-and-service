---
title: PurchRFQReplyLine in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Request for quotation vendor reply lines in WorksheetLine(PurchRFQReplyLine)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchRFQReplyLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQReplyLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request for quotation vendor reply lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[CalendarDays](#CalendarDays)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[Comment](#Comment)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[DeliveryDate](#DeliveryDate)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[DoSeal](#DoSeal)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[ExternalItemId](#ExternalItemId)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[IsAlternate](#IsAlternate)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[LeadTime](#LeadTime)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[LineAmount](#LineAmount)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[LineDisc](#LineDisc)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[LineNum](#LineNum)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[LinePercent](#LinePercent)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[MaximumRetailPrice_IN](#MaximumRetailPrice_IN)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[MultiLnDisc](#MultiLnDisc)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[MultiLnPercent](#MultiLnPercent)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[Name](#Name)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[PdsCWQty](#PdsCWQty)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[PriceUnit](#PriceUnit)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[PurchMarkup](#PurchMarkup)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[PurchPrice](#PurchPrice)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[PurchQty](#PurchQty)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[PurchUnit](#PurchUnit)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[QtyOrdered](#QtyOrdered)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[ReplyReceived](#ReplyReceived)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[RFQId](#RFQId)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[RFQLineRecId](#RFQLineRecId)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[RFQMark](#RFQMark)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[ValidFrom](#ValidFrom)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[ValidTo](#ValidTo)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[Relationship_PurchRFQLineRelationshipId](#Relationship_PurchRFQLineRelationshipId)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[Relationship_PurchRFQTableRelationshipId](#Relationship_PurchRFQTableRelationshipId)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchRFQReplyLine.md" target="_blank">WorksheetLine/PurchRFQReplyLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQReplyLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CalendarDays name="CalendarDays">CalendarDays</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDate name="DeliveryDate">DeliveryDate</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DoSeal name="DoSeal">DoSeal</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoSeal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExternalItemId name="ExternalItemId">ExternalItemId</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAlternate name="IsAlternate">IsAlternate</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAlternate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LeadTime name="LeadTime">LeadTime</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeadTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineDisc name="LineDisc">LineDisc</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LinePercent name="LinePercent">LinePercent</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinePercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MaximumRetailPrice_IN name="MaximumRetailPrice_IN">MaximumRetailPrice_IN</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRetailPrice_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MultiLnDisc name="MultiLnDisc">MultiLnDisc</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiLnDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MultiLnPercent name="MultiLnPercent">MultiLnPercent</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiLnPercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Name name="Name">Name</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsCWQty name="PdsCWQty">PdsCWQty</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PriceUnit name="PriceUnit">PriceUnit</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchMarkup name="PurchMarkup">PurchMarkup</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchPrice name="PurchPrice">PurchPrice</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit price</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unit price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchQty name="PurchQty">PurchQty</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchUnit name="PurchUnit">PurchUnit</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QtyOrdered name="QtyOrdered">QtyOrdered</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyOrdered attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReplyReceived name="ReplyReceived">ReplyReceived</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyReceived attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RFQId name="RFQId">RFQId</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQLineRecId name="RFQLineRecId">RFQLineRecId</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQLineRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RFQMark name="RFQMark">RFQMark</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQMark attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Effective date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expiration date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expiration date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

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

### <a href=#Relationship_PurchRFQLineRelationshipId name="Relationship_PurchRFQLineRelationshipId">Relationship_PurchRFQLineRelationshipId</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRFQLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PurchRFQLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchRFQLine.cdm.json/PurchRFQLine</a></td><td><a href="PurchRFQLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchRFQTableRelationshipId name="Relationship_PurchRFQTableRelationshipId">Relationship_PurchRFQTableRelationshipId</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRFQTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PurchRFQTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQTable.cdm.json/PurchRFQTable</a></td><td><a href="../WorksheetHeader/PurchRFQTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/PurchRFQReplyLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

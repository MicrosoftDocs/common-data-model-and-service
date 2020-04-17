---
title: RDeferralsCountingJournalLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RDeferralsCountingJournalLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/RDeferrals/WorksheetLine/RDeferralsCountingJournalLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RDeferralsCountingJournalLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[AcquisitionDate](#AcquisitionDate)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[DeferralBookId](#DeferralBookId)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[DeferralID](#DeferralID)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[DeferralsAmount](#DeferralsAmount)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[LifeTime](#LifeTime)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[Months](#Months)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[Name](#Name)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[RDeferralsCountingJournal](#RDeferralsCountingJournal)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[RemainAmount](#RemainAmount)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[WritingOffAmount](#WritingOffAmount)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[WritingOffAmountTotal](#WritingOffAmountTotal)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[WritingOffReportYear](#WritingOffReportYear)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[WroteOffAmount](#WroteOffAmount)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[DataAreaId](#DataAreaId)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[Relationship_RDeferralsBookTableRelationshipId](#Relationship_RDeferralsBookTableRelationshipId)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[Relationship_RDeferralsCountingJournalRelationshipId](#Relationship_RDeferralsCountingJournalRelationshipId)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[Relationship_RDeferralsTableRelationshipId](#Relationship_RDeferralsTableRelationshipId)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RDeferralsCountingJournalLine.md" target="_blank">WorksheetLine/RDeferralsCountingJournalLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RDeferralsCountingJournalLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcquisitionDate name="AcquisitionDate">AcquisitionDate</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DeferralBookId name="DeferralBookId">DeferralBookId</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferralBookId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferralID name="DeferralID">DeferralID</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferralID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferralsAmount name="DeferralsAmount">DeferralsAmount</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferralsAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LifeTime name="LifeTime">LifeTime</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LifeTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Months name="Months">Months</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Months attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

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

### <a href=#RDeferralsCountingJournal name="RDeferralsCountingJournal">RDeferralsCountingJournal</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RDeferralsCountingJournal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RemainAmount name="RemainAmount">RemainAmount</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WritingOffAmount name="WritingOffAmount">WritingOffAmount</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WritingOffAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WritingOffAmountTotal name="WritingOffAmountTotal">WritingOffAmountTotal</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WritingOffAmountTotal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WritingOffReportYear name="WritingOffReportYear">WritingOffReportYear</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WritingOffReportYear attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WroteOffAmount name="WroteOffAmount">WroteOffAmount</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WroteOffAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

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

### <a href=#Relationship_RDeferralsBookTableRelationshipId name="Relationship_RDeferralsBookTableRelationshipId">Relationship_RDeferralsBookTableRelationshipId</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RDeferralsBookTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RDeferralsBookTable.md" target="_blank">/core/erp/Tables/Finance/RDeferrals/Main/RDeferralsBookTable.cdm.json/RDeferralsBookTable</a></td><td><a href="../Main/RDeferralsBookTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RDeferralsCountingJournalRelationshipId name="Relationship_RDeferralsCountingJournalRelationshipId">Relationship_RDeferralsCountingJournalRelationshipId</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RDeferralsCountingJournalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RDeferralsCountingJournal.md" target="_blank">/core/erp/Tables/Finance/RDeferrals/WorksheetHeader/RDeferralsCountingJournal.cdm.json/RDeferralsCountingJournal</a></td><td><a href="../WorksheetHeader/RDeferralsCountingJournal.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RDeferralsTableRelationshipId name="Relationship_RDeferralsTableRelationshipId">Relationship_RDeferralsTableRelationshipId</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RDeferralsTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RDeferralsTable.md" target="_blank">/core/erp/Tables/Finance/RDeferrals/Main/RDeferralsTable.cdm.json/RDeferralsTable</a></td><td><a href="../Main/RDeferralsTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/RDeferralsCountingJournalLine (this entity)  

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

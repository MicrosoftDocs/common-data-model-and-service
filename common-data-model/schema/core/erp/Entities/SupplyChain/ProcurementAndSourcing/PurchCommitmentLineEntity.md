---
title: PurchCommitmentLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# PurchCommitmentLineEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/ProcurementAndSourcing/PurchCommitmentLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AgreementLine](#AgreementLine)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[Comment](#Comment)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[LedgerDimension](#LedgerDimension)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[LineAmount](#LineAmount)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[LineDate](#LineDate)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[OriginalAmount](#OriginalAmount)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[PurchCommitmentHeader_PSN](#PurchCommitmentHeader_PSN)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[CommitmentNumber](#CommitmentNumber)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[Currency](#Currency)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[DefaultDate](#DefaultDate)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[FiscalYear](#FiscalYear)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[Preparer](#Preparer)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[CommitmentName](#CommitmentName)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[ReasonComment](#ReasonComment)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[VendorAccount](#VendorAccount)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[FiscalCalendarYear_FiscalCalendar](#FiscalCalendarYear_FiscalCalendar)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[FiscalCalendarYear_Name](#FiscalCalendarYear_Name)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[FiscalCalendar_CalendarId](#FiscalCalendar_CalendarId)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[LedgerDimensionDisplayValue](#LedgerDimensionDisplayValue)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[AgreementLineNumber](#AgreementLineNumber)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[AgreementNumber](#AgreementNumber)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[Relationship_LedgerDimensionCombinationRelationshipId](#Relationship_LedgerDimensionCombinationRelationshipId)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[BackingTable_PurchCommitmentLine_PSNRelationshipId](#BackingTable_PurchCommitmentLine_PSNRelationshipId)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchCommitmentLineEntity.md" target="_blank">ProcurementAndSourcing/PurchCommitmentLineEntity</a>|

### <a href=#AgreementLine name="AgreementLine">AgreementLine</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDate name="LineDate">LineDate</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalAmount name="OriginalAmount">OriginalAmount</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchCommitmentHeader_PSN name="PurchCommitmentHeader_PSN">PurchCommitmentHeader_PSN</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchCommitmentHeader_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommitmentNumber name="CommitmentNumber">CommitmentNumber</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommitmentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDate name="DefaultDate">DefaultDate</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalYear name="FiscalYear">FiscalYear</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Preparer name="Preparer">Preparer</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Preparer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommitmentName name="CommitmentName">CommitmentName</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommitmentName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonComment name="ReasonComment">ReasonComment</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccount name="VendorAccount">VendorAccount</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarYear_FiscalCalendar name="FiscalCalendarYear_FiscalCalendar">FiscalCalendarYear_FiscalCalendar</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarYear_FiscalCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarYear_Name name="FiscalCalendarYear_Name">FiscalCalendarYear_Name</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarYear_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendar_CalendarId name="FiscalCalendar_CalendarId">FiscalCalendar_CalendarId</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendar_CalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionDisplayValue name="LedgerDimensionDisplayValue">LedgerDimensionDisplayValue</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementLineNumber name="AgreementLineNumber">AgreementLineNumber</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementNumber name="AgreementNumber">AgreementNumber</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionCombinationRelationshipId name="Relationship_LedgerDimensionCombinationRelationshipId">Relationship_LedgerDimensionCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PurchCommitmentLine_PSNRelationshipId name="BackingTable_PurchCommitmentLine_PSNRelationshipId">BackingTable_PurchCommitmentLine_PSNRelationshipId</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchCommitmentLine_PSNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/PublicSector/Miscellaneous/PurchCommitmentLine_PSN.md" target="_blank">/core/erp/Tables/Finance/PublicSector/Miscellaneous/PurchCommitmentLine_PSN.cdm.json/PurchCommitmentLine_PSN</a></td><td><a href="../../../Tables/Finance/PublicSector/Miscellaneous/PurchCommitmentLine_PSN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchCommitmentLineEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

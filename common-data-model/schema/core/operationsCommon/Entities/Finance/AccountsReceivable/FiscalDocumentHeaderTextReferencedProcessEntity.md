---
title: FiscalDocumentHeaderTextReferencedProcessEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Fiscal document header text referenced process entity in AccountsReceivable(FiscalDocumentHeaderTextReferencedProcessEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal document header text referenced process entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Agency](#Agency)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[DocuRef](#DocuRef)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[FiscalDocumentDirection](#FiscalDocumentDirection)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[FiscalDocumentFiscalEstablishmentId](#FiscalDocumentFiscalEstablishmentId)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[FiscalDocumentHeaderTextId](#FiscalDocumentHeaderTextId)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[FiscalDocumentNumber](#FiscalDocumentNumber)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[FiscalDocumentSeries](#FiscalDocumentSeries)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[FiscalDocumentStatus](#FiscalDocumentStatus)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[FiscalDocumentThirdPartyCNPJorCPF](#FiscalDocumentThirdPartyCNPJorCPF)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[FiscalDocumentVoucher](#FiscalDocumentVoucher)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[ProcessNumber](#ProcessNumber)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[RefCompanyId](#RefCompanyId)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[RefRecId](#RefRecId)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[RefTableId](#RefTableId)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[Relationship_FiscalDocumentHeaderTextEntityRelationshipId](#Relationship_FiscalDocumentHeaderTextEntityRelationshipId)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[BackingTable_FiscalDocumentReferencedProcess_BRRelationshipId](#BackingTable_FiscalDocumentReferencedProcess_BRRelationshipId)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="FiscalDocumentHeaderTextReferencedProcessEntity.md" target="_blank">AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity</a>|

### <a href=#Agency name="Agency">Agency</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Agency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuRef name="DocuRef">DocuRef</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentDirection name="FiscalDocumentDirection">FiscalDocumentDirection</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentDirection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentFiscalEstablishmentId name="FiscalDocumentFiscalEstablishmentId">FiscalDocumentFiscalEstablishmentId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentFiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentHeaderTextId name="FiscalDocumentHeaderTextId">FiscalDocumentHeaderTextId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentHeaderTextId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentNumber name="FiscalDocumentNumber">FiscalDocumentNumber</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

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

### <a href=#FiscalDocumentSeries name="FiscalDocumentSeries">FiscalDocumentSeries</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSeries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentStatus name="FiscalDocumentStatus">FiscalDocumentStatus</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentThirdPartyCNPJorCPF name="FiscalDocumentThirdPartyCNPJorCPF">FiscalDocumentThirdPartyCNPJorCPF</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentThirdPartyCNPJorCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentVoucher name="FiscalDocumentVoucher">FiscalDocumentVoucher</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessNumber name="ProcessNumber">ProcessNumber</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefCompanyId name="RefCompanyId">RefCompanyId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentHeaderTextEntityRelationshipId name="Relationship_FiscalDocumentHeaderTextEntityRelationshipId">Relationship_FiscalDocumentHeaderTextEntityRelationshipId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentHeaderTextEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_FiscalDocumentReferencedProcess_BRRelationshipId name="BackingTable_FiscalDocumentReferencedProcess_BRRelationshipId">BackingTable_FiscalDocumentReferencedProcess_BRRelationshipId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FiscalDocumentReferencedProcess_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Miscellaneous/FiscalDocumentReferencedProcess_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FiscalDocumentReferencedProcess_BR.cdm.json/FiscalDocumentReferencedProcess_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Miscellaneous/FiscalDocumentReferencedProcess_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/FiscalDocumentHeaderTextReferencedProcessEntity (this entity)  

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

---
title: EFDocumentReceivedXmlEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Received NF-e XML documents in AccountsReceivable(EFDocumentReceivedXmlEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/EFDocumentReceivedXmlEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Received NF-e XML documents</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Accesskey](#Accesskey)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[CNPJ](#CNPJ)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[FiscalDocumentReference](#FiscalDocumentReference)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[Number](#Number)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[Series](#Series)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[FiscalEstablishmentReference](#FiscalEstablishmentReference)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[IBGECode](#IBGECode)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[StatusFromSEFAZ](#StatusFromSEFAZ)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[DateAndTimeOfTheLastInquiry](#DateAndTimeOfTheLastInquiry)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[ManualInsertion](#ManualInsertion)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[Posted](#Posted)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[ReturnCode](#ReturnCode)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[Description](#Description)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[BackingTable_EFDocumentReceivedXML_BRRelationshipId](#BackingTable_EFDocumentReceivedXML_BRRelationshipId)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="EFDocumentReceivedXmlEntity.md" target="_blank">AccountsReceivable/EFDocumentReceivedXmlEntity</a>|

### <a href=#Accesskey name="Accesskey">Accesskey</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Accesskey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CNPJ name="CNPJ">CNPJ</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CNPJ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentReference name="FiscalDocumentReference">FiscalDocumentReference</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Number name="Number">Number</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Number attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Series name="Series">Series</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Series attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentReference name="FiscalEstablishmentReference">FiscalEstablishmentReference</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IBGECode name="IBGECode">IBGECode</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IBGECode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatusFromSEFAZ name="StatusFromSEFAZ">StatusFromSEFAZ</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatusFromSEFAZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateAndTimeOfTheLastInquiry name="DateAndTimeOfTheLastInquiry">DateAndTimeOfTheLastInquiry</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateAndTimeOfTheLastInquiry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualInsertion name="ManualInsertion">ManualInsertion</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualInsertion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnCode name="ReturnCode">ReturnCode</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EFDocumentReceivedXML_BRRelationshipId name="BackingTable_EFDocumentReceivedXML_BRRelationshipId">BackingTable_EFDocumentReceivedXML_BRRelationshipId</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EFDocumentReceivedXML_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Transaction/EFDocumentReceivedXML_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/EFDocumentReceivedXML_BR.cdm.json/EFDocumentReceivedXML_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Transaction/EFDocumentReceivedXML_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/EFDocumentReceivedXmlEntity (this entity)  

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

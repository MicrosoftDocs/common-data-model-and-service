---
title: EFDocHist_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# EFDocHist_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocHist_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocHist_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[ContingencyMode](#ContingencyMode)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[ContingencyReason](#ContingencyReason)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[Date](#Date)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[EFDocAuthority](#EFDocAuthority)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[EFDRefRecId](#EFDRefRecId)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[FiscalDocStatus](#FiscalDocStatus)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[MessageStatus](#MessageStatus)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[MessageType](#MessageType)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[ReceiptNumber](#ReceiptNumber)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[ReturnCodeDescription](#ReturnCodeDescription)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[ReturnCodeRefRecId](#ReturnCodeRefRecId)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[ReturnMessage](#ReturnMessage)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[Time](#Time)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[Relationship_EFDocAuthorityRelationshipId](#Relationship_EFDocAuthorityRelationshipId)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[Relationship_EFDReturnCode_BRRelationshipId](#Relationship_EFDReturnCode_BRRelationshipId)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[Relationship_ElectronicFiscalDoc_BRRelationshipId](#Relationship_ElectronicFiscalDoc_BRRelationshipId)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EFDocHist_BR.md" target="_blank">Miscellaneous/EFDocHist_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocHist_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ContingencyMode name="ContingencyMode">ContingencyMode</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContingencyMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ContingencyReason name="ContingencyReason">ContingencyReason</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContingencyReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Date name="Date">Date</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Date attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#EFDocAuthority name="EFDocAuthority">EFDocAuthority</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocAuthority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFDRefRecId name="EFDRefRecId">EFDRefRecId</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocStatus name="FiscalDocStatus">FiscalDocStatus</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MessageStatus name="MessageStatus">MessageStatus</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MessageType name="MessageType">MessageType</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReceiptNumber name="ReceiptNumber">ReceiptNumber</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnCodeDescription name="ReturnCodeDescription">ReturnCodeDescription</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnCodeRefRecId name="ReturnCodeRefRecId">ReturnCodeRefRecId</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnCodeRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReturnMessage name="ReturnMessage">ReturnMessage</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnMessage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Time name="Time">Time</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Time attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

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

### <a href=#Relationship_EFDocAuthorityRelationshipId name="Relationship_EFDocAuthorityRelationshipId">Relationship_EFDocAuthorityRelationshipId</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDocAuthorityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EFDocAuthority_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocAuthority_BR.cdm.json/EFDocAuthority_BR</a></td><td><a href="EFDocAuthority_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EFDReturnCode_BRRelationshipId name="Relationship_EFDReturnCode_BRRelationshipId">Relationship_EFDReturnCode_BRRelationshipId</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDReturnCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EFDReturnCode_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDReturnCode_BR.cdm.json/EFDReturnCode_BR</a></td><td><a href="EFDReturnCode_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ElectronicFiscalDoc_BRRelationshipId name="Relationship_ElectronicFiscalDoc_BRRelationshipId">Relationship_ElectronicFiscalDoc_BRRelationshipId</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ElectronicFiscalDoc_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/EFDocument_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/EFDocument_BR.cdm.json/EFDocument_BR</a></td><td><a href="../Transaction/EFDocument_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/EFDocHist_BR (this entity)  

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

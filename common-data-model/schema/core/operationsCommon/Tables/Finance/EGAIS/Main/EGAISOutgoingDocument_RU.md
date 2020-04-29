---
title: EGAISOutgoingDocument_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Outgoing EGAIS documents

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/EGAIS/Main/EGAISOutgoingDocument_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EGAISOutgoingDocument_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Outgoing EGAIS documents</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[BranchId](#BranchId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[DigitalSignature](#DigitalSignature)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[DocumentId](#DocumentId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[DocumentType](#DocumentType)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[DocumentVersion](#DocumentVersion)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Info](#Info)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[ReplyId](#ReplyId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[ResponseXML](#ResponseXML)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[SentDateTime](#SentDateTime)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[SourceRecId](#SourceRecId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Status](#Status)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Url](#Url)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[XML](#XML)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Relationship_Branches_RURelationshipId](#Relationship_Branches_RURelationshipId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Relationship_EGAISChargeOnJour_RURelationshipId](#Relationship_EGAISChargeOnJour_RURelationshipId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Relationship_EGAISConfirmTicket_RURelationshipId](#Relationship_EGAISConfirmTicket_RURelationshipId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Relationship_EGAISInfoVersionTTN_RURelationshipId](#Relationship_EGAISInfoVersionTTN_RURelationshipId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Relationship_EGAISQuery_RURelationshipId](#Relationship_EGAISQuery_RURelationshipId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Relationship_EGAISRequestRepealWB_RURelationshipId](#Relationship_EGAISRequestRepealWB_RURelationshipId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Relationship_EGAISWaybillActJour_RURelationshipId](#Relationship_EGAISWaybillActJour_RURelationshipId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Relationship_EGAISWaybillJour_RURelationshipId](#Relationship_EGAISWaybillJour_RURelationshipId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Relationship_EGAISWriteOffJour_RURelationshipId](#Relationship_EGAISWriteOffJour_RURelationshipId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EGAISOutgoingDocument_RU.md" target="_blank">Main/EGAISOutgoingDocument_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EGAISOutgoingDocument_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BranchId name="BranchId">BranchId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BranchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DigitalSignature name="DigitalSignature">DigitalSignature</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DigitalSignature attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentId name="DocumentId">DocumentId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentType name="DocumentType">DocumentType</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#DocumentVersion name="DocumentVersion">DocumentVersion</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Info name="Info">Info</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Info attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyId name="ReplyId">ReplyId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponseXML name="ResponseXML">ResponseXML</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Response</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponseXML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Response</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SentDateTime name="SentDateTime">SentDateTime</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sent date and time</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SentDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sent date and time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#SourceRecId name="SourceRecId">SourceRecId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Url name="Url">Url</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Url attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XML name="XML">XML</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

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

### <a href=#Relationship_Branches_RURelationshipId name="Relationship_Branches_RURelationshipId">Relationship_Branches_RURelationshipId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Branches_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Group/Branches_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Group/Branches_RU.cdm.json/Branches_RU</a></td><td><a href="../../APARShared/Group/Branches_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EGAISChargeOnJour_RURelationshipId name="Relationship_EGAISChargeOnJour_RURelationshipId">Relationship_EGAISChargeOnJour_RURelationshipId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EGAISChargeOnJour_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/EGAISChargeOnJour_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/WorksheetHeader/EGAISChargeOnJour_RU.cdm.json/EGAISChargeOnJour_RU</a></td><td><a href="../WorksheetHeader/EGAISChargeOnJour_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EGAISConfirmTicket_RURelationshipId name="Relationship_EGAISConfirmTicket_RURelationshipId">Relationship_EGAISConfirmTicket_RURelationshipId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EGAISConfirmTicket_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EGAISConfirmTicket_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/Main/EGAISConfirmTicket_RU.cdm.json/EGAISConfirmTicket_RU</a></td><td><a href="EGAISConfirmTicket_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EGAISInfoVersionTTN_RURelationshipId name="Relationship_EGAISInfoVersionTTN_RURelationshipId">Relationship_EGAISInfoVersionTTN_RURelationshipId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EGAISInfoVersionTTN_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/EGAISInfoVersionTTN_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/Group/EGAISInfoVersionTTN_RU.cdm.json/EGAISInfoVersionTTN_RU</a></td><td><a href="../Group/EGAISInfoVersionTTN_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EGAISQuery_RURelationshipId name="Relationship_EGAISQuery_RURelationshipId">Relationship_EGAISQuery_RURelationshipId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EGAISQuery_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/EGAISQuery_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/Group/EGAISQuery_RU.cdm.json/EGAISQuery_RU</a></td><td><a href="../Group/EGAISQuery_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EGAISRequestRepealWB_RURelationshipId name="Relationship_EGAISRequestRepealWB_RURelationshipId">Relationship_EGAISRequestRepealWB_RURelationshipId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EGAISRequestRepealWB_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EGAISRequestRepealWB_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/Main/EGAISRequestRepealWB_RU.cdm.json/EGAISRequestRepealWB_RU</a></td><td><a href="EGAISRequestRepealWB_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EGAISWaybillActJour_RURelationshipId name="Relationship_EGAISWaybillActJour_RURelationshipId">Relationship_EGAISWaybillActJour_RURelationshipId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EGAISWaybillActJour_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/EGAISWaybillActJour_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/WorksheetHeader/EGAISWaybillActJour_RU.cdm.json/EGAISWaybillActJour_RU</a></td><td><a href="../WorksheetHeader/EGAISWaybillActJour_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EGAISWaybillJour_RURelationshipId name="Relationship_EGAISWaybillJour_RURelationshipId">Relationship_EGAISWaybillJour_RURelationshipId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EGAISWaybillJour_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/EGAISWaybillJour_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/WorksheetHeader/EGAISWaybillJour_RU.cdm.json/EGAISWaybillJour_RU</a></td><td><a href="../WorksheetHeader/EGAISWaybillJour_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EGAISWriteOffJour_RURelationshipId name="Relationship_EGAISWriteOffJour_RURelationshipId">Relationship_EGAISWriteOffJour_RURelationshipId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EGAISWriteOffJour_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/EGAISWriteOffJour_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/EGAIS/WorksheetHeader/EGAISWriteOffJour_RU.cdm.json/EGAISWriteOffJour_RU</a></td><td><a href="../WorksheetHeader/EGAISWriteOffJour_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/EGAISOutgoingDocument_RU (this entity)  

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

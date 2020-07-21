---
title: EFDocAuthorityEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# NF-e authority in AccountsReceivable(EFDocAuthorityEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/EFDocAuthorityEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>NF-e authority</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Authority](#Authority)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|
|[Name](#Name)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|
|[IgnoreAccents](#IgnoreAccents)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|
|[CancelAsEvent](#CancelAsEvent)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|
|[AuthorityType](#AuthorityType)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|
|[ContingencyMode](#ContingencyMode)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|
|[SVCAuthorityId](#SVCAuthorityId)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|
|[NfceConsumerInquiryUrl](#NfceConsumerInquiryUrl)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|
|[NfceMaxAmountWithUnindentifiedCustomer](#NfceMaxAmountWithUnindentifiedCustomer)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|
|[ProcessNfceSynchronous](#ProcessNfceSynchronous)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|
|[ICMSTaxBaseAmountLimit](#ICMSTaxBaseAmountLimit)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|
|[BackingTable_EFDocAuthority_BRRelationshipId](#BackingTable_EFDocAuthority_BRRelationshipId)||<a href="EFDocAuthorityEntity.md" target="_blank">AccountsReceivable/EFDocAuthorityEntity</a>|

### <a href=#Authority name="Authority">Authority</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Authority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IgnoreAccents name="IgnoreAccents">IgnoreAccents</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IgnoreAccents attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CancelAsEvent name="CancelAsEvent">CancelAsEvent</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelAsEvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuthorityType name="AuthorityType">AuthorityType</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuthorityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContingencyMode name="ContingencyMode">ContingencyMode</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContingencyMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SVCAuthorityId name="SVCAuthorityId">SVCAuthorityId</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SVCAuthorityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NfceConsumerInquiryUrl name="NfceConsumerInquiryUrl">NfceConsumerInquiryUrl</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NfceConsumerInquiryUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NfceMaxAmountWithUnindentifiedCustomer name="NfceMaxAmountWithUnindentifiedCustomer">NfceMaxAmountWithUnindentifiedCustomer</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NfceMaxAmountWithUnindentifiedCustomer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessNfceSynchronous name="ProcessNfceSynchronous">ProcessNfceSynchronous</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessNfceSynchronous attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ICMSTaxBaseAmountLimit name="ICMSTaxBaseAmountLimit">ICMSTaxBaseAmountLimit</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSTaxBaseAmountLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EFDocAuthority_BRRelationshipId name="BackingTable_EFDocAuthority_BRRelationshipId">BackingTable_EFDocAuthority_BRRelationshipId</a>

First included in: AccountsReceivable/EFDocAuthorityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EFDocAuthority_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocAuthority_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocAuthority_BR.cdm.json/EFDocAuthority_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocAuthority_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

---
title: RetailTransactionServiceProfileEntity in ChannelManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Commerce Data Exchange: Real-time Service profile in ChannelManagement(RetailTransactionServiceProfileEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/RetailTransactionServiceProfileEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service profile</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CentralTableServer](#CentralTableServer)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[CentralTableServerPort](#CentralTableServerPort)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[Language](#Language)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[Name](#Name)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[PosTSPassword](#PosTSPassword)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[ProfileId](#ProfileId)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[Protocol](#Protocol)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[RetailTSData](#RetailTSData)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[SecurityOff](#SecurityOff)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[ServerCertificateDNS](#ServerCertificateDNS)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[ServerServiceName](#ServerServiceName)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[TSStaff](#TSStaff)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[TSVersion](#TSVersion)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[ReportExecutionTimeout](#ReportExecutionTimeout)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[TransferFileChunkSize](#TransferFileChunkSize)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[UserId](#UserId)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[ServiceHostUrl](#ServiceHostUrl)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[IssuerUri](#IssuerUri)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[IdentityProvider](#IdentityProvider)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[IdentityProviderClaimType](#IdentityProviderClaimType)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[IssuedTokenType](#IssuedTokenType)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[AudienceUrn](#AudienceUrn)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[AosUrl](#AosUrl)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|
|[BackingTable_RetailTransactionServiceProfileRelationshipId](#BackingTable_RetailTransactionServiceProfileRelationshipId)||<a href="RetailTransactionServiceProfileEntity.md" target="_blank">ChannelManagement/RetailTransactionServiceProfileEntity</a>|

### <a href=#CentralTableServer name="CentralTableServer">CentralTableServer</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Server</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralTableServer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Server</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CentralTableServerPort name="CentralTableServerPort">CentralTableServerPort</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Port</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralTableServerPort attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Port</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Language name="Language">Language</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Language attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

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

### <a href=#PosTSPassword name="PosTSPassword">PosTSPassword</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PosTSPassword attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileId name="ProfileId">ProfileId</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Protocol name="Protocol">Protocol</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Protocol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailTSData name="RetailTSData">RetailTSData</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Data for Real-time Service</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTSData attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Data for Real-time Service</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecurityOff name="SecurityOff">SecurityOff</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Security mode off</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityOff attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Security mode off</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServerCertificateDNS name="ServerCertificateDNS">ServerCertificateDNS</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServerCertificateDNS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServerServiceName name="ServerServiceName">ServerServiceName</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServerServiceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TSStaff name="TSStaff">TSStaff</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service staff</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSStaff attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service staff</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TSVersion name="TSVersion">TSVersion</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportExecutionTimeout name="ReportExecutionTimeout">ReportExecutionTimeout</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Report generation timeout (secs.)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportExecutionTimeout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Report generation timeout (secs.)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferFileChunkSize name="TransferFileChunkSize">TransferFileChunkSize</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferFileChunkSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserId name="UserId">UserId</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceHostUrl name="ServiceHostUrl">ServiceHostUrl</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceHostUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IssuerUri name="IssuerUri">IssuerUri</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssuerUri attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentityProvider name="IdentityProvider">IdentityProvider</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentityProvider attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentityProviderClaimType name="IdentityProviderClaimType">IdentityProviderClaimType</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentityProviderClaimType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IssuedTokenType name="IssuedTokenType">IssuedTokenType</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssuedTokenType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AudienceUrn name="AudienceUrn">AudienceUrn</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AudienceUrn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AosUrl name="AosUrl">AosUrl</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AosUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailTransactionServiceProfileRelationshipId name="BackingTable_RetailTransactionServiceProfileRelationshipId">BackingTable_RetailTransactionServiceProfileRelationshipId</a>

First included in: ChannelManagement/RetailTransactionServiceProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionServiceProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/ChannelManagement/Parameter/RetailTransactionServiceProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/Parameter/RetailTransactionServiceProfile.cdm.json/RetailTransactionServiceProfile</a></td><td><a href="../../../Tables/Commerce/ChannelManagement/Parameter/RetailTransactionServiceProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

---
title: EFDocAuthority_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# NF-e authority

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocAuthority_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocAuthority_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>NF-e authority</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[AuthorityId](#AuthorityId)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[AuthorityType](#AuthorityType)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[CancelAsEvent](#CancelAsEvent)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[convertAccentedCharacters](#convertAccentedCharacters)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[Description](#Description)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[ConsumerEFDocInquiryUrl](#ConsumerEFDocInquiryUrl)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[ConsumerEFDocMaxAmountWithoutCustomer](#ConsumerEFDocMaxAmountWithoutCustomer)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[ConsumerEFDSyncProcess](#ConsumerEFDSyncProcess)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[ContingencyMode](#ContingencyMode)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[SVCAuthorityId](#SVCAuthorityId)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[ICMSLimitBaseAmount](#ICMSLimitBaseAmount)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|
|[ICMSLimitBaseAmountIsSet](#ICMSLimitBaseAmountIsSet)||<a href="EFDocAuthority_BR.md" target="_blank">Miscellaneous/EFDocAuthority_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocAuthority_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AuthorityId name="AuthorityId">AuthorityId</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuthorityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuthorityType name="AuthorityType">AuthorityType</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuthorityType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CancelAsEvent name="CancelAsEvent">CancelAsEvent</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelAsEvent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#convertAccentedCharacters name="convertAccentedCharacters">convertAccentedCharacters</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the convertAccentedCharacters attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumerEFDocInquiryUrl name="ConsumerEFDocInquiryUrl">ConsumerEFDocInquiryUrl</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Internet address for NFC-e inquiry</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDocInquiryUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Internet address for NFC-e inquiry</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumerEFDocMaxAmountWithoutCustomer name="ConsumerEFDocMaxAmountWithoutCustomer">ConsumerEFDocMaxAmountWithoutCustomer</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDocMaxAmountWithoutCustomer attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumerEFDSyncProcess name="ConsumerEFDSyncProcess">ConsumerEFDSyncProcess</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerEFDSyncProcess attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ContingencyMode name="ContingencyMode">ContingencyMode</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContingencyMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SVCAuthorityId name="SVCAuthorityId">SVCAuthorityId</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SVC Authority</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SVCAuthorityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>SVC Authority</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ICMSLimitBaseAmount name="ICMSLimitBaseAmount">ICMSLimitBaseAmount</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum ICMS base amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSLimitBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum ICMS base amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSLimitBaseAmountIsSet name="ICMSLimitBaseAmountIsSet">ICMSLimitBaseAmountIsSet</a>

First included in: Miscellaneous/EFDocAuthority_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSLimitBaseAmountIsSet attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

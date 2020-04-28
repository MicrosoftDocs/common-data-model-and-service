---
title: FBBookingPeriodFiscalDocument_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Booking period fiscal document relationships

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBBookingPeriodFiscalDocument_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBBookingPeriodFiscalDocument_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Booking period fiscal document relationships</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[FBBookingPeriod_BR](#FBBookingPeriod_BR)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[FiscalDocument_BR](#FiscalDocument_BR)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[FiscalSituation](#FiscalSituation)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[HasCofins](#HasCofins)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[HasIcms](#HasIcms)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[HasIcmsSt](#HasIcmsSt)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[HasIpi](#HasIpi)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[HasIss](#HasIss)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[HasPis](#HasPis)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[RetailZReport_BR](#RetailZReport_BR)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[SpedContribRecord](#SpedContribRecord)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[SpedFiscalRecord](#SpedFiscalRecord)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[ThirdPartyType](#ThirdPartyType)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[HasIcmsDiff](#HasIcmsDiff)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[HasInss](#HasInss)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[HasInssRet](#HasInssRet)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[Relationship_FBBookingPeriod_BRRelationshipId](#Relationship_FBBookingPeriod_BRRelationshipId)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|
|[Relationship_FiscalDocument_BRRelationshipId](#Relationship_FiscalDocument_BRRelationshipId)||<a href="FBBookingPeriodFiscalDocument_BR.md" target="_blank">Transaction/FBBookingPeriodFiscalDocument_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBBookingPeriodFiscalDocument_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBBookingPeriod_BR name="FBBookingPeriod_BR">FBBookingPeriod_BR</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBBookingPeriod_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocument_BR name="FiscalDocument_BR">FiscalDocument_BR</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocument_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalSituation name="FiscalSituation">FiscalSituation</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalSituation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HasCofins name="HasCofins">HasCofins</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has COFINS tax transaction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasCofins attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Has COFINS tax transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#HasIcms name="HasIcms">HasIcms</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has ICMS tax transaction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasIcms attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Has ICMS tax transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#HasIcmsSt name="HasIcmsSt">HasIcmsSt</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has ICMS-ST tax transaction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasIcmsSt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Has ICMS-ST tax transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#HasIpi name="HasIpi">HasIpi</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has IPI tax transaction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasIpi attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Has IPI tax transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#HasIss name="HasIss">HasIss</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has ISS tax transaction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasIss attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Has ISS tax transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#HasPis name="HasPis">HasPis</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has PIS tax transaction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasPis attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Has PIS tax transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RetailZReport_BR name="RetailZReport_BR">RetailZReport_BR</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailZReport_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SpedContribRecord name="SpedContribRecord">SpedContribRecord</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sped contributions record</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpedContribRecord attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sped contributions record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpedFiscalRecord name="SpedFiscalRecord">SpedFiscalRecord</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sped fiscal record</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpedFiscalRecord attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sped fiscal record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyType name="ThirdPartyType">ThirdPartyType</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HasIcmsDiff name="HasIcmsDiff">HasIcmsDiff</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has ICMS-DIFF tax transaction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasIcmsDiff attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Has ICMS-DIFF tax transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#HasInss name="HasInss">HasInss</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has INSS tax transaction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasInss attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Has INSS tax transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#HasInssRet name="HasInssRet">HasInssRet</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has Retained INSS tax transaction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasInssRet attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Has Retained INSS tax transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_FBBookingPeriod_BRRelationshipId name="Relationship_FBBookingPeriod_BRRelationshipId">Relationship_FBBookingPeriod_BRRelationshipId</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBBookingPeriod_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FBBookingPeriod_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBBookingPeriod_BR.cdm.json/FBBookingPeriod_BR</a></td><td><a href="FBBookingPeriod_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocument_BRRelationshipId name="Relationship_FiscalDocument_BRRelationshipId">Relationship_FiscalDocument_BRRelationshipId</a>

First included in: Transaction/FBBookingPeriodFiscalDocument_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocument_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FiscalDocument_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocument_BR.cdm.json/FiscalDocument_BR</a></td><td><a href="FiscalDocument_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

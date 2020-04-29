---
title: RTax25LedgerAccountGroupEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Ledger posting groups of profit tax

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/RTax25/RTax25LedgerAccountGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger posting groups of profit tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountForFATaxes](#AccountForFATaxes)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[CTA](#CTA)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[CTL](#CTL)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[DTA](#DTA)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[DTL](#DTL)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[LedgerPostingGroup](#LedgerPostingGroup)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[WritingOffDTA](#WritingOffDTA)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[WritingOffDTL](#WritingOffDTL)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[AccountForFATaxesDisplayValue](#AccountForFATaxesDisplayValue)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[CTADisplayValue](#CTADisplayValue)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[CTLDisplayValue](#CTLDisplayValue)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[DTADisplayValue](#DTADisplayValue)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[DTLDisplayValue](#DTLDisplayValue)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[WritingOffDTADisplayValue](#WritingOffDTADisplayValue)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[WritingOffDTLDisplayValue](#WritingOffDTLDisplayValue)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[Relationship_AccountForFATaxesCombinationRelationshipId](#Relationship_AccountForFATaxesCombinationRelationshipId)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[Relationship_CTACombinationRelationshipId](#Relationship_CTACombinationRelationshipId)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[Relationship_CTLCombinationRelationshipId](#Relationship_CTLCombinationRelationshipId)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[Relationship_DTACombinationRelationshipId](#Relationship_DTACombinationRelationshipId)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[Relationship_DTLCombinationRelationshipId](#Relationship_DTLCombinationRelationshipId)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[Relationship_WritingOffDTACombinationRelationshipId](#Relationship_WritingOffDTACombinationRelationshipId)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[Relationship_WritingOffDTLCombinationRelationshipId](#Relationship_WritingOffDTLCombinationRelationshipId)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[BackingTable_RTax25LedgerAccountGroupRelationshipId](#BackingTable_RTax25LedgerAccountGroupRelationshipId)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RTax25LedgerAccountGroupEntity.md" target="_blank">RTax25/RTax25LedgerAccountGroupEntity</a>|

### <a href=#AccountForFATaxes name="AccountForFATaxes">AccountForFATaxes</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountForFATaxes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CTA name="CTA">CTA</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CTA attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CTL name="CTL">CTL</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CTL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DTA name="DTA">DTA</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DTA attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DTL name="DTL">DTL</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DTL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerPostingGroup name="LedgerPostingGroup">LedgerPostingGroup</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPostingGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WritingOffDTA name="WritingOffDTA">WritingOffDTA</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WritingOffDTA attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WritingOffDTL name="WritingOffDTL">WritingOffDTL</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WritingOffDTL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountForFATaxesDisplayValue name="AccountForFATaxesDisplayValue">AccountForFATaxesDisplayValue</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account for FA taxes</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountForFATaxesDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account for FA taxes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CTADisplayValue name="CTADisplayValue">CTADisplayValue</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CTA</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CTADisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CTA</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CTLDisplayValue name="CTLDisplayValue">CTLDisplayValue</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CTL</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CTLDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CTL</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DTADisplayValue name="DTADisplayValue">DTADisplayValue</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>DTA</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DTADisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>DTA</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DTLDisplayValue name="DTLDisplayValue">DTLDisplayValue</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>DTL</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DTLDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>DTL</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WritingOffDTADisplayValue name="WritingOffDTADisplayValue">WritingOffDTADisplayValue</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Writing off DTA</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WritingOffDTADisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Writing off DTA</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WritingOffDTLDisplayValue name="WritingOffDTLDisplayValue">WritingOffDTLDisplayValue</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Writing off DTL</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WritingOffDTLDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Writing off DTL</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AccountForFATaxesCombinationRelationshipId name="Relationship_AccountForFATaxesCombinationRelationshipId">Relationship_AccountForFATaxesCombinationRelationshipId</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountForFATaxesCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CTACombinationRelationshipId name="Relationship_CTACombinationRelationshipId">Relationship_CTACombinationRelationshipId</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CTACombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CTLCombinationRelationshipId name="Relationship_CTLCombinationRelationshipId">Relationship_CTLCombinationRelationshipId</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CTLCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DTACombinationRelationshipId name="Relationship_DTACombinationRelationshipId">Relationship_DTACombinationRelationshipId</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DTACombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DTLCombinationRelationshipId name="Relationship_DTLCombinationRelationshipId">Relationship_DTLCombinationRelationshipId</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DTLCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WritingOffDTACombinationRelationshipId name="Relationship_WritingOffDTACombinationRelationshipId">Relationship_WritingOffDTACombinationRelationshipId</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WritingOffDTACombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WritingOffDTLCombinationRelationshipId name="Relationship_WritingOffDTLCombinationRelationshipId">Relationship_WritingOffDTLCombinationRelationshipId</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WritingOffDTLCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RTax25LedgerAccountGroupRelationshipId name="BackingTable_RTax25LedgerAccountGroupRelationshipId">BackingTable_RTax25LedgerAccountGroupRelationshipId</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RTax25LedgerAccountGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/RTax25/Group/RTax25LedgerAccountGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Group/RTax25LedgerAccountGroup.cdm.json/RTax25LedgerAccountGroup</a></td><td><a href="../../../Tables/Finance/RTax25/Group/RTax25LedgerAccountGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: RTax25/RTax25LedgerAccountGroupEntity (this entity)  

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

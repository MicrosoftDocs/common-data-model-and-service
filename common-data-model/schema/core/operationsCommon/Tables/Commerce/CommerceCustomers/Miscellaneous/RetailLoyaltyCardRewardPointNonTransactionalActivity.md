---
title: RetailLoyaltyCardRewardPointNonTransactionalActivity in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Non-transactional loyalty activity in Miscellaneous(RetailLoyaltyCardRewardPointNonTransactionalActivity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyCardRewardPointNonTransactionalActivity/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Non-transactional loyalty activity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[CardNumber](#CardNumber)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[NonTransactionalActivityId](#NonTransactionalActivityId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[LoyaltyOtherActivityTypeId](#LoyaltyOtherActivityTypeId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[OMOperatingUnitID](#OMOperatingUnitID)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[EntryDate](#EntryDate)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[EntryTime](#EntryTime)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[RetailAffiliationId](#RetailAffiliationId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[Status](#Status)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[ErrorLogs](#ErrorLogs)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[Relationship_RetailLoyaltyCardRelationshipId](#Relationship_RetailLoyaltyCardRelationshipId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[Relationship_LoyaltyOtherActivityTypeIdRelationshipId](#Relationship_LoyaltyOtherActivityTypeIdRelationshipId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[Relationship_RetailAffiliationRelationshipId](#Relationship_RetailAffiliationRelationshipId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|
|[Relationship_OMOperatingUnitIdRelationshipId](#Relationship_OMOperatingUnitIdRelationshipId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyCardRewardPointNonTransactionalActivity/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CardNumber name="CardNumber">CardNumber</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NonTransactionalActivityId name="NonTransactionalActivityId">NonTransactionalActivityId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonTransactionalActivityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyOtherActivityTypeId name="LoyaltyOtherActivityTypeId">LoyaltyOtherActivityTypeId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyOtherActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMOperatingUnitID name="OMOperatingUnitID">OMOperatingUnitID</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EntryDate name="EntryDate">EntryDate</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#EntryTime name="EntryTime">EntryTime</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#RetailAffiliationId name="RetailAffiliationId">RetailAffiliationId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailAffiliationId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ErrorLogs name="ErrorLogs">ErrorLogs</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorLogs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyCardRelationshipId name="Relationship_RetailLoyaltyCardRelationshipId">Relationship_RetailLoyaltyCardRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltyCardRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailLoyaltyCard.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyCard.cdm.json/RetailLoyaltyCard</a></td><td><a href="RetailLoyaltyCard.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LoyaltyOtherActivityTypeIdRelationshipId name="Relationship_LoyaltyOtherActivityTypeIdRelationshipId">Relationship_LoyaltyOtherActivityTypeIdRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LoyaltyOtherActivityTypeIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailLoyaltyOtherActivityType.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyOtherActivityType.cdm.json/RetailLoyaltyOtherActivityType</a></td><td><a href="RetailLoyaltyOtherActivityType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailAffiliationRelationshipId name="Relationship_RetailAffiliationRelationshipId">Relationship_RetailAffiliationRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailAffiliationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailAffiliation.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailAffiliation.cdm.json/RetailAffiliation</a></td><td><a href="RetailAffiliation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OMOperatingUnitIdRelationshipId name="Relationship_OMOperatingUnitIdRelationshipId">Relationship_OMOperatingUnitIdRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OMOperatingUnitIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/OMOperatingUnit.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/OMOperatingUnit.cdm.json/OMOperatingUnit</a></td><td><a href="../../../Common/GAB/Main/OMOperatingUnit.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

---
title: RetailLoyaltyCardRewardPointNonTransactionalActivityEntity in CommerceCustomers - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Non-transactional loyalty activity in CommerceCustomers(RetailLoyaltyCardRewardPointNonTransactionalActivityEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Non-transactional loyalty activity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CardNumber](#CardNumber)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[NonTransactionalActivityId](#NonTransactionalActivityId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[LoyaltyOtherActivityTypeId](#LoyaltyOtherActivityTypeId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[OMOperatingUnitID](#OMOperatingUnitID)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[EntryDate](#EntryDate)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[EntryTime](#EntryTime)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[RetailAffiliationId](#RetailAffiliationId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[Status](#Status)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[ErrorLogs](#ErrorLogs)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[Relationship_RetailLoyaltyCardRelationshipId](#Relationship_RetailLoyaltyCardRelationshipId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[Relationship_LoyaltyOtherActivityTypeIdRelationshipId](#Relationship_LoyaltyOtherActivityTypeIdRelationshipId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[Relationship_RetailAffiliationRelationshipId](#Relationship_RetailAffiliationRelationshipId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[Relationship_OMOperatingUnitIdRelationshipId](#Relationship_OMOperatingUnitIdRelationshipId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|
|[BackingTable_RetailLoyaltyCardRewardPointNonTransactionalActivityRelationshipId](#BackingTable_RetailLoyaltyCardRewardPointNonTransactionalActivityRelationshipId)||<a href="RetailLoyaltyCardRewardPointNonTransactionalActivityEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity</a>|

### <a href=#CardNumber name="CardNumber">CardNumber</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

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

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

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

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

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

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryDate name="EntryDate">EntryDate</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryTime name="EntryTime">EntryTime</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailAffiliationId name="RetailAffiliationId">RetailAffiliationId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailAffiliationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorLogs name="ErrorLogs">ErrorLogs</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

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

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LoyaltyOtherActivityTypeIdRelationshipId name="Relationship_LoyaltyOtherActivityTypeIdRelationshipId">Relationship_LoyaltyOtherActivityTypeIdRelationshipId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailAffiliationRelationshipId name="Relationship_RetailAffiliationRelationshipId">Relationship_RetailAffiliationRelationshipId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OMOperatingUnitIdRelationshipId name="Relationship_OMOperatingUnitIdRelationshipId">Relationship_OMOperatingUnitIdRelationshipId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailLoyaltyCardRewardPointNonTransactionalActivityRelationshipId name="BackingTable_RetailLoyaltyCardRewardPointNonTransactionalActivityRelationshipId">BackingTable_RetailLoyaltyCardRewardPointNonTransactionalActivityRelationshipId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointNonTransactionalActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailLoyaltyCardRewardPointNonTransactionalActivityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity.cdm.json/RetailLoyaltyCardRewardPointNonTransactionalActivity</a></td><td><a href="../../../Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyCardRewardPointNonTransactionalActivity.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

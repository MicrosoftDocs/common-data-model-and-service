---
title: RetailLoyaltyEarnSchemeLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailLoyaltyEarnSchemeLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Main/RetailLoyaltyEarnSchemeLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyEarnSchemeLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[FromActivityAmountCurrency](#FromActivityAmountCurrency)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[FromActivityAmountQty](#FromActivityAmountQty)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[FromActivityRetailGroupMemberLine](#FromActivityRetailGroupMemberLine)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[FromActivityType](#FromActivityType)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[LoyaltyScheme](#LoyaltyScheme)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[LoyaltyTier](#LoyaltyTier)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[ToRewardPoint](#ToRewardPoint)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[ToRewardPointAmountQty](#ToRewardPointAmountQty)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[ValidFrom](#ValidFrom)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[ValidTo](#ValidTo)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[LineNum](#LineNum)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[RetailAffiliationId](#RetailAffiliationId)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[RetailFromOtherActivityTypeId](#RetailFromOtherActivityTypeId)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[Relationship_FromActivityAmountCurrencyRelationshipId](#Relationship_FromActivityAmountCurrencyRelationshipId)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[Relationship_RetailGroupMemberLineRelationshipId](#Relationship_RetailGroupMemberLineRelationshipId)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[Relationship_RetailLoyaltyRewardPointRelationshipId](#Relationship_RetailLoyaltyRewardPointRelationshipId)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[Relationship_RetailLoyaltySchemeRelationshipId](#Relationship_RetailLoyaltySchemeRelationshipId)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[Relationship_RetailLoyaltyTierRelationshipId](#Relationship_RetailLoyaltyTierRelationshipId)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[Relationship_RetailAffiliationRelationshipId](#Relationship_RetailAffiliationRelationshipId)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|
|[Relationship_RetailFromOtherActivityTypeRelationshipId](#Relationship_RetailFromOtherActivityTypeRelationshipId)||<a href="RetailLoyaltyEarnSchemeLine.md" target="_blank">Main/RetailLoyaltyEarnSchemeLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyEarnSchemeLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FromActivityAmountCurrency name="FromActivityAmountCurrency">FromActivityAmountCurrency</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromActivityAmountCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromActivityAmountQty name="FromActivityAmountQty">FromActivityAmountQty</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromActivityAmountQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FromActivityRetailGroupMemberLine name="FromActivityRetailGroupMemberLine">FromActivityRetailGroupMemberLine</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromActivityRetailGroupMemberLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FromActivityType name="FromActivityType">FromActivityType</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromActivityType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoyaltyScheme name="LoyaltyScheme">LoyaltyScheme</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyScheme attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LoyaltyTier name="LoyaltyTier">LoyaltyTier</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTier attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ToRewardPoint name="ToRewardPoint">ToRewardPoint</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToRewardPoint attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ToRewardPointAmountQty name="ToRewardPointAmountQty">ToRewardPointAmountQty</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToRewardPointAmountQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RetailAffiliationId name="RetailAffiliationId">RetailAffiliationId</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailAffiliationId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailFromOtherActivityTypeId name="RetailFromOtherActivityTypeId">RetailFromOtherActivityTypeId</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailFromOtherActivityTypeId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_FromActivityAmountCurrencyRelationshipId name="Relationship_FromActivityAmountCurrencyRelationshipId">Relationship_FromActivityAmountCurrencyRelationshipId</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FromActivityAmountCurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailGroupMemberLineRelationshipId name="Relationship_RetailGroupMemberLineRelationshipId">Relationship_RetailGroupMemberLineRelationshipId</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailGroupMemberLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailGroupMemberLine.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailGroupMemberLine.cdm.json/RetailGroupMemberLine</a></td><td><a href="../Miscellaneous/RetailGroupMemberLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyRewardPointRelationshipId name="Relationship_RetailLoyaltyRewardPointRelationshipId">Relationship_RetailLoyaltyRewardPointRelationshipId</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltyRewardPointRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyRewardPoint.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailLoyaltyRewardPoint.cdm.json/RetailLoyaltyRewardPoint</a></td><td><a href="../Miscellaneous/RetailLoyaltyRewardPoint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltySchemeRelationshipId name="Relationship_RetailLoyaltySchemeRelationshipId">Relationship_RetailLoyaltySchemeRelationshipId</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltySchemeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailLoyaltyScheme.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailLoyaltyScheme.cdm.json/RetailLoyaltyScheme</a></td><td><a href="RetailLoyaltyScheme.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyTierRelationshipId name="Relationship_RetailLoyaltyTierRelationshipId">Relationship_RetailLoyaltyTierRelationshipId</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltyTierRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyTier.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailLoyaltyTier.cdm.json/RetailLoyaltyTier</a></td><td><a href="../Miscellaneous/RetailLoyaltyTier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailAffiliationRelationshipId name="Relationship_RetailAffiliationRelationshipId">Relationship_RetailAffiliationRelationshipId</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailAffiliation.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailAffiliation.cdm.json/RetailAffiliation</a></td><td><a href="../Miscellaneous/RetailAffiliation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailFromOtherActivityTypeRelationshipId name="Relationship_RetailFromOtherActivityTypeRelationshipId">Relationship_RetailFromOtherActivityTypeRelationshipId</a>

First included in: Main/RetailLoyaltyEarnSchemeLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailFromOtherActivityTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyOtherActivityType.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailLoyaltyOtherActivityType.cdm.json/RetailLoyaltyOtherActivityType</a></td><td><a href="../Miscellaneous/RetailLoyaltyOtherActivityType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

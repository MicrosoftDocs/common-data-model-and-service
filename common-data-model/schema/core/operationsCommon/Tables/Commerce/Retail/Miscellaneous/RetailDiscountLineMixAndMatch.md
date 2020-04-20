---
title: RetailDiscountLineMixAndMatch - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailDiscountLineMixAndMatch

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDiscountLineMixAndMatch.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDiscountLineMixAndMatch/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[Description](#Description)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[DiscountPercentOrValue](#DiscountPercentOrValue)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[IsDiscountCodeRequired](#IsDiscountCodeRequired)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[LineNum](#LineNum)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[Name](#Name)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[OfferId](#OfferId)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[RetailGroupMemberLine](#RetailGroupMemberLine)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[Status](#Status)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[UnitOfMeasure](#UnitOfMeasure)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[LineType](#LineType)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[Relationship_OfferIdRelationshipId](#Relationship_OfferIdRelationshipId)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[Relationship_RetailGroupMemberLineRelationshipId](#Relationship_RetailGroupMemberLineRelationshipId)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[discountType](#discountType)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[lineGroup](#lineGroup)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[numberOfItemsNeeded](#numberOfItemsNeeded)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|
|[Relationship_MixAndMatchLineGroupsRelationshipId](#Relationship_MixAndMatchLineGroupsRelationshipId)||<a href="RetailDiscountLineMixAndMatch.md" target="_blank">Miscellaneous/RetailDiscountLineMixAndMatch</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDiscountLineMixAndMatch/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

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

### <a href=#DiscountPercentOrValue name="DiscountPercentOrValue">DiscountPercentOrValue</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentOrValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsDiscountCodeRequired name="IsDiscountCodeRequired">IsDiscountCodeRequired</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDiscountCodeRequired attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

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

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OfferId name="OfferId">OfferId</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfferId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailGroupMemberLine name="RetailGroupMemberLine">RetailGroupMemberLine</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailGroupMemberLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UnitOfMeasure name="UnitOfMeasure">UnitOfMeasure</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineType name="LineType">LineType</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

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

### <a href=#Relationship_OfferIdRelationshipId name="Relationship_OfferIdRelationshipId">Relationship_OfferIdRelationshipId</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OfferIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RetailPeriodicDiscount.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/WorksheetHeader/RetailPeriodicDiscount.cdm.json/RetailPeriodicDiscount</a></td><td><a href="../WorksheetHeader/RetailPeriodicDiscount.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailGroupMemberLineRelationshipId name="Relationship_RetailGroupMemberLineRelationshipId">Relationship_RetailGroupMemberLineRelationshipId</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailGroupMemberLine.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailGroupMemberLine.cdm.json/RetailGroupMemberLine</a></td><td><a href="RetailGroupMemberLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#discountType name="discountType">discountType</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the discountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#lineGroup name="lineGroup">lineGroup</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lineGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#numberOfItemsNeeded name="numberOfItemsNeeded">numberOfItemsNeeded</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberOfItemsNeeded attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_MixAndMatchLineGroupsRelationshipId name="Relationship_MixAndMatchLineGroupsRelationshipId">Relationship_MixAndMatchLineGroupsRelationshipId</a>

First included in: Miscellaneous/RetailDiscountLineMixAndMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MixAndMatchLineGroupsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/RetailMixAndMatchLineGroupSetup.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Group/RetailMixAndMatchLineGroupSetup.cdm.json/RetailMixAndMatchLineGroupSetup</a></td><td><a href="../Group/RetailMixAndMatchLineGroupSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

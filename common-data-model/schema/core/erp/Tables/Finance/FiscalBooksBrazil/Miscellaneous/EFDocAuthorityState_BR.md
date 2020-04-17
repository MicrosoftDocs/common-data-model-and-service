---
title: EFDocAuthorityState_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# EFDocAuthorityState_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocAuthorityState_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocAuthorityState_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EFDocAuthorityState_BR.md" target="_blank">Miscellaneous/EFDocAuthorityState_BR</a>|
|[AuthorityId](#AuthorityId)||<a href="EFDocAuthorityState_BR.md" target="_blank">Miscellaneous/EFDocAuthorityState_BR</a>|
|[LogisticsAddressState](#LogisticsAddressState)||<a href="EFDocAuthorityState_BR.md" target="_blank">Miscellaneous/EFDocAuthorityState_BR</a>|
|[AddExempt](#AddExempt)||<a href="EFDocAuthorityState_BR.md" target="_blank">Miscellaneous/EFDocAuthorityState_BR</a>|
|[ValidateBenefitCodes](#ValidateBenefitCodes)||<a href="EFDocAuthorityState_BR.md" target="_blank">Miscellaneous/EFDocAuthorityState_BR</a>|
|[Relationship_EFDocAuthority_BRRelationshipId](#Relationship_EFDocAuthority_BRRelationshipId)||<a href="EFDocAuthorityState_BR.md" target="_blank">Miscellaneous/EFDocAuthorityState_BR</a>|
|[Relationship_LogisticsAddressStateRelationshipId](#Relationship_LogisticsAddressStateRelationshipId)||<a href="EFDocAuthorityState_BR.md" target="_blank">Miscellaneous/EFDocAuthorityState_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/EFDocAuthorityState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocAuthorityState_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AuthorityId name="AuthorityId">AuthorityId</a>

First included in: Miscellaneous/EFDocAuthorityState_BR (this entity)  

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

### <a href=#LogisticsAddressState name="LogisticsAddressState">LogisticsAddressState</a>

First included in: Miscellaneous/EFDocAuthorityState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsAddressState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AddExempt name="AddExempt">AddExempt</a>

First included in: Miscellaneous/EFDocAuthorityState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddExempt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidateBenefitCodes name="ValidateBenefitCodes">ValidateBenefitCodes</a>

First included in: Miscellaneous/EFDocAuthorityState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateBenefitCodes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_EFDocAuthority_BRRelationshipId name="Relationship_EFDocAuthority_BRRelationshipId">Relationship_EFDocAuthority_BRRelationshipId</a>

First included in: Miscellaneous/EFDocAuthorityState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDocAuthority_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EFDocAuthority_BR.md" target="_blank">/core/erp/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocAuthority_BR.cdm.json/EFDocAuthority_BR</a></td><td><a href="EFDocAuthority_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsAddressStateRelationshipId name="Relationship_LogisticsAddressStateRelationshipId">Relationship_LogisticsAddressStateRelationshipId</a>

First included in: Miscellaneous/EFDocAuthorityState_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressStateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md" target="_blank">/core/erp/Tables/Common/GAB/Group/LogisticsAddressState.cdm.json/LogisticsAddressState</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

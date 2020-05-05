---
title: VendVendorRequestNewVendor - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# New vendor requests 

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Vendor/Worksheet/VendVendorRequestNewVendor.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendVendorRequestNewVendor/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor requests</td></tr><tr><td>en</td><td>New vendor requests </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[RequestId](#RequestId)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[RequestStatus](#RequestStatus)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[VendorName](#VendorName)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[SponsoredBy](#SponsoredBy)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[ReasonRef](#ReasonRef)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[VendorPortalAccessAllowed](#VendorPortalAccessAllowed)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[DateSubmitted](#DateSubmitted)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[DateResolved](#DateResolved)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[RequestEntityType](#RequestEntityType)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[DataAreaId](#DataAreaId)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[Relationship_ReasonTableRefRelationshipId](#Relationship_ReasonTableRefRelationshipId)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[ProspectiveVendorRegistration](#ProspectiveVendorRegistration)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|
|[Relationship_VendProspectiveVendorRegistrationRelationshipId](#Relationship_VendProspectiveVendorRegistrationRelationshipId)||<a href="VendVendorRequestNewVendor.md" target="_blank">Worksheet/VendVendorRequestNewVendor</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendVendorRequestNewVendor/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

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

### <a href=#RequestId name="RequestId">RequestId</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestId attribute are listed below.</summary>

**is.readOnly**  
</details>

### <a href=#RequestStatus name="RequestStatus">RequestStatus</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#VendorName name="VendorName">VendorName</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorName attribute are listed below.</summary>

**is.readOnly**  
</details>

### <a href=#SponsoredBy name="SponsoredBy">SponsoredBy</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SponsoredBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requester name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonRef name="ReasonRef">ReasonRef</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonRef attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#VendorPortalAccessAllowed name="VendorPortalAccessAllowed">VendorPortalAccessAllowed</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPortalAccessAllowed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DateSubmitted name="DateSubmitted">DateSubmitted</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateSubmitted attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#DateResolved name="DateResolved">DateResolved</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateResolved attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#RequestEntityType name="RequestEntityType">RequestEntityType</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestEntityType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

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

### <a href=#Relationship_ReasonTableRefRelationshipId name="Relationship_ReasonTableRefRelationshipId">Relationship_ReasonTableRefRelationshipId</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReasonTableRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Transaction/ReasonTableRef.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Transaction/ReasonTableRef.cdm.json/ReasonTableRef</a></td><td><a href="../../../Finance/Ledger/Transaction/ReasonTableRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

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

### <a href=#ProspectiveVendorRegistration name="ProspectiveVendorRegistration">ProspectiveVendorRegistration</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProspectiveVendorRegistration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_VendProspectiveVendorRegistrationRelationshipId name="Relationship_VendProspectiveVendorRegistrationRelationshipId">Relationship_VendProspectiveVendorRegistrationRelationshipId</a>

First included in: Worksheet/VendVendorRequestNewVendor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendProspectiveVendorRegistrationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProcurementAndSourcing/WorksheetHeader/VendProspectiveVendorRegistration.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/VendProspectiveVendorRegistration.cdm.json/VendProspectiveVendorRegistration</a></td><td><a href="../../ProcurementAndSourcing/WorksheetHeader/VendProspectiveVendorRegistration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

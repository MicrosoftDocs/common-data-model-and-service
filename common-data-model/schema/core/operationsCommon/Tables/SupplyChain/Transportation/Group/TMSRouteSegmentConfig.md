---
title: TMSRouteSegmentConfig in Group - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Route segment configuration in Group(TMSRouteSegmentConfig)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSRouteSegmentConfig.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TMSRouteSegmentConfig/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Route segment configuration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[RouteStartHubCode](#RouteStartHubCode)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[CarrierCode](#CarrierCode)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[CarrierGroupCode](#CarrierGroupCode)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[CarrierServiceCode](#CarrierServiceCode)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[FreightTermCode](#FreightTermCode)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[InvoiceAccountType](#InvoiceAccountType)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[ModeCode](#ModeCode)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Name](#Name)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[ResponsibleForPayment](#ResponsibleForPayment)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[RouteConfigCode](#RouteConfigCode)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[RouteEndHubCode](#RouteEndHubCode)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Sequence](#Sequence)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[VendorCode](#VendorCode)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[VendorInvoiceCode](#VendorInvoiceCode)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[DataAreaId](#DataAreaId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_DlvTermRelationshipId](#Relationship_DlvTermRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_TMSCarrierRelationshipId](#Relationship_TMSCarrierRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_TMSCarrierGroupRelationshipId](#Relationship_TMSCarrierGroupRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_TMSCarrierServiceRelationshipId](#Relationship_TMSCarrierServiceRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_TMSHubMasterEndRelationshipId](#Relationship_TMSHubMasterEndRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_TMSHubMasterStartRelationshipId](#Relationship_TMSHubMasterStartRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_TMSModeRelationshipId](#Relationship_TMSModeRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_TMSRouteConfigRelationshipId](#Relationship_TMSRouteConfigRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_TMSRouteEndHubConfigRelationshipId](#Relationship_TMSRouteEndHubConfigRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_TMSRouteStartHubConfigRelationshipId](#Relationship_TMSRouteStartHubConfigRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_VendTableInvoiceRelationshipId](#Relationship_VendTableInvoiceRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TMSRouteSegmentConfig.md" target="_blank">Group/TMSRouteSegmentConfig</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TMSRouteSegmentConfig/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RouteStartHubCode name="RouteStartHubCode">RouteStartHubCode</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteStartHubCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierCode name="CarrierCode">CarrierCode</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierGroupCode name="CarrierGroupCode">CarrierGroupCode</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierServiceCode name="CarrierServiceCode">CarrierServiceCode</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierServiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightTermCode name="FreightTermCode">FreightTermCode</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightTermCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccountType name="InvoiceAccountType">InvoiceAccountType</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ModeCode name="ModeCode">ModeCode</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

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

### <a href=#ResponsibleForPayment name="ResponsibleForPayment">ResponsibleForPayment</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsibleForPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RouteConfigCode name="RouteConfigCode">RouteConfigCode</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteConfigCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteEndHubCode name="RouteEndHubCode">RouteEndHubCode</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteEndHubCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Sequence name="Sequence">Sequence</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendorCode name="VendorCode">VendorCode</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceCode name="VendorInvoiceCode">VendorInvoiceCode</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

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

### <a href=#Relationship_DlvTermRelationshipId name="Relationship_DlvTermRelationshipId">Relationship_DlvTermRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DlvTermRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Group/DlvTerm.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/DlvTerm.cdm.json/DlvTerm</a></td><td><a href="../../SalesAndMarketing/Group/DlvTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSCarrierRelationshipId name="Relationship_TMSCarrierRelationshipId">Relationship_TMSCarrierRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSCarrierRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TMSCarrier.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSCarrier.cdm.json/TMSCarrier</a></td><td><a href="../Main/TMSCarrier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSCarrierGroupRelationshipId name="Relationship_TMSCarrierGroupRelationshipId">Relationship_TMSCarrierGroupRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSCarrierGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TMSCarrierGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSCarrierGroup.cdm.json/TMSCarrierGroup</a></td><td><a href="../Main/TMSCarrierGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSCarrierServiceRelationshipId name="Relationship_TMSCarrierServiceRelationshipId">Relationship_TMSCarrierServiceRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSCarrierServiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TMSCarrierService.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSCarrierService.cdm.json/TMSCarrierService</a></td><td><a href="TMSCarrierService.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSHubMasterEndRelationshipId name="Relationship_TMSHubMasterEndRelationshipId">Relationship_TMSHubMasterEndRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSHubMasterEndRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TMSHubMaster.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSHubMaster.cdm.json/TMSHubMaster</a></td><td><a href="TMSHubMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSHubMasterStartRelationshipId name="Relationship_TMSHubMasterStartRelationshipId">Relationship_TMSHubMasterStartRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSHubMasterStartRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TMSHubMaster.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSHubMaster.cdm.json/TMSHubMaster</a></td><td><a href="TMSHubMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSModeRelationshipId name="Relationship_TMSModeRelationshipId">Relationship_TMSModeRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSModeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TMSMode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSMode.cdm.json/TMSMode</a></td><td><a href="TMSMode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSRouteConfigRelationshipId name="Relationship_TMSRouteConfigRelationshipId">Relationship_TMSRouteConfigRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSRouteConfigRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TMSRouteConfig.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSRouteConfig.cdm.json/TMSRouteConfig</a></td><td><a href="TMSRouteConfig.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSRouteEndHubConfigRelationshipId name="Relationship_TMSRouteEndHubConfigRelationshipId">Relationship_TMSRouteEndHubConfigRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSRouteEndHubConfigRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TMSRouteHubConfig.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSRouteHubConfig.cdm.json/TMSRouteHubConfig</a></td><td><a href="TMSRouteHubConfig.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSRouteStartHubConfigRelationshipId name="Relationship_TMSRouteStartHubConfigRelationshipId">Relationship_TMSRouteStartHubConfigRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSRouteStartHubConfigRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TMSRouteHubConfig.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSRouteHubConfig.cdm.json/TMSRouteHubConfig</a></td><td><a href="TMSRouteHubConfig.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableInvoiceRelationshipId name="Relationship_VendTableInvoiceRelationshipId">Relationship_VendTableInvoiceRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableInvoiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/TMSRouteSegmentConfig (this entity)  

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

---
title: InventTransferParmTableFiscalInfo_BR in WorksheetHeader - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Transfer order - update table in WorksheetHeader

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventTransferParmTableFiscalInfo_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTransferParmTableFiscalInfo_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transfer order - update table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[InventTransferParmTable](#InventTransferParmTable)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[ThirdPartyEFDocAccessKey_BR](#ThirdPartyEFDocAccessKey_BR)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[ThirdPartyFiscalDocumentModel](#ThirdPartyFiscalDocumentModel)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[ThirdPartyFiscalDocumentNumber](#ThirdPartyFiscalDocumentNumber)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[ThirdPartyFiscalDocumentSeries](#ThirdPartyFiscalDocumentSeries)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[ThirdPartyFiscalDocumentSpecie](#ThirdPartyFiscalDocumentSpecie)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[VehicleLicensePlate_BR](#VehicleLicensePlate_BR)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[VehicleLicensePlateState_BR](#VehicleLicensePlateState_BR)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[VolumeQty_BR](#VolumeQty_BR)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[VolumeType_BR](#VolumeType_BR)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[ThirdPartyFiscalDocumentDate](#ThirdPartyFiscalDocumentDate)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[Relationship_FiscalDocModel_BRRelationshipId](#Relationship_FiscalDocModel_BRRelationshipId)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[Relationship_InventTransferParmTableRelationshipId](#Relationship_InventTransferParmTableRelationshipId)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventTransferParmTableFiscalInfo_BR.md" target="_blank">WorksheetHeader/InventTransferParmTableFiscalInfo_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTransferParmTableFiscalInfo_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InventTransferParmTable name="InventTransferParmTable">InventTransferParmTable</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransferParmTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ThirdPartyEFDocAccessKey_BR name="ThirdPartyEFDocAccessKey_BR">ThirdPartyEFDocAccessKey_BR</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyEFDocAccessKey_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyFiscalDocumentModel name="ThirdPartyFiscalDocumentModel">ThirdPartyFiscalDocumentModel</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyFiscalDocumentModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyFiscalDocumentNumber name="ThirdPartyFiscalDocumentNumber">ThirdPartyFiscalDocumentNumber</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyFiscalDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyFiscalDocumentSeries name="ThirdPartyFiscalDocumentSeries">ThirdPartyFiscalDocumentSeries</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyFiscalDocumentSeries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyFiscalDocumentSpecie name="ThirdPartyFiscalDocumentSpecie">ThirdPartyFiscalDocumentSpecie</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyFiscalDocumentSpecie attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VehicleLicensePlate_BR name="VehicleLicensePlate_BR">VehicleLicensePlate_BR</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleLicensePlate_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VehicleLicensePlateState_BR name="VehicleLicensePlateState_BR">VehicleLicensePlateState_BR</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleLicensePlateState_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VolumeQty_BR name="VolumeQty_BR">VolumeQty_BR</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VolumeQty_BR attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VolumeType_BR name="VolumeType_BR">VolumeType_BR</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VolumeType_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdPartyFiscalDocumentDate name="ThirdPartyFiscalDocumentDate">ThirdPartyFiscalDocumentDate</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdPartyFiscalDocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

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

### <a href=#Relationship_FiscalDocModel_BRRelationshipId name="Relationship_FiscalDocModel_BRRelationshipId">Relationship_FiscalDocModel_BRRelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocModel_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FiscalBooksBrazil/Group/FiscalDocModel_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Group/FiscalDocModel_BR.cdm.json/FiscalDocModel_BR</a></td><td><a href="../../../Finance/FiscalBooksBrazil/Group/FiscalDocModel_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransferParmTableRelationshipId name="Relationship_InventTransferParmTableRelationshipId">Relationship_InventTransferParmTableRelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransferParmTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventTransferParmTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventTransferParmTable.cdm.json/InventTransferParmTable</a></td><td><a href="InventTransferParmTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/InventTransferParmTableFiscalInfo_BR (this entity)  

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

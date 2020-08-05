---
title: ProdJournalRouteProj in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Project routing journal transactions in WorksheetLine(ProdJournalRouteProj)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/WorksheetLine/ProdJournalRouteProj.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProdJournalRouteProj/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project routing journal transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[ActivityNumber](#ActivityNumber)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[JournalId](#JournalId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[LineNum](#LineNum)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[PeriodDate](#PeriodDate)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[ProjId](#ProjId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[ProjLinePropertyId](#ProjLinePropertyId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[ProjSalesCurrencyId](#ProjSalesCurrencyId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[ProjSalesPrice](#ProjSalesPrice)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[ProjTaxGroupId](#ProjTaxGroupId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[ProjTaxItemGroupId](#ProjTaxItemGroupId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[ProjTransDate](#ProjTransDate)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[ProjTransId](#ProjTransId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[TransType](#TransType)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[Txt](#Txt)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[DataAreaId](#DataAreaId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[Relationship_ProjectSalesCurrencyRelationshipId](#Relationship_ProjectSalesCurrencyRelationshipId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[Relationship_ProjectTaxGroupHeadingRelationshipId](#Relationship_ProjectTaxGroupHeadingRelationshipId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[Relationship_ProjectTaxItemGroupHeadingRelationshipId](#Relationship_ProjectTaxItemGroupHeadingRelationshipId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[Relationship_ProjLinePropertyRelationshipId](#Relationship_ProjLinePropertyRelationshipId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[Relationship_ProjTableRelationshipId](#Relationship_ProjTableRelationshipId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[Relationship_RouteProdJournalTableRelationshipId](#Relationship_RouteProdJournalTableRelationshipId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ProdJournalRouteProj.md" target="_blank">WorksheetLine/ProdJournalRouteProj</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProdJournalRouteProj/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PeriodDate name="PeriodDate">PeriodDate</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ProjId name="ProjId">ProjId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjLinePropertyId name="ProjLinePropertyId">ProjLinePropertyId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjLinePropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjSalesCurrencyId name="ProjSalesCurrencyId">ProjSalesCurrencyId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjSalesCurrencyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjSalesPrice name="ProjSalesPrice">ProjSalesPrice</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjSalesPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ProjTaxGroupId name="ProjTaxGroupId">ProjTaxGroupId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTaxGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjTaxItemGroupId name="ProjTaxItemGroupId">ProjTaxItemGroupId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTaxItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjTransDate name="ProjTransDate">ProjTransDate</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ProjTransId name="ProjTransId">ProjTransId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransType name="TransType">TransType</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Txt name="Txt">Txt</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Txt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

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

### <a href=#Relationship_ProjectSalesCurrencyRelationshipId name="Relationship_ProjectSalesCurrencyRelationshipId">Relationship_ProjectSalesCurrencyRelationshipId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectSalesCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProjectTaxGroupHeadingRelationshipId name="Relationship_ProjectTaxGroupHeadingRelationshipId">Relationship_ProjectTaxGroupHeadingRelationshipId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectTaxGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjectTaxItemGroupHeadingRelationshipId name="Relationship_ProjectTaxItemGroupHeadingRelationshipId">Relationship_ProjectTaxItemGroupHeadingRelationshipId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectTaxItemGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxItemGroupHeading.cdm.json/TaxItemGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjLinePropertyRelationshipId name="Relationship_ProjLinePropertyRelationshipId">Relationship_ProjLinePropertyRelationshipId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjLinePropertyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProjLineProperty.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjLineProperty.cdm.json/ProjLineProperty</a></td><td><a href="../Group/ProjLineProperty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjTableRelationshipId name="Relationship_ProjTableRelationshipId">Relationship_ProjTableRelationshipId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/ProjTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.cdm.json/ProjTable</a></td><td><a href="../Main/ProjTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RouteProdJournalTableRelationshipId name="Relationship_RouteProdJournalTableRelationshipId">Relationship_RouteProdJournalTableRelationshipId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RouteProdJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductionControl/WorksheetHeader/ProdJournalTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetHeader/ProdJournalTable.cdm.json/ProdJournalTable</a></td><td><a href="../../../SupplyChain/ProductionControl/WorksheetHeader/ProdJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/ProdJournalRouteProj (this entity)  

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

---
title: EFDocReceivedXmlApprovedDivergences_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# EFDocReceivedXmlApprovedDivergences_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocReceivedXmlApprovedDivergences_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[ApprovalReason](#ApprovalReason)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[EFDocumentReceivedXML_BR](#EFDocumentReceivedXML_BR)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[ICMSAmount](#ICMSAmount)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[ICMSBaseAmount](#ICMSBaseAmount)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[ICMSSTAmount](#ICMSSTAmount)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[ICMSSTBaseAmount](#ICMSSTBaseAmount)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[IPIAmount](#IPIAmount)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[TotalAmount](#TotalAmount)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[TotalMarkupFreightAmount](#TotalMarkupFreightAmount)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[TotalMarkupInsuranceAmount](#TotalMarkupInsuranceAmount)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[TotalMarkupOtherAmount](#TotalMarkupOtherAmount)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[TotalProductAmount](#TotalProductAmount)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[Relationship_EFDocumentReceivedXML_BRRelationshipId](#Relationship_EFDocumentReceivedXML_BRRelationshipId)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EFDocReceivedXmlApprovedDivergences_BR.md" target="_blank">Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocReceivedXmlApprovedDivergences_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ApprovalReason name="ApprovalReason">ApprovalReason</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovalReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFDocumentReceivedXML_BR name="EFDocumentReceivedXML_BR">EFDocumentReceivedXML_BR</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocumentReceivedXML_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSAmount name="ICMSAmount">ICMSAmount</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSBaseAmount name="ICMSBaseAmount">ICMSBaseAmount</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSSTAmount name="ICMSSTAmount">ICMSSTAmount</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSSTAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSSTBaseAmount name="ICMSSTBaseAmount">ICMSSTBaseAmount</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSSTBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IPIAmount name="IPIAmount">IPIAmount</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IPIAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalAmount name="TotalAmount">TotalAmount</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalMarkupFreightAmount name="TotalMarkupFreightAmount">TotalMarkupFreightAmount</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalMarkupFreightAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalMarkupInsuranceAmount name="TotalMarkupInsuranceAmount">TotalMarkupInsuranceAmount</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalMarkupInsuranceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalMarkupOtherAmount name="TotalMarkupOtherAmount">TotalMarkupOtherAmount</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalMarkupOtherAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalProductAmount name="TotalProductAmount">TotalProductAmount</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalProductAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

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

### <a href=#Relationship_EFDocumentReceivedXML_BRRelationshipId name="Relationship_EFDocumentReceivedXML_BRRelationshipId">Relationship_EFDocumentReceivedXML_BRRelationshipId</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDocumentReceivedXML_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/EFDocumentReceivedXML_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/EFDocumentReceivedXML_BR.cdm.json/EFDocumentReceivedXML_BR</a></td><td><a href="../Transaction/EFDocumentReceivedXML_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/EFDocReceivedXmlApprovedDivergences_BR (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

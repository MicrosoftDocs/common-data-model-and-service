---
title: WMSBillOfLadingCarrier - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# WMSBillOfLadingCarrier

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/Inventory/TransactionLine/WMSBillOfLadingCarrier.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WMSBillOfLadingCarrier/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[additionalInfo](#additionalInfo)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[billOfLadingId](#billOfLadingId)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[handlingPackageType](#handlingPackageType)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[handlingQty](#handlingQty)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[hazardousMaterial](#hazardousMaterial)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[packageAppearance](#packageAppearance)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[packagePackageType](#packagePackageType)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[packageQty](#packageQty)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[pdsCWHandlingQty](#pdsCWHandlingQty)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[pdsCWPackageQty](#pdsCWPackageQty)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[weight](#weight)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[DataAreaId](#DataAreaId)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[Relationship_SalesPackageAppearanceRelationshipId](#Relationship_SalesPackageAppearanceRelationshipId)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[Relationship_WMSBillOfLadingRelationshipId](#Relationship_WMSBillOfLadingRelationshipId)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WMSBillOfLadingCarrier.md" target="_blank">TransactionLine/WMSBillOfLadingCarrier</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WMSBillOfLadingCarrier/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#additionalInfo name="additionalInfo">additionalInfo</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the additionalInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#billOfLadingId name="billOfLadingId">billOfLadingId</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the billOfLadingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#handlingPackageType name="handlingPackageType">handlingPackageType</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the handlingPackageType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#handlingQty name="handlingQty">handlingQty</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the handlingQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#hazardousMaterial name="hazardousMaterial">hazardousMaterial</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the hazardousMaterial attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#packageAppearance name="packageAppearance">packageAppearance</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the packageAppearance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#packagePackageType name="packagePackageType">packagePackageType</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the packagePackageType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#packageQty name="packageQty">packageQty</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the packageQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#pdsCWHandlingQty name="pdsCWHandlingQty">pdsCWHandlingQty</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pdsCWHandlingQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#pdsCWPackageQty name="pdsCWPackageQty">pdsCWPackageQty</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pdsCWPackageQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#weight name="weight">weight</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the weight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

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

### <a href=#Relationship_SalesPackageAppearanceRelationshipId name="Relationship_SalesPackageAppearanceRelationshipId">Relationship_SalesPackageAppearanceRelationshipId</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesPackageAppearanceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Group/SalesPackageAppearance.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Group/SalesPackageAppearance.cdm.json/SalesPackageAppearance</a></td><td><a href="../../SalesAndMarketing/Group/SalesPackageAppearance.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WMSBillOfLadingRelationshipId name="Relationship_WMSBillOfLadingRelationshipId">Relationship_WMSBillOfLadingRelationshipId</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSBillOfLadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/WMSBillOfLading.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/TransactionHeader/WMSBillOfLading.cdm.json/WMSBillOfLading</a></td><td><a href="../TransactionHeader/WMSBillOfLading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionLine/WMSBillOfLadingCarrier (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

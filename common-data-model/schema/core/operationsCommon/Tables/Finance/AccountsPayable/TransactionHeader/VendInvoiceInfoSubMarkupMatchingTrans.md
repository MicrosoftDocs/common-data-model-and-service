---
title: VendInvoiceInfoSubMarkupMatchingTrans - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Vendor invoice expected purchase order charges

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendInvoiceInfoSubMarkupMatchingTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expected charges</td></tr><tr><td>en</td><td>Vendor invoice expected purchase order charges</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[CurrencyConverted](#CurrencyConverted)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[ExpectedMarkup](#ExpectedMarkup)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[ExpectedMarkupCode](#ExpectedMarkupCode)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[LineNum](#LineNum)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[MarkupCode](#MarkupCode)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[ModuleType](#ModuleType)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[TransRecId](#TransRecId)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[TransTableId](#TransTableId)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[Relationship_MarkupTransRelationshipId](#Relationship_MarkupTransRelationshipId)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[VendInvoiceInfoSubTableOrigPurchId](#VendInvoiceInfoSubTableOrigPurchId)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[VendInvoiceInfoSubTableParmId](#VendInvoiceInfoSubTableParmId)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[VendInvoiceInfoSubTableTableRefId](#VendInvoiceInfoSubTableTableRefId)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[Relationship_FK_VendInvoiceInfoSubTableRelationshipId](#Relationship_FK_VendInvoiceInfoSubTableRelationshipId)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|
|[Relationship_PurchTable_3580RelationshipId](#Relationship_PurchTable_3580RelationshipId)||<a href="VendInvoiceInfoSubMarkupMatchingTrans.md" target="_blank">TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendInvoiceInfoSubMarkupMatchingTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrencyConverted name="CurrencyConverted">CurrencyConverted</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyConverted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ExpectedMarkup name="ExpectedMarkup">ExpectedMarkup</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExpectedMarkupCode name="ExpectedMarkupCode">ExpectedMarkupCode</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedMarkupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

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

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

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

### <a href=#MarkupCode name="MarkupCode">MarkupCode</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModuleType name="ModuleType">ModuleType</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModuleType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransRecId name="TransRecId">TransRecId</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransTableId name="TransTableId">TransTableId</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

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

### <a href=#Relationship_MarkupTransRelationshipId name="Relationship_MarkupTransRelationshipId">Relationship_MarkupTransRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MarkupTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/Transaction/MarkupTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/MarkupTrans.cdm.json/MarkupTrans</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/Transaction/MarkupTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

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

### <a href=#VendInvoiceInfoSubTableOrigPurchId name="VendInvoiceInfoSubTableOrigPurchId">VendInvoiceInfoSubTableOrigPurchId</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceInfoSubTableOrigPurchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendInvoiceInfoSubTableParmId name="VendInvoiceInfoSubTableParmId">VendInvoiceInfoSubTableParmId</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceInfoSubTableParmId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendInvoiceInfoSubTableTableRefId name="VendInvoiceInfoSubTableTableRefId">VendInvoiceInfoSubTableTableRefId</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceInfoSubTableTableRefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FK_VendInvoiceInfoSubTableRelationshipId name="Relationship_FK_VendInvoiceInfoSubTableRelationshipId">Relationship_FK_VendInvoiceInfoSubTableRelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FK_VendInvoiceInfoSubTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionLine/VendInvoiceInfoSubTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/TransactionLine/VendInvoiceInfoSubTable.cdm.json/VendInvoiceInfoSubTable</a></td><td><a href="../TransactionLine/VendInvoiceInfoSubTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchTable_3580RelationshipId name="Relationship_PurchTable_3580RelationshipId">Relationship_PurchTable_3580RelationshipId</a>

First included in: TransactionHeader/VendInvoiceInfoSubMarkupMatchingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchTable_3580RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.cdm.json/PurchTable</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

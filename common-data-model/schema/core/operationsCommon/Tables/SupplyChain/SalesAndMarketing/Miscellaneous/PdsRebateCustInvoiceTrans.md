---
title: PdsRebateCustInvoiceTrans in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Customer invoice rebate lines in Miscellaneous(PdsRebateCustInvoiceTrans)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Miscellaneous/PdsRebateCustInvoiceTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PdsRebateCustInvoiceTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer invoice rebate lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[CustInvoiceTransRecId](#CustInvoiceTransRecId)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[SalesLineCreatedDate](#SalesLineCreatedDate)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[SalesLinePdsExcludeFromRebate](#SalesLinePdsExcludeFromRebate)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[SalesLinePdsItemRebateGroupId](#SalesLinePdsItemRebateGroupId)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[SalesLineReceiptDateRequested](#SalesLineReceiptDateRequested)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[SalesLineShippingDateRequested](#SalesLineShippingDateRequested)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[SalesTablePdsCustRebateGroupId](#SalesTablePdsCustRebateGroupId)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[SalesTablePdsRebateProgramTMAGroup](#SalesTablePdsRebateProgramTMAGroup)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[Relationship_CustInvoiceTransRelationshipId](#Relationship_CustInvoiceTransRelationshipId)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[Relationship_PdsCustRebateGroupRelationshipId](#Relationship_PdsCustRebateGroupRelationshipId)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[Relationship_PdsItemRebateGroupRelationshipId](#Relationship_PdsItemRebateGroupRelationshipId)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[Relationship_PdsRebateProgramTMATableRelationshipId](#Relationship_PdsRebateProgramTMATableRelationshipId)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PdsRebateCustInvoiceTrans.md" target="_blank">Miscellaneous/PdsRebateCustInvoiceTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PdsRebateCustInvoiceTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustInvoiceTransRecId name="CustInvoiceTransRecId">CustInvoiceTransRecId</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceTransRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SalesLineCreatedDate name="SalesLineCreatedDate">SalesLineCreatedDate</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineCreatedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SalesLinePdsExcludeFromRebate name="SalesLinePdsExcludeFromRebate">SalesLinePdsExcludeFromRebate</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLinePdsExcludeFromRebate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesLinePdsItemRebateGroupId name="SalesLinePdsItemRebateGroupId">SalesLinePdsItemRebateGroupId</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLinePdsItemRebateGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLineReceiptDateRequested name="SalesLineReceiptDateRequested">SalesLineReceiptDateRequested</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineReceiptDateRequested attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SalesLineShippingDateRequested name="SalesLineShippingDateRequested">SalesLineShippingDateRequested</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineShippingDateRequested attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SalesTablePdsCustRebateGroupId name="SalesTablePdsCustRebateGroupId">SalesTablePdsCustRebateGroupId</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTablePdsCustRebateGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTablePdsRebateProgramTMAGroup name="SalesTablePdsRebateProgramTMAGroup">SalesTablePdsRebateProgramTMAGroup</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTablePdsRebateProgramTMAGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

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

### <a href=#Relationship_CustInvoiceTransRelationshipId name="Relationship_CustInvoiceTransRelationshipId">Relationship_CustInvoiceTransRelationshipId</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Transaction/CustInvoiceTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustInvoiceTrans.cdm.json/CustInvoiceTrans</a></td><td><a href="../../../Finance/AccountsReceivable/Transaction/CustInvoiceTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PdsCustRebateGroupRelationshipId name="Relationship_PdsCustRebateGroupRelationshipId">Relationship_PdsCustRebateGroupRelationshipId</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsCustRebateGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/PdsCustRebateGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/PdsCustRebateGroup.cdm.json/PdsCustRebateGroup</a></td><td><a href="../Group/PdsCustRebateGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PdsItemRebateGroupRelationshipId name="Relationship_PdsItemRebateGroupRelationshipId">Relationship_PdsItemRebateGroupRelationshipId</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsItemRebateGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/PdsItemRebateGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/PdsItemRebateGroup.cdm.json/PdsItemRebateGroup</a></td><td><a href="../Group/PdsItemRebateGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PdsRebateProgramTMATableRelationshipId name="Relationship_PdsRebateProgramTMATableRelationshipId">Relationship_PdsRebateProgramTMATableRelationshipId</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsRebateProgramTMATableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/PdsRebateProgramTMATable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/PdsRebateProgramTMATable.cdm.json/PdsRebateProgramTMATable</a></td><td><a href="../Group/PdsRebateProgramTMATable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/PdsRebateCustInvoiceTrans (this entity)  

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

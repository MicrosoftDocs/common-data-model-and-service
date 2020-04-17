---
title: CustEinvoiceIntegrationPaymModeChg - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# CustEinvoiceIntegrationPaymModeChg

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/AccountsReceivable/Main/CustEinvoiceIntegrationPaymModeChg.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustEinvoiceIntegrationPaymModeChg/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[CustEinvoiceIntegrationTypeTable](#CustEinvoiceIntegrationTypeTable)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[FromPaymMode](#FromPaymMode)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[FromPaymSpec](#FromPaymSpec)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[Status](#Status)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[ToPaymMode](#ToPaymMode)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[ToPaymSpec](#ToPaymSpec)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[Warning](#Warning)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[DataAreaId](#DataAreaId)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[Relationship_CustEinvoiceIntegrationTypeTableRelationshipId](#Relationship_CustEinvoiceIntegrationTypeTableRelationshipId)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[Relationship_CustPaymModeTable_FromPaymModeRelationshipId](#Relationship_CustPaymModeTable_FromPaymModeRelationshipId)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[Relationship_CustPaymModeTable_ToPaymModeRelationshipId](#Relationship_CustPaymModeTable_ToPaymModeRelationshipId)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[Relationship_FromPaymModeSpecRelationshipId](#Relationship_FromPaymModeSpecRelationshipId)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[Relationship_ToPaymModeSpecRelationshipId](#Relationship_ToPaymModeSpecRelationshipId)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustEinvoiceIntegrationPaymModeChg.md" target="_blank">Main/CustEinvoiceIntegrationPaymModeChg</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustEinvoiceIntegrationPaymModeChg/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustEinvoiceIntegrationTypeTable name="CustEinvoiceIntegrationTypeTable">CustEinvoiceIntegrationTypeTable</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustEinvoiceIntegrationTypeTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FromPaymMode name="FromPaymMode">FromPaymMode</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromPaymMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromPaymSpec name="FromPaymSpec">FromPaymSpec</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromPaymSpec attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ToPaymMode name="ToPaymMode">ToPaymMode</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToPaymMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToPaymSpec name="ToPaymSpec">ToPaymSpec</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToPaymSpec attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Warning name="Warning">Warning</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Warning attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

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

### <a href=#Relationship_CustEinvoiceIntegrationTypeTableRelationshipId name="Relationship_CustEinvoiceIntegrationTypeTableRelationshipId">Relationship_CustEinvoiceIntegrationTypeTableRelationshipId</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustEinvoiceIntegrationTypeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CustEinvoiceIntegrationTypeTable.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Group/CustEinvoiceIntegrationTypeTable.cdm.json/CustEinvoiceIntegrationTypeTable</a></td><td><a href="../Group/CustEinvoiceIntegrationTypeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustPaymModeTable_FromPaymModeRelationshipId name="Relationship_CustPaymModeTable_FromPaymModeRelationshipId">Relationship_CustPaymModeTable_FromPaymModeRelationshipId</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustPaymModeTable_FromPaymModeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/CustPaymModeTable.md" target="_blank">/core/erp/Tables/Finance/Bank/Group/CustPaymModeTable.cdm.json/CustPaymModeTable</a></td><td><a href="../../Bank/Group/CustPaymModeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustPaymModeTable_ToPaymModeRelationshipId name="Relationship_CustPaymModeTable_ToPaymModeRelationshipId">Relationship_CustPaymModeTable_ToPaymModeRelationshipId</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustPaymModeTable_ToPaymModeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/CustPaymModeTable.md" target="_blank">/core/erp/Tables/Finance/Bank/Group/CustPaymModeTable.cdm.json/CustPaymModeTable</a></td><td><a href="../../Bank/Group/CustPaymModeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FromPaymModeSpecRelationshipId name="Relationship_FromPaymModeSpecRelationshipId">Relationship_FromPaymModeSpecRelationshipId</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FromPaymModeSpecRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/CustPaymModeSpec.md" target="_blank">/core/erp/Tables/Finance/Bank/Group/CustPaymModeSpec.cdm.json/CustPaymModeSpec</a></td><td><a href="../../Bank/Group/CustPaymModeSpec.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ToPaymModeSpecRelationshipId name="Relationship_ToPaymModeSpecRelationshipId">Relationship_ToPaymModeSpecRelationshipId</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ToPaymModeSpecRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/CustPaymModeSpec.md" target="_blank">/core/erp/Tables/Finance/Bank/Group/CustPaymModeSpec.cdm.json/CustPaymModeSpec</a></td><td><a href="../../Bank/Group/CustPaymModeSpec.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/CustEinvoiceIntegrationPaymModeChg (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

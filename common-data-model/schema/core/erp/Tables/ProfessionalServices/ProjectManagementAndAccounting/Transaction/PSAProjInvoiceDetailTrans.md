---
title: PSAProjInvoiceDetailTrans - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# PSAProjInvoiceDetailTrans

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/PSAProjInvoiceDetailTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PSAProjInvoiceDetailTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[LineNum](#LineNum)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[ProposalId](#ProposalId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[RefLineRecId](#RefLineRecId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[RefRecId](#RefRecId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[RefTableId](#RefTableId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[TransId](#TransId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[Relationship_ProjProposalJourRelationshipId](#Relationship_ProjProposalJourRelationshipId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[Relationship_PSAProjInvoiceDetailRelationshipId](#Relationship_PSAProjInvoiceDetailRelationshipId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[Relationship_PSAProjInvoiceDetailLineRelationshipId](#Relationship_PSAProjInvoiceDetailLineRelationshipId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[Relationship_PSAProjInvoiceDetailLineRefRelationshipId](#Relationship_PSAProjInvoiceDetailLineRefRelationshipId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PSAProjInvoiceDetailTrans.md" target="_blank">Transaction/PSAProjInvoiceDetailTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PSAProjInvoiceDetailTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

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

### <a href=#ProposalId name="ProposalId">ProposalId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefLineRecId name="RefLineRecId">RefLineRecId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefLineRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransId name="TransId">TransId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

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

### <a href=#Relationship_ProjProposalJourRelationshipId name="Relationship_ProjProposalJourRelationshipId">Relationship_ProjProposalJourRelationshipId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjProposalJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProjProposalJour.md" target="_blank">/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjProposalJour.cdm.json/ProjProposalJour</a></td><td><a href="ProjProposalJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PSAProjInvoiceDetailRelationshipId name="Relationship_PSAProjInvoiceDetailRelationshipId">Relationship_PSAProjInvoiceDetailRelationshipId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PSAProjInvoiceDetailRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PSAProjInvoiceDetailLine.md" target="_blank">/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/PSAProjInvoiceDetailLine.cdm.json/PSAProjInvoiceDetailLine</a></td><td><a href="PSAProjInvoiceDetailLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PSAProjInvoiceDetailLineRelationshipId name="Relationship_PSAProjInvoiceDetailLineRelationshipId">Relationship_PSAProjInvoiceDetailLineRelationshipId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PSAProjInvoiceDetailLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PSAProjInvoiceDetailLine.md" target="_blank">/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/PSAProjInvoiceDetailLine.cdm.json/PSAProjInvoiceDetailLine</a></td><td><a href="PSAProjInvoiceDetailLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PSAProjInvoiceDetailLineRefRelationshipId name="Relationship_PSAProjInvoiceDetailLineRefRelationshipId">Relationship_PSAProjInvoiceDetailLineRefRelationshipId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PSAProjInvoiceDetailLineRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PSAProjInvoiceDetailLine.md" target="_blank">/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/PSAProjInvoiceDetailLine.cdm.json/PSAProjInvoiceDetailLine</a></td><td><a href="PSAProjInvoiceDetailLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/PSAProjInvoiceDetailTrans (this entity)  

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

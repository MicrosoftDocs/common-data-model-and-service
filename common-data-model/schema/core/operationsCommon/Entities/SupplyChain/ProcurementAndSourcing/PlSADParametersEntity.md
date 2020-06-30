---
title: PlSADParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# SAD parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PlSADParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>SAD parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InsuranceAccount](#InsuranceAccount)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[AdditionalCostsFormInvoice](#AdditionalCostsFormInvoice)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[MiscPaymentsAccount](#MiscPaymentsAccount)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[TransportAccount](#TransportAccount)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[DutyRounding](#DutyRounding)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[ExciseTaxRounding](#ExciseTaxRounding)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[MiscPayments](#MiscPayments)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[MiscellaneousChargesFromTheSADDocumentAccount](#MiscellaneousChargesFromTheSADDocumentAccount)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[TransportOnSADDocumentAccount](#TransportOnSADDocumentAccount)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[VATRounding](#VATRounding)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[InsuranceAccountDisplayValue](#InsuranceAccountDisplayValue)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[MiscPaymentsAccountDisplayValue](#MiscPaymentsAccountDisplayValue)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[TransportAccountDisplayValue](#TransportAccountDisplayValue)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[MiscellaneousChargesFromTheSADDocumentAccountDisplayValue](#MiscellaneousChargesFromTheSADDocumentAccountDisplayValue)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[TransportOnSADDocumentAccountDisplayValue](#TransportOnSADDocumentAccountDisplayValue)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[Relationship_InsuranceAccountCombinationRelationshipId](#Relationship_InsuranceAccountCombinationRelationshipId)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[Relationship_MiscPaymentsAccountCombinationRelationshipId](#Relationship_MiscPaymentsAccountCombinationRelationshipId)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[Relationship_TransportAccountCombinationRelationshipId](#Relationship_TransportAccountCombinationRelationshipId)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[Relationship_MiscellaneousChargesFromTheSADDocumentAccountCombinationRelationshipId](#Relationship_MiscellaneousChargesFromTheSADDocumentAccountCombinationRelationshipId)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[Relationship_TransportOnSADDocumentAccountCombinationRelationshipId](#Relationship_TransportOnSADDocumentAccountCombinationRelationshipId)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[BackingTable_PlSADParametersRelationshipId](#BackingTable_PlSADParametersRelationshipId)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PlSADParametersEntity.md" target="_blank">ProcurementAndSourcing/PlSADParametersEntity</a>|

### <a href=#InsuranceAccount name="InsuranceAccount">InsuranceAccount</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdditionalCostsFormInvoice name="AdditionalCostsFormInvoice">AdditionalCostsFormInvoice</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdditionalCostsFormInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MiscPaymentsAccount name="MiscPaymentsAccount">MiscPaymentsAccount</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MiscPaymentsAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportAccount name="TransportAccount">TransportAccount</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DutyRounding name="DutyRounding">DutyRounding</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DutyRounding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExciseTaxRounding name="ExciseTaxRounding">ExciseTaxRounding</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseTaxRounding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MiscPayments name="MiscPayments">MiscPayments</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MiscPayments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MiscellaneousChargesFromTheSADDocumentAccount name="MiscellaneousChargesFromTheSADDocumentAccount">MiscellaneousChargesFromTheSADDocumentAccount</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MiscellaneousChargesFromTheSADDocumentAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportOnSADDocumentAccount name="TransportOnSADDocumentAccount">TransportOnSADDocumentAccount</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportOnSADDocumentAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATRounding name="VATRounding">VATRounding</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATRounding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuranceAccountDisplayValue name="InsuranceAccountDisplayValue">InsuranceAccountDisplayValue</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MiscPaymentsAccountDisplayValue name="MiscPaymentsAccountDisplayValue">MiscPaymentsAccountDisplayValue</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MiscPaymentsAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportAccountDisplayValue name="TransportAccountDisplayValue">TransportAccountDisplayValue</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MiscellaneousChargesFromTheSADDocumentAccountDisplayValue name="MiscellaneousChargesFromTheSADDocumentAccountDisplayValue">MiscellaneousChargesFromTheSADDocumentAccountDisplayValue</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MiscellaneousChargesFromTheSADDocumentAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportOnSADDocumentAccountDisplayValue name="TransportOnSADDocumentAccountDisplayValue">TransportOnSADDocumentAccountDisplayValue</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportOnSADDocumentAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InsuranceAccountCombinationRelationshipId name="Relationship_InsuranceAccountCombinationRelationshipId">Relationship_InsuranceAccountCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InsuranceAccountCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MiscPaymentsAccountCombinationRelationshipId name="Relationship_MiscPaymentsAccountCombinationRelationshipId">Relationship_MiscPaymentsAccountCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MiscPaymentsAccountCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransportAccountCombinationRelationshipId name="Relationship_TransportAccountCombinationRelationshipId">Relationship_TransportAccountCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransportAccountCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MiscellaneousChargesFromTheSADDocumentAccountCombinationRelationshipId name="Relationship_MiscellaneousChargesFromTheSADDocumentAccountCombinationRelationshipId">Relationship_MiscellaneousChargesFromTheSADDocumentAccountCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MiscellaneousChargesFromTheSADDocumentAccountCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransportOnSADDocumentAccountCombinationRelationshipId name="Relationship_TransportOnSADDocumentAccountCombinationRelationshipId">Relationship_TransportOnSADDocumentAccountCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransportOnSADDocumentAccountCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PlSADParametersRelationshipId name="BackingTable_PlSADParametersRelationshipId">BackingTable_PlSADParametersRelationshipId</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PlSADParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Parameter/PlSADParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Parameter/PlSADParameters.cdm.json/PlSADParameters</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Parameter/PlSADParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PlSADParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

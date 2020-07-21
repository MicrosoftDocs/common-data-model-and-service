---
title: PurchAgreementClassificationEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Purchase agreement classification in ProcurementAndSourcing(PurchAgreementClassificationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchAgreementClassificationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase agreement classification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ArePurchaseAgreementActitivitesEnabled](#ArePurchaseAgreementActitivitesEnabled)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[ArePurchaseAgreementCertificationsEnabled](#ArePurchaseAgreementCertificationsEnabled)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[ClassificationDescription](#ClassificationDescription)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[IsDirectInvoicingRequired](#IsDirectInvoicingRequired)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[ClassificationName](#ClassificationName)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[ArePurchaseAgreementSubcontractorsEnabled](#ArePurchaseAgreementSubcontractorsEnabled)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[PrimaryResponsibleWorkerName](#PrimaryResponsibleWorkerName)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[SecondaryResponsibleWorkerName](#SecondaryResponsibleWorkerName)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[PrimaryResponsibleWorkerRecId](#PrimaryResponsibleWorkerRecId)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[SecondaryResponsibleWorkerRecId](#SecondaryResponsibleWorkerRecId)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[MatchingPolicy](#MatchingPolicy)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[Relationship_HcmWorkerPrimaryRelationshipId](#Relationship_HcmWorkerPrimaryRelationshipId)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[Relationship_HcmWorkerSecondaryRelationshipId](#Relationship_HcmWorkerSecondaryRelationshipId)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|
|[BackingTable_AgreementClassificationRelationshipId](#BackingTable_AgreementClassificationRelationshipId)||<a href="PurchAgreementClassificationEntity.md" target="_blank">ProcurementAndSourcing/PurchAgreementClassificationEntity</a>|

### <a href=#ArePurchaseAgreementActitivitesEnabled name="ArePurchaseAgreementActitivitesEnabled">ArePurchaseAgreementActitivitesEnabled</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseAgreementActitivitesEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePurchaseAgreementCertificationsEnabled name="ArePurchaseAgreementCertificationsEnabled">ArePurchaseAgreementCertificationsEnabled</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseAgreementCertificationsEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClassificationDescription name="ClassificationDescription">ClassificationDescription</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassificationDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDirectInvoicingRequired name="IsDirectInvoicingRequired">IsDirectInvoicingRequired</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDirectInvoicingRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClassificationName name="ClassificationName">ClassificationName</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassificationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePurchaseAgreementSubcontractorsEnabled name="ArePurchaseAgreementSubcontractorsEnabled">ArePurchaseAgreementSubcontractorsEnabled</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseAgreementSubcontractorsEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryResponsibleWorkerName name="PrimaryResponsibleWorkerName">PrimaryResponsibleWorkerName</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary responsible worker</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryResponsibleWorkerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary responsible worker</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryResponsibleWorkerName name="SecondaryResponsibleWorkerName">SecondaryResponsibleWorkerName</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Secondary responsible worker</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryResponsibleWorkerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Secondary responsible worker</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryResponsibleWorkerRecId name="PrimaryResponsibleWorkerRecId">PrimaryResponsibleWorkerRecId</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryResponsibleWorkerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryResponsibleWorkerRecId name="SecondaryResponsibleWorkerRecId">SecondaryResponsibleWorkerRecId</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryResponsibleWorkerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MatchingPolicy name="MatchingPolicy">MatchingPolicy</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchingPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HcmWorkerPrimaryRelationshipId name="Relationship_HcmWorkerPrimaryRelationshipId">Relationship_HcmWorkerPrimaryRelationshipId</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmWorkerPrimaryRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HcmWorkerSecondaryRelationshipId name="Relationship_HcmWorkerSecondaryRelationshipId">Relationship_HcmWorkerSecondaryRelationshipId</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmWorkerSecondaryRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_AgreementClassificationRelationshipId name="BackingTable_AgreementClassificationRelationshipId">BackingTable_AgreementClassificationRelationshipId</a>

First included in: ProcurementAndSourcing/PurchAgreementClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AgreementClassificationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/AgreementClassification.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/AgreementClassification.cdm.json/AgreementClassification</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/AgreementClassification.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

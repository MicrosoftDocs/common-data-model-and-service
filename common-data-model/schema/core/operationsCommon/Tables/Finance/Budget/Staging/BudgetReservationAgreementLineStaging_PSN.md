---
title: BudgetReservationAgreementLineStaging_PSN in Staging - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Budget reservation line and purchase agreement line in Staging

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Staging/BudgetReservationAgreementLineStaging_PSN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetReservationAgreementLineStaging_PSN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget reservation line and purchase agreement line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[DefinitionGroup](#DefinitionGroup)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[ExecutionId](#ExecutionId)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[IsSelected](#IsSelected)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[TransferStatus](#TransferStatus)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[BudgetReservationDocumentNumber](#BudgetReservationDocumentNumber)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[BudgetReservationLineNumber](#BudgetReservationLineNumber)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[AgreementLineNumber](#AgreementLineNumber)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[ItemId](#ItemId)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[EffectiveDate](#EffectiveDate)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[ExpirationDate](#ExpirationDate)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[PurchaseNumberSequence](#PurchaseNumberSequence)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[VendorAccount](#VendorAccount)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[BuyingLegalEntityId](#BuyingLegalEntityId)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[Relationship_CompanyInfoRelationshipId](#Relationship_CompanyInfoRelationshipId)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|
|[Relationship_BudgetReservationHeader_PSNRelationshipId](#Relationship_BudgetReservationHeader_PSNRelationshipId)||<a href="BudgetReservationAgreementLineStaging_PSN.md" target="_blank">Staging/BudgetReservationAgreementLineStaging_PSN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetReservationAgreementLineStaging_PSN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefinitionGroup name="DefinitionGroup">DefinitionGroup</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefinitionGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExecutionId name="ExecutionId">ExecutionId</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSelected name="IsSelected">IsSelected</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSelected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TransferStatus name="TransferStatus">TransferStatus</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BudgetReservationDocumentNumber name="BudgetReservationDocumentNumber">BudgetReservationDocumentNumber</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReservationLineNumber name="BudgetReservationLineNumber">BudgetReservationLineNumber</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationLineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AgreementLineNumber name="AgreementLineNumber">AgreementLineNumber</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementLineNumber attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveDate name="EffectiveDate">EffectiveDate</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ExpirationDate name="ExpirationDate">ExpirationDate</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PurchaseNumberSequence name="PurchaseNumberSequence">PurchaseNumberSequence</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseNumberSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccount name="VendorAccount">VendorAccount</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyingLegalEntityId name="BuyingLegalEntityId">BuyingLegalEntityId</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyingLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyInfoRelationshipId name="Relationship_CompanyInfoRelationshipId">Relationship_CompanyInfoRelationshipId</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyInfoRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BudgetReservationHeader_PSNRelationshipId name="Relationship_BudgetReservationHeader_PSNRelationshipId">Relationship_BudgetReservationHeader_PSNRelationshipId</a>

First included in: Staging/BudgetReservationAgreementLineStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetReservationHeader_PSNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/BudgetReservationHeader_PSN.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/WorksheetHeader/BudgetReservationHeader_PSN.cdm.json/BudgetReservationHeader_PSN</a></td><td><a href="../WorksheetHeader/BudgetReservationHeader_PSN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

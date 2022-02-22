---
title: BudgetReservationAgreementLineEntity_PSN in Budgeting - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Budget reservation line and purchase agreement line in Budgeting(BudgetReservationAgreementLineEntity_PSN)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetReservationAgreementLineEntity_PSN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget reservation line and purchase agreement line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BudgetReservationDocumentNumber](#BudgetReservationDocumentNumber)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[BudgetReservationLineNumber](#BudgetReservationLineNumber)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[AgreementLineNumber](#AgreementLineNumber)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[ItemId](#ItemId)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[EffectiveDate](#EffectiveDate)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[ExpirationDate](#ExpirationDate)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[PurchaseNumberSequence](#PurchaseNumberSequence)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[VendorAccount](#VendorAccount)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[AgreementLineRecId](#AgreementLineRecId)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[BudgetReservationLineRecId](#BudgetReservationLineRecId)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[BuyingLegalEntityRecId](#BuyingLegalEntityRecId)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[BuyingLegalEntityId](#BuyingLegalEntityId)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[BackingTable_BudgetResLineAgreementLine_PSNRelationshipId](#BackingTable_BudgetResLineAgreementLine_PSNRelationshipId)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BudgetReservationAgreementLineEntity_PSN.md" target="_blank">Budgeting/BudgetReservationAgreementLineEntity_PSN</a>|

### <a href=#BudgetReservationDocumentNumber name="BudgetReservationDocumentNumber">BudgetReservationDocumentNumber</a>

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

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

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementLineNumber name="AgreementLineNumber">AgreementLineNumber</a>

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

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

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpirationDate name="ExpirationDate">ExpirationDate</a>

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseNumberSequence name="PurchaseNumberSequence">PurchaseNumberSequence</a>

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

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

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementLineRecId name="AgreementLineRecId">AgreementLineRecId</a>

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementLineRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReservationLineRecId name="BudgetReservationLineRecId">BudgetReservationLineRecId</a>

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationLineRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyingLegalEntityRecId name="BuyingLegalEntityRecId">BuyingLegalEntityRecId</a>

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyingLegalEntityRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyingLegalEntityId name="BuyingLegalEntityId">BuyingLegalEntityId</a>

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyingLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BudgetResLineAgreementLine_PSNRelationshipId name="BackingTable_BudgetResLineAgreementLine_PSNRelationshipId">BackingTable_BudgetResLineAgreementLine_PSNRelationshipId</a>

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetResLineAgreementLine_PSNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/WorksheetLine/BudgetResLineAgreementLine_PSN.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/WorksheetLine/BudgetResLineAgreementLine_PSN.cdm.json/BudgetResLineAgreementLine_PSN</a></td><td><a href="../../../Tables/Finance/Budget/WorksheetLine/BudgetResLineAgreementLine_PSN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Budgeting/BudgetReservationAgreementLineEntity_PSN (this entity)  

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

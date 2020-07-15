---
title: ProjInvoiceJourAdjustment_TH in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/14/2020
ms.author: nebanfic
---

# Customer invoice journal adjustment in Miscellaneous(ProjInvoiceJourAdjustment_TH)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ProjInvoiceJourAdjustment_TH.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjInvoiceJourAdjustment_TH/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer invoice journal adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[ProjInvoiceJour](#ProjInvoiceJour)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[AdjustDateTime](#AdjustDateTime)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[InvoicingName](#InvoicingName)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[Reference](#Reference)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[TaxInvoiceId](#TaxInvoiceId)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[IsPrinted](#IsPrinted)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[AdjustmentType](#AdjustmentType)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[Description](#Description)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[DeliveryPostingAddress](#DeliveryPostingAddress)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[CustomerPhone](#CustomerPhone)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[CustomerTeleFax](#CustomerTeleFax)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[InvoiceTaxRegNumber](#InvoiceTaxRegNumber)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[InvoiceBranch](#InvoiceBranch)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[InvoiceBranchName](#InvoiceBranchName)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[DataAreaId](#DataAreaId)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[Relationship_ProjInvoiceJourRelationshipId](#Relationship_ProjInvoiceJourRelationshipId)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ProjInvoiceJourAdjustment_TH.md" target="_blank">Miscellaneous/ProjInvoiceJourAdjustment_TH</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjInvoiceJourAdjustment_TH/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProjInvoiceJour name="ProjInvoiceJour">ProjInvoiceJour</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjInvoiceJour attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdjustDateTime name="AdjustDateTime">AdjustDateTime</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#InvoicingName name="InvoicingName">InvoicingName</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicingName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reference name="Reference">Reference</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxInvoiceId name="TaxInvoiceId">TaxInvoiceId</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrinted name="IsPrinted">IsPrinted</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrinted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AdjustmentType name="AdjustmentType">AdjustmentType</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostingAddress name="DeliveryPostingAddress">DeliveryPostingAddress</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostingAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPhone name="CustomerPhone">CustomerPhone</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerTeleFax name="CustomerTeleFax">CustomerTeleFax</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTeleFax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceTaxRegNumber name="InvoiceTaxRegNumber">InvoiceTaxRegNumber</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceTaxRegNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceBranch name="InvoiceBranch">InvoiceBranch</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceBranch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceBranchName name="InvoiceBranchName">InvoiceBranchName</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Branch name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceBranchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Branch name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

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

### <a href=#Relationship_ProjInvoiceJourRelationshipId name="Relationship_ProjInvoiceJourRelationshipId">Relationship_ProjInvoiceJourRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjInvoiceJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/ProjInvoiceJour.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjInvoiceJour.cdm.json/ProjInvoiceJour</a></td><td><a href="../Transaction/ProjInvoiceJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceJourAdjustment_TH (this entity)  

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

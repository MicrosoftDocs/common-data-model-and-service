---
title: ProjProjectFormSetupEntity in ProjectManagementAndAccounting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Project form setup in ProjectManagementAndAccounting(ProjProjectFormSetupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjProjectFormSetupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project form setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AssociatedPaymentAttachmentOnInvoice](#AssociatedPaymentAttachmentOnInvoice)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[Invoice](#Invoice)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[PackingSlip](#PackingSlip)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[ItemNumberInForms](#ItemNumberInForms)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[Key](#Key)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[PrintPackingSlipSpecificationsOnInvoice](#PrintPackingSlipSpecificationsOnInvoice)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[PrePrintLevelInvoice](#PrePrintLevelInvoice)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[PrintEuroAmount](#PrintEuroAmount)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[PrintTaxExemptNumberOnInvoice](#PrintTaxExemptNumberOnInvoice)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[SpecifyIndexCalculation](#SpecifyIndexCalculation)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[SeparateTaxExemptBalanceInForms](#SeparateTaxExemptBalanceInForms)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[SalesTaxSpecification](#SalesTaxSpecification)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[TotalsFirstLastPage](#TotalsFirstLastPage)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[BackingTable_ProjFormletterParametersRelationshipId](#BackingTable_ProjFormletterParametersRelationshipId)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjProjectFormSetupEntity.md" target="_blank">ProjectManagementAndAccounting/ProjProjectFormSetupEntity</a>|

### <a href=#AssociatedPaymentAttachmentOnInvoice name="AssociatedPaymentAttachmentOnInvoice">AssociatedPaymentAttachmentOnInvoice</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssociatedPaymentAttachmentOnInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invoice name="Invoice">Invoice</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingSlip name="PackingSlip">PackingSlip</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlip attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumberInForms name="ItemNumberInForms">ItemNumberInForms</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumberInForms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintPackingSlipSpecificationsOnInvoice name="PrintPackingSlipSpecificationsOnInvoice">PrintPackingSlipSpecificationsOnInvoice</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintPackingSlipSpecificationsOnInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrePrintLevelInvoice name="PrePrintLevelInvoice">PrePrintLevelInvoice</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintEuroAmount name="PrintEuroAmount">PrintEuroAmount</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintEuroAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintTaxExemptNumberOnInvoice name="PrintTaxExemptNumberOnInvoice">PrintTaxExemptNumberOnInvoice</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTaxExemptNumberOnInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecifyIndexCalculation name="SpecifyIndexCalculation">SpecifyIndexCalculation</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecifyIndexCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SeparateTaxExemptBalanceInForms name="SeparateTaxExemptBalanceInForms">SeparateTaxExemptBalanceInForms</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SeparateTaxExemptBalanceInForms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxSpecification name="SalesTaxSpecification">SalesTaxSpecification</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxSpecification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalsFirstLastPage name="TotalsFirstLastPage">TotalsFirstLastPage</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalsFirstLastPage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProjFormletterParametersRelationshipId name="BackingTable_ProjFormletterParametersRelationshipId">BackingTable_ProjFormletterParametersRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjFormletterParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Parameter/ProjFormletterParameters.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Parameter/ProjFormletterParameters.cdm.json/ProjFormletterParameters</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Parameter/ProjFormletterParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjProjectFormSetupEntity (this entity)  

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

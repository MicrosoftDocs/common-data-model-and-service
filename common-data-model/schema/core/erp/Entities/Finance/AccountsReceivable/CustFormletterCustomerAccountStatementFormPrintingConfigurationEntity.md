---
title: CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Finance/AccountsReceivable/CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PaperFormat](#PaperFormat)||<a href="CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity.md" target="_blank">AccountsReceivable/CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity</a>|
|[IsTaxExemptNumberDisplayed](#IsTaxExemptNumberDisplayed)||<a href="CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity.md" target="_blank">AccountsReceivable/CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity</a>|
|[DisplayedPaymentAttachmentType](#DisplayedPaymentAttachmentType)||<a href="CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity.md" target="_blank">AccountsReceivable/CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity</a>|
|[BackingTable_CustFormletterParametersRelationshipId](#BackingTable_CustFormletterParametersRelationshipId)||<a href="CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity.md" target="_blank">AccountsReceivable/CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity.md" target="_blank">AccountsReceivable/CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity</a>|

### <a href=#PaperFormat name="PaperFormat">PaperFormat</a>

First included in: AccountsReceivable/CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaperFormat attribute are listed below.</summary>

**is.dataFormat.array**  
</details>

### <a href=#IsTaxExemptNumberDisplayed name="IsTaxExemptNumberDisplayed">IsTaxExemptNumberDisplayed</a>

First included in: AccountsReceivable/CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxExemptNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.array**  
</details>

### <a href=#DisplayedPaymentAttachmentType name="DisplayedPaymentAttachmentType">DisplayedPaymentAttachmentType</a>

First included in: AccountsReceivable/CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayedPaymentAttachmentType attribute are listed below.</summary>

**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustFormletterParametersRelationshipId name="BackingTable_CustFormletterParametersRelationshipId">BackingTable_CustFormletterParametersRelationshipId</a>

First included in: AccountsReceivable/CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustFormletterParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/CustFormletterParameters.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Parameter/CustFormletterParameters.cdm.json/CustFormletterParameters</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/CustFormletterParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CustFormletterCustomerAccountStatementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

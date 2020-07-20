---
title: JournalizingTransactionPostingDefinitionReceivableEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Transaction posting definition receivable in GeneralLedger(JournalizingTransactionPostingDefinitionReceivableEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction posting definition receivable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustBillingClassificationRecId](#CustBillingClassificationRecId)||<a href="JournalizingTransactionPostingDefinitionReceivableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity</a>|
|[CustBillingCodeRecId](#CustBillingCodeRecId)||<a href="JournalizingTransactionPostingDefinitionReceivableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity</a>|
|[CustomerTransactionType](#CustomerTransactionType)||<a href="JournalizingTransactionPostingDefinitionReceivableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity</a>|
|[PostingDefinitionRecId](#PostingDefinitionRecId)||<a href="JournalizingTransactionPostingDefinitionReceivableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity</a>|
|[AttributeTypeBillingClassificationBillingCodeAll](#AttributeTypeBillingClassificationBillingCodeAll)||<a href="JournalizingTransactionPostingDefinitionReceivableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity</a>|
|[PostingDefinition](#PostingDefinition)||<a href="JournalizingTransactionPostingDefinitionReceivableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity</a>|
|[BillingClassification](#BillingClassification)||<a href="JournalizingTransactionPostingDefinitionReceivableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity</a>|
|[BillingCode](#BillingCode)||<a href="JournalizingTransactionPostingDefinitionReceivableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity</a>|
|[BackingTable_JournalizingDefinitionCustomerTransRelationshipId](#BackingTable_JournalizingDefinitionCustomerTransRelationshipId)||<a href="JournalizingTransactionPostingDefinitionReceivableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JournalizingTransactionPostingDefinitionReceivableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity</a>|

### <a href=#CustBillingClassificationRecId name="CustBillingClassificationRecId">CustBillingClassificationRecId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustBillingClassificationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustBillingCodeRecId name="CustBillingCodeRecId">CustBillingCodeRecId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustBillingCodeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerTransactionType name="CustomerTransactionType">CustomerTransactionType</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingDefinitionRecId name="PostingDefinitionRecId">PostingDefinitionRecId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDefinitionRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeTypeBillingClassificationBillingCodeAll name="AttributeTypeBillingClassificationBillingCodeAll">AttributeTypeBillingClassificationBillingCodeAll</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attribute type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeTypeBillingClassificationBillingCodeAll attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attribute type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingDefinition name="PostingDefinition">PostingDefinition</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingClassification name="BillingClassification">BillingClassification</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingClassification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingCode name="BillingCode">BillingCode</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_JournalizingDefinitionCustomerTransRelationshipId name="BackingTable_JournalizingDefinitionCustomerTransRelationshipId">BackingTable_JournalizingDefinitionCustomerTransRelationshipId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JournalizingDefinitionCustomerTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountingFoundation/Group/JournalizingDefinitionCustomerTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/JournalizingDefinitionCustomerTrans.cdm.json/JournalizingDefinitionCustomerTrans</a></td><td><a href="../../../Tables/Finance/AccountingFoundation/Group/JournalizingDefinitionCustomerTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionReceivableEntity (this entity)  

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

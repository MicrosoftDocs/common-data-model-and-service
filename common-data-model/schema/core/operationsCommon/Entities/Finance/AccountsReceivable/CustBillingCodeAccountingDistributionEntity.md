---
title: CustBillingCodeAccountingDistributionEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Billing code with accounting distribution in AccountsReceivable(CustBillingCodeAccountingDistributionEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustBillingCodeAccountingDistributionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Billing code with accounting distribution</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustBillingCodeVersion](#CustBillingCodeVersion)||<a href="CustBillingCodeAccountingDistributionEntity.md" target="_blank">AccountsReceivable/CustBillingCodeAccountingDistributionEntity</a>|
|[LedgerAccount](#LedgerAccount)||<a href="CustBillingCodeAccountingDistributionEntity.md" target="_blank">AccountsReceivable/CustBillingCodeAccountingDistributionEntity</a>|
|[Percent](#Percent)||<a href="CustBillingCodeAccountingDistributionEntity.md" target="_blank">AccountsReceivable/CustBillingCodeAccountingDistributionEntity</a>|
|[CustBillingCode](#CustBillingCode)||<a href="CustBillingCodeAccountingDistributionEntity.md" target="_blank">AccountsReceivable/CustBillingCodeAccountingDistributionEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="CustBillingCodeAccountingDistributionEntity.md" target="_blank">AccountsReceivable/CustBillingCodeAccountingDistributionEntity</a>|
|[ValidTo](#ValidTo)||<a href="CustBillingCodeAccountingDistributionEntity.md" target="_blank">AccountsReceivable/CustBillingCodeAccountingDistributionEntity</a>|
|[BillingCode](#BillingCode)||<a href="CustBillingCodeAccountingDistributionEntity.md" target="_blank">AccountsReceivable/CustBillingCodeAccountingDistributionEntity</a>|
|[LedgerAccountDisplayValue](#LedgerAccountDisplayValue)||<a href="CustBillingCodeAccountingDistributionEntity.md" target="_blank">AccountsReceivable/CustBillingCodeAccountingDistributionEntity</a>|
|[Relationship_LedgerAccountCombinationRelationshipId](#Relationship_LedgerAccountCombinationRelationshipId)||<a href="CustBillingCodeAccountingDistributionEntity.md" target="_blank">AccountsReceivable/CustBillingCodeAccountingDistributionEntity</a>|
|[BackingTable_CustBillingCodeLedgerAccountRelationshipId](#BackingTable_CustBillingCodeLedgerAccountRelationshipId)||<a href="CustBillingCodeAccountingDistributionEntity.md" target="_blank">AccountsReceivable/CustBillingCodeAccountingDistributionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustBillingCodeAccountingDistributionEntity.md" target="_blank">AccountsReceivable/CustBillingCodeAccountingDistributionEntity</a>|

### <a href=#CustBillingCodeVersion name="CustBillingCodeVersion">CustBillingCodeVersion</a>

First included in: AccountsReceivable/CustBillingCodeAccountingDistributionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustBillingCodeVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAccount name="LedgerAccount">LedgerAccount</a>

First included in: AccountsReceivable/CustBillingCodeAccountingDistributionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Percent name="Percent">Percent</a>

First included in: AccountsReceivable/CustBillingCodeAccountingDistributionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustBillingCode name="CustBillingCode">CustBillingCode</a>

First included in: AccountsReceivable/CustBillingCodeAccountingDistributionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustBillingCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: AccountsReceivable/CustBillingCodeAccountingDistributionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: AccountsReceivable/CustBillingCodeAccountingDistributionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingCode name="BillingCode">BillingCode</a>

First included in: AccountsReceivable/CustBillingCodeAccountingDistributionEntity (this entity)  

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

### <a href=#LedgerAccountDisplayValue name="LedgerAccountDisplayValue">LedgerAccountDisplayValue</a>

First included in: AccountsReceivable/CustBillingCodeAccountingDistributionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerAccountCombinationRelationshipId name="Relationship_LedgerAccountCombinationRelationshipId">Relationship_LedgerAccountCombinationRelationshipId</a>

First included in: AccountsReceivable/CustBillingCodeAccountingDistributionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_CustBillingCodeLedgerAccountRelationshipId name="BackingTable_CustBillingCodeLedgerAccountRelationshipId">BackingTable_CustBillingCodeLedgerAccountRelationshipId</a>

First included in: AccountsReceivable/CustBillingCodeAccountingDistributionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustBillingCodeLedgerAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Group/CustBillingCodeLedgerAccount.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustBillingCodeLedgerAccount.cdm.json/CustBillingCodeLedgerAccount</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Group/CustBillingCodeLedgerAccount.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CustBillingCodeAccountingDistributionEntity (this entity)  

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

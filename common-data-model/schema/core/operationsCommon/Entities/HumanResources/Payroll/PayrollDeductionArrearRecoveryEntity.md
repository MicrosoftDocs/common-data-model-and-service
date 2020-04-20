---
title: PayrollDeductionArrearRecoveryEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# PayrollDeductionArrearRecoveryEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollDeductionArrearRecoveryEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[PayStatementNumber](#PayStatementNumber)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|
|[AmountInTransactionCurrency](#AmountInTransactionCurrency)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|
|[ArrearsTransaction](#ArrearsTransaction)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|
|[ArrearsChangeType](#ArrearsChangeType)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|
|[PayStatement](#PayStatement)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|
|[RecoveryCreatedBy](#RecoveryCreatedBy)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|
|[RecoveryCreatedDateTime](#RecoveryCreatedDateTime)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|
|[BenefitId](#BenefitId)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|
|[Relationship_PayrollPayStatementHeaderEntityRelationshipId](#Relationship_PayrollPayStatementHeaderEntityRelationshipId)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|
|[Relationship_HcmBenefitEntityRelationshipId](#Relationship_HcmBenefitEntityRelationshipId)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|
|[BackingTable_PRLDeductionArrearRecoveryRelationshipId](#BackingTable_PRLDeductionArrearRecoveryRelationshipId)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PayrollDeductionArrearRecoveryEntity.md" target="_blank">Payroll/PayrollDeductionArrearRecoveryEntity</a>|

### <a href=#PayStatementNumber name="PayStatementNumber">PayStatementNumber</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInTransactionCurrency name="AmountInTransactionCurrency">AmountInTransactionCurrency</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArrearsTransaction name="ArrearsTransaction">ArrearsTransaction</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArrearsTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArrearsChangeType name="ArrearsChangeType">ArrearsChangeType</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArrearsChangeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayStatement name="PayStatement">PayStatement</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecoveryCreatedBy name="RecoveryCreatedBy">RecoveryCreatedBy</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoveryCreatedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecoveryCreatedDateTime name="RecoveryCreatedDateTime">RecoveryCreatedDateTime</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoveryCreatedDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitId name="BenefitId">BenefitId</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayrollPayStatementHeaderEntityRelationshipId name="Relationship_PayrollPayStatementHeaderEntityRelationshipId">Relationship_PayrollPayStatementHeaderEntityRelationshipId</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollPayStatementHeaderEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HcmBenefitEntityRelationshipId name="Relationship_HcmBenefitEntityRelationshipId">Relationship_HcmBenefitEntityRelationshipId</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmBenefitEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PRLDeductionArrearRecoveryRelationshipId name="BackingTable_PRLDeductionArrearRecoveryRelationshipId">BackingTable_PRLDeductionArrearRecoveryRelationshipId</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PRLDeductionArrearRecoveryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/Transaction/PRLDeductionArrearRecovery.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Transaction/PRLDeductionArrearRecovery.cdm.json/PRLDeductionArrearRecovery</a></td><td><a href="../../../Tables/HumanResources/Payroll/Transaction/PRLDeductionArrearRecovery.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Payroll/PayrollDeductionArrearRecoveryEntity (this entity)  

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

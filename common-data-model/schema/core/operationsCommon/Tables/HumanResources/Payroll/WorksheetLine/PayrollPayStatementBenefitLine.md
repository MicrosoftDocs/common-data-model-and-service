---
title: PayrollPayStatementBenefitLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# PayrollPayStatementBenefitLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/HumanResources/Payroll/WorksheetLine/PayrollPayStatementBenefitLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PayrollPayStatementBenefitLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[AccountingCurrencyAmount](#AccountingCurrencyAmount)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[AccountingDate](#AccountingDate)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[AccountingDistributionTemplate](#AccountingDistributionTemplate)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[IsEmployer](#IsEmployer)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[IsLineLocked](#IsLineLocked)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[IsMarkedForRemoval](#IsMarkedForRemoval)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[IsPayStatementLineOverridden](#IsPayStatementLineOverridden)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[PayStatement](#PayStatement)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[Position](#Position)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[ReversedPayStatementLine](#ReversedPayStatementLine)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[Source](#Source)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[SourceDocumentLine](#SourceDocumentLine)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[VendTrans](#VendTrans)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[LineNum](#LineNum)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[DataAreaId](#DataAreaId)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[Relationship_AccountingDistributionTemplate_FKRelationshipId](#Relationship_AccountingDistributionTemplate_FKRelationshipId)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[Relationship_PayStatement_FKRelationshipId](#Relationship_PayStatement_FKRelationshipId)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[Relationship_SourceDocumentLine_FKRelationshipId](#Relationship_SourceDocumentLine_FKRelationshipId)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[Relationship_VendTrans_FKRelationshipId](#Relationship_VendTrans_FKRelationshipId)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[BaseTimeEarningBaseAmount](#BaseTimeEarningBaseAmount)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[BaseTimeEarningBaseHours](#BaseTimeEarningBaseHours)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[Benefit](#Benefit)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[PremiumEarningBaseAmount](#PremiumEarningBaseAmount)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|
|[PremiumEarningBaseHours](#PremiumEarningBaseHours)||<a href="PayrollPayStatementBenefitLine.md" target="_blank">WorksheetLine/PayrollPayStatementBenefitLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PayrollPayStatementBenefitLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingCurrencyAmount name="AccountingCurrencyAmount">AccountingCurrencyAmount</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#AccountingDistributionTemplate name="AccountingDistributionTemplate">AccountingDistributionTemplate</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsEmployer name="IsEmployer">IsEmployer</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEmployer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsLineLocked name="IsLineLocked">IsLineLocked</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLineLocked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsMarkedForRemoval name="IsMarkedForRemoval">IsMarkedForRemoval</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMarkedForRemoval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsPayStatementLineOverridden name="IsPayStatementLineOverridden">IsPayStatementLineOverridden</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPayStatementLineOverridden attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PayStatement name="PayStatement">PayStatement</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayStatement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

</details>

### <a href=#ReversedPayStatementLine name="ReversedPayStatementLine">ReversedPayStatementLine</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversedPayStatementLine attribute are listed below.</summary>

</details>

### <a href=#Source name="Source">Source</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Source attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceDocumentLine name="SourceDocumentLine">SourceDocumentLine</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendTrans name="VendTrans">VendTrans</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

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

### <a href=#Relationship_AccountingDistributionTemplate_FKRelationshipId name="Relationship_AccountingDistributionTemplate_FKRelationshipId">Relationship_AccountingDistributionTemplate_FKRelationshipId</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountingDistributionTemplate_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountingFoundation/Group/AccountingDistributionTemplate.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/AccountingDistributionTemplate.cdm.json/AccountingDistributionTemplate</a></td><td><a href="../../../Finance/AccountingFoundation/Group/AccountingDistributionTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayStatement_FKRelationshipId name="Relationship_PayStatement_FKRelationshipId">Relationship_PayStatement_FKRelationshipId</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayStatement_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PayrollPayStatement.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/WorksheetHeader/PayrollPayStatement.cdm.json/PayrollPayStatement</a></td><td><a href="../WorksheetHeader/PayrollPayStatement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourceDocumentLine_FKRelationshipId name="Relationship_SourceDocumentLine_FKRelationshipId">Relationship_SourceDocumentLine_FKRelationshipId</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceDocumentLine_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.cdm.json/SourceDocumentLine</a></td><td><a href="../../../Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTrans_FKRelationshipId name="Relationship_VendTrans_FKRelationshipId">Relationship_VendTrans_FKRelationshipId</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTrans_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsPayable/Transaction/VendTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendTrans.cdm.json/VendTrans</a></td><td><a href="../../../Finance/AccountsPayable/Transaction/VendTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

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

### <a href=#BaseTimeEarningBaseAmount name="BaseTimeEarningBaseAmount">BaseTimeEarningBaseAmount</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseTimeEarningBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BaseTimeEarningBaseHours name="BaseTimeEarningBaseHours">BaseTimeEarningBaseHours</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseTimeEarningBaseHours attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Benefit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PremiumEarningBaseAmount name="PremiumEarningBaseAmount">PremiumEarningBaseAmount</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumEarningBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PremiumEarningBaseHours name="PremiumEarningBaseHours">PremiumEarningBaseHours</a>

First included in: WorksheetLine/PayrollPayStatementBenefitLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumEarningBaseHours attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

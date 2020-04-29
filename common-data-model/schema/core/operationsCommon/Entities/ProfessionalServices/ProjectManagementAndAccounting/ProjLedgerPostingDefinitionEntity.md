---
title: ProjLedgerPostingDefinitionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Project ledger posting definition

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project ledger posting definition</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProjectAccountType](#ProjectAccountType)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[ProjectId](#ProjectId)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[ProjectGroup](#ProjectGroup)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[CategoryId](#CategoryId)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[CategoryGroup](#CategoryGroup)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[ProjFundingSource](#ProjFundingSource)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[TaxGroupId](#TaxGroupId)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[ProjectContractId](#ProjectContractId)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[FundingSourceId](#FundingSourceId)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[MainAccountIdDisplayValue](#MainAccountIdDisplayValue)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[MainAccountId](#MainAccountId)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[ProjCode](#ProjCode)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[CategoryCode](#CategoryCode)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[ProjRelation](#ProjRelation)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[ProjCategoryRelation](#ProjCategoryRelation)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[BorrowingLegalEntity](#BorrowingLegalEntity)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[LendingLegalEntity](#LendingLegalEntity)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[Relationship_MainAccountIdCombinationRelationshipId](#Relationship_MainAccountIdCombinationRelationshipId)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[BackingTable_ProjPostingRelationshipId](#BackingTable_ProjPostingRelationshipId)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjLedgerPostingDefinitionEntity.md" target="_blank">ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity</a>|

### <a href=#ProjectAccountType name="ProjectAccountType">ProjectAccountType</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project ID</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectGroup name="ProjectGroup">ProjectGroup</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project group</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryId name="CategoryId">CategoryId</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryGroup name="CategoryGroup">CategoryGroup</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjFundingSource name="ProjFundingSource">ProjFundingSource</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjFundingSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroupId name="TaxGroupId">TaxGroupId</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectContractId name="ProjectContractId">ProjectContractId</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectContractId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FundingSourceId name="FundingSourceId">FundingSourceId</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundingSourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdDisplayValue name="MainAccountIdDisplayValue">MainAccountIdDisplayValue</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountId name="MainAccountId">MainAccountId</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjCode name="ProjCode">ProjCode</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryCode name="CategoryCode">CategoryCode</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjRelation name="ProjRelation">ProjRelation</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjCategoryRelation name="ProjCategoryRelation">ProjCategoryRelation</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjCategoryRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BorrowingLegalEntity name="BorrowingLegalEntity">BorrowingLegalEntity</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BorrowingLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LendingLegalEntity name="LendingLegalEntity">LendingLegalEntity</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LendingLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountIdCombinationRelationshipId name="Relationship_MainAccountIdCombinationRelationshipId">Relationship_MainAccountIdCombinationRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_ProjPostingRelationshipId name="BackingTable_ProjPostingRelationshipId">BackingTable_ProjPostingRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjPostingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPosting.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPosting.cdm.json/ProjPosting</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPosting.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjLedgerPostingDefinitionEntity (this entity)  

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

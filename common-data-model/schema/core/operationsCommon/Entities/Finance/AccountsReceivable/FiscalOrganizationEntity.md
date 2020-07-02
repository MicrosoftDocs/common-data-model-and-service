---
title: FiscalOrganizationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Fiscal organization entity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/FiscalOrganizationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal organization entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TypeOfActivity](#TypeOfActivity)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[TypeOfAssessmentContribution](#TypeOfAssessmentContribution)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[BookingAndAssessmentCriteria](#BookingAndAssessmentCriteria)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[AssessmentRegimen](#AssessmentRegimen)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[SalesTaxCOFINSExpense](#SalesTaxCOFINSExpense)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[ConstitutionArchiveDate](#ConstitutionArchiveDate)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[ConversionArchiveDate](#ConversionArchiveDate)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[CreditAllocationMethod](#CreditAllocationMethod)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[RootFiscalEstablishmentDataArea](#RootFiscalEstablishmentDataArea)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[RootFiscalEstablishment](#RootFiscalEstablishment)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[LegalEntityType](#LegalEntityType)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[LayoutVersion](#LayoutVersion)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[CompanyType](#CompanyType)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[LargeCompany](#LargeCompany)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[LegalNature](#LegalNature)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[SalesTaxPISExpense](#SalesTaxPISExpense)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[SCPCode](#SCPCode)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[SCPParticipation](#SCPParticipation)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[SalesTaxCOFINSExpenseDisplayValue](#SalesTaxCOFINSExpenseDisplayValue)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[SalesTaxPISExpenseDisplayValue](#SalesTaxPISExpenseDisplayValue)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[Relationship_SalesTaxCOFINSExpenseCombinationRelationshipId](#Relationship_SalesTaxCOFINSExpenseCombinationRelationshipId)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[Relationship_SalesTaxPISExpenseCombinationRelationshipId](#Relationship_SalesTaxPISExpenseCombinationRelationshipId)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|
|[BackingTable_FiscalOrganization_BRRelationshipId](#BackingTable_FiscalOrganization_BRRelationshipId)||<a href="FiscalOrganizationEntity.md" target="_blank">AccountsReceivable/FiscalOrganizationEntity</a>|

### <a href=#TypeOfActivity name="TypeOfActivity">TypeOfActivity</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeOfActivity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeOfAssessmentContribution name="TypeOfAssessmentContribution">TypeOfAssessmentContribution</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeOfAssessmentContribution attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BookingAndAssessmentCriteria name="BookingAndAssessmentCriteria">BookingAndAssessmentCriteria</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookingAndAssessmentCriteria attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssessmentRegimen name="AssessmentRegimen">AssessmentRegimen</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessmentRegimen attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxCOFINSExpense name="SalesTaxCOFINSExpense">SalesTaxCOFINSExpense</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxCOFINSExpense attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstitutionArchiveDate name="ConstitutionArchiveDate">ConstitutionArchiveDate</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstitutionArchiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConversionArchiveDate name="ConversionArchiveDate">ConversionArchiveDate</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConversionArchiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditAllocationMethod name="CreditAllocationMethod">CreditAllocationMethod</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditAllocationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RootFiscalEstablishmentDataArea name="RootFiscalEstablishmentDataArea">RootFiscalEstablishmentDataArea</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Root company</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RootFiscalEstablishmentDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Root company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RootFiscalEstablishment name="RootFiscalEstablishment">RootFiscalEstablishment</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RootFiscalEstablishment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityType name="LegalEntityType">LegalEntityType</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutVersion name="LayoutVersion">LayoutVersion</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyType name="CompanyType">CompanyType</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LargeCompany name="LargeCompany">LargeCompany</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LargeCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalNature name="LegalNature">LegalNature</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalNature attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxPISExpense name="SalesTaxPISExpense">SalesTaxPISExpense</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxPISExpense attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SCPCode name="SCPCode">SCPCode</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SCPCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SCPParticipation name="SCPParticipation">SCPParticipation</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SCPParticipation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxCOFINSExpenseDisplayValue name="SalesTaxCOFINSExpenseDisplayValue">SalesTaxCOFINSExpenseDisplayValue</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax COFINS expense</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxCOFINSExpenseDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax COFINS expense</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxPISExpenseDisplayValue name="SalesTaxPISExpenseDisplayValue">SalesTaxPISExpenseDisplayValue</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax PIS expense</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxPISExpenseDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax PIS expense</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTaxCOFINSExpenseCombinationRelationshipId name="Relationship_SalesTaxCOFINSExpenseCombinationRelationshipId">Relationship_SalesTaxCOFINSExpenseCombinationRelationshipId</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTaxCOFINSExpenseCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesTaxPISExpenseCombinationRelationshipId name="Relationship_SalesTaxPISExpenseCombinationRelationshipId">Relationship_SalesTaxPISExpenseCombinationRelationshipId</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTaxPISExpenseCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_FiscalOrganization_BRRelationshipId name="BackingTable_FiscalOrganization_BRRelationshipId">BackingTable_FiscalOrganization_BRRelationshipId</a>

First included in: AccountsReceivable/FiscalOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FiscalOrganization_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Main/FiscalOrganization_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FiscalOrganization_BR.cdm.json/FiscalOrganization_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Main/FiscalOrganization_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

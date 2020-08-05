---
title: CustVendPaymProposalBatchProcess in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Payment proposal batch process. in Miscellaneous(CustVendPaymProposalBatchProcess)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Bank/Miscellaneous/CustVendPaymProposalBatchProcess.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustVendPaymProposalBatchProcess/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment proposal batch process.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[JournalId](#JournalId)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[LedgerJournalType](#LedgerJournalType)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[ModuleCustVend](#ModuleCustVend)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[IncludeInvoicesFromOtherCompanies](#IncludeInvoicesFromOtherCompanies)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[CreatePaymPerInvoiceCompany](#CreatePaymPerInvoiceCompany)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[LimitPaymCreationToLedgerCompanyOnly](#LimitPaymCreationToLedgerCompanyOnly)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[DefaultOffsetAccountType](#DefaultOffsetAccountType)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[DefaultOffsetAccount](#DefaultOffsetAccount)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[DefaultOffsetLedgerDimension](#DefaultOffsetLedgerDimension)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[ChangePaymMode](#ChangePaymMode)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[CanUseSpecTransSetBasedInsert](#CanUseSpecTransSetBasedInsert)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[CanUseCustVendPaymProposalLineSetBasedInsert](#CanUseCustVendPaymProposalLineSetBasedInsert)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[State](#State)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[UserId](#UserId)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[TargetState](#TargetState)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[BatchJobId](#BatchJobId)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[DataAreaId](#DataAreaId)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[Relationship_LedgerJournalTableRelationshipId](#Relationship_LedgerJournalTableRelationshipId)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[Relationship_DefaultOffsetLedgerDimensionRelationshipId](#Relationship_DefaultOffsetLedgerDimensionRelationshipId)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustVendPaymProposalBatchProcess.md" target="_blank">Miscellaneous/CustVendPaymProposalBatchProcess</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustVendPaymProposalBatchProcess/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerJournalType name="LedgerJournalType">LedgerJournalType</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ModuleCustVend name="ModuleCustVend">ModuleCustVend</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModuleCustVend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IncludeInvoicesFromOtherCompanies name="IncludeInvoicesFromOtherCompanies">IncludeInvoicesFromOtherCompanies</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeInvoicesFromOtherCompanies attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CreatePaymPerInvoiceCompany name="CreatePaymPerInvoiceCompany">CreatePaymPerInvoiceCompany</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatePaymPerInvoiceCompany attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LimitPaymCreationToLedgerCompanyOnly name="LimitPaymCreationToLedgerCompanyOnly">LimitPaymCreationToLedgerCompanyOnly</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitPaymCreationToLedgerCompanyOnly attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefaultOffsetAccountType name="DefaultOffsetAccountType">DefaultOffsetAccountType</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOffsetAccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefaultOffsetAccount name="DefaultOffsetAccount">DefaultOffsetAccount</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOffsetAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOffsetLedgerDimension name="DefaultOffsetLedgerDimension">DefaultOffsetLedgerDimension</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ChangePaymMode name="ChangePaymMode">ChangePaymMode</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangePaymMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CanUseSpecTransSetBasedInsert name="CanUseSpecTransSetBasedInsert">CanUseSpecTransSetBasedInsert</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanUseSpecTransSetBasedInsert attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CanUseCustVendPaymProposalLineSetBasedInsert name="CanUseCustVendPaymProposalLineSetBasedInsert">CanUseCustVendPaymProposalLineSetBasedInsert</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanUseCustVendPaymProposalLineSetBasedInsert attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#State name="State">State</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current state</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Current state</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UserId name="UserId">UserId</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The user ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The user ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetState name="TargetState">TargetState</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target state</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Target state</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BatchJobId name="BatchJobId">BatchJobId</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchJobId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

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

### <a href=#Relationship_LedgerJournalTableRelationshipId name="Relationship_LedgerJournalTableRelationshipId">Relationship_LedgerJournalTableRelationshipId</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/WorksheetHeader/LedgerJournalTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetHeader/LedgerJournalTable.cdm.json/LedgerJournalTable</a></td><td><a href="../../AccountingFoundation/WorksheetHeader/LedgerJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultOffsetLedgerDimensionRelationshipId name="Relationship_DefaultOffsetLedgerDimensionRelationshipId">Relationship_DefaultOffsetLedgerDimensionRelationshipId</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultOffsetLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/CustVendPaymProposalBatchProcess (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

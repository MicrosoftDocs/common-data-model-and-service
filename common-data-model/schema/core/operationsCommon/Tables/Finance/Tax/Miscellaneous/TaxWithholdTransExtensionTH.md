---
title: TaxWithholdTransExtensionTH - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Withholding tax transaction for Thailand

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxWithholdTransExtensionTH.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdTransExtensionTH/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax transaction for Thailand</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[AccountingCurExpenseAmount](#AccountingCurExpenseAmount)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[AccountingCurUpdatedWithholdBaseAmt](#AccountingCurUpdatedWithholdBaseAmt)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[ExpenseLedgerDimension](#ExpenseLedgerDimension)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[HideInReports](#HideInReports)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[InvoiceCurExpenseAmount](#InvoiceCurExpenseAmount)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[InvoiceCurUpdatedWithholdBaseAmount](#InvoiceCurUpdatedWithholdBaseAmount)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[LedgerJournalTrans](#LedgerJournalTrans)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[ReceiptNumber](#ReceiptNumber)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[TaxWithholdTrans](#TaxWithholdTrans)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[TransCurExpenseAmount](#TransCurExpenseAmount)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[Relationship_ExpenseLedgerDimensionRelationshipId](#Relationship_ExpenseLedgerDimensionRelationshipId)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[Relationship_LedgerJournalTransRelationshipId](#Relationship_LedgerJournalTransRelationshipId)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[Relationship_TaxWithholdTransRelationshipId](#Relationship_TaxWithholdTransRelationshipId)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxWithholdTransExtensionTH.md" target="_blank">Miscellaneous/TaxWithholdTransExtensionTH</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdTransExtensionTH/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingCurExpenseAmount name="AccountingCurExpenseAmount">AccountingCurExpenseAmount</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurExpenseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AccountingCurUpdatedWithholdBaseAmt name="AccountingCurUpdatedWithholdBaseAmt">AccountingCurUpdatedWithholdBaseAmt</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Updated base for withholding tax in accounting currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurUpdatedWithholdBaseAmt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Updated base for withholding tax in accounting currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExpenseLedgerDimension name="ExpenseLedgerDimension">ExpenseLedgerDimension</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#HideInReports name="HideInReports">HideInReports</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideInReports attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceCurExpenseAmount name="InvoiceCurExpenseAmount">InvoiceCurExpenseAmount</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCurExpenseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceCurUpdatedWithholdBaseAmount name="InvoiceCurUpdatedWithholdBaseAmount">InvoiceCurUpdatedWithholdBaseAmount</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Updated base for withholding tax in invoice currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCurUpdatedWithholdBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Updated base for withholding tax in invoice currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LedgerJournalTrans name="LedgerJournalTrans">LedgerJournalTrans</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReceiptNumber name="ReceiptNumber">ReceiptNumber</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdTrans name="TaxWithholdTrans">TaxWithholdTrans</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransCurExpenseAmount name="TransCurExpenseAmount">TransCurExpenseAmount</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransCurExpenseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

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

### <a href=#Relationship_ExpenseLedgerDimensionRelationshipId name="Relationship_ExpenseLedgerDimensionRelationshipId">Relationship_ExpenseLedgerDimensionRelationshipId</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExpenseLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerJournalTransRelationshipId name="Relationship_LedgerJournalTransRelationshipId">Relationship_LedgerJournalTransRelationshipId</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.cdm.json/LedgerJournalTrans</a></td><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdTransRelationshipId name="Relationship_TaxWithholdTransRelationshipId">Relationship_TaxWithholdTransRelationshipId</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/TaxWithholdTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxWithholdTrans.cdm.json/TaxWithholdTrans</a></td><td><a href="../Transaction/TaxWithholdTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/TaxWithholdTransExtensionTH (this entity)  

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

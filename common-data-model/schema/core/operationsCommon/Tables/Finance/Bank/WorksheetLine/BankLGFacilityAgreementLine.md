---
title: BankLGFacilityAgreementLine in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Letter of guarantee facility agreement line in WorksheetLine(BankLGFacilityAgreementLine)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/BankLGFacilityAgreementLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankLGFacilityAgreementLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Letter of guarantee facility agreement line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[BankDocumentFacilityAgreementLine](#BankDocumentFacilityAgreementLine)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[CashMarginCalc](#CashMarginCalc)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[DecreaseValueCommissionCalc](#DecreaseValueCommissionCalc)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[ExtensionCommissionCalc](#ExtensionCommissionCalc)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[IncreaseValueCommissionCalc](#IncreaseValueCommissionCalc)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[IssuanceCommissionCalc](#IssuanceCommissionCalc)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[DataAreaId](#DataAreaId)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[Relationship_BankDocumentFacilityAgreementLineRelationshipId](#Relationship_BankDocumentFacilityAgreementLineRelationshipId)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[Relationship_CashMarginCalcRelationshipId](#Relationship_CashMarginCalcRelationshipId)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[Relationship_DecreaseValueCommissionCalcRelationshipId](#Relationship_DecreaseValueCommissionCalcRelationshipId)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[Relationship_ExtensionCommissionCalcRelationshipId](#Relationship_ExtensionCommissionCalcRelationshipId)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[Relationship_IncreaseValueCommissionCalcRelationshipId](#Relationship_IncreaseValueCommissionCalcRelationshipId)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[Relationship_IssuanceCommissionCalcRelationshipId](#Relationship_IssuanceCommissionCalcRelationshipId)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="BankLGFacilityAgreementLine.md" target="_blank">WorksheetLine/BankLGFacilityAgreementLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankLGFacilityAgreementLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankDocumentFacilityAgreementLine name="BankDocumentFacilityAgreementLine">BankDocumentFacilityAgreementLine</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankDocumentFacilityAgreementLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CashMarginCalc name="CashMarginCalc">CashMarginCalc</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashMarginCalc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DecreaseValueCommissionCalc name="DecreaseValueCommissionCalc">DecreaseValueCommissionCalc</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DecreaseValueCommissionCalc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExtensionCommissionCalc name="ExtensionCommissionCalc">ExtensionCommissionCalc</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtensionCommissionCalc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IncreaseValueCommissionCalc name="IncreaseValueCommissionCalc">IncreaseValueCommissionCalc</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncreaseValueCommissionCalc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IssuanceCommissionCalc name="IssuanceCommissionCalc">IssuanceCommissionCalc</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssuanceCommissionCalc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

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

### <a href=#Relationship_BankDocumentFacilityAgreementLineRelationshipId name="Relationship_BankDocumentFacilityAgreementLineRelationshipId">Relationship_BankDocumentFacilityAgreementLineRelationshipId</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankDocumentFacilityAgreementLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankDocumentFacilityAgreementLine.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/BankDocumentFacilityAgreementLine.cdm.json/BankDocumentFacilityAgreementLine</a></td><td><a href="BankDocumentFacilityAgreementLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CashMarginCalcRelationshipId name="Relationship_CashMarginCalcRelationshipId">Relationship_CashMarginCalcRelationshipId</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashMarginCalcRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankLGAmountCalculation.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/BankLGAmountCalculation.cdm.json/BankLGAmountCalculation</a></td><td><a href="BankLGAmountCalculation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DecreaseValueCommissionCalcRelationshipId name="Relationship_DecreaseValueCommissionCalcRelationshipId">Relationship_DecreaseValueCommissionCalcRelationshipId</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DecreaseValueCommissionCalcRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankLGAmountCalculation.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/BankLGAmountCalculation.cdm.json/BankLGAmountCalculation</a></td><td><a href="BankLGAmountCalculation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExtensionCommissionCalcRelationshipId name="Relationship_ExtensionCommissionCalcRelationshipId">Relationship_ExtensionCommissionCalcRelationshipId</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExtensionCommissionCalcRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankLGAmountCalculation.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/BankLGAmountCalculation.cdm.json/BankLGAmountCalculation</a></td><td><a href="BankLGAmountCalculation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IncreaseValueCommissionCalcRelationshipId name="Relationship_IncreaseValueCommissionCalcRelationshipId">Relationship_IncreaseValueCommissionCalcRelationshipId</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IncreaseValueCommissionCalcRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankLGAmountCalculation.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/BankLGAmountCalculation.cdm.json/BankLGAmountCalculation</a></td><td><a href="BankLGAmountCalculation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IssuanceCommissionCalcRelationshipId name="Relationship_IssuanceCommissionCalcRelationshipId">Relationship_IssuanceCommissionCalcRelationshipId</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IssuanceCommissionCalcRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BankLGAmountCalculation.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/BankLGAmountCalculation.cdm.json/BankLGAmountCalculation</a></td><td><a href="BankLGAmountCalculation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/BankLGFacilityAgreementLine (this entity)  

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

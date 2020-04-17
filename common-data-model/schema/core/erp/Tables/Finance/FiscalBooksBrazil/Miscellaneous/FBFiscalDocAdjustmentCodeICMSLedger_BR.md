---
title: FBFiscalDocAdjustmentCodeICMSLedger_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# FBFiscalDocAdjustmentCodeICMSLedger_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBFiscalDocAdjustmentCodeICMSLedger_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBFiscalDocAdjustmentCodeICMSLedger_BR.md" target="_blank">Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR</a>|
|[Company](#Company)||<a href="FBFiscalDocAdjustmentCodeICMSLedger_BR.md" target="_blank">Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR</a>|
|[FBFiscalDocumentAdjustmentCodeICMS_BR](#FBFiscalDocumentAdjustmentCodeICMS_BR)||<a href="FBFiscalDocAdjustmentCodeICMSLedger_BR.md" target="_blank">Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR</a>|
|[LedgerDimension](#LedgerDimension)||<a href="FBFiscalDocAdjustmentCodeICMSLedger_BR.md" target="_blank">Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR</a>|
|[TaxCode](#TaxCode)||<a href="FBFiscalDocAdjustmentCodeICMSLedger_BR.md" target="_blank">Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR</a>|
|[Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId](#Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId)||<a href="FBFiscalDocAdjustmentCodeICMSLedger_BR.md" target="_blank">Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR</a>|
|[Relationship_LedgerDimensionRelationshipId](#Relationship_LedgerDimensionRelationshipId)||<a href="FBFiscalDocAdjustmentCodeICMSLedger_BR.md" target="_blank">Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR</a>|
|[Relationship_TaxTableRelationshipId](#Relationship_TaxTableRelationshipId)||<a href="FBFiscalDocAdjustmentCodeICMSLedger_BR.md" target="_blank">Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBFiscalDocAdjustmentCodeICMSLedger_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.array**  
</details>

### <a href=#FBFiscalDocumentAdjustmentCodeICMS_BR name="FBFiscalDocumentAdjustmentCodeICMS_BR">FBFiscalDocumentAdjustmentCodeICMS_BR</a>

First included in: Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBFiscalDocumentAdjustmentCodeICMS_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode attribute are listed below.</summary>

**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId name="Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId">Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId</a>

First included in: Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">/core/erp/Tables/Finance/FiscalBooksBrazil/Main/FBFiscalDocumentAdjustmentCodeICMS_BR.cdm.json/FBFiscalDocumentAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionRelationshipId name="Relationship_LedgerDimensionRelationshipId">Relationship_LedgerDimensionRelationshipId</a>

First included in: Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxTableRelationshipId name="Relationship_TaxTableRelationshipId">Relationship_TaxTableRelationshipId</a>

First included in: Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxTable.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../../Tax/Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

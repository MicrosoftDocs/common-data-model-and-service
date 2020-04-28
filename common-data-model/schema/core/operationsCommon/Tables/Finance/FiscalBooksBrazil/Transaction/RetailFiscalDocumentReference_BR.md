---
title: RetailFiscalDocumentReference_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Retail fiscal document references

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/RetailFiscalDocumentReference_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFiscalDocumentReference_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail fiscal document references</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[AccountNum](#AccountNum)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[Channel](#Channel)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[FiscalDocumentNumber](#FiscalDocumentNumber)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[FiscalDocumentSeries](#FiscalDocumentSeries)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[FiscalDocumentSourceText](#FiscalDocumentSourceText)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[RefAccessKey](#RefAccessKey)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[RefDocumentDate](#RefDocumentDate)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[RefModel](#RefModel)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[RefNum](#RefNum)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[RefPrinterSerialNumber](#RefPrinterSerialNumber)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[RefReceiptNumber](#RefReceiptNumber)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[RefTerminalNumber](#RefTerminalNumber)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[ReplicationCounterFromOrigin](#ReplicationCounterFromOrigin)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[SourceRecId](#SourceRecId)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[SourceTableId](#SourceTableId)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[store](#store)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[terminal](#terminal)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[transactionId](#transactionId)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[Relationship_ExternalFiscalDocument_BRRelationshipId](#Relationship_ExternalFiscalDocument_BRRelationshipId)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[Relationship_FiscalDocument_BRRelationshipId](#Relationship_FiscalDocument_BRRelationshipId)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[Relationship_RetailFiscalDocument_BRRelationshipId](#Relationship_RetailFiscalDocument_BRRelationshipId)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailFiscalDocumentReference_BR.md" target="_blank">Transaction/RetailFiscalDocumentReference_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFiscalDocumentReference_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocumentNumber name="FiscalDocumentNumber">FiscalDocumentNumber</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSeries name="FiscalDocumentSeries">FiscalDocumentSeries</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSeries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSourceText name="FiscalDocumentSourceText">FiscalDocumentSourceText</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSourceText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefAccessKey name="RefAccessKey">RefAccessKey</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefAccessKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefDocumentDate name="RefDocumentDate">RefDocumentDate</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefDocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#RefModel name="RefModel">RefModel</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefNum name="RefNum">RefNum</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RefPrinterSerialNumber name="RefPrinterSerialNumber">RefPrinterSerialNumber</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefPrinterSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefReceiptNumber name="RefReceiptNumber">RefReceiptNumber</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefTerminalNumber name="RefTerminalNumber">RefTerminalNumber</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTerminalNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplicationCounterFromOrigin name="ReplicationCounterFromOrigin">ReplicationCounterFromOrigin</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplicationCounterFromOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceRecId name="SourceRecId">SourceRecId</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceTableId name="SourceTableId">SourceTableId</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#store name="store">store</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the store attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#terminal name="terminal">terminal</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#transactionId name="transactionId">transactionId</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

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

### <a href=#Relationship_ExternalFiscalDocument_BRRelationshipId name="Relationship_ExternalFiscalDocument_BRRelationshipId">Relationship_ExternalFiscalDocument_BRRelationshipId</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExternalFiscalDocument_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/ExternalFiscalDocument_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/ExternalFiscalDocument_BR.cdm.json/ExternalFiscalDocument_BR</a></td><td><a href="../Miscellaneous/ExternalFiscalDocument_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocument_BRRelationshipId name="Relationship_FiscalDocument_BRRelationshipId">Relationship_FiscalDocument_BRRelationshipId</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocument_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FiscalDocument_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocument_BR.cdm.json/FiscalDocument_BR</a></td><td><a href="FiscalDocument_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailFiscalDocument_BRRelationshipId name="Relationship_RetailFiscalDocument_BRRelationshipId">Relationship_RetailFiscalDocument_BRRelationshipId</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailFiscalDocument_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailFiscalDocument_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/RetailFiscalDocument_BR.cdm.json/RetailFiscalDocument_BR</a></td><td><a href="RetailFiscalDocument_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RetailFiscalDocumentReference_BR (this entity)  

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

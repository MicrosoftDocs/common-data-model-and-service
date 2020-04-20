---
title: RetailZReportTotalizerTaxTrans_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailZReportTotalizerTaxTrans_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailZReportTotalizerTaxTrans_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailZReportTotalizerTaxTrans_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[AdditionalFiscalMemoryIndex](#AdditionalFiscalMemoryIndex)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[CFOP](#CFOP)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[FiscalPrinterSerialNumber](#FiscalPrinterSerialNumber)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[FiscalValue](#FiscalValue)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[Origin](#Origin)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[ReplicationCounterFromOrigin](#ReplicationCounterFromOrigin)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[StoreId](#StoreId)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[TaxAmount](#TaxAmount)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[TaxationCode](#TaxationCode)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[TaxationOrigin](#TaxationOrigin)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[TaxBaseAmountExempt](#TaxBaseAmountExempt)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[TaxBaseAmountOther](#TaxBaseAmountOther)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[TaxCode](#TaxCode)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[TaxType](#TaxType)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[TaxValue](#TaxValue)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[TerminalId](#TerminalId)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[TotalizerName](#TotalizerName)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[ZReportNumber](#ZReportNumber)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[Relationship_RetailStoreTableRelationshipId](#Relationship_RetailStoreTableRelationshipId)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[Relationship_RetailTerminalTableRelationshipId](#Relationship_RetailTerminalTableRelationshipId)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[Relationship_RetailZReportTotalizer_BRRelationshipId](#Relationship_RetailZReportTotalizer_BRRelationshipId)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[Relationship_TaxTableRelationshipId](#Relationship_TaxTableRelationshipId)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailZReportTotalizerTaxTrans_BR.md" target="_blank">Transaction/RetailZReportTotalizerTaxTrans_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailZReportTotalizerTaxTrans_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdditionalFiscalMemoryIndex name="AdditionalFiscalMemoryIndex">AdditionalFiscalMemoryIndex</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdditionalFiscalMemoryIndex attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CFOP name="CFOP">CFOP</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalPrinterSerialNumber name="FiscalPrinterSerialNumber">FiscalPrinterSerialNumber</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalPrinterSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalValue name="FiscalValue">FiscalValue</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Origin name="Origin">Origin</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Origin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplicationCounterFromOrigin name="ReplicationCounterFromOrigin">ReplicationCounterFromOrigin</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplicationCounterFromOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StoreId name="StoreId">StoreId</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxationCode name="TaxationCode">TaxationCode</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxationOrigin name="TaxationOrigin">TaxationOrigin</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxBaseAmount name="TaxBaseAmount">TaxBaseAmount</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseAmountExempt name="TaxBaseAmountExempt">TaxBaseAmountExempt</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmountExempt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseAmountOther name="TaxBaseAmountOther">TaxBaseAmountOther</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmountOther attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxValue name="TaxValue">TaxValue</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TerminalId name="TerminalId">TerminalId</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalizerName name="TotalizerName">TotalizerName</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalizerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZReportNumber name="ZReportNumber">ZReportNumber</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZReportNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

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

### <a href=#Relationship_RetailStoreTableRelationshipId name="Relationship_RetailStoreTableRelationshipId">Relationship_RetailStoreTableRelationshipId</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailStoreTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailStoreTable.cdm.json/RetailStoreTable</a></td><td><a href="../Main/RetailStoreTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTerminalTableRelationshipId name="Relationship_RetailTerminalTableRelationshipId">Relationship_RetailTerminalTableRelationshipId</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTerminalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailTerminalTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailZReportTotalizer_BRRelationshipId name="Relationship_RetailZReportTotalizer_BRRelationshipId">Relationship_RetailZReportTotalizer_BRRelationshipId</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailZReportTotalizer_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailZReportTotalizer_BR.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailZReportTotalizer_BR.cdm.json/RetailZReportTotalizer_BR</a></td><td><a href="RetailZReportTotalizer_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxTableRelationshipId name="Relationship_TaxTableRelationshipId">Relationship_TaxTableRelationshipId</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../../../Finance/Tax/Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RetailZReportTotalizerTaxTrans_BR (this entity)  

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

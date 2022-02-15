---
title: InterCompanyEndpointActionPolicy in Group - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Intercompany configuration in Group(InterCompanyEndpointActionPolicy)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/InterCompanyEndpointActionPolicy.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InterCompanyEndpointActionPolicy/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intercompany configuration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[AutoPostCustPaym](#AutoPostCustPaym)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[CopyAutoSumFromOriginalCust](#CopyAutoSumFromOriginalCust)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[EditDiscount](#EditDiscount)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[EditPrice](#EditPrice)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[InterCompanyTradingPartner](#InterCompanyTradingPartner)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[InvoiceOriginalSales](#InvoiceOriginalSales)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[LedgerJournalNameIdCustPaym](#LedgerJournalNameIdCustPaym)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[MarkupAllocateAfter](#MarkupAllocateAfter)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[MarkupInventoriedOnly](#MarkupInventoriedOnly)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[PickinglistAutoPrint](#PickinglistAutoPrint)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[PostPurchInvoice](#PostPurchInvoice)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[PostSalesInvoice](#PostSalesInvoice)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[PriceDiscountSearch](#PriceDiscountSearch)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[PrintPurchInvoice](#PrintPurchInvoice)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[PrintPurchPackingslip](#PrintPurchPackingslip)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[PrintSalesInvoice](#PrintSalesInvoice)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[PrintSalesPackingslip](#PrintSalesPackingslip)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[SalesIdNumbering](#SalesIdNumbering)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[SalesIdNumberSequence](#SalesIdNumberSequence)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[UnitPriceEqualsCostPrice](#UnitPriceEqualsCostPrice)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[Relationship_InterCompanyTradingPartnerRelationshipId](#Relationship_InterCompanyTradingPartnerRelationshipId)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[Relationship_LedgerJournalNameRelationshipId](#Relationship_LedgerJournalNameRelationshipId)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|
|[Relationship_NumberSequenceTableRelationshipId](#Relationship_NumberSequenceTableRelationshipId)||<a href="InterCompanyEndpointActionPolicy.md" target="_blank">Group/InterCompanyEndpointActionPolicy</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InterCompanyEndpointActionPolicy/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AutoPostCustPaym name="AutoPostCustPaym">AutoPostCustPaym</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoPostCustPaym attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CopyAutoSumFromOriginalCust name="CopyAutoSumFromOriginalCust">CopyAutoSumFromOriginalCust</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CopyAutoSumFromOriginalCust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EditDiscount name="EditDiscount">EditDiscount</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EditDiscount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EditPrice name="EditPrice">EditPrice</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EditPrice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InterCompanyTradingPartner name="InterCompanyTradingPartner">InterCompanyTradingPartner</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterCompanyTradingPartner attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InvoiceOriginalSales name="InvoiceOriginalSales">InvoiceOriginalSales</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceOriginalSales attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LedgerJournalNameIdCustPaym name="LedgerJournalNameIdCustPaym">LedgerJournalNameIdCustPaym</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalNameIdCustPaym attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarkupAllocateAfter name="MarkupAllocateAfter">MarkupAllocateAfter</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupAllocateAfter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MarkupInventoriedOnly name="MarkupInventoriedOnly">MarkupInventoriedOnly</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupInventoriedOnly attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PickinglistAutoPrint name="PickinglistAutoPrint">PickinglistAutoPrint</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickinglistAutoPrint attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PostPurchInvoice name="PostPurchInvoice">PostPurchInvoice</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostPurchInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PostSalesInvoice name="PostSalesInvoice">PostSalesInvoice</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostSalesInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PriceDiscountSearch name="PriceDiscountSearch">PriceDiscountSearch</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceDiscountSearch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintPurchInvoice name="PrintPurchInvoice">PrintPurchInvoice</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintPurchInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintPurchPackingslip name="PrintPurchPackingslip">PrintPurchPackingslip</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintPurchPackingslip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintSalesInvoice name="PrintSalesInvoice">PrintSalesInvoice</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintSalesInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintSalesPackingslip name="PrintSalesPackingslip">PrintSalesPackingslip</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintSalesPackingslip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesIdNumbering name="SalesIdNumbering">SalesIdNumbering</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesIdNumbering attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesIdNumberSequence name="SalesIdNumberSequence">SalesIdNumberSequence</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number sequence code</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesIdNumberSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number sequence code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnitPriceEqualsCostPrice name="UnitPriceEqualsCostPrice">UnitPriceEqualsCostPrice</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPriceEqualsCostPrice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_InterCompanyTradingPartnerRelationshipId name="Relationship_InterCompanyTradingPartnerRelationshipId">Relationship_InterCompanyTradingPartnerRelationshipId</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InterCompanyTradingPartnerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InterCompanyTradingPartner.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/InterCompanyTradingPartner.cdm.json/InterCompanyTradingPartner</a></td><td><a href="InterCompanyTradingPartner.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalNameRelationshipId name="Relationship_LedgerJournalNameRelationshipId">Relationship_LedgerJournalNameRelationshipId</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountingFoundation/Group/LedgerJournalName.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/LedgerJournalName.cdm.json/LedgerJournalName</a></td><td><a href="../../../Finance/AccountingFoundation/Group/LedgerJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_NumberSequenceTableRelationshipId name="Relationship_NumberSequenceTableRelationshipId">Relationship_NumberSequenceTableRelationshipId</a>

First included in: Group/InterCompanyEndpointActionPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

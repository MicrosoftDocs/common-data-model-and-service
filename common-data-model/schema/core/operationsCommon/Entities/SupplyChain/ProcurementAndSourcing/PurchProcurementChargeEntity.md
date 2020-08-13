---
title: PurchProcurementChargeEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Procurement charge codes in ProcurementAndSourcing(PurchProcurementChargeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchProcurementChargeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement charge codes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DebitPostingMainAccountId](#DebitPostingMainAccountId)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[DebitPostingMainAccountIdDisplayValue](#DebitPostingMainAccountIdDisplayValue)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[DebitPostingType](#DebitPostingType)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[DebitPostingMethod](#DebitPostingMethod)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[ChargeCode](#ChargeCode)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[MaximumAllowedPurchaseOrderChargeAmount](#MaximumAllowedPurchaseOrderChargeAmount)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[SalesTaxItemGroupCode](#SalesTaxItemGroupCode)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[ChargeDescription](#ChargeDescription)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[CreditPostingMainAccountId](#CreditPostingMainAccountId)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[CreditPostingMainAccountIdDisplayValue](#CreditPostingMainAccountIdDisplayValue)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[CreditPostingType](#CreditPostingType)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[CreditPostingMethod](#CreditPostingMethod)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[WillIntrastatInvoiceValueIncludeChargeAmounts](#WillIntrastatInvoiceValueIncludeChargeAmounts)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[WillIntrastatStatisticalValueIncludeChargeAmounts](#WillIntrastatStatisticalValueIncludeChargeAmounts)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[WillPurchaseDocumentComparisonIncludeCharge](#WillPurchaseDocumentComparisonIncludeCharge)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[ChargeClassification](#ChargeClassification)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[TaxRateTypeName](#TaxRateTypeName)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[Relationship_DebitPostingMainAccountIdCombinationRelationshipId](#Relationship_DebitPostingMainAccountIdCombinationRelationshipId)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[Relationship_CreditPostingMainAccountIdCombinationRelationshipId](#Relationship_CreditPostingMainAccountIdCombinationRelationshipId)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[BackingTable_MarkupTableRelationshipId](#BackingTable_MarkupTableRelationshipId)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchProcurementChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementChargeEntity</a>|

### <a href=#DebitPostingMainAccountId name="DebitPostingMainAccountId">DebitPostingMainAccountId</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitPostingMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitPostingMainAccountIdDisplayValue name="DebitPostingMainAccountIdDisplayValue">DebitPostingMainAccountIdDisplayValue</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Debit account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitPostingMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Debit account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitPostingType name="DebitPostingType">DebitPostingType</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitPostingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitPostingMethod name="DebitPostingMethod">DebitPostingMethod</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitPostingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeCode name="ChargeCode">ChargeCode</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAllowedPurchaseOrderChargeAmount name="MaximumAllowedPurchaseOrderChargeAmount">MaximumAllowedPurchaseOrderChargeAmount</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAllowedPurchaseOrderChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxItemGroupCode name="SalesTaxItemGroupCode">SalesTaxItemGroupCode</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeDescription name="ChargeDescription">ChargeDescription</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditPostingMainAccountId name="CreditPostingMainAccountId">CreditPostingMainAccountId</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditPostingMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditPostingMainAccountIdDisplayValue name="CreditPostingMainAccountIdDisplayValue">CreditPostingMainAccountIdDisplayValue</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditPostingMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditPostingType name="CreditPostingType">CreditPostingType</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditPostingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditPostingMethod name="CreditPostingMethod">CreditPostingMethod</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditPostingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillIntrastatInvoiceValueIncludeChargeAmounts name="WillIntrastatInvoiceValueIncludeChargeAmounts">WillIntrastatInvoiceValueIncludeChargeAmounts</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillIntrastatInvoiceValueIncludeChargeAmounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillIntrastatStatisticalValueIncludeChargeAmounts name="WillIntrastatStatisticalValueIncludeChargeAmounts">WillIntrastatStatisticalValueIncludeChargeAmounts</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillIntrastatStatisticalValueIncludeChargeAmounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchaseDocumentComparisonIncludeCharge name="WillPurchaseDocumentComparisonIncludeCharge">WillPurchaseDocumentComparisonIncludeCharge</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchaseDocumentComparisonIncludeCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeClassification name="ChargeClassification">ChargeClassification</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeClassification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRateTypeName name="TaxRateTypeName">TaxRateTypeName</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax rate type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRateTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax rate type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DebitPostingMainAccountIdCombinationRelationshipId name="Relationship_DebitPostingMainAccountIdCombinationRelationshipId">Relationship_DebitPostingMainAccountIdCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DebitPostingMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CreditPostingMainAccountIdCombinationRelationshipId name="Relationship_CreditPostingMainAccountIdCombinationRelationshipId">Relationship_CreditPostingMainAccountIdCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CreditPostingMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_MarkupTableRelationshipId name="BackingTable_MarkupTableRelationshipId">BackingTable_MarkupTableRelationshipId</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MarkupTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupTable.cdm.json/MarkupTable</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchProcurementChargeEntity (this entity)  

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

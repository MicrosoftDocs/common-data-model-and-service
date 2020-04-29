---
title: PurchPurchaseRebateParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Vendor rebate parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseRebateParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor rebate parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WillInvoiceProcessingCreateRebateClaim](#WillInvoiceProcessingCreateRebateClaim)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[RebateWeekStartingDay](#RebateWeekStartingDay)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[RebateAccrualProcessingJournalNameId](#RebateAccrualProcessingJournalNameId)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[IsRebateInvoicePostedManually](#IsRebateInvoicePostedManually)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[RebateLiabilityProcurementProductCategoryRecId](#RebateLiabilityProcurementProductCategoryRecId)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[RebateLiabilityProcurementProductCategoryName](#RebateLiabilityProcurementProductCategoryName)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[AccruedLiabilityMainAccountId](#AccruedLiabilityMainAccountId)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[AccruedLiabilityMainAccountIdDisplayValue](#AccruedLiabilityMainAccountIdDisplayValue)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[InterimExpenseMainAccountId](#InterimExpenseMainAccountId)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[InterimExpenseMainAccountIdDisplayValue](#InterimExpenseMainAccountIdDisplayValue)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[Relationship_LedgerDimensionCombinationRelationshipId](#Relationship_LedgerDimensionCombinationRelationshipId)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[Relationship_OffsetLedgerDimensionCombinationRelationshipId](#Relationship_OffsetLedgerDimensionCombinationRelationshipId)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[Relationship_ProcurementProductCategoryRelationshipId](#Relationship_ProcurementProductCategoryRelationshipId)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[BackingTable_TAMVendRebateParametersRelationshipId](#BackingTable_TAMVendRebateParametersRelationshipId)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchPurchaseRebateParametersEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRebateParametersEntity</a>|

### <a href=#WillInvoiceProcessingCreateRebateClaim name="WillInvoiceProcessingCreateRebateClaim">WillInvoiceProcessingCreateRebateClaim</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInvoiceProcessingCreateRebateClaim attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateWeekStartingDay name="RebateWeekStartingDay">RebateWeekStartingDay</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateWeekStartingDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateAccrualProcessingJournalNameId name="RebateAccrualProcessingJournalNameId">RebateAccrualProcessingJournalNameId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateAccrualProcessingJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRebateInvoicePostedManually name="IsRebateInvoicePostedManually">IsRebateInvoicePostedManually</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRebateInvoicePostedManually attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateLiabilityProcurementProductCategoryRecId name="RebateLiabilityProcurementProductCategoryRecId">RebateLiabilityProcurementProductCategoryRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateLiabilityProcurementProductCategoryRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateLiabilityProcurementProductCategoryName name="RebateLiabilityProcurementProductCategoryName">RebateLiabilityProcurementProductCategoryName</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateLiabilityProcurementProductCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccruedLiabilityMainAccountId name="AccruedLiabilityMainAccountId">AccruedLiabilityMainAccountId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccruedLiabilityMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccruedLiabilityMainAccountIdDisplayValue name="AccruedLiabilityMainAccountIdDisplayValue">AccruedLiabilityMainAccountIdDisplayValue</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccruedLiabilityMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterimExpenseMainAccountId name="InterimExpenseMainAccountId">InterimExpenseMainAccountId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterimExpenseMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterimExpenseMainAccountIdDisplayValue name="InterimExpenseMainAccountIdDisplayValue">InterimExpenseMainAccountIdDisplayValue</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterimExpenseMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionCombinationRelationshipId name="Relationship_LedgerDimensionCombinationRelationshipId">Relationship_LedgerDimensionCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OffsetLedgerDimensionCombinationRelationshipId name="Relationship_OffsetLedgerDimensionCombinationRelationshipId">Relationship_OffsetLedgerDimensionCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProcurementProductCategoryRelationshipId name="Relationship_ProcurementProductCategoryRelationshipId">Relationship_ProcurementProductCategoryRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProcurementProductCategoryRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_TAMVendRebateParametersRelationshipId name="BackingTable_TAMVendRebateParametersRelationshipId">BackingTable_TAMVendRebateParametersRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TAMVendRebateParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/TAMVendRebateParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/TAMVendRebateParameters.cdm.json/TAMVendRebateParameters</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/TAMVendRebateParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRebateParametersEntity (this entity)  

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

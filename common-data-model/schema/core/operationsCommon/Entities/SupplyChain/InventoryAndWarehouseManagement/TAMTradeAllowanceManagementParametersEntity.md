---
title: TAMTradeAllowanceManagementParametersEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Trade allowance management parameters in InventoryAndWarehouseManagement(TAMTradeAllowanceManagementParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trade allowance management parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DeductionLedgerJournalName](#DeductionLedgerJournalName)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[DefaultCustomerHierarchyName](#DefaultCustomerHierarchyName)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[OneTimePromotionTradeAllowanceTemplateId](#OneTimePromotionTradeAllowanceTemplateId)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[WillFundAnalyticsIncludeClosedTradeAllowanceAgreement](#WillFundAnalyticsIncludeClosedTradeAllowanceAgreement)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[LumpSumExpenseMainAccountId](#LumpSumExpenseMainAccountId)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[LumpSumProcurementCategoryId](#LumpSumProcurementCategoryId)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[TradeAllowanceAgreementStatus](#TradeAllowanceAgreementStatus)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[DefaultSalesRebateProgramTypeId](#DefaultSalesRebateProgramTypeId)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[LumpSumExpenseMainAccountIdDisplayValue](#LumpSumExpenseMainAccountIdDisplayValue)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[LumpSumProcurementCategoryName](#LumpSumProcurementCategoryName)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[Relationship_LumpSumExpenseAccountCombinationRelationshipId](#Relationship_LumpSumExpenseAccountCombinationRelationshipId)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[BackingTable_TAMPromotionParametersRelationshipId](#BackingTable_TAMPromotionParametersRelationshipId)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TAMTradeAllowanceManagementParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity</a>|

### <a href=#DeductionLedgerJournalName name="DeductionLedgerJournalName">DeductionLedgerJournalName</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionLedgerJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustomerHierarchyName name="DefaultCustomerHierarchyName">DefaultCustomerHierarchyName</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustomerHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OneTimePromotionTradeAllowanceTemplateId name="OneTimePromotionTradeAllowanceTemplateId">OneTimePromotionTradeAllowanceTemplateId</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OneTimePromotionTradeAllowanceTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillFundAnalyticsIncludeClosedTradeAllowanceAgreement name="WillFundAnalyticsIncludeClosedTradeAllowanceAgreement">WillFundAnalyticsIncludeClosedTradeAllowanceAgreement</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillFundAnalyticsIncludeClosedTradeAllowanceAgreement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LumpSumExpenseMainAccountId name="LumpSumExpenseMainAccountId">LumpSumExpenseMainAccountId</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LumpSumExpenseMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LumpSumProcurementCategoryId name="LumpSumProcurementCategoryId">LumpSumProcurementCategoryId</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LumpSumProcurementCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAllowanceAgreementStatus name="TradeAllowanceAgreementStatus">TradeAllowanceAgreementStatus</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAllowanceAgreementStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesRebateProgramTypeId name="DefaultSalesRebateProgramTypeId">DefaultSalesRebateProgramTypeId</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesRebateProgramTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LumpSumExpenseMainAccountIdDisplayValue name="LumpSumExpenseMainAccountIdDisplayValue">LumpSumExpenseMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LumpSumExpenseMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LumpSumProcurementCategoryName name="LumpSumProcurementCategoryName">LumpSumProcurementCategoryName</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LumpSumProcurementCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LumpSumExpenseAccountCombinationRelationshipId name="Relationship_LumpSumExpenseAccountCombinationRelationshipId">Relationship_LumpSumExpenseAccountCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LumpSumExpenseAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_TAMPromotionParametersRelationshipId name="BackingTable_TAMPromotionParametersRelationshipId">BackingTable_TAMPromotionParametersRelationshipId</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TAMPromotionParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/TAMPromotionParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/TAMPromotionParameters.cdm.json/TAMPromotionParameters</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/TAMPromotionParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/TAMTradeAllowanceManagementParametersEntity (this entity)  

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

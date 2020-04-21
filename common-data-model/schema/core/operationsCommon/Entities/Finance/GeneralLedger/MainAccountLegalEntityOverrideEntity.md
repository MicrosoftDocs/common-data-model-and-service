---
title: MainAccountLegalEntityOverrideEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# MainAccountLegalEntityOverrideEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/MainAccountLegalEntityOverrideEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[MainAccountId](#MainAccountId)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[ChartOfAccounts](#ChartOfAccounts)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[LegalEntityId](#LegalEntityId)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[MainAccountRecId](#MainAccountRecId)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[ChartOfAccountsRecId](#ChartOfAccountsRecId)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[LegalEntityRecId](#LegalEntityRecId)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[AutoAllocate](#AutoAllocate)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[FixedDimensions](#FixedDimensions)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[FixedDimensionsDisplayValue](#FixedDimensionsDisplayValue)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[SalesTaxCode](#SalesTaxCode)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[SalesTaxDirection](#SalesTaxDirection)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[IsExempt](#IsExempt)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[ItemSalesTaxGroup](#ItemSalesTaxGroup)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[ItemSalesTaxGroupHeadingLegalEntity](#ItemSalesTaxGroupHeadingLegalEntity)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[TaxTableLegalEntity](#TaxTableLegalEntity)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[ValidateSalesTax](#ValidateSalesTax)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[ActiveFrom](#ActiveFrom)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[ActiveTo](#ActiveTo)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[IsSuspended](#IsSuspended)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[ExchangeAdjustmentRateType](#ExchangeAdjustmentRateType)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[ReportingExchangeAdjustmentRateType](#ReportingExchangeAdjustmentRateType)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[Relationship_ExchangeRateTypeRelationshipId](#Relationship_ExchangeRateTypeRelationshipId)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[Relationship_ReportingExchangeRateTypeRelationshipId](#Relationship_ReportingExchangeRateTypeRelationshipId)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|
|[BackingTable_MainAccountLegalEntityRelationshipId](#BackingTable_MainAccountLegalEntityRelationshipId)||<a href="MainAccountLegalEntityOverrideEntity.md" target="_blank">GeneralLedger/MainAccountLegalEntityOverrideEntity</a>|

### <a href=#MainAccountId name="MainAccountId">MainAccountId</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChartOfAccounts name="ChartOfAccounts">ChartOfAccounts</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChartOfAccounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountRecId name="MainAccountRecId">MainAccountRecId</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChartOfAccountsRecId name="ChartOfAccountsRecId">ChartOfAccountsRecId</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChartOfAccountsRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityRecId name="LegalEntityRecId">LegalEntityRecId</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoAllocate name="AutoAllocate">AutoAllocate</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoAllocate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedDimensions name="FixedDimensions">FixedDimensions</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedDimensions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedDimensionsDisplayValue name="FixedDimensionsDisplayValue">FixedDimensionsDisplayValue</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedDimensionsDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxCode name="SalesTaxCode">SalesTaxCode</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxDirection name="SalesTaxDirection">SalesTaxDirection</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxDirection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExempt name="IsExempt">IsExempt</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExempt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroup name="ItemSalesTaxGroup">ItemSalesTaxGroup</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroupHeadingLegalEntity name="ItemSalesTaxGroupHeadingLegalEntity">ItemSalesTaxGroupHeadingLegalEntity</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroupHeadingLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxTableLegalEntity name="TaxTableLegalEntity">TaxTableLegalEntity</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTableLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateSalesTax name="ValidateSalesTax">ValidateSalesTax</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveFrom name="ActiveFrom">ActiveFrom</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveTo name="ActiveTo">ActiveTo</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSuspended name="IsSuspended">IsSuspended</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSuspended attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeAdjustmentRateType name="ExchangeAdjustmentRateType">ExchangeAdjustmentRateType</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeAdjustmentRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingExchangeAdjustmentRateType name="ReportingExchangeAdjustmentRateType">ReportingExchangeAdjustmentRateType</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingExchangeAdjustmentRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ExchangeRateTypeRelationshipId name="Relationship_ExchangeRateTypeRelationshipId">Relationship_ExchangeRateTypeRelationshipId</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExchangeRateTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingExchangeRateTypeRelationshipId name="Relationship_ReportingExchangeRateTypeRelationshipId">Relationship_ReportingExchangeRateTypeRelationshipId</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingExchangeRateTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_MainAccountLegalEntityRelationshipId name="BackingTable_MainAccountLegalEntityRelationshipId">BackingTable_MainAccountLegalEntityRelationshipId</a>

First included in: GeneralLedger/MainAccountLegalEntityOverrideEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MainAccountLegalEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FinancialDimensions/Main/MainAccountLegalEntity.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/MainAccountLegalEntity.cdm.json/MainAccountLegalEntity</a></td><td><a href="../../../Tables/Finance/FinancialDimensions/Main/MainAccountLegalEntity.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

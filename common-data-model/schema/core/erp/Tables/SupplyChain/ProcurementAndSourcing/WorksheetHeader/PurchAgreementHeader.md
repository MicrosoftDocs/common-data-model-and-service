---
title: PurchAgreementHeader - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# PurchAgreementHeader

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchAgreementHeader.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchAgreementHeader/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[AgreementClassification](#AgreementClassification)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[AgreementState](#AgreementState)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Currency](#Currency)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[DefaultAgreementLineEffectiveDate](#DefaultAgreementLineEffectiveDate)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[DefaultAgreementLineExpirationDate](#DefaultAgreementLineExpirationDate)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[DefaultAgreementLineType](#DefaultAgreementLineType)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[DefaultDimension](#DefaultDimension)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[DocumentExternalReference](#DocumentExternalReference)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[DocumentTitle](#DocumentTitle)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[EarliestLineEffectiveDate](#EarliestLineEffectiveDate)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[InterCompanySkipUpdate](#InterCompanySkipUpdate)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[IsDeleted](#IsDeleted)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Language](#Language)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[LatestLineExpirationDate](#LatestLineExpirationDate)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Originator](#Originator)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Relationship_AgreementClassificationRelationshipId](#Relationship_AgreementClassificationRelationshipId)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Relationship_LanguageTableRelationshipId](#Relationship_LanguageTableRelationshipId)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Relationship_OriginatorRelationshipId](#Relationship_OriginatorRelationshipId)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[BuyingLegalEntity](#BuyingLegalEntity)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[InterestBasedOnCEB_PSN](#InterestBasedOnCEB_PSN)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[MaximumAmount_PSN](#MaximumAmount_PSN)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[MinimumAmount_PSN](#MinimumAmount_PSN)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[ParentPurchAgreementID_PSN](#ParentPurchAgreementID_PSN)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[ProcurementClassification_PSN](#ProcurementClassification_PSN)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[PurchAgreementType_PSN](#PurchAgreementType_PSN)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[PurchNumberSequence](#PurchNumberSequence)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Purpose_PSN](#Purpose_PSN)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Renewable_PSN](#Renewable_PSN)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[VendAccount](#VendAccount)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[VendorDataAreaId](#VendorDataAreaId)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[WorkflowStatus_PSN](#WorkflowStatus_PSN)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[PrimaryResponsibleWorker](#PrimaryResponsibleWorker)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[SecondaryResponsibleWorker](#SecondaryResponsibleWorker)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[MatchingPolicy](#MatchingPolicy)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Relationship_CompanyInfoRelationshipId](#Relationship_CompanyInfoRelationshipId)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="PurchAgreementHeader.md" target="_blank">WorksheetHeader/PurchAgreementHeader</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchAgreementHeader/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AgreementClassification name="AgreementClassification">AgreementClassification</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementClassification attribute are listed below.</summary>

</details>

### <a href=#AgreementState name="AgreementState">AgreementState</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultAgreementLineEffectiveDate name="DefaultAgreementLineEffectiveDate">DefaultAgreementLineEffectiveDate</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultAgreementLineEffectiveDate attribute are listed below.</summary>

</details>

### <a href=#DefaultAgreementLineExpirationDate name="DefaultAgreementLineExpirationDate">DefaultAgreementLineExpirationDate</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultAgreementLineExpirationDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DefaultAgreementLineType name="DefaultAgreementLineType">DefaultAgreementLineType</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultAgreementLineType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocumentExternalReference name="DocumentExternalReference">DocumentExternalReference</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentExternalReference attribute are listed below.</summary>

</details>

### <a href=#DocumentTitle name="DocumentTitle">DocumentTitle</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentTitle attribute are listed below.</summary>

</details>

### <a href=#EarliestLineEffectiveDate name="EarliestLineEffectiveDate">EarliestLineEffectiveDate</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EarliestLineEffectiveDate attribute are listed below.</summary>

**is.readOnly**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InterCompanySkipUpdate name="InterCompanySkipUpdate">InterCompanySkipUpdate</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterCompanySkipUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsDeleted name="IsDeleted">IsDeleted</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeleted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Language name="Language">Language</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Language attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LatestLineExpirationDate name="LatestLineExpirationDate">LatestLineExpirationDate</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LatestLineExpirationDate attribute are listed below.</summary>

**is.readOnly**  
</details>

### <a href=#Originator name="Originator">Originator</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Originator attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_AgreementClassificationRelationshipId name="Relationship_AgreementClassificationRelationshipId">Relationship_AgreementClassificationRelationshipId</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AgreementClassificationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AgreementClassification.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/Group/AgreementClassification.cdm.json/AgreementClassification</a></td><td><a href="../Group/AgreementClassification.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LanguageTableRelationshipId name="Relationship_LanguageTableRelationshipId">Relationship_LanguageTableRelationshipId</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LanguageTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Group/LanguageTable.cdm.json/LanguageTable</a></td><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginatorRelationshipId name="Relationship_OriginatorRelationshipId">Relationship_OriginatorRelationshipId</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginatorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/DirPerson.md" target="_blank">/core/erp/Tables/Common/GAB/Main/DirPerson.cdm.json/DirPerson</a></td><td><a href="../../../Common/GAB/Main/DirPerson.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyingLegalEntity name="BuyingLegalEntity">BuyingLegalEntity</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyingLegalEntity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InterestBasedOnCEB_PSN name="InterestBasedOnCEB_PSN">InterestBasedOnCEB_PSN</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestBasedOnCEB_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaximumAmount_PSN name="MaximumAmount_PSN">MaximumAmount_PSN</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAmount_PSN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MinimumAmount_PSN name="MinimumAmount_PSN">MinimumAmount_PSN</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumAmount_PSN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ParentPurchAgreementID_PSN name="ParentPurchAgreementID_PSN">ParentPurchAgreementID_PSN</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentPurchAgreementID_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProcurementClassification_PSN name="ProcurementClassification_PSN">ProcurementClassification_PSN</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementClassification_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchAgreementType_PSN name="PurchAgreementType_PSN">PurchAgreementType_PSN</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchAgreementType_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PurchNumberSequence name="PurchNumberSequence">PurchNumberSequence</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchNumberSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Purpose_PSN name="Purpose_PSN">Purpose_PSN</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purpose_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Renewable_PSN name="Renewable_PSN">Renewable_PSN</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Renewable_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendAccount name="VendAccount">VendAccount</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorDataAreaId name="VendorDataAreaId">VendorDataAreaId</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowStatus_PSN name="WorkflowStatus_PSN">WorkflowStatus_PSN</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowStatus_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrimaryResponsibleWorker name="PrimaryResponsibleWorker">PrimaryResponsibleWorker</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryResponsibleWorker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SecondaryResponsibleWorker name="SecondaryResponsibleWorker">SecondaryResponsibleWorker</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryResponsibleWorker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MatchingPolicy name="MatchingPolicy">MatchingPolicy</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchingPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_CompanyInfoRelationshipId name="Relationship_CompanyInfoRelationshipId">Relationship_CompanyInfoRelationshipId</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyInfoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: WorksheetHeader/PurchAgreementHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/erp/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

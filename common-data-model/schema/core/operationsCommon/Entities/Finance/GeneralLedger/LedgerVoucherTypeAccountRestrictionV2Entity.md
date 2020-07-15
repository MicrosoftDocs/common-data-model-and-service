---
title: LedgerVoucherTypeAccountRestrictionV2Entity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Restriction type for voucher V2 in GeneralLedger(LedgerVoucherTypeAccountRestrictionV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Restriction type for voucher V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DefaultApproverRecId](#DefaultApproverRecId)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[JournalName](#JournalName)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[DefaultPreparedByWorkerRecId](#DefaultPreparedByWorkerRecId)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[IsDefaultType](#IsDefaultType)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[Description](#Description)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[VoucherType](#VoucherType)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[LedgerPrintLayoutGroupRecId](#LedgerPrintLayoutGroupRecId)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[VoucherTypeNumber](#VoucherTypeNumber)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[NumberSequenceTableRecId](#NumberSequenceTableRecId)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[Priority](#Priority)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[DefaultApprovedBy](#DefaultApprovedBy)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[DefaultedPreparedBy](#DefaultedPreparedBy)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[LedgerPrintLayoutGroup](#LedgerPrintLayoutGroup)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[NumberSequenceCode](#NumberSequenceCode)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[NumberSequenceScope](#NumberSequenceScope)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[AccountRelation](#AccountRelation)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[AccountType](#AccountType)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[AccountCode](#AccountCode)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[LedgerDimension](#LedgerDimension)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[LedgerDimensionDisplayValue](#LedgerDimensionDisplayValue)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[RestrictionType](#RestrictionType)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[NotNullableLedgerDimensionDisplayValue](#NotNullableLedgerDimensionDisplayValue)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[Relationship_LedgerDimensionCombinationRelationshipId](#Relationship_LedgerDimensionCombinationRelationshipId)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[BackingTable_LedgerVoucherType_CNRelationshipId](#BackingTable_LedgerVoucherType_CNRelationshipId)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerVoucherTypeAccountRestrictionV2Entity.md" target="_blank">GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity</a>|

### <a href=#DefaultApproverRecId name="DefaultApproverRecId">DefaultApproverRecId</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultApproverRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalName name="JournalName">JournalName</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPreparedByWorkerRecId name="DefaultPreparedByWorkerRecId">DefaultPreparedByWorkerRecId</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPreparedByWorkerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultType name="IsDefaultType">IsDefaultType</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherType name="VoucherType">VoucherType</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerPrintLayoutGroupRecId name="LedgerPrintLayoutGroupRecId">LedgerPrintLayoutGroupRecId</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPrintLayoutGroupRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherTypeNumber name="VoucherTypeNumber">VoucherTypeNumber</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherTypeNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceTableRecId name="NumberSequenceTableRecId">NumberSequenceTableRecId</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceTableRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Priority name="Priority">Priority</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Priority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultApprovedBy name="DefaultApprovedBy">DefaultApprovedBy</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultApprovedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultedPreparedBy name="DefaultedPreparedBy">DefaultedPreparedBy</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultedPreparedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerPrintLayoutGroup name="LedgerPrintLayoutGroup">LedgerPrintLayoutGroup</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPrintLayoutGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceCode name="NumberSequenceCode">NumberSequenceCode</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceScope name="NumberSequenceScope">NumberSequenceScope</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceScope attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountRelation name="AccountRelation">AccountRelation</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCode name="AccountCode">AccountCode</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionDisplayValue name="LedgerDimensionDisplayValue">LedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RestrictionType name="RestrictionType">RestrictionType</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestrictionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NotNullableLedgerDimensionDisplayValue name="NotNullableLedgerDimensionDisplayValue">NotNullableLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotNullableLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionCombinationRelationshipId name="Relationship_LedgerDimensionCombinationRelationshipId">Relationship_LedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

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

### <a href=#BackingTable_LedgerVoucherType_CNRelationshipId name="BackingTable_LedgerVoucherType_CNRelationshipId">BackingTable_LedgerVoucherType_CNRelationshipId</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerVoucherType_CNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Group/LedgerVoucherType_CN.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerVoucherType_CN.cdm.json/LedgerVoucherType_CN</a></td><td><a href="../../../Tables/Finance/Ledger/Group/LedgerVoucherType_CN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/LedgerVoucherTypeAccountRestrictionV2Entity (this entity)  

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

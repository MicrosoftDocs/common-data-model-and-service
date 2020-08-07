---
title: JmgPayAgreementLineEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Pay agreement lines in ProductionControl(JmgPayAgreementLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgPayAgreementLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pay agreement lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AbsenceIndirectTimeAndAttendanceActivityId](#AbsenceIndirectTimeAndAttendanceActivityId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[ProjectActivityNumber](#ProjectActivityNumber)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[WillCancelPayment](#WillCancelPayment)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[RequiredCertificateType](#RequiredCertificateType)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[SwitchCodeIndirectTimeAndAttendanceActivityId](#SwitchCodeIndirectTimeAndAttendanceActivityId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[PrimaryPayQuantityFactor](#PrimaryPayQuantityFactor)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[FromAgreementDate](#FromAgreementDate)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[AbsenceCode](#AbsenceCode)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[JobPayRateMethod](#JobPayRateMethod)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[MaximumSeniorityUnit](#MaximumSeniorityUnit)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[OnCallIndirectTimeAndAttendanceActivityId](#OnCallIndirectTimeAndAttendanceActivityId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[PayAgreementCode](#PayAgreementCode)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[ConstantPayQuantity](#ConstantPayQuantity)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[PrimaryPayTypeCode](#PrimaryPayTypeCode)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[PayAgreementCountUnitId](#PayAgreementCountUnitId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[WageType](#WageType)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[TimeProfileId](#TimeProfileId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[ProfileStartCode](#ProfileStartCode)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[ProjectId](#ProjectId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[RoundOffSeconds](#RoundOffSeconds)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[WillRoundOffQuantityBeforeMultiplyingFactor](#WillRoundOffQuantityBeforeMultiplyingFactor)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[PayQuantityRoundingType](#PayQuantityRoundingType)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[RouteOperationId](#RouteOperationId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[SecondaryPayQuantityFactor](#SecondaryPayQuantityFactor)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[SecondaryPayTypeCode](#SecondaryPayTypeCode)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[MinimumSeniorityUnit](#MinimumSeniorityUnit)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[MaximumSeniority](#MaximumSeniority)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[MinimumSeniority](#MinimumSeniority)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[RequiredSkillId](#RequiredSkillId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[PayAgreementExceptionId](#PayAgreementExceptionId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[FromAgreementTime](#FromAgreementTime)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[RecordId](#RecordId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[IsInvertedSign](#IsInvertedSign)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[ToAgreementTime](#ToAgreementTime)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[ToAgreementDate](#ToAgreementDate)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[IsPayQuantityFixed](#IsPayQuantityFixed)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[IsPaidTimeRequired](#IsPaidTimeRequired)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[Relationship_JmgPayAgreementEntityRelationshipId](#Relationship_JmgPayAgreementEntityRelationshipId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[Relationship_JmgPayTypeEntityRelationshipId](#Relationship_JmgPayTypeEntityRelationshipId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[Relationship_RouteOperationEntityRelationshipId](#Relationship_RouteOperationEntityRelationshipId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[BackingTable_JmgPayAgreementLineRelationshipId](#BackingTable_JmgPayAgreementLineRelationshipId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgPayAgreementLineEntity.md" target="_blank">ProductionControl/JmgPayAgreementLineEntity</a>|

### <a href=#AbsenceIndirectTimeAndAttendanceActivityId name="AbsenceIndirectTimeAndAttendanceActivityId">AbsenceIndirectTimeAndAttendanceActivityId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbsenceIndirectTimeAndAttendanceActivityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectActivityNumber name="ProjectActivityNumber">ProjectActivityNumber</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCancelPayment name="WillCancelPayment">WillCancelPayment</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCancelPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredCertificateType name="RequiredCertificateType">RequiredCertificateType</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredCertificateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SwitchCodeIndirectTimeAndAttendanceActivityId name="SwitchCodeIndirectTimeAndAttendanceActivityId">SwitchCodeIndirectTimeAndAttendanceActivityId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SwitchCodeIndirectTimeAndAttendanceActivityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryPayQuantityFactor name="PrimaryPayQuantityFactor">PrimaryPayQuantityFactor</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryPayQuantityFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromAgreementDate name="FromAgreementDate">FromAgreementDate</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromAgreementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AbsenceCode name="AbsenceCode">AbsenceCode</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbsenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobPayRateMethod name="JobPayRateMethod">JobPayRateMethod</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobPayRateMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumSeniorityUnit name="MaximumSeniorityUnit">MaximumSeniorityUnit</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumSeniorityUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnCallIndirectTimeAndAttendanceActivityId name="OnCallIndirectTimeAndAttendanceActivityId">OnCallIndirectTimeAndAttendanceActivityId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnCallIndirectTimeAndAttendanceActivityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayAgreementCode name="PayAgreementCode">PayAgreementCode</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayAgreementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstantPayQuantity name="ConstantPayQuantity">ConstantPayQuantity</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstantPayQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryPayTypeCode name="PrimaryPayTypeCode">PrimaryPayTypeCode</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryPayTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayAgreementCountUnitId name="PayAgreementCountUnitId">PayAgreementCountUnitId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayAgreementCountUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WageType name="WageType">WageType</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WageType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileId name="TimeProfileId">TimeProfileId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileStartCode name="ProfileStartCode">ProfileStartCode</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileStartCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundOffSeconds name="RoundOffSeconds">RoundOffSeconds</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOffSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRoundOffQuantityBeforeMultiplyingFactor name="WillRoundOffQuantityBeforeMultiplyingFactor">WillRoundOffQuantityBeforeMultiplyingFactor</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRoundOffQuantityBeforeMultiplyingFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayQuantityRoundingType name="PayQuantityRoundingType">PayQuantityRoundingType</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayQuantityRoundingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationId name="RouteOperationId">RouteOperationId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryPayQuantityFactor name="SecondaryPayQuantityFactor">SecondaryPayQuantityFactor</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryPayQuantityFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryPayTypeCode name="SecondaryPayTypeCode">SecondaryPayTypeCode</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryPayTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumSeniorityUnit name="MinimumSeniorityUnit">MinimumSeniorityUnit</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumSeniorityUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumSeniority name="MaximumSeniority">MaximumSeniority</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumSeniority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumSeniority name="MinimumSeniority">MinimumSeniority</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumSeniority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredSkillId name="RequiredSkillId">RequiredSkillId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredSkillId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayAgreementExceptionId name="PayAgreementExceptionId">PayAgreementExceptionId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayAgreementExceptionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromAgreementTime name="FromAgreementTime">FromAgreementTime</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromAgreementTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecordId name="RecordId">RecordId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvertedSign name="IsInvertedSign">IsInvertedSign</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvertedSign attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToAgreementTime name="ToAgreementTime">ToAgreementTime</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToAgreementTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToAgreementDate name="ToAgreementDate">ToAgreementDate</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToAgreementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPayQuantityFixed name="IsPayQuantityFixed">IsPayQuantityFixed</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPayQuantityFixed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPaidTimeRequired name="IsPaidTimeRequired">IsPaidTimeRequired</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPaidTimeRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JmgPayAgreementEntityRelationshipId name="Relationship_JmgPayAgreementEntityRelationshipId">Relationship_JmgPayAgreementEntityRelationshipId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JmgPayAgreementEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_JmgPayTypeEntityRelationshipId name="Relationship_JmgPayTypeEntityRelationshipId">Relationship_JmgPayTypeEntityRelationshipId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JmgPayTypeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RouteOperationEntityRelationshipId name="Relationship_RouteOperationEntityRelationshipId">Relationship_RouteOperationEntityRelationshipId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RouteOperationEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_JmgPayAgreementLineRelationshipId name="BackingTable_JmgPayAgreementLineRelationshipId">BackingTable_JmgPayAgreementLineRelationshipId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgPayAgreementLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Main/JmgPayAgreementLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/JmgPayAgreementLine.cdm.json/JmgPayAgreementLine</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Main/JmgPayAgreementLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgPayAgreementLineEntity (this entity)  

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

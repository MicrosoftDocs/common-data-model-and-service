---
title: ProjGrantV2Entity in ProjectManagementAndAccounting - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Project grants V2 in ProjectManagementAndAccounting(ProjGrantV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjGrantV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project grants V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ActualAwardDate](#ActualAwardDate)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[ActualExpirationDate](#ActualExpirationDate)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[ActualStartDate](#ActualStartDate)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[ApplicationDueDate](#ApplicationDueDate)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[ApplicationSubmittedDate](#ApplicationSubmittedDate)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[AwardedAmount](#AwardedAmount)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[BoardApprovalDate](#BoardApprovalDate)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[CFDAId](#CFDAId)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[CustAccount](#CustAccount)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[EstimatedAwardDate](#EstimatedAwardDate)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[FederalMandate](#FederalMandate)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[GrantApplicationId](#GrantApplicationId)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[GrantDescription](#GrantDescription)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[GrantId](#GrantId)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[GrantManagerWorker](#GrantManagerWorker)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[GrantMatchingComments](#GrantMatchingComments)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[GrantName](#GrantName)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[GrantParentId](#GrantParentId)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[GrantPurpose](#GrantPurpose)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[GrantStatus](#GrantStatus)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[MatchingAmount](#MatchingAmount)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[MatchingPercentage](#MatchingPercentage)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[OrganizationUnitId](#OrganizationUnitId)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[PassThrough](#PassThrough)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[ProjGrantMatching](#ProjGrantMatching)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[ProjGrantorType](#ProjGrantorType)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[ProjGrantType](#ProjGrantType)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[ProjLocalTrackingId](#ProjLocalTrackingId)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[RejectionNotification](#RejectionNotification)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[RenewalActionDate](#RenewalActionDate)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[RequestedAmount](#RequestedAmount)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[StateMandate](#StateMandate)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[SubGrantor](#SubGrantor)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[WorkerContact](#WorkerContact)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[CFDA](#CFDA)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[GrantorAgency](#GrantorAgency)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[GrantManagerWorker_PersonnelNumber](#GrantManagerWorker_PersonnelNumber)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[ProjGrantMatching_MatchingTypeCode](#ProjGrantMatching_MatchingTypeCode)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[ProjGrantorType_GrantorType](#ProjGrantorType_GrantorType)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[ProjGrantType_GrantType](#ProjGrantType_GrantType)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[WorkerContact_PersonnelNumber](#WorkerContact_PersonnelNumber)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[BackingTable_ProjGrantRelationshipId](#BackingTable_ProjGrantRelationshipId)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjGrantV2Entity.md" target="_blank">ProjectManagementAndAccounting/ProjGrantV2Entity</a>|

### <a href=#ActualAwardDate name="ActualAwardDate">ActualAwardDate</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualAwardDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualExpirationDate name="ActualExpirationDate">ActualExpirationDate</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualStartDate name="ActualStartDate">ActualStartDate</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicationDueDate name="ApplicationDueDate">ApplicationDueDate</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationDueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicationSubmittedDate name="ApplicationSubmittedDate">ApplicationSubmittedDate</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationSubmittedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AwardedAmount name="AwardedAmount">AwardedAmount</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AwardedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BoardApprovalDate name="BoardApprovalDate">BoardApprovalDate</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BoardApprovalDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDAId name="CFDAId">CFDAId</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDAId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccount name="CustAccount">CustAccount</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedAwardDate name="EstimatedAwardDate">EstimatedAwardDate</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedAwardDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FederalMandate name="FederalMandate">FederalMandate</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FederalMandate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantApplicationId name="GrantApplicationId">GrantApplicationId</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantApplicationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantDescription name="GrantDescription">GrantDescription</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantId name="GrantId">GrantId</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantManagerWorker name="GrantManagerWorker">GrantManagerWorker</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantManagerWorker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantMatchingComments name="GrantMatchingComments">GrantMatchingComments</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantMatchingComments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantName name="GrantName">GrantName</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantParentId name="GrantParentId">GrantParentId</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantParentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantPurpose name="GrantPurpose">GrantPurpose</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantStatus name="GrantStatus">GrantStatus</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MatchingAmount name="MatchingAmount">MatchingAmount</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchingAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MatchingPercentage name="MatchingPercentage">MatchingPercentage</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchingPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationUnitId name="OrganizationUnitId">OrganizationUnitId</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PassThrough name="PassThrough">PassThrough</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassThrough attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjGrantMatching name="ProjGrantMatching">ProjGrantMatching</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjGrantMatching attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjGrantorType name="ProjGrantorType">ProjGrantorType</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjGrantorType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjGrantType name="ProjGrantType">ProjGrantType</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjGrantType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjLocalTrackingId name="ProjLocalTrackingId">ProjLocalTrackingId</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjLocalTrackingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RejectionNotification name="RejectionNotification">RejectionNotification</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RejectionNotification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RenewalActionDate name="RenewalActionDate">RenewalActionDate</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RenewalActionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedAmount name="RequestedAmount">RequestedAmount</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StateMandate name="StateMandate">StateMandate</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StateMandate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubGrantor name="SubGrantor">SubGrantor</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubGrantor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerContact name="WorkerContact">WorkerContact</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerContact attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDA name="CFDA">CFDA</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDA attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantorAgency name="GrantorAgency">GrantorAgency</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantorAgency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantManagerWorker_PersonnelNumber name="GrantManagerWorker_PersonnelNumber">GrantManagerWorker_PersonnelNumber</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantManagerWorker_PersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjGrantMatching_MatchingTypeCode name="ProjGrantMatching_MatchingTypeCode">ProjGrantMatching_MatchingTypeCode</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjGrantMatching_MatchingTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjGrantorType_GrantorType name="ProjGrantorType_GrantorType">ProjGrantorType_GrantorType</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjGrantorType_GrantorType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjGrantType_GrantType name="ProjGrantType_GrantType">ProjGrantType_GrantType</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjGrantType_GrantType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerContact_PersonnelNumber name="WorkerContact_PersonnelNumber">WorkerContact_PersonnelNumber</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerContact_PersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProjGrantRelationshipId name="BackingTable_ProjGrantRelationshipId">BackingTable_ProjGrantRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjGrantRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjGrant.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjGrant.cdm.json/ProjGrant</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjGrant.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjGrantV2Entity (this entity)  

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

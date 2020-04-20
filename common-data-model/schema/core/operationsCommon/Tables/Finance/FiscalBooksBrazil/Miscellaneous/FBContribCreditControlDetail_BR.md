---
title: FBContribCreditControlDetail_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# FBContribCreditControlDetail_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBContribCreditControlDetail_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBContribCreditControlDetail_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[AssessmentRegimen](#AssessmentRegimen)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[CreditBalance](#CreditBalance)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[CreditOrigin](#CreditOrigin)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[CreditOriginCNPJ](#CreditOriginCNPJ)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[CreditType](#CreditType)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[CurrentCreditCompensated](#CurrentCreditCompensated)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[CurrentCreditDeducted](#CurrentCreditDeducted)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[CurrentCreditReimbursed](#CurrentCreditReimbursed)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[CurrentCreditTransferred](#CurrentCreditTransferred)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[FBTaxAssessment_BR](#FBTaxAssessment_BR)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[OtherDeductedAmount](#OtherDeductedAmount)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[PeriodMonth](#PeriodMonth)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[PeriodYear](#PeriodYear)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[PreviousCompensationDeducted](#PreviousCompensationDeducted)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[PreviousCreditBalance](#PreviousCreditBalance)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[PreviousCreditDeducted](#PreviousCreditDeducted)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[PreviousReimbursementDeducted](#PreviousReimbursementDeducted)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|
|[Relationship_FBTaxAssessment_BRRelationshipId](#Relationship_FBTaxAssessment_BRRelationshipId)||<a href="FBContribCreditControlDetail_BR.md" target="_blank">Miscellaneous/FBContribCreditControlDetail_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBContribCreditControlDetail_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssessmentRegimen name="AssessmentRegimen">AssessmentRegimen</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessmentRegimen attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditBalance name="CreditBalance">CreditBalance</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CreditOrigin name="CreditOrigin">CreditOrigin</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditOriginCNPJ name="CreditOriginCNPJ">CreditOriginCNPJ</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditOriginCNPJ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditType name="CreditType">CreditType</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentCreditCompensated name="CurrentCreditCompensated">CurrentCreditCompensated</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentCreditCompensated attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentCreditDeducted name="CurrentCreditDeducted">CurrentCreditDeducted</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentCreditDeducted attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentCreditReimbursed name="CurrentCreditReimbursed">CurrentCreditReimbursed</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentCreditReimbursed attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentCreditTransferred name="CurrentCreditTransferred">CurrentCreditTransferred</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentCreditTransferred attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FBTaxAssessment_BR name="FBTaxAssessment_BR">FBTaxAssessment_BR</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBTaxAssessment_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OtherDeductedAmount name="OtherDeductedAmount">OtherDeductedAmount</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OtherDeductedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PeriodMonth name="PeriodMonth">PeriodMonth</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodMonth attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PeriodYear name="PeriodYear">PeriodYear</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PreviousCompensationDeducted name="PreviousCompensationDeducted">PreviousCompensationDeducted</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreviousCompensationDeducted attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PreviousCreditBalance name="PreviousCreditBalance">PreviousCreditBalance</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreviousCreditBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PreviousCreditDeducted name="PreviousCreditDeducted">PreviousCreditDeducted</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreviousCreditDeducted attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PreviousReimbursementDeducted name="PreviousReimbursementDeducted">PreviousReimbursementDeducted</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreviousReimbursementDeducted attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Relationship_FBTaxAssessment_BRRelationshipId name="Relationship_FBTaxAssessment_BRRelationshipId">Relationship_FBTaxAssessment_BRRelationshipId</a>

First included in: Miscellaneous/FBContribCreditControlDetail_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBTaxAssessment_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FBTaxAssessment_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBTaxAssessment_BR.cdm.json/FBTaxAssessment_BR</a></td><td><a href="../Transaction/FBTaxAssessment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

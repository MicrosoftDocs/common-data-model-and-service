---
title: BankLGGuarantee in WorksheetHeader - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Letter of guarantee in WorksheetHeader(BankLGGuarantee)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Bank/WorksheetHeader/BankLGGuarantee.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankLGGuarantee/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Letter of guarantee</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[BankAccountCurrencyExpenseAmount](#BankAccountCurrencyExpenseAmount)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[BankAccountCurrencyGuaranteeAmount](#BankAccountCurrencyGuaranteeAmount)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[BankAccountCurrencyMarginAmount](#BankAccountCurrencyMarginAmount)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[BankNum](#BankNum)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[CancellationReason](#CancellationReason)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[CurrentAction](#CurrentAction)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[ExpiryDateTime](#ExpiryDateTime)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[FacilityAgreementLine](#FacilityAgreementLine)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[FacilityStatus](#FacilityStatus)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[LastExecutionAction](#LastExecutionAction)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[Number](#Number)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[OriginType](#OriginType)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[PreFacilityStatus](#PreFacilityStatus)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[PreStatus](#PreStatus)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[RequestReason](#RequestReason)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[Status](#Status)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[DefaultDimension](#DefaultDimension)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[DataAreaId](#DataAreaId)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[Relationship_BankDocumentFacilityAgreementLineRelationshipId](#Relationship_BankDocumentFacilityAgreementLineRelationshipId)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[Relationship_BankLGActionRelationshipId](#Relationship_BankLGActionRelationshipId)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[Relationship_CancellationReasonRelationshipId](#Relationship_CancellationReasonRelationshipId)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[Relationship_PurposeCodeRelationshipId](#Relationship_PurposeCodeRelationshipId)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[Relationship_DimensionAttributeValueSetRelationshipId](#Relationship_DimensionAttributeValueSetRelationshipId)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="BankLGGuarantee.md" target="_blank">WorksheetHeader/BankLGGuarantee</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BankLGGuarantee/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankAccountCurrencyExpenseAmount name="BankAccountCurrencyExpenseAmount">BankAccountCurrencyExpenseAmount</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountCurrencyExpenseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankAccountCurrencyGuaranteeAmount name="BankAccountCurrencyGuaranteeAmount">BankAccountCurrencyGuaranteeAmount</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountCurrencyGuaranteeAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankAccountCurrencyMarginAmount name="BankAccountCurrencyMarginAmount">BankAccountCurrencyMarginAmount</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountCurrencyMarginAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankNum name="BankNum">BankNum</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CancellationReason name="CancellationReason">CancellationReason</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancellationReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentAction name="CurrentAction">CurrentAction</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentAction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExpiryDateTime name="ExpiryDateTime">ExpiryDateTime</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpiryDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FacilityAgreementLine name="FacilityAgreementLine">FacilityAgreementLine</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FacilityAgreementLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FacilityStatus name="FacilityStatus">FacilityStatus</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FacilityStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LastExecutionAction name="LastExecutionAction">LastExecutionAction</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last action</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastExecutionAction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last action</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Number name="Number">Number</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Number attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginType name="OriginType">OriginType</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PreFacilityStatus name="PreFacilityStatus">PreFacilityStatus</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreFacilityStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PreStatus name="PreStatus">PreStatus</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RequestReason name="RequestReason">RequestReason</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankDocumentFacilityAgreementLineRelationshipId name="Relationship_BankDocumentFacilityAgreementLineRelationshipId">Relationship_BankDocumentFacilityAgreementLineRelationshipId</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankDocumentFacilityAgreementLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/BankDocumentFacilityAgreementLine.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/BankDocumentFacilityAgreementLine.cdm.json/BankDocumentFacilityAgreementLine</a></td><td><a href="../WorksheetLine/BankDocumentFacilityAgreementLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BankLGActionRelationshipId name="Relationship_BankLGActionRelationshipId">Relationship_BankLGActionRelationshipId</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankLGActionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/BankLGAction.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/BankLGAction.cdm.json/BankLGAction</a></td><td><a href="../WorksheetLine/BankLGAction.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CancellationReasonRelationshipId name="Relationship_CancellationReasonRelationshipId">Relationship_CancellationReasonRelationshipId</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CancellationReasonRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Group/ReasonTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/ReasonTable.cdm.json/ReasonTable</a></td><td><a href="../../Ledger/Group/ReasonTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurposeCodeRelationshipId name="Relationship_PurposeCodeRelationshipId">Relationship_PurposeCodeRelationshipId</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurposeCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Group/ReasonTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/ReasonTable.cdm.json/ReasonTable</a></td><td><a href="../../Ledger/Group/ReasonTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeValueSetRelationshipId name="Relationship_DimensionAttributeValueSetRelationshipId">Relationship_DimensionAttributeValueSetRelationshipId</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/BankLGGuarantee (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

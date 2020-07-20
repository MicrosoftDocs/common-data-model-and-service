---
title: FBFiscalDocumentAdjustmentCodeICMS_BR in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Adjustment and information for fiscal documents in Main(FBFiscalDocumentAdjustmentCodeICMS_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBFiscalDocumentAdjustmentCodeICMS_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBFiscalDocumentAdjustmentCodeICMS_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Adjustment and information for fiscal documents</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[AdjustmentCode](#AdjustmentCode)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[AssessmentType](#AssessmentType)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[Classification](#Classification)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[CollectionType](#CollectionType)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[CreatePayment](#CreatePayment)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[Description](#Description)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[GIAAdjustmentCode](#GIAAdjustmentCode)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[OccurrenceCode](#OccurrenceCode)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[ResponsibilityType](#ResponsibilityType)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[RevenueCode](#RevenueCode)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[SourceTaxationType](#SourceTaxationType)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[SpedAdjustmentCode](#SpedAdjustmentCode)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[State](#State)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[TaxType](#TaxType)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[ValidFrom](#ValidFrom)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[ValidTo](#ValidTo)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[ClassificationIcmsDif](#ClassificationIcmsDif)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[IsPovertyFund](#IsPovertyFund)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[Table52](#Table52)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[LiteralCode](#LiteralCode)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[SuppressAdjustmentCode](#SuppressAdjustmentCode)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[TaxBenefitCodeType](#TaxBenefitCodeType)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|
|[Relationship_TaxBenefitCodeType_BRRelationshipId](#Relationship_TaxBenefitCodeType_BRRelationshipId)||<a href="FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">Main/FBFiscalDocumentAdjustmentCodeICMS_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBFiscalDocumentAdjustmentCodeICMS_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdjustmentCode name="AdjustmentCode">AdjustmentCode</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identification</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Identification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssessmentType name="AssessmentType">AssessmentType</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessmentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Classification name="Classification">Classification</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Classification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CollectionType name="CollectionType">CollectionType</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CreatePayment name="CreatePayment">CreatePayment</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatePayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GIAAdjustmentCode name="GIAAdjustmentCode">GIAAdjustmentCode</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GIAAdjustmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OccurrenceCode name="OccurrenceCode">OccurrenceCode</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OccurrenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponsibilityType name="ResponsibilityType">ResponsibilityType</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsibilityType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RevenueCode name="RevenueCode">RevenueCode</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceTaxationType name="SourceTaxationType">SourceTaxationType</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTaxationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SpedAdjustmentCode name="SpedAdjustmentCode">SpedAdjustmentCode</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpedAdjustmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#State name="State">State</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ClassificationIcmsDif name="ClassificationIcmsDif">ClassificationIcmsDif</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassificationIcmsDif attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsPovertyFund name="IsPovertyFund">IsPovertyFund</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>FCP</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPovertyFund attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>FCP</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Table52 name="Table52">Table52</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Table 5.2</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Table52 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Table 5.2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#LiteralCode name="LiteralCode">LiteralCode</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Literal adjustment code</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LiteralCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Literal adjustment code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SuppressAdjustmentCode name="SuppressAdjustmentCode">SuppressAdjustmentCode</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Suppress code</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SuppressAdjustmentCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Suppress code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxBenefitCodeType name="TaxBenefitCodeType">TaxBenefitCodeType</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBenefitCodeType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_TaxBenefitCodeType_BRRelationshipId name="Relationship_TaxBenefitCodeType_BRRelationshipId">Relationship_TaxBenefitCodeType_BRRelationshipId</a>

First included in: Main/FBFiscalDocumentAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxBenefitCodeType_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Miscellaneous/TaxBenefitCodeType_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxBenefitCodeType_BR.cdm.json/TaxBenefitCodeType_BR</a></td><td><a href="../../Tax/Miscellaneous/TaxBenefitCodeType_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

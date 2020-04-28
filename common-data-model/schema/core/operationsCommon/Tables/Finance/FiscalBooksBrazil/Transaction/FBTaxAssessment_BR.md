---
title: FBTaxAssessment_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Tax assessment

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBTaxAssessment_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBTaxAssessment_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax assessment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[City](#City)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[FBBookingPeriod_BR](#FBBookingPeriod_BR)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[FBFiscalDocumentAdjCodeICMSFixedAsset_BR](#FBFiscalDocumentAdjCodeICMSFixedAsset_BR)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[FBFiscalDocumentAdjustmentCodeICMS_BR](#FBFiscalDocumentAdjustmentCodeICMS_BR)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[FBGeneralAdjustmentCodeICMS_BR](#FBGeneralAdjustmentCodeICMS_BR)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[FBGeneralAdjustmentCodeICMSFixedAsset_BR](#FBGeneralAdjustmentCodeICMSFixedAsset_BR)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[FBObservationCodeTable_BR](#FBObservationCodeTable_BR)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[FromDate](#FromDate)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[State](#State)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[Status](#Status)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[TaxType](#TaxType)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[ToDate](#ToDate)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[Voucher](#Voucher)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[VoucherDataArea](#VoucherDataArea)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[VoucherTransDate](#VoucherTransDate)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[ContribAssessmentRegimen](#ContribAssessmentRegimen)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[ContribCreditAllocationMethod](#ContribCreditAllocationMethod)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[ContribContributionType](#ContribContributionType)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[CreditInventoryAdjustment](#CreditInventoryAdjustment)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[Relationship_FBBookingPeriod_BRRelationshipId](#Relationship_FBBookingPeriod_BRRelationshipId)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[Relationship_FBFiscalDocumentAdjCodeICMSFixedAsset_BRRelationshipId](#Relationship_FBFiscalDocumentAdjCodeICMSFixedAsset_BRRelationshipId)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId](#Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[Relationship_FBGeneralAdjustmentCode_BRRelationshipId](#Relationship_FBGeneralAdjustmentCode_BRRelationshipId)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[Relationship_FBGeneralAdjustmentCodeICMS_BRRelationshipId](#Relationship_FBGeneralAdjustmentCodeICMS_BRRelationshipId)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[Relationship_FBGeneralAdjustmentCodeICMSFixedAsset_BRRelationshipId](#Relationship_FBGeneralAdjustmentCodeICMSFixedAsset_BRRelationshipId)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|
|[Relationship_FBObservationCodeTable_BRRelationshipId](#Relationship_FBObservationCodeTable_BRRelationshipId)||<a href="FBTaxAssessment_BR.md" target="_blank">Transaction/FBTaxAssessment_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBTaxAssessment_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#City name="City">City</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the City attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FBBookingPeriod_BR name="FBBookingPeriod_BR">FBBookingPeriod_BR</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBBookingPeriod_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBFiscalDocumentAdjCodeICMSFixedAsset_BR name="FBFiscalDocumentAdjCodeICMSFixedAsset_BR">FBFiscalDocumentAdjCodeICMSFixedAsset_BR</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment code for fixed asset</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBFiscalDocumentAdjCodeICMSFixedAsset_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Adjustment code for fixed asset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBFiscalDocumentAdjustmentCodeICMS_BR name="FBFiscalDocumentAdjustmentCodeICMS_BR">FBFiscalDocumentAdjustmentCodeICMS_BR</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBFiscalDocumentAdjustmentCodeICMS_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBGeneralAdjustmentCodeICMS_BR name="FBGeneralAdjustmentCodeICMS_BR">FBGeneralAdjustmentCodeICMS_BR</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBGeneralAdjustmentCodeICMS_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBGeneralAdjustmentCodeICMSFixedAsset_BR name="FBGeneralAdjustmentCodeICMSFixedAsset_BR">FBGeneralAdjustmentCodeICMSFixedAsset_BR</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment code for fixed asset</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBGeneralAdjustmentCodeICMSFixedAsset_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Adjustment code for fixed asset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBObservationCodeTable_BR name="FBObservationCodeTable_BR">FBObservationCodeTable_BR</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBObservationCodeTable_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#State name="State">State</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

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

### <a href=#Status name="Status">Status</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherDataArea name="VoucherDataArea">VoucherDataArea</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherTransDate name="VoucherTransDate">VoucherTransDate</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ContribAssessmentRegimen name="ContribAssessmentRegimen">ContribAssessmentRegimen</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContribAssessmentRegimen attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ContribCreditAllocationMethod name="ContribCreditAllocationMethod">ContribCreditAllocationMethod</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContribCreditAllocationMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ContribContributionType name="ContribContributionType">ContribContributionType</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContribContributionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditInventoryAdjustment name="CreditInventoryAdjustment">CreditInventoryAdjustment</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Credit inventory adjustment</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditInventoryAdjustment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enable Credit inventory adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_FBBookingPeriod_BRRelationshipId name="Relationship_FBBookingPeriod_BRRelationshipId">Relationship_FBBookingPeriod_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBBookingPeriod_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FBBookingPeriod_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBBookingPeriod_BR.cdm.json/FBBookingPeriod_BR</a></td><td><a href="FBBookingPeriod_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBFiscalDocumentAdjCodeICMSFixedAsset_BRRelationshipId name="Relationship_FBFiscalDocumentAdjCodeICMSFixedAsset_BRRelationshipId">Relationship_FBFiscalDocumentAdjCodeICMSFixedAsset_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBFiscalDocumentAdjCodeICMSFixedAsset_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBFiscalDocumentAdjustmentCodeICMS_BR.cdm.json/FBFiscalDocumentAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId name="Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId">Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBFiscalDocumentAdjustmentCodeICMS_BR.cdm.json/FBFiscalDocumentAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBGeneralAdjustmentCode_BRRelationshipId name="Relationship_FBGeneralAdjustmentCode_BRRelationshipId">Relationship_FBGeneralAdjustmentCode_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBGeneralAdjustmentCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCode_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCode_BR.cdm.json/FBGeneralAdjustmentCode_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCode_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBGeneralAdjustmentCodeICMS_BRRelationshipId name="Relationship_FBGeneralAdjustmentCodeICMS_BRRelationshipId">Relationship_FBGeneralAdjustmentCodeICMS_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBGeneralAdjustmentCodeICMS_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBGeneralAdjustmentCodeICMSFixedAsset_BRRelationshipId name="Relationship_FBGeneralAdjustmentCodeICMSFixedAsset_BRRelationshipId">Relationship_FBGeneralAdjustmentCodeICMSFixedAsset_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBGeneralAdjustmentCodeICMSFixedAsset_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBObservationCodeTable_BRRelationshipId name="Relationship_FBObservationCodeTable_BRRelationshipId">Relationship_FBObservationCodeTable_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBObservationCodeTable_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBObservationCodeTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBObservationCodeTable_BR.cdm.json/FBObservationCodeTable_BR</a></td><td><a href="../Main/FBObservationCodeTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

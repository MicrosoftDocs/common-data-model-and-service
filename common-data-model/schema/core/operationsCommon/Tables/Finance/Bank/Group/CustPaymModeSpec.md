---
title: CustPaymModeSpec in Group - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Customer specifications in Group(CustPaymModeSpec)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Bank/Group/CustPaymModeSpec.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustPaymModeSpec/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer specifications</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[ClassId](#ClassId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[EPPaymentType_BR](#EPPaymentType_BR)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[EPPaymentWay_BR](#EPPaymentWay_BR)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[EPSegment_BR](#EPSegment_BR)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[EPSegmentReturn_BR](#EPSegmentReturn_BR)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Name](#Name)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[PaymMode](#PaymMode)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Specification](#Specification)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[SpecParameters](#SpecParameters)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[LocalInstrument_W](#LocalInstrument_W)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[ChargeBearer_W](#ChargeBearer_W)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[ServiceLevel_W](#ServiceLevel_W)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[CategoryPurpose_W](#CategoryPurpose_W)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[DataAreaId](#DataAreaId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Relationship_CustPaymModeTableRelationshipId](#Relationship_CustPaymModeTableRelationshipId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Relationship_EPPaymentType_BRRelationshipId](#Relationship_EPPaymentType_BRRelationshipId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Relationship_EPPaymentWay_BRRelationshipId](#Relationship_EPPaymentWay_BRRelationshipId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Relationship_EPSegment_BRRelationshipId](#Relationship_EPSegment_BRRelationshipId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Relationship_EPSegmentReturn_BRRelationshipId](#Relationship_EPSegmentReturn_BRRelationshipId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId](#Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId](#Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId](#Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId](#Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustPaymModeSpec.md" target="_blank">Group/CustPaymModeSpec</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustPaymModeSpec/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ClassId name="ClassId">ClassId</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EPPaymentType_BR name="EPPaymentType_BR">EPPaymentType_BR</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPPaymentType_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EPPaymentWay_BR name="EPPaymentWay_BR">EPPaymentWay_BR</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPPaymentWay_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EPSegment_BR name="EPSegment_BR">EPSegment_BR</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remittance segment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPSegment_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remittance segment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EPSegmentReturn_BR name="EPSegmentReturn_BR">EPSegmentReturn_BR</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Return segment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPSegmentReturn_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Return segment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymMode name="PaymMode">PaymMode</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Specification name="Specification">Specification</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Specification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecParameters name="SpecParameters">SpecParameters</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecParameters attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocalInstrument_W name="LocalInstrument_W">LocalInstrument_W</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocalInstrument_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ChargeBearer_W name="ChargeBearer_W">ChargeBearer_W</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeBearer_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceLevel_W name="ServiceLevel_W">ServiceLevel_W</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLevel_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CategoryPurpose_W name="CategoryPurpose_W">CategoryPurpose_W</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryPurpose_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/CustPaymModeSpec (this entity)  

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

### <a href=#Relationship_CustPaymModeTableRelationshipId name="Relationship_CustPaymModeTableRelationshipId">Relationship_CustPaymModeTableRelationshipId</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustPaymModeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CustPaymModeTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/CustPaymModeTable.cdm.json/CustPaymModeTable</a></td><td><a href="CustPaymModeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EPPaymentType_BRRelationshipId name="Relationship_EPPaymentType_BRRelationshipId">Relationship_EPPaymentType_BRRelationshipId</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EPPaymentType_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EPPaymentTypeTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/EPPaymentTypeTable_BR.cdm.json/EPPaymentTypeTable_BR</a></td><td><a href="EPPaymentTypeTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EPPaymentWay_BRRelationshipId name="Relationship_EPPaymentWay_BRRelationshipId">Relationship_EPPaymentWay_BRRelationshipId</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EPPaymentWay_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EPPaymentWayTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/EPPaymentWayTable_BR.cdm.json/EPPaymentWayTable_BR</a></td><td><a href="EPPaymentWayTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EPSegment_BRRelationshipId name="Relationship_EPSegment_BRRelationshipId">Relationship_EPSegment_BRRelationshipId</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EPSegment_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EPSegmentTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/EPSegmentTable_BR.cdm.json/EPSegmentTable_BR</a></td><td><a href="EPSegmentTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EPSegmentReturn_BRRelationshipId name="Relationship_EPSegmentReturn_BRRelationshipId">Relationship_EPSegmentReturn_BRRelationshipId</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EPSegmentReturn_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EPSegmentTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/EPSegmentTable_BR.cdm.json/EPSegmentTable_BR</a></td><td><a href="EPSegmentTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId name="Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId">Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId name="Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId">Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId name="Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId">Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId name="Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId">Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId</a>

First included in: Group/CustPaymModeSpec (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/CustPaymModeSpec (this entity)  

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

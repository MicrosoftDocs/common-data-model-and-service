---
title: FBTaxTransTaxAssessmentPayment_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Tax assessment and tax assessment payment relationship

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBTaxTransTaxAssessmentPayment_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBTaxTransTaxAssessmentPayment_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax assessment and tax assessment payment relationship</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBTaxTransTaxAssessmentPayment_BR.md" target="_blank">Miscellaneous/FBTaxTransTaxAssessmentPayment_BR</a>|
|[FBTaxAssessmentPayment_BR](#FBTaxAssessmentPayment_BR)||<a href="FBTaxTransTaxAssessmentPayment_BR.md" target="_blank">Miscellaneous/FBTaxTransTaxAssessmentPayment_BR</a>|
|[FBTaxTrans_BR](#FBTaxTrans_BR)||<a href="FBTaxTransTaxAssessmentPayment_BR.md" target="_blank">Miscellaneous/FBTaxTransTaxAssessmentPayment_BR</a>|
|[Relationship_FBTaxAssessmentPayment_BRRelationshipId](#Relationship_FBTaxAssessmentPayment_BRRelationshipId)||<a href="FBTaxTransTaxAssessmentPayment_BR.md" target="_blank">Miscellaneous/FBTaxTransTaxAssessmentPayment_BR</a>|
|[Relationship_FBTaxTrans_BRRelationshipId](#Relationship_FBTaxTrans_BRRelationshipId)||<a href="FBTaxTransTaxAssessmentPayment_BR.md" target="_blank">Miscellaneous/FBTaxTransTaxAssessmentPayment_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FBTaxTransTaxAssessmentPayment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBTaxTransTaxAssessmentPayment_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBTaxAssessmentPayment_BR name="FBTaxAssessmentPayment_BR">FBTaxAssessmentPayment_BR</a>

First included in: Miscellaneous/FBTaxTransTaxAssessmentPayment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBTaxAssessmentPayment_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBTaxTrans_BR name="FBTaxTrans_BR">FBTaxTrans_BR</a>

First included in: Miscellaneous/FBTaxTransTaxAssessmentPayment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBTaxTrans_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_FBTaxAssessmentPayment_BRRelationshipId name="Relationship_FBTaxAssessmentPayment_BRRelationshipId">Relationship_FBTaxAssessmentPayment_BRRelationshipId</a>

First included in: Miscellaneous/FBTaxTransTaxAssessmentPayment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBTaxAssessmentPayment_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FBTaxAssessmentPayment_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBTaxAssessmentPayment_BR.cdm.json/FBTaxAssessmentPayment_BR</a></td><td><a href="../Transaction/FBTaxAssessmentPayment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBTaxTrans_BRRelationshipId name="Relationship_FBTaxTrans_BRRelationshipId">Relationship_FBTaxTrans_BRRelationshipId</a>

First included in: Miscellaneous/FBTaxTransTaxAssessmentPayment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBTaxTrans_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FBTaxTrans_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBTaxTrans_BR.cdm.json/FBTaxTrans_BR</a></td><td><a href="../Transaction/FBTaxTrans_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

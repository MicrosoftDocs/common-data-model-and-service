---
title: FBTaxAssessmentINSSCPRBTaxTrans_BR in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Tax assessment details (INSS-CPRB) in Miscellaneous(FBTaxAssessmentINSSCPRBTaxTrans_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBTaxAssessmentINSSCPRBTaxTrans_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax assessment details (INSS-CPRB)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBTaxAssessmentINSSCPRBTaxTrans_BR.md" target="_blank">Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR</a>|
|[FBEconomicActivityCode_BR](#FBEconomicActivityCode_BR)||<a href="FBTaxAssessmentINSSCPRBTaxTrans_BR.md" target="_blank">Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR</a>|
|[FBTaxAssessmentINSSCPRB_BR](#FBTaxAssessmentINSSCPRB_BR)||<a href="FBTaxAssessmentINSSCPRBTaxTrans_BR.md" target="_blank">Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR</a>|
|[FBTaxTrans_BR](#FBTaxTrans_BR)||<a href="FBTaxAssessmentINSSCPRBTaxTrans_BR.md" target="_blank">Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="FBTaxAssessmentINSSCPRBTaxTrans_BR.md" target="_blank">Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR</a>|
|[Relationship_FBTaxAssessmentINSSCPRB_BRRelationshipId](#Relationship_FBTaxAssessmentINSSCPRB_BRRelationshipId)||<a href="FBTaxAssessmentINSSCPRBTaxTrans_BR.md" target="_blank">Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR</a>|
|[Relationship_FBTaxTrans_BRRelationshipId](#Relationship_FBTaxTrans_BRRelationshipId)||<a href="FBTaxAssessmentINSSCPRBTaxTrans_BR.md" target="_blank">Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR</a>|
|[Relationship_FBEconomicActivityCode_BRRelationshipId](#Relationship_FBEconomicActivityCode_BRRelationshipId)||<a href="FBTaxAssessmentINSSCPRBTaxTrans_BR.md" target="_blank">Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="FBTaxAssessmentINSSCPRBTaxTrans_BR.md" target="_blank">Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBTaxAssessmentINSSCPRBTaxTrans_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBEconomicActivityCode_BR name="FBEconomicActivityCode_BR">FBEconomicActivityCode_BR</a>

First included in: Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBEconomicActivityCode_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBTaxAssessmentINSSCPRB_BR name="FBTaxAssessmentINSSCPRB_BR">FBTaxAssessmentINSSCPRB_BR</a>

First included in: Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBTaxAssessmentINSSCPRB_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBTaxTrans_BR name="FBTaxTrans_BR">FBTaxTrans_BR</a>

First included in: Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR (this entity)  

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

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR (this entity)  

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

### <a href=#Relationship_FBTaxAssessmentINSSCPRB_BRRelationshipId name="Relationship_FBTaxAssessmentINSSCPRB_BRRelationshipId">Relationship_FBTaxAssessmentINSSCPRB_BRRelationshipId</a>

First included in: Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBTaxAssessmentINSSCPRB_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FBTaxAssessmentINSSCPRB_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBTaxAssessmentINSSCPRB_BR.cdm.json/FBTaxAssessmentINSSCPRB_BR</a></td><td><a href="FBTaxAssessmentINSSCPRB_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBTaxTrans_BRRelationshipId name="Relationship_FBTaxTrans_BRRelationshipId">Relationship_FBTaxTrans_BRRelationshipId</a>

First included in: Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR (this entity)  

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

### <a href=#Relationship_FBEconomicActivityCode_BRRelationshipId name="Relationship_FBEconomicActivityCode_BRRelationshipId">Relationship_FBEconomicActivityCode_BRRelationshipId</a>

First included in: Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBEconomicActivityCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FBEconomicActivityCode_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBEconomicActivityCode_BR.cdm.json/FBEconomicActivityCode_BR</a></td><td><a href="FBEconomicActivityCode_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/FBTaxAssessmentINSSCPRBTaxTrans_BR (this entity)  

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

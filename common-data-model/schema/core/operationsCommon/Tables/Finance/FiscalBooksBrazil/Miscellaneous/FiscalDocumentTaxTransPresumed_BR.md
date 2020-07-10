---
title: FiscalDocumentTaxTransPresumed_BR in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Presumed tax in Miscellaneous(FiscalDocumentTaxTransPresumed_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FiscalDocumentTaxTransPresumed_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FiscalDocumentTaxTransPresumed_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Presumed tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[PresumedTaxBaseAmount](#PresumedTaxBaseAmount)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[PresumedTaxAmount](#PresumedTaxAmount)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[FiscalDocumentTaxTrans_BR](#FiscalDocumentTaxTrans_BR)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[PresumedTaxAmountPerInvUnit](#PresumedTaxAmountPerInvUnit)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[PresumedTaxBaseAmountPerInvUnit](#PresumedTaxBaseAmountPerInvUnit)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[PresumedTaxPercentage](#PresumedTaxPercentage)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[PresumedFCPTaxBaseAmountPerInvUnit](#PresumedFCPTaxBaseAmountPerInvUnit)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[PresumedFCPTaxAmountPerInvUnit](#PresumedFCPTaxAmountPerInvUnit)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[PresumedFCPTaxBaseAmount](#PresumedFCPTaxBaseAmount)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[PresumedFCPTaxAmount](#PresumedFCPTaxAmount)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[PresumedFCPTaxPercentage](#PresumedFCPTaxPercentage)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[PresumedvICMSSubstituto](#PresumedvICMSSubstituto)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[SPEDOriginalTaxTrans](#SPEDOriginalTaxTrans)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[SPEDPresumedTaxAmount](#SPEDPresumedTaxAmount)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[SPEDPresumedTaxAmountPerInvUnit](#SPEDPresumedTaxAmountPerInvUnit)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[SPEDPresumedTaxBaseAmount](#SPEDPresumedTaxBaseAmount)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[SPEDPresumedTaxBaseAmountPerInvUnit](#SPEDPresumedTaxBaseAmountPerInvUnit)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[SPEDPresumedTaxPercentage](#SPEDPresumedTaxPercentage)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[SPEDPresumedFCPTaxAmount](#SPEDPresumedFCPTaxAmount)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[SPEDPresumedFCPTaxAmountPerInvUnit](#SPEDPresumedFCPTaxAmountPerInvUnit)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[Relationship_FiscalDocumentTaxTransRelationshipId](#Relationship_FiscalDocumentTaxTransRelationshipId)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="FiscalDocumentTaxTransPresumed_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransPresumed_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FiscalDocumentTaxTransPresumed_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PresumedTaxBaseAmount name="PresumedTaxBaseAmount">PresumedTaxBaseAmount</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedTaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PresumedTaxAmount name="PresumedTaxAmount">PresumedTaxAmount</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FiscalDocumentTaxTrans_BR name="FiscalDocumentTaxTrans_BR">FiscalDocumentTaxTrans_BR</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTaxTrans_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PresumedTaxAmountPerInvUnit name="PresumedTaxAmountPerInvUnit">PresumedTaxAmountPerInvUnit</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedTaxAmountPerInvUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PresumedTaxBaseAmountPerInvUnit name="PresumedTaxBaseAmountPerInvUnit">PresumedTaxBaseAmountPerInvUnit</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedTaxBaseAmountPerInvUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PresumedTaxPercentage name="PresumedTaxPercentage">PresumedTaxPercentage</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedTaxPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PresumedFCPTaxBaseAmountPerInvUnit name="PresumedFCPTaxBaseAmountPerInvUnit">PresumedFCPTaxBaseAmountPerInvUnit</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedFCPTaxBaseAmountPerInvUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PresumedFCPTaxAmountPerInvUnit name="PresumedFCPTaxAmountPerInvUnit">PresumedFCPTaxAmountPerInvUnit</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedFCPTaxAmountPerInvUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PresumedFCPTaxBaseAmount name="PresumedFCPTaxBaseAmount">PresumedFCPTaxBaseAmount</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedFCPTaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PresumedFCPTaxAmount name="PresumedFCPTaxAmount">PresumedFCPTaxAmount</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedFCPTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PresumedFCPTaxPercentage name="PresumedFCPTaxPercentage">PresumedFCPTaxPercentage</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedFCPTaxPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PresumedvICMSSubstituto name="PresumedvICMSSubstituto">PresumedvICMSSubstituto</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresumedvICMSSubstituto attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SPEDOriginalTaxTrans name="SPEDOriginalTaxTrans">SPEDOriginalTaxTrans</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDOriginalTaxTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SPEDPresumedTaxAmount name="SPEDPresumedTaxAmount">SPEDPresumedTaxAmount</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDPresumedTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SPEDPresumedTaxAmountPerInvUnit name="SPEDPresumedTaxAmountPerInvUnit">SPEDPresumedTaxAmountPerInvUnit</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDPresumedTaxAmountPerInvUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SPEDPresumedTaxBaseAmount name="SPEDPresumedTaxBaseAmount">SPEDPresumedTaxBaseAmount</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDPresumedTaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SPEDPresumedTaxBaseAmountPerInvUnit name="SPEDPresumedTaxBaseAmountPerInvUnit">SPEDPresumedTaxBaseAmountPerInvUnit</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDPresumedTaxBaseAmountPerInvUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SPEDPresumedTaxPercentage name="SPEDPresumedTaxPercentage">SPEDPresumedTaxPercentage</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDPresumedTaxPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SPEDPresumedFCPTaxAmount name="SPEDPresumedFCPTaxAmount">SPEDPresumedFCPTaxAmount</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDPresumedFCPTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SPEDPresumedFCPTaxAmountPerInvUnit name="SPEDPresumedFCPTaxAmountPerInvUnit">SPEDPresumedFCPTaxAmountPerInvUnit</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SPEDPresumedFCPTaxAmountPerInvUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

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

### <a href=#Relationship_FiscalDocumentTaxTransRelationshipId name="Relationship_FiscalDocumentTaxTransRelationshipId">Relationship_FiscalDocumentTaxTransRelationshipId</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentTaxTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FiscalDocumentTaxTrans_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocumentTaxTrans_BR.cdm.json/FiscalDocumentTaxTrans_BR</a></td><td><a href="../Transaction/FiscalDocumentTaxTrans_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/FiscalDocumentTaxTransPresumed_BR (this entity)  

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

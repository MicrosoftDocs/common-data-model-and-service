---
title: EFDocumentReceivedXmlViewAddress_BR in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# NF-e received XML document address in Transaction(EFDocumentReceivedXmlViewAddress_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/EFDocumentReceivedXmlViewAddress_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocumentReceivedXmlViewAddress_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>NF-e received XML document address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[BuildingComplement](#BuildingComplement)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[CityIbgeCode](#CityIbgeCode)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[CityName](#CityName)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[DistrictName](#DistrictName)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[EFDocumentReceivedXmlView_BR](#EFDocumentReceivedXmlView_BR)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[StateId](#StateId)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[StreetName](#StreetName)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[StreetNumber](#StreetNumber)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[ZipCode](#ZipCode)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[Relationship_EFDocumentReceivedXmlView_BRRelationshipId](#Relationship_EFDocumentReceivedXmlView_BRRelationshipId)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EFDocumentReceivedXmlViewAddress_BR.md" target="_blank">Transaction/EFDocumentReceivedXmlViewAddress_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EFDocumentReceivedXmlViewAddress_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BuildingComplement name="BuildingComplement">BuildingComplement</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuildingComplement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CityIbgeCode name="CityIbgeCode">CityIbgeCode</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CityIbgeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CityName name="CityName">CityName</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DistrictName name="DistrictName">DistrictName</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EFDocumentReceivedXmlView_BR name="EFDocumentReceivedXmlView_BR">EFDocumentReceivedXmlView_BR</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EFDocumentReceivedXmlView_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#StateId name="StateId">StateId</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StreetName name="StreetName">StreetName</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StreetName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StreetNumber name="StreetNumber">StreetNumber</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZipCode name="ZipCode">ZipCode</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

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

### <a href=#Relationship_EFDocumentReceivedXmlView_BRRelationshipId name="Relationship_EFDocumentReceivedXmlView_BRRelationshipId">Relationship_EFDocumentReceivedXmlView_BRRelationshipId</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EFDocumentReceivedXmlView_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EFDocumentReceivedXmlView_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/EFDocumentReceivedXmlView_BR.cdm.json/EFDocumentReceivedXmlView_BR</a></td><td><a href="EFDocumentReceivedXmlView_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/EFDocumentReceivedXmlViewAddress_BR (this entity)  

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

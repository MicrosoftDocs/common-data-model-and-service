---
title: FBBookingPeriodPresumedIncDocuments_BR in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Incoming fiscal documents used for presumed taxes in Miscellaneous(FBBookingPeriodPresumedIncDocuments_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBBookingPeriodPresumedIncDocuments_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Incoming fiscal documents used for presumed taxes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[FBBookingPeriod_BR](#FBBookingPeriod_BR)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[FiscalDocument_BR](#FiscalDocument_BR)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[FiscalDocumentLine_BR](#FiscalDocumentLine_BR)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[ItemId](#ItemId)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[ProductName](#ProductName)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[Quantity](#Quantity)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[TaxAmountICMS](#TaxAmountICMS)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[TaxAmountICMSST](#TaxAmountICMSST)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[TaxBaseAmountICMSST](#TaxBaseAmountICMSST)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[TaxRateICMSST](#TaxRateICMSST)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[Unit](#Unit)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[IsReturn](#IsReturn)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[Relationship_FBBookingPeriod_BRRelationshipId](#Relationship_FBBookingPeriod_BRRelationshipId)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[Relationship_FiscalDocument_BRRelationshipId](#Relationship_FiscalDocument_BRRelationshipId)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[Relationship_FiscalDocumentLine_BRRelationshipId](#Relationship_FiscalDocumentLine_BRRelationshipId)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="FBBookingPeriodPresumedIncDocuments_BR.md" target="_blank">Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBBookingPeriodPresumedIncDocuments_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBBookingPeriod_BR name="FBBookingPeriod_BR">FBBookingPeriod_BR</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBBookingPeriod_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocument_BR name="FiscalDocument_BR">FiscalDocument_BR</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocument_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocumentLine_BR name="FiscalDocumentLine_BR">FiscalDocumentLine_BR</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentLine_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountICMS name="TaxAmountICMS">TaxAmountICMS</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountICMS attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountICMSST name="TaxAmountICMSST">TaxAmountICMSST</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountICMSST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseAmountICMSST name="TaxBaseAmountICMSST">TaxBaseAmountICMSST</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmountICMSST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxRateICMSST name="TaxRateICMSST">TaxRateICMSST</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRateICMSST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Unit name="Unit">Unit</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Unit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReturn name="IsReturn">IsReturn</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>@FiscalBooks_SpedFiscal:IsReturnFD</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReturn attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@FiscalBooks_SpedFiscal:IsReturnFD</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

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

### <a href=#Relationship_FBBookingPeriod_BRRelationshipId name="Relationship_FBBookingPeriod_BRRelationshipId">Relationship_FBBookingPeriod_BRRelationshipId</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FBBookingPeriod_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBBookingPeriod_BR.cdm.json/FBBookingPeriod_BR</a></td><td><a href="../Transaction/FBBookingPeriod_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocument_BRRelationshipId name="Relationship_FiscalDocument_BRRelationshipId">Relationship_FiscalDocument_BRRelationshipId</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocument_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FiscalDocument_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocument_BR.cdm.json/FiscalDocument_BR</a></td><td><a href="../Transaction/FiscalDocument_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentLine_BRRelationshipId name="Relationship_FiscalDocumentLine_BRRelationshipId">Relationship_FiscalDocumentLine_BRRelationshipId</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentLine_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FiscalDocumentLine_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocumentLine_BR.cdm.json/FiscalDocumentLine_BR</a></td><td><a href="../Transaction/FiscalDocumentLine_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/FBBookingPeriodPresumedIncDocuments_BR (this entity)  

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

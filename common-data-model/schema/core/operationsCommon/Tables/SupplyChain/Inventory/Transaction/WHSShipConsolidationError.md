---
title: WHSShipConsolidationError - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Validation errors

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/WHSShipConsolidationError.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSShipConsolidationError/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Validation errors</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[ErrorHardStop](#ErrorHardStop)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[ErrorOverride](#ErrorOverride)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[ErrorOverridenBy](#ErrorOverridenBy)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[ErrorParm1](#ErrorParm1)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[ErrorParm2](#ErrorParm2)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[ErrorParm3](#ErrorParm3)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[ErrorParm4](#ErrorParm4)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[LabelId](#LabelId)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[ProposedShipment](#ProposedShipment)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[ProposedShipmentContent](#ProposedShipmentContent)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[ShipConsolidationSession](#ShipConsolidationSession)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[DataAreaId](#DataAreaId)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[Relationship_WHSShipConsolidationSessionRelationshipId](#Relationship_WHSShipConsolidationSessionRelationshipId)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[Relationship_WHSShipConsolidationProposedShipmentRelationshipId](#Relationship_WHSShipConsolidationProposedShipmentRelationshipId)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[Relationship_WHSShipConsolidationProposedShipmentContentRelationshipId](#Relationship_WHSShipConsolidationProposedShipmentContentRelationshipId)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WHSShipConsolidationError.md" target="_blank">Transaction/WHSShipConsolidationError</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSShipConsolidationError/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ErrorHardStop name="ErrorHardStop">ErrorHardStop</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorHardStop attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ErrorOverride name="ErrorOverride">ErrorOverride</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorOverride attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ErrorOverridenBy name="ErrorOverridenBy">ErrorOverridenBy</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorOverridenBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorParm1 name="ErrorParm1">ErrorParm1</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Error Parameter 1</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorParm1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Error Parameter 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorParm2 name="ErrorParm2">ErrorParm2</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Error Parameter 2</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorParm2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Error Parameter 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorParm3 name="ErrorParm3">ErrorParm3</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Error Parameter 3</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorParm3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Error Parameter 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorParm4 name="ErrorParm4">ErrorParm4</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Error Parameter 4</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorParm4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Error Parameter 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LabelId name="LabelId">LabelId</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProposedShipment name="ProposedShipment">ProposedShipment</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedShipment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProposedShipmentContent name="ProposedShipmentContent">ProposedShipmentContent</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedShipmentContent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ShipConsolidationSession name="ShipConsolidationSession">ShipConsolidationSession</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipConsolidationSession attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

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

### <a href=#Relationship_WHSShipConsolidationSessionRelationshipId name="Relationship_WHSShipConsolidationSessionRelationshipId">Relationship_WHSShipConsolidationSessionRelationshipId</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSShipConsolidationSessionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WHSShipConsolidationSession.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSShipConsolidationSession.cdm.json/WHSShipConsolidationSession</a></td><td><a href="../Main/WHSShipConsolidationSession.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSShipConsolidationProposedShipmentRelationshipId name="Relationship_WHSShipConsolidationProposedShipmentRelationshipId">Relationship_WHSShipConsolidationProposedShipmentRelationshipId</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSShipConsolidationProposedShipmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WHSShipConsolidationProposedShipment.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSShipConsolidationProposedShipment.cdm.json/WHSShipConsolidationProposedShipment</a></td><td><a href="../Main/WHSShipConsolidationProposedShipment.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSShipConsolidationProposedShipmentContentRelationshipId name="Relationship_WHSShipConsolidationProposedShipmentContentRelationshipId">Relationship_WHSShipConsolidationProposedShipmentContentRelationshipId</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSShipConsolidationProposedShipmentContentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WHSShipConsolidationProposedShipmentContent.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSShipConsolidationProposedShipmentContent.cdm.json/WHSShipConsolidationProposedShipmentContent</a></td><td><a href="../Main/WHSShipConsolidationProposedShipmentContent.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/WHSShipConsolidationError (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

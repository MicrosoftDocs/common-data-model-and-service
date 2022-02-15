---
title: TaxReasonCodeForRestitutionComplementSetupData_BR in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Reason code for restitution/complement setup data in Miscellaneous(TaxReasonCodeForRestitutionComplementSetupData_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReasonCodeForRestitutionComplementSetupData_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code for restitution/complement setup data</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[ItemCode](#ItemCode)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[ItemRelation](#ItemRelation)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[TaxReasonCodeForRestitutionComplementSetupHeading_BR](#TaxReasonCodeForRestitutionComplementSetupHeading_BR)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[CFOPRelation](#CFOPRelation)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[CFOPCode](#CFOPCode)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[TaxationCode](#TaxationCode)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[FBReasonCodeForRestitution](#FBReasonCodeForRestitution)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[FBReasonCodeForComplement](#FBReasonCodeForComplement)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[Relationship_TaxReasonCodeForRestitutionComplementSetupHeading_BRRelationshipId](#Relationship_TaxReasonCodeForRestitutionComplementSetupHeading_BRRelationshipId)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[Relationship_FBReasonCodeForRestitutionComplement_BR_RestitutionRelationshipId](#Relationship_FBReasonCodeForRestitutionComplement_BR_RestitutionRelationshipId)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[Relationship_FBReasonCodeForRestitutionComplement_BR_ComplementRelationshipId](#Relationship_FBReasonCodeForRestitutionComplement_BR_ComplementRelationshipId)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[Relationship_CFOPTableRelationshipId](#Relationship_CFOPTableRelationshipId)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[Relationship_CFOPGroupRelationshipId](#Relationship_CFOPGroupRelationshipId)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[Relationship_InventItemGroupRelationshipId](#Relationship_InventItemGroupRelationshipId)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxReasonCodeForRestitutionComplementSetupData_BR.md" target="_blank">Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReasonCodeForRestitutionComplementSetupData_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item code</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ItemRelation name="ItemRelation">ItemRelation</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReasonCodeForRestitutionComplementSetupHeading_BR name="TaxReasonCodeForRestitutionComplementSetupHeading_BR">TaxReasonCodeForRestitutionComplementSetupHeading_BR</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReasonCodeForRestitutionComplementSetupHeading_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CFOPRelation name="CFOPRelation">CFOPRelation</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFOP relation</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFOP relation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPCode name="CFOPCode">CFOPCode</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CFOP code</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFOP code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxationCode name="TaxationCode">TaxationCode</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FBReasonCodeForRestitution name="FBReasonCodeForRestitution">FBReasonCodeForRestitution</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code for restitution</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBReasonCodeForRestitution attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code for restitution</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBReasonCodeForComplement name="FBReasonCodeForComplement">FBReasonCodeForComplement</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason code for complement</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBReasonCodeForComplement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason code for complement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

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

### <a href=#Relationship_TaxReasonCodeForRestitutionComplementSetupHeading_BRRelationshipId name="Relationship_TaxReasonCodeForRestitutionComplementSetupHeading_BRRelationshipId">Relationship_TaxReasonCodeForRestitutionComplementSetupHeading_BRRelationshipId</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReasonCodeForRestitutionComplementSetupHeading_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReasonCodeForRestitutionComplementSetupHeading_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxReasonCodeForRestitutionComplementSetupHeading_BR.cdm.json/TaxReasonCodeForRestitutionComplementSetupHeading_BR</a></td><td><a href="TaxReasonCodeForRestitutionComplementSetupHeading_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBReasonCodeForRestitutionComplement_BR_RestitutionRelationshipId name="Relationship_FBReasonCodeForRestitutionComplement_BR_RestitutionRelationshipId">Relationship_FBReasonCodeForRestitutionComplement_BR_RestitutionRelationshipId</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBReasonCodeForRestitutionComplement_BR_RestitutionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FiscalBooksBrazil/Miscellaneous/FBReasonCodeForRestitutionComplement_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBReasonCodeForRestitutionComplement_BR.cdm.json/FBReasonCodeForRestitutionComplement_BR</a></td><td><a href="../../FiscalBooksBrazil/Miscellaneous/FBReasonCodeForRestitutionComplement_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBReasonCodeForRestitutionComplement_BR_ComplementRelationshipId name="Relationship_FBReasonCodeForRestitutionComplement_BR_ComplementRelationshipId">Relationship_FBReasonCodeForRestitutionComplement_BR_ComplementRelationshipId</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBReasonCodeForRestitutionComplement_BR_ComplementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FiscalBooksBrazil/Miscellaneous/FBReasonCodeForRestitutionComplement_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBReasonCodeForRestitutionComplement_BR.cdm.json/FBReasonCodeForRestitutionComplement_BR</a></td><td><a href="../../FiscalBooksBrazil/Miscellaneous/FBReasonCodeForRestitutionComplement_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CFOPTableRelationshipId name="Relationship_CFOPTableRelationshipId">Relationship_CFOPTableRelationshipId</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CFOPTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/CFOPTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/CFOPTable_BR.cdm.json/CFOPTable_BR</a></td><td><a href="../../Bank/Group/CFOPTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CFOPGroupRelationshipId name="Relationship_CFOPGroupRelationshipId">Relationship_CFOPGroupRelationshipId</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CFOPGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Group/CFOPGroup_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Group/CFOPGroup_BR.cdm.json/CFOPGroup_BR</a></td><td><a href="../../APARShared/Group/CFOPGroup_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventItemGroupRelationshipId name="Relationship_InventItemGroupRelationshipId">Relationship_InventItemGroupRelationshipId</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventItemGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventItemGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventItemGroup.cdm.json/InventItemGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventItemGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/TaxReasonCodeForRestitutionComplementSetupData_BR (this entity)  

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

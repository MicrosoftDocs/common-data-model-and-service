---
title: VendVendorRegistrationQuestionnaireConfigurationEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Vendor registration questionnaire configuration in ProcurementAndSourcing(VendVendorRegistrationQuestionnaireConfigurationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/VendVendorRegistrationQuestionnaireConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor registration questionnaire configuration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[QuestionnaireDataAreaId](#QuestionnaireDataAreaId)||<a href="VendVendorRegistrationQuestionnaireConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendVendorRegistrationQuestionnaireConfigurationEntity</a>|
|[QuestionnaireId](#QuestionnaireId)||<a href="VendVendorRegistrationQuestionnaireConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendVendorRegistrationQuestionnaireConfigurationEntity</a>|
|[VendorRegistrationConfigurationRecId](#VendorRegistrationConfigurationRecId)||<a href="VendVendorRegistrationQuestionnaireConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendVendorRegistrationQuestionnaireConfigurationEntity</a>|
|[VendorRegistrationConfigurationName](#VendorRegistrationConfigurationName)||<a href="VendVendorRegistrationQuestionnaireConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendVendorRegistrationQuestionnaireConfigurationEntity</a>|
|[BackingTable_VendRequestProfileQuestionnaireRelationshipId](#BackingTable_VendRequestProfileQuestionnaireRelationshipId)||<a href="VendVendorRegistrationQuestionnaireConfigurationEntity.md" target="_blank">ProcurementAndSourcing/VendVendorRegistrationQuestionnaireConfigurationEntity</a>|

### <a href=#QuestionnaireDataAreaId name="QuestionnaireDataAreaId">QuestionnaireDataAreaId</a>

First included in: ProcurementAndSourcing/VendVendorRegistrationQuestionnaireConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionnaireDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuestionnaireId name="QuestionnaireId">QuestionnaireId</a>

First included in: ProcurementAndSourcing/VendVendorRegistrationQuestionnaireConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionnaireId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorRegistrationConfigurationRecId name="VendorRegistrationConfigurationRecId">VendorRegistrationConfigurationRecId</a>

First included in: ProcurementAndSourcing/VendVendorRegistrationQuestionnaireConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorRegistrationConfigurationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorRegistrationConfigurationName name="VendorRegistrationConfigurationName">VendorRegistrationConfigurationName</a>

First included in: ProcurementAndSourcing/VendVendorRegistrationQuestionnaireConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorRegistrationConfigurationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_VendRequestProfileQuestionnaireRelationshipId name="BackingTable_VendRequestProfileQuestionnaireRelationshipId">BackingTable_VendRequestProfileQuestionnaireRelationshipId</a>

First included in: ProcurementAndSourcing/VendVendorRegistrationQuestionnaireConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendRequestProfileQuestionnaireRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendRequestProfileQuestionnaire.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendRequestProfileQuestionnaire.cdm.json/VendRequestProfileQuestionnaire</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendRequestProfileQuestionnaire.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

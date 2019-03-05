---
title: CodeableConcept - Common Data Model | Microsoft Docs
description: This describes the CodeableConcept entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Codeable Concept

A Codeable Concept represents a value that is usually supplied by providing a reference to one or more terminologies, but may also be defined by the provision of text.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[codeableConceptId](#codeableConceptId)|Unique identifier for entity instances|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[stateCode](#stateCode)|Status of the Codeable Concept|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[stateCode_display](#stateCode_display)||<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[statusCode](#statusCode)|Reason for the status of the Codeable Concept|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[statusCode_display](#statusCode_display)||<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[name](#name)|The name of the custom entity.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[entityImageId](#entityImageId)||<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[code](#code)|Code defined by a terminology system.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[text](#text)|Plain text representation of the concept.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[type](#type)|Type of: Code-ableConcept represents a value that is usually supplied by providing a reference to one or more terminologies or ontologies, but may also be defined by the provision of text.|<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|
|[type_display](#type_display)||<a href="CodeableConcept.md" target="_blank">electronicMedicalRecords/CodeableConcept</a>|

### <a href=#codeableConceptId name="codeableConceptId">codeableConceptId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Codeable Concept</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_codeableconceptid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the codeableConceptId attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CodeableConcept/hasAttributes/codeableConceptId](#codeableConceptId)</td><td>attribute</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Codeable Concept</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for entity instances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msemr_codeableconceptid</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>1</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

- **is.dataFormat.date**  
- **means.measurement.date**  
- **is.dataFormat.time**  
- **means.measurement.time**  
- **means.measurement.date.creation**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>createdon</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>2</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdBy attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the user who created the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>createdby</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>3</td><td>integer</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../service/User.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User</a></td><td><a href="../../../service/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

- **is.dataFormat.date**  
- **means.measurement.date**  
- **is.dataFormat.time**  
- **means.measurement.time**  
- **means.measurement.date.modify**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedon</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>4</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedBy attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the user who modified the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedby</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>5</td><td>integer</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../service/User.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User</a></td><td><a href="../../../service/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOnBehalfBy attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the delegate user who created the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>createdonbehalfby</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>6</td><td>integer</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../service/User.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User</a></td><td><a href="../../../service/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOnBehalfBy attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the delegate user who modified the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedonbehalfby</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>7</td><td>integer</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../service/User.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User</a></td><td><a href="../../../service/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the organizationId attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organization Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the organization</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>organizationid</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>16</td><td>integer</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Organization.md" target="_blank">/core/applicationCommon/foundationCommon/Organization.cdm.json/Organization</a></td><td><a href="../../../../Organization.md#organizationId" target="_blank">organizationId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Codeable Concept  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Codeable Concept</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

- **is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

- **means.entityState**  
the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CodeableConcept/hasAttributes/stateCode](#stateCode)</td><td>attribute</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status of the Codeable Concept</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>statecode</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>18</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode_display attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **means.reference.displayText**  
- **is.readOnly**  
- **is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>stateCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

</details>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Codeable Concept  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Codeable Concept</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

- **is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

- **is.correlatedWith**  
the attribute value is correlated with the sourceAttribute  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>stateCode</td><td>attributeName</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status Reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason for the status of the Codeable Concept</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>statuscode</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>20</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode_display attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **means.reference.displayText**  
- **is.readOnly**  
- **is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>statusCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

</details>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the versionNumber attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **is.dataFormat.big**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>versionnumber</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>22</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence number of the import that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>importsequencenumber</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>23</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr></table>

</details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

- **is.dataFormat.date**  
- **means.measurement.date**  
- **is.dataFormat.time**  
- **means.measurement.time**  
- **means.measurement.date.creation**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>overriddencreatedon</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>24</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeZoneRuleVersionNumber attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>timezoneruleversionnumber</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>25</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr></table>

</details>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCConversionTimeZoneCode attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>utcconversiontimezonecode</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>26</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr></table>

</details>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **means.identity.name**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the custom entity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msemr_name</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>27</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the entityImageId attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>entityimageid</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>28</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#code name="code">code</a>

Code defined by a terminology system.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>description</td><td>Code defined by a terminology system.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_code</td></tr></table>

#### Traits

<details>
<summary>List of traits for the code attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Code defined by a terminology system.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msemr_code</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>32</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#text name="text">text</a>

Plain text representation of the concept.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Text</td></tr><tr><td>description</td><td>Plain text representation of the concept.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_text</td></tr></table>

#### Traits

<details>
<summary>List of traits for the text attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Text</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Plain text representation of the concept.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msemr_text</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>33</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>2000</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#type name="type">type</a>

Type of: Code-ableConcept represents a value that is usually supplied by providing a reference to one or more terminologies or ontologies, but may also be defined by the provision of text.  
First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Type of: Code-ableConcept represents a value that is usually supplied by providing a reference to one or more terminologies or ontologies, but may also be defined by the provision of text.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Action Participant Role</td><td>935000000</td></tr><tr><td>en</td><td>Action Reason</td><td>935000001</td></tr><tr><td>en</td><td>Activity Reason</td><td>935000002</td></tr><tr><td>en</td><td>Additional Dosage Instruction</td><td>935000003</td></tr><tr><td>en</td><td>Additive Code</td><td>935000004</td></tr><tr><td>en</td><td>Administration Method Code</td><td>935000005</td></tr><tr><td>en</td><td>Administration Site Code</td><td>935000006</td></tr><tr><td>en</td><td>Admit Source</td><td>935000007</td></tr><tr><td>en</td><td>Allergy Intolerance</td><td>935000008</td></tr><tr><td>en</td><td>Animal Breed</td><td>935000009</td></tr><tr><td>en</td><td>Animal Gender</td><td>935000010</td></tr><tr><td>en</td><td>Animal Species</td><td>935000011</td></tr><tr><td>en</td><td>As Needed Reason Code</td><td>935000012</td></tr><tr><td>en</td><td>Care Plan Activity</td><td>935000013</td></tr><tr><td>en</td><td>Care Plan Activity Category</td><td>935000014</td></tr><tr><td>en</td><td>Care Plan Activity Outcome</td><td>935000015</td></tr><tr><td>en</td><td>Care Plan Category</td><td>935000016</td></tr><tr><td>en</td><td>Care Team Category</td><td>935000017</td></tr><tr><td>en</td><td>Clinical Finding</td><td>935000018</td></tr><tr><td>en</td><td>Clinical Impression Code</td><td>935000019</td></tr><tr><td>en</td><td>Clinical Impression Prognosis</td><td>935000020</td></tr><tr><td>en</td><td>Communication Category</td><td>935000021</td></tr><tr><td>en</td><td>Condition Category Code</td><td>935000022</td></tr><tr><td>en</td><td>Condition Code</td><td>935000023</td></tr><tr><td>en</td><td>Condition Outcome Code</td><td>935000024</td></tr><tr><td>en</td><td>Condition Severity</td><td>935000025</td></tr><tr><td>en</td><td>Condition Stage</td><td>935000026</td></tr><tr><td>en</td><td>Contact Entity Type</td><td>935000027</td></tr><tr><td>en</td><td>Contact Role</td><td>935000028</td></tr><tr><td>en</td><td>Data Requirement Code Filter Value Code</td><td>935000029</td></tr><tr><td>en</td><td>Definition Topic</td><td>935000030</td></tr><tr><td>en</td><td>Detected Issue</td><td>935000031</td></tr><tr><td>en</td><td>Device Component Operational Status</td><td>935000032</td></tr><tr><td>en</td><td>Device Component Parameter Group</td><td>935000033</td></tr><tr><td>en</td><td>Device Metric Type</td><td>935000034</td></tr><tr><td>en</td><td>Device Safety</td><td>935000035</td></tr><tr><td>en</td><td>Device Specification Spec Type</td><td>935000036</td></tr><tr><td>en</td><td>Device Type</td><td>935000037</td></tr><tr><td>en</td><td>Diagnosis Role</td><td>935000038</td></tr><tr><td>en</td><td>Diagnostic Report</td><td>935000039</td></tr><tr><td>en</td><td>Diet</td><td>935000040</td></tr><tr><td>en</td><td>Diet Code</td><td>935000041</td></tr><tr><td>en</td><td>Discharge Disposition</td><td>935000042</td></tr><tr><td>en</td><td>Encounter Reason Code</td><td>935000043</td></tr><tr><td>en</td><td>Encounter Type</td><td>935000044</td></tr><tr><td>en</td><td>Endpoint Payload Type</td><td>935000045</td></tr><tr><td>en</td><td>Enteral Formula Additive Type Code</td><td>935000046</td></tr><tr><td>en</td><td>Enteral Formula Type Code</td><td>935000047</td></tr><tr><td>en</td><td>Enteral Route Code</td><td>935000048</td></tr><tr><td>en</td><td>Episode Of Care Type</td><td>935000049</td></tr><tr><td>en</td><td>Event History</td><td>935000050</td></tr><tr><td>en</td><td>Family History Not Done Reason</td><td>935000051</td></tr><tr><td>en</td><td>Family Member</td><td>935000053</td></tr><tr><td>en</td><td>FHIR Type</td><td>935000054</td></tr><tr><td>en</td><td>Financial Account</td><td>935000055</td></tr><tr><td>en</td><td>Fluid Consistency Type Code</td><td>935000056</td></tr><tr><td>en</td><td>Food Type Code</td><td>935000057</td></tr><tr><td>en</td><td>Form Code</td><td>935000058</td></tr><tr><td>en</td><td>Goal Category</td><td>935000059</td></tr><tr><td>en</td><td>Goal Priority</td><td>935000060</td></tr><tr><td>en</td><td>Goal Start Event</td><td>935000061</td></tr><tr><td>en</td><td>Goal Target Detail</td><td>935000062</td></tr><tr><td>en</td><td>Group</td><td>935000063</td></tr><tr><td>en</td><td>Imaging Study</td><td>935000064</td></tr><tr><td>en</td><td>Immunization Request</td><td>935000065</td></tr><tr><td>en</td><td>Investigation Type</td><td>935000066</td></tr><tr><td>en</td><td>Jurisdiction</td><td>935000067</td></tr><tr><td>en</td><td>Language</td><td>935000068</td></tr><tr><td>en</td><td>Library</td><td>935000070</td></tr><tr><td>en</td><td>Link Type</td><td>935000071</td></tr><tr><td>en</td><td>Location Type</td><td>935000072</td></tr><tr><td>en</td><td>LOINC Code</td><td>935000073</td></tr><tr><td>en</td><td>Medication Administration Category</td><td>935000074</td></tr><tr><td>en</td><td>Medication As Needed Reason Code</td><td>935000075</td></tr><tr><td>en</td><td>Medication Code</td><td>935000076</td></tr><tr><td>en</td><td>Medication Container</td><td>935000077</td></tr><tr><td>en</td><td>Medication Ingredient</td><td>935000078</td></tr><tr><td>en</td><td>Medication Package Content</td><td>935000079</td></tr><tr><td>en</td><td>Medication Request Category</td><td>935000080</td></tr><tr><td>en</td><td>Medication Statement</td><td>935000081</td></tr><tr><td>en</td><td>Nutrient Modifier Code</td><td>935000082</td></tr><tr><td>en</td><td>Observation Category Code</td><td>935000083</td></tr><tr><td>en</td><td>Observation Component Value</td><td>935000084</td></tr><tr><td>en</td><td>Observation Interpretation Code</td><td>935000085</td></tr><tr><td>en</td><td>Observation Method</td><td>935000086</td></tr><tr><td>en</td><td>Observation Reference Range Applies To Code</td><td>935000087</td></tr><tr><td>en</td><td>Observation Reference Range Meaning Code</td><td>935000088</td></tr><tr><td>en</td><td>Observation Value Absent Reason</td><td>935000089</td></tr><tr><td>en</td><td>Observation Value Code</td><td>935000090</td></tr><tr><td>en</td><td>Participant Role</td><td>935000091</td></tr><tr><td>en</td><td>Participant Type</td><td>935000092</td></tr><tr><td>en</td><td>Participation Mode</td><td>935000093</td></tr><tr><td>en</td><td>Patient Referral Type</td><td>935000094</td></tr><tr><td>en</td><td>Patient Relationship Type</td><td>935000095</td></tr><tr><td>en</td><td>Plan Definition Action Code</td><td>935000096</td></tr><tr><td>en</td><td>Plan Definition Action Reason</td><td>935000097</td></tr><tr><td>en</td><td>Plan Definition Goal Target</td><td>935000098</td></tr><tr><td>en</td><td>Practice Setting Code</td><td>935000099</td></tr><tr><td>en</td><td>Practitioner Role</td><td>935000100</td></tr><tr><td>en</td><td>Practitioner Specialty</td><td>935000101</td></tr><tr><td>en</td><td>Priority</td><td>935000102</td></tr><tr><td>en</td><td>Procedure Category Code</td><td>935000103</td></tr><tr><td>en</td><td>Procedure Code</td><td>935000104</td></tr><tr><td>en</td><td>Procedure Device Action Code</td><td>935000105</td></tr><tr><td>en</td><td>Procedure Follow up Code</td><td>935000106</td></tr><tr><td>en</td><td>Procedure Outcome Code</td><td>935000107</td></tr><tr><td>en</td><td>Procedure Performer Role Code</td><td>935000108</td></tr><tr><td>en</td><td>Procedure Reason Code</td><td>935000109</td></tr><tr><td>en</td><td>Provenance</td><td>935000110</td></tr><tr><td>en</td><td>Quantity Unit Code</td><td>935000111</td></tr><tr><td>en</td><td>Questionnaire</td><td>935000112</td></tr><tr><td>en</td><td>Questionnaire Response</td><td>935000113</td></tr><tr><td>en</td><td>Re-Admission Indicator</td><td>935000114</td></tr><tr><td>en</td><td>Reason Medication Given Code</td><td>935000116</td></tr><tr><td>en</td><td>Reason Medication Not Given Code</td><td>935000117</td></tr><tr><td>en</td><td>Referral Method</td><td>935000118</td></tr><tr><td>en</td><td>Request Group Action Code</td><td>935000119</td></tr><tr><td>en</td><td>Request Group Reason Code</td><td>935000120</td></tr><tr><td>en</td><td>Request Intent</td><td>935000121</td></tr><tr><td>en</td><td>Resource Type</td><td>935000122</td></tr><tr><td>en</td><td>Risk Assessment Code</td><td>935000123</td></tr><tr><td>en</td><td>Risk Assessment Method</td><td>935000124</td></tr><tr><td>en</td><td>Risk Assessment Outcome</td><td>935000125</td></tr><tr><td>en</td><td>Risk Assessment Reason Code</td><td>935000126</td></tr><tr><td>en</td><td>Route Code</td><td>935000127</td></tr><tr><td>en</td><td>Sequence</td><td>935000128</td></tr><tr><td>en</td><td>Service Category</td><td>935000129</td></tr><tr><td>en</td><td>Service Characteristic</td><td>935000130</td></tr><tr><td>en</td><td>Service Delivery Location Role Type</td><td>935000131</td></tr><tr><td>en</td><td>Service Eligibility</td><td>935000132</td></tr><tr><td>en</td><td>Service Provision Condition</td><td>935000133</td></tr><tr><td>en</td><td>Service Type</td><td>935000134</td></tr><tr><td>en</td><td>Snomed CT Medication Codes</td><td>935000135</td></tr><tr><td>en</td><td>Special Arrangement</td><td>935000136</td></tr><tr><td>en</td><td>Special Courtesy</td><td>935000137</td></tr><tr><td>en</td><td>Specialty</td><td>935000138</td></tr><tr><td>en</td><td>Specimen Collection Method</td><td>935000139</td></tr><tr><td>en</td><td>Specimen Container</td><td>935000140</td></tr><tr><td>en</td><td>Specimen Processing Procedure</td><td>935000141</td></tr><tr><td>en</td><td>Specimen Type</td><td>935000142</td></tr><tr><td>en</td><td>Structure Map</td><td>935000143</td></tr><tr><td>en</td><td>Substance Admin Substitution Reason</td><td>935000144</td></tr><tr><td>en</td><td>Substance Category Code</td><td>935000145</td></tr><tr><td>en</td><td>Substance Code</td><td>935000146</td></tr><tr><td>en</td><td>Supplement Type Code</td><td>935000147</td></tr><tr><td>en</td><td>Symptom Code</td><td>935000148</td></tr><tr><td>en</td><td>Task Business Status</td><td>935000149</td></tr><tr><td>en</td><td>Task Code</td><td>935000150</td></tr><tr><td>en</td><td>Task Input Parameter Type</td><td>935000151</td></tr><tr><td>en</td><td>Task Output Parameter Type</td><td>935000152</td></tr><tr><td>en</td><td>Task Performer Type</td><td>935000153</td></tr><tr><td>en</td><td>Task Reason</td><td>935000154</td></tr><tr><td>en</td><td>Task Status Reason</td><td>935000155</td></tr><tr><td>en</td><td>Texture Modified Food Type Code</td><td>935000156</td></tr><tr><td>en</td><td>Texture Modifier Code</td><td>935000157</td></tr><tr><td>en</td><td>Topic</td><td>935000158</td></tr><tr><td>en</td><td>Use Context</td><td>935000159</td></tr><tr><td>en</td><td>Value Set</td><td>935000160</td></tr><tr><td>en</td><td>Vision Prescription Product Code</td><td>935000161</td></tr><tr><td>en</td><td>Vision Prescription Reason Code</td><td>935000162</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the type attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Action Participant Role</td><td>935000000</td></tr><tr><td>en</td><td>Action Reason</td><td>935000001</td></tr><tr><td>en</td><td>Activity Reason</td><td>935000002</td></tr><tr><td>en</td><td>Additional Dosage Instruction</td><td>935000003</td></tr><tr><td>en</td><td>Additive Code</td><td>935000004</td></tr><tr><td>en</td><td>Administration Method Code</td><td>935000005</td></tr><tr><td>en</td><td>Administration Site Code</td><td>935000006</td></tr><tr><td>en</td><td>Admit Source</td><td>935000007</td></tr><tr><td>en</td><td>Allergy Intolerance</td><td>935000008</td></tr><tr><td>en</td><td>Animal Breed</td><td>935000009</td></tr><tr><td>en</td><td>Animal Gender</td><td>935000010</td></tr><tr><td>en</td><td>Animal Species</td><td>935000011</td></tr><tr><td>en</td><td>As Needed Reason Code</td><td>935000012</td></tr><tr><td>en</td><td>Care Plan Activity</td><td>935000013</td></tr><tr><td>en</td><td>Care Plan Activity Category</td><td>935000014</td></tr><tr><td>en</td><td>Care Plan Activity Outcome</td><td>935000015</td></tr><tr><td>en</td><td>Care Plan Category</td><td>935000016</td></tr><tr><td>en</td><td>Care Team Category</td><td>935000017</td></tr><tr><td>en</td><td>Clinical Finding</td><td>935000018</td></tr><tr><td>en</td><td>Clinical Impression Code</td><td>935000019</td></tr><tr><td>en</td><td>Clinical Impression Prognosis</td><td>935000020</td></tr><tr><td>en</td><td>Communication Category</td><td>935000021</td></tr><tr><td>en</td><td>Condition Category Code</td><td>935000022</td></tr><tr><td>en</td><td>Condition Code</td><td>935000023</td></tr><tr><td>en</td><td>Condition Outcome Code</td><td>935000024</td></tr><tr><td>en</td><td>Condition Severity</td><td>935000025</td></tr><tr><td>en</td><td>Condition Stage</td><td>935000026</td></tr><tr><td>en</td><td>Contact Entity Type</td><td>935000027</td></tr><tr><td>en</td><td>Contact Role</td><td>935000028</td></tr><tr><td>en</td><td>Data Requirement Code Filter Value Code</td><td>935000029</td></tr><tr><td>en</td><td>Definition Topic</td><td>935000030</td></tr><tr><td>en</td><td>Detected Issue</td><td>935000031</td></tr><tr><td>en</td><td>Device Component Operational Status</td><td>935000032</td></tr><tr><td>en</td><td>Device Component Parameter Group</td><td>935000033</td></tr><tr><td>en</td><td>Device Metric Type</td><td>935000034</td></tr><tr><td>en</td><td>Device Safety</td><td>935000035</td></tr><tr><td>en</td><td>Device Specification Spec Type</td><td>935000036</td></tr><tr><td>en</td><td>Device Type</td><td>935000037</td></tr><tr><td>en</td><td>Diagnosis Role</td><td>935000038</td></tr><tr><td>en</td><td>Diagnostic Report</td><td>935000039</td></tr><tr><td>en</td><td>Diet</td><td>935000040</td></tr><tr><td>en</td><td>Diet Code</td><td>935000041</td></tr><tr><td>en</td><td>Discharge Disposition</td><td>935000042</td></tr><tr><td>en</td><td>Encounter Reason Code</td><td>935000043</td></tr><tr><td>en</td><td>Encounter Type</td><td>935000044</td></tr><tr><td>en</td><td>Endpoint Payload Type</td><td>935000045</td></tr><tr><td>en</td><td>Enteral Formula Additive Type Code</td><td>935000046</td></tr><tr><td>en</td><td>Enteral Formula Type Code</td><td>935000047</td></tr><tr><td>en</td><td>Enteral Route Code</td><td>935000048</td></tr><tr><td>en</td><td>Episode Of Care Type</td><td>935000049</td></tr><tr><td>en</td><td>Event History</td><td>935000050</td></tr><tr><td>en</td><td>Family History Not Done Reason</td><td>935000051</td></tr><tr><td>en</td><td>Family Member</td><td>935000053</td></tr><tr><td>en</td><td>FHIR Type</td><td>935000054</td></tr><tr><td>en</td><td>Financial Account</td><td>935000055</td></tr><tr><td>en</td><td>Fluid Consistency Type Code</td><td>935000056</td></tr><tr><td>en</td><td>Food Type Code</td><td>935000057</td></tr><tr><td>en</td><td>Form Code</td><td>935000058</td></tr><tr><td>en</td><td>Goal Category</td><td>935000059</td></tr><tr><td>en</td><td>Goal Priority</td><td>935000060</td></tr><tr><td>en</td><td>Goal Start Event</td><td>935000061</td></tr><tr><td>en</td><td>Goal Target Detail</td><td>935000062</td></tr><tr><td>en</td><td>Group</td><td>935000063</td></tr><tr><td>en</td><td>Imaging Study</td><td>935000064</td></tr><tr><td>en</td><td>Immunization Request</td><td>935000065</td></tr><tr><td>en</td><td>Investigation Type</td><td>935000066</td></tr><tr><td>en</td><td>Jurisdiction</td><td>935000067</td></tr><tr><td>en</td><td>Language</td><td>935000068</td></tr><tr><td>en</td><td>Library</td><td>935000070</td></tr><tr><td>en</td><td>Link Type</td><td>935000071</td></tr><tr><td>en</td><td>Location Type</td><td>935000072</td></tr><tr><td>en</td><td>LOINC Code</td><td>935000073</td></tr><tr><td>en</td><td>Medication Administration Category</td><td>935000074</td></tr><tr><td>en</td><td>Medication As Needed Reason Code</td><td>935000075</td></tr><tr><td>en</td><td>Medication Code</td><td>935000076</td></tr><tr><td>en</td><td>Medication Container</td><td>935000077</td></tr><tr><td>en</td><td>Medication Ingredient</td><td>935000078</td></tr><tr><td>en</td><td>Medication Package Content</td><td>935000079</td></tr><tr><td>en</td><td>Medication Request Category</td><td>935000080</td></tr><tr><td>en</td><td>Medication Statement</td><td>935000081</td></tr><tr><td>en</td><td>Nutrient Modifier Code</td><td>935000082</td></tr><tr><td>en</td><td>Observation Category Code</td><td>935000083</td></tr><tr><td>en</td><td>Observation Component Value</td><td>935000084</td></tr><tr><td>en</td><td>Observation Interpretation Code</td><td>935000085</td></tr><tr><td>en</td><td>Observation Method</td><td>935000086</td></tr><tr><td>en</td><td>Observation Reference Range Applies To Code</td><td>935000087</td></tr><tr><td>en</td><td>Observation Reference Range Meaning Code</td><td>935000088</td></tr><tr><td>en</td><td>Observation Value Absent Reason</td><td>935000089</td></tr><tr><td>en</td><td>Observation Value Code</td><td>935000090</td></tr><tr><td>en</td><td>Participant Role</td><td>935000091</td></tr><tr><td>en</td><td>Participant Type</td><td>935000092</td></tr><tr><td>en</td><td>Participation Mode</td><td>935000093</td></tr><tr><td>en</td><td>Patient Referral Type</td><td>935000094</td></tr><tr><td>en</td><td>Patient Relationship Type</td><td>935000095</td></tr><tr><td>en</td><td>Plan Definition Action Code</td><td>935000096</td></tr><tr><td>en</td><td>Plan Definition Action Reason</td><td>935000097</td></tr><tr><td>en</td><td>Plan Definition Goal Target</td><td>935000098</td></tr><tr><td>en</td><td>Practice Setting Code</td><td>935000099</td></tr><tr><td>en</td><td>Practitioner Role</td><td>935000100</td></tr><tr><td>en</td><td>Practitioner Specialty</td><td>935000101</td></tr><tr><td>en</td><td>Priority</td><td>935000102</td></tr><tr><td>en</td><td>Procedure Category Code</td><td>935000103</td></tr><tr><td>en</td><td>Procedure Code</td><td>935000104</td></tr><tr><td>en</td><td>Procedure Device Action Code</td><td>935000105</td></tr><tr><td>en</td><td>Procedure Follow up Code</td><td>935000106</td></tr><tr><td>en</td><td>Procedure Outcome Code</td><td>935000107</td></tr><tr><td>en</td><td>Procedure Performer Role Code</td><td>935000108</td></tr><tr><td>en</td><td>Procedure Reason Code</td><td>935000109</td></tr><tr><td>en</td><td>Provenance</td><td>935000110</td></tr><tr><td>en</td><td>Quantity Unit Code</td><td>935000111</td></tr><tr><td>en</td><td>Questionnaire</td><td>935000112</td></tr><tr><td>en</td><td>Questionnaire Response</td><td>935000113</td></tr><tr><td>en</td><td>Re-Admission Indicator</td><td>935000114</td></tr><tr><td>en</td><td>Reason Medication Given Code</td><td>935000116</td></tr><tr><td>en</td><td>Reason Medication Not Given Code</td><td>935000117</td></tr><tr><td>en</td><td>Referral Method</td><td>935000118</td></tr><tr><td>en</td><td>Request Group Action Code</td><td>935000119</td></tr><tr><td>en</td><td>Request Group Reason Code</td><td>935000120</td></tr><tr><td>en</td><td>Request Intent</td><td>935000121</td></tr><tr><td>en</td><td>Resource Type</td><td>935000122</td></tr><tr><td>en</td><td>Risk Assessment Code</td><td>935000123</td></tr><tr><td>en</td><td>Risk Assessment Method</td><td>935000124</td></tr><tr><td>en</td><td>Risk Assessment Outcome</td><td>935000125</td></tr><tr><td>en</td><td>Risk Assessment Reason Code</td><td>935000126</td></tr><tr><td>en</td><td>Route Code</td><td>935000127</td></tr><tr><td>en</td><td>Sequence</td><td>935000128</td></tr><tr><td>en</td><td>Service Category</td><td>935000129</td></tr><tr><td>en</td><td>Service Characteristic</td><td>935000130</td></tr><tr><td>en</td><td>Service Delivery Location Role Type</td><td>935000131</td></tr><tr><td>en</td><td>Service Eligibility</td><td>935000132</td></tr><tr><td>en</td><td>Service Provision Condition</td><td>935000133</td></tr><tr><td>en</td><td>Service Type</td><td>935000134</td></tr><tr><td>en</td><td>Snomed CT Medication Codes</td><td>935000135</td></tr><tr><td>en</td><td>Special Arrangement</td><td>935000136</td></tr><tr><td>en</td><td>Special Courtesy</td><td>935000137</td></tr><tr><td>en</td><td>Specialty</td><td>935000138</td></tr><tr><td>en</td><td>Specimen Collection Method</td><td>935000139</td></tr><tr><td>en</td><td>Specimen Container</td><td>935000140</td></tr><tr><td>en</td><td>Specimen Processing Procedure</td><td>935000141</td></tr><tr><td>en</td><td>Specimen Type</td><td>935000142</td></tr><tr><td>en</td><td>Structure Map</td><td>935000143</td></tr><tr><td>en</td><td>Substance Admin Substitution Reason</td><td>935000144</td></tr><tr><td>en</td><td>Substance Category Code</td><td>935000145</td></tr><tr><td>en</td><td>Substance Code</td><td>935000146</td></tr><tr><td>en</td><td>Supplement Type Code</td><td>935000147</td></tr><tr><td>en</td><td>Symptom Code</td><td>935000148</td></tr><tr><td>en</td><td>Task Business Status</td><td>935000149</td></tr><tr><td>en</td><td>Task Code</td><td>935000150</td></tr><tr><td>en</td><td>Task Input Parameter Type</td><td>935000151</td></tr><tr><td>en</td><td>Task Output Parameter Type</td><td>935000152</td></tr><tr><td>en</td><td>Task Performer Type</td><td>935000153</td></tr><tr><td>en</td><td>Task Reason</td><td>935000154</td></tr><tr><td>en</td><td>Task Status Reason</td><td>935000155</td></tr><tr><td>en</td><td>Texture Modified Food Type Code</td><td>935000156</td></tr><tr><td>en</td><td>Texture Modifier Code</td><td>935000157</td></tr><tr><td>en</td><td>Topic</td><td>935000158</td></tr><tr><td>en</td><td>Use Context</td><td>935000159</td></tr><tr><td>en</td><td>Value Set</td><td>935000160</td></tr><tr><td>en</td><td>Vision Prescription Product Code</td><td>935000161</td></tr><tr><td>en</td><td>Vision Prescription Reason Code</td><td>935000162</td></tr></table></td><td>any</td><td></td></tr></table>

- **is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type of: Code-ableConcept represents a value that is usually supplied by providing a reference to one or more terminologies or ontologies, but may also be defined by the provision of text.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msemr_type</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>34</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#type_display name="type_display">type_display</a>

First included in: electronicMedicalRecords/CodeableConcept (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the type_display attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **means.reference.displayText**  
- **is.readOnly**  
- **is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>type</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

</details>

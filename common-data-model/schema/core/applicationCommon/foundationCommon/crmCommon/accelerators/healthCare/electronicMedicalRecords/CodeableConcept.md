---
title: CodeableConcept
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/5/2019
ms.author: tpalmer
---

# Codeable Concept

## Properties

Display Name: Codeable Concept

Description: A Codeable Concept represents a value that is usually supplied by providing a reference to one or more terminologies, but may also be defined by the provision of text.

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json)

## Instances

[/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept](CodeableConcept.md)

## Attributes - Summary

|Name|Description|First Included in Instance|
|---|---|---|
|[codeableConceptId](#codeableConceptId)|Unique identifier for entity instances|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[createdOn](#createdOn)|Date and time when the record was created.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[organizationId](#organizationId)|Unique identifier for the organization|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[stateCode](#stateCode)|Status of the Codeable Concept|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[stateCode_display](#stateCode_display)||[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[statusCode](#statusCode)|Reason for the status of the Codeable Concept|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[statusCode_display](#statusCode_display)||[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[versionNumber](#versionNumber)|Version Number|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[name](#name)|The name of the custom entity.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[entityImageId](#entityImageId)||[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[code](#code)|Code defined by a terminology system.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[text](#text)|Plain text representation of the concept.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[type](#type)|Type of: Code-ableConcept represents a value that is usually supplied by providing a reference to one or more terminologies or ontologies, but may also be defined by the provision of text.|[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|
|[type_display](#type_display)||[electronicMedicalRecords/CodeableConcept](CodeableConcept.md)|

## Attribute - Details

### <a name="codeableConceptId">codeableConceptId</a>

Unique identifier for entity instances

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Codeable Concept</td></tr>
<tr><td>description</td><td>Unique identifier for entity instances</td></tr>
<tr><td>isPrimaryKey</td><td>true</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>sourceName</td><td>msemr_codeableconceptid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>attribute</td><td>"CodeableConcept_/hasAttributes/codeableConceptId"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"CodeableConcept_/hasAttributes/codeableConceptId"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Codeable Concept</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier for entity instances</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>msemr_codeableconceptid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>1</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="createdOn">createdOn</a>

Date and time when the record was created.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created On</td></tr>
<tr><td>description</td><td>Date and time when the record was created.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>createdon</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### means.measurement.date.creation

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created On</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Date and time when the record was created.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>createdon</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>2</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="createdBy">createdBy</a>

Unique identifier of the user who created the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created By</td></tr>
<tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>createdby</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created By</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the user who created the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>createdby</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>3</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "createdBy",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Created By"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier of the user who created the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By",
  "description": "Unique identifier of the user who created the record.",
  "isNullable": true,
  "sourceName": "createdby",
  "sourceOrdering": 3
}
```

</details>

### <a name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified On</td></tr>
<tr><td>description</td><td>Date and time when the record was modified.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>modifiedon</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### means.measurement.date.modify

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified On</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Date and time when the record was modified.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>modifiedon</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>4</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified By</td></tr>
<tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>modifiedby</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified By</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the user who modified the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>modifiedby</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>5</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "modifiedBy",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Modified By"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier of the user who modified the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By",
  "description": "Unique identifier of the user who modified the record.",
  "isNullable": true,
  "sourceName": "modifiedby",
  "sourceOrdering": 5
}
```

</details>

### <a name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created By (Delegate)</td></tr>
<tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>createdonbehalfby</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created By (Delegate)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the delegate user who created the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>createdonbehalfby</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>6</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "createdOnBehalfBy",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Created By (Delegate)"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier of the delegate user who created the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By (Delegate)",
  "description": "Unique identifier of the delegate user who created the record.",
  "isNullable": true,
  "sourceName": "createdonbehalfby",
  "sourceOrdering": 6
}
```

</details>

### <a name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified By (Delegate)</td></tr>
<tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>modifiedonbehalfby</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified By (Delegate)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the delegate user who modified the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>modifiedonbehalfby</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>7</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "modifiedOnBehalfBy",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Modified By (Delegate)"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier of the delegate user who modified the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By (Delegate)",
  "description": "Unique identifier of the delegate user who modified the record.",
  "isNullable": true,
  "sourceName": "modifiedonbehalfby",
  "sourceOrdering": 7
}
```

</details>

### <a name="organizationId">organizationId</a>

Unique identifier for the organization

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Organization Id</td></tr>
<tr><td>description</td><td>Unique identifier for the organization</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>organizationid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Organization Id</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier for the organization</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>organizationid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>16</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "organizationId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Organization Id"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for the organization"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Organization Id",
  "description": "Unique identifier for the organization",
  "isNullable": true,
  "sourceName": "organizationid",
  "sourceOrdering": 16
}
```

</details>

### <a name="stateCode">stateCode</a>

Status of the Codeable Concept

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Status</td></tr>
<tr><td>description</td><td>Status of the Codeable Concept</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>sourceName</td><td>statecode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Active",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Inactive",
    "attributeValue": "1",
    "displayOrder": "1"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Active</td><td>0</td><td>0</td></tr>
<tr><td>en</td><td>Inactive</td><td>1</td><td>1</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### means.entityState

the attribute represents the current state of the entity.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>attribute</td><td>"CodeableConcept_/hasAttributes/stateCode"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"CodeableConcept_/hasAttributes/stateCode"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Status</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Status of the Codeable Concept</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>statecode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>18</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="stateCode_display">stateCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>stateCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="statusCode">statusCode</a>

Reason for the status of the Codeable Concept

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Status Reason</td></tr>
<tr><td>description</td><td>Reason for the status of the Codeable Concept</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>statuscode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Active",
    "attributeValue": "1",
    "displayOrder": "0",
    "correlatedValue": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Inactive",
    "attributeValue": "2",
    "displayOrder": "1",
    "correlatedValue": "1"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>correlatedValue</th></tr>
<tr><td>en</td><td>Active</td><td>1</td><td>0</td><td>0</td></tr>
<tr><td>en</td><td>Inactive</td><td>2</td><td>1</td><td>1</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.correlatedWith

the attribute value is correlated with the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>sourceAttribute</td><td>stateCode</td><td>attributeName</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Status Reason</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Reason for the status of the Codeable Concept</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>statuscode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>20</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="statusCode_display">statusCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>statusCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="versionNumber">versionNumber</a>

Version Number

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Version Number</td></tr>
<tr><td>description</td><td>Version Number</td></tr>
<tr><td>dataFormat</td><td>Int64</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>versionnumber</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.dataFormat.big

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Version Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Version Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>versionnumber</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>22</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Import Sequence Number</td></tr>
<tr><td>description</td><td>Sequence number of the import that created this record.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>-2147483648</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>importsequencenumber</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Import Sequence Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Sequence number of the import that created this record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>importsequencenumber</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>23</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Record Created On</td></tr>
<tr><td>description</td><td>Date and time that the record was migrated.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>overriddencreatedon</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### means.measurement.date.creation

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Record Created On</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Date and time that the record was migrated.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>overriddencreatedon</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>24</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr>
<tr><td>description</td><td>For internal use only.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>-1</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Time Zone Rule Version Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>For internal use only.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>timezoneruleversionnumber</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>25</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr>
<tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>-1</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>utcconversiontimezonecode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>26</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="name">name</a>

The name of the custom entity.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Name</td></tr>
<tr><td>description</td><td>The name of the custom entity.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>msemr_name</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.identity.name

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The name of the custom entity.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>msemr_name</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>27</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="entityImageId">entityImageId</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>entityimageid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>entityimageid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>28</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="code">code</a>

Code defined by a terminology system.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Code</td></tr>
<tr><td>description</td><td>Code defined by a terminology system.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>msemr_code</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Code</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Code defined by a terminology system.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>msemr_code</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>32</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="text">text</a>

Plain text representation of the concept.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Text</td></tr>
<tr><td>description</td><td>Plain text representation of the concept.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>2000</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>msemr_text</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Text</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Plain text representation of the concept.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>msemr_text</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>33</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>2000</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="type">type</a>

Type of: Code-ableConcept represents a value that is usually supplied by providing a reference to one or more terminologies or ontologies, but may also be defined by the provision of text.

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Type</td></tr>
<tr><td>description</td><td>Type of: Code-ableConcept represents a value that is usually supplied by providing a reference to one or more terminologies or ontologies, but may also be defined by the provision of text.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>msemr_type</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Additional Dosage Instruction",
    "attributeValue": "935000003",
    "displayOrder": "3"
  },
  {
    "languageTag": "en",
    "displayText": "Additive Code",
    "attributeValue": "935000004",
    "displayOrder": "4"
  },
  {
    "languageTag": "en",
    "displayText": "Allergy Intolerance",
    "attributeValue": "935000008",
    "displayOrder": "8"
  },
  {
    "languageTag": "en",
    "displayText": "Animal Breed",
    "attributeValue": "935000009",
    "displayOrder": "9"
  },
  {
    "languageTag": "en",
    "displayText": "Animal Gender",
    "attributeValue": "935000010",
    "displayOrder": "10"
  },
  {
    "languageTag": "en",
    "displayText": "Action Participant Role",
    "attributeValue": "935000000",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Action Reason",
    "attributeValue": "935000001",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Activity Reason",
    "attributeValue": "935000002",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Care Plan Activity Category",
    "attributeValue": "935000014",
    "displayOrder": "14"
  },
  {
    "languageTag": "en",
    "displayText": "Care Plan Activity Outcome",
    "attributeValue": "935000015",
    "displayOrder": "15"
  },
  {
    "languageTag": "en",
    "displayText": "Care Plan Category",
    "attributeValue": "935000016",
    "displayOrder": "16"
  },
  {
    "languageTag": "en",
    "displayText": "Administration Method Code",
    "attributeValue": "935000005",
    "displayOrder": "5"
  },
  {
    "languageTag": "en",
    "displayText": "Administration Site Code",
    "attributeValue": "935000006",
    "displayOrder": "6"
  },
  {
    "languageTag": "en",
    "displayText": "Admit Source",
    "attributeValue": "935000007",
    "displayOrder": "7"
  },
  {
    "languageTag": "en",
    "displayText": "Clinical Impression Prognosis",
    "attributeValue": "935000020",
    "displayOrder": "20"
  },
  {
    "languageTag": "en",
    "displayText": "Communication Category",
    "attributeValue": "935000021",
    "displayOrder": "21"
  },
  {
    "languageTag": "en",
    "displayText": "Condition Category Code",
    "attributeValue": "935000022",
    "displayOrder": "22"
  },
  {
    "languageTag": "en",
    "displayText": "Animal Species",
    "attributeValue": "935000011",
    "displayOrder": "11"
  },
  {
    "languageTag": "en",
    "displayText": "As Needed Reason Code",
    "attributeValue": "935000012",
    "displayOrder": "12"
  },
  {
    "languageTag": "en",
    "displayText": "Care Plan Activity",
    "attributeValue": "935000013",
    "displayOrder": "13"
  },
  {
    "languageTag": "en",
    "displayText": "Condition Stage",
    "attributeValue": "935000026",
    "displayOrder": "26"
  },
  {
    "languageTag": "en",
    "displayText": "Contact Entity Type",
    "attributeValue": "935000027",
    "displayOrder": "27"
  },
  {
    "languageTag": "en",
    "displayText": "Contact Role",
    "attributeValue": "935000028",
    "displayOrder": "28"
  },
  {
    "languageTag": "en",
    "displayText": "Care Team Category",
    "attributeValue": "935000017",
    "displayOrder": "17"
  },
  {
    "languageTag": "en",
    "displayText": "Clinical Finding",
    "attributeValue": "935000018",
    "displayOrder": "18"
  },
  {
    "languageTag": "en",
    "displayText": "Clinical Impression Code",
    "attributeValue": "935000019",
    "displayOrder": "19"
  },
  {
    "languageTag": "en",
    "displayText": "Device Component Operational Status",
    "attributeValue": "935000032",
    "displayOrder": "32"
  },
  {
    "languageTag": "en",
    "displayText": "Device Component Parameter Group",
    "attributeValue": "935000033",
    "displayOrder": "33"
  },
  {
    "languageTag": "en",
    "displayText": "Device Metric Type",
    "attributeValue": "935000034",
    "displayOrder": "34"
  },
  {
    "languageTag": "en",
    "displayText": "Condition Code",
    "attributeValue": "935000023",
    "displayOrder": "23"
  },
  {
    "languageTag": "en",
    "displayText": "Condition Outcome Code",
    "attributeValue": "935000024",
    "displayOrder": "24"
  },
  {
    "languageTag": "en",
    "displayText": "Condition Severity",
    "attributeValue": "935000025",
    "displayOrder": "25"
  },
  {
    "languageTag": "en",
    "displayText": "Diagnosis Role",
    "attributeValue": "935000038",
    "displayOrder": "38"
  },
  {
    "languageTag": "en",
    "displayText": "Diagnostic Report",
    "attributeValue": "935000039",
    "displayOrder": "39"
  },
  {
    "languageTag": "en",
    "displayText": "Diet",
    "attributeValue": "935000040",
    "displayOrder": "40"
  },
  {
    "languageTag": "en",
    "displayText": "Data Requirement Code Filter Value Code",
    "attributeValue": "935000029",
    "displayOrder": "29"
  },
  {
    "languageTag": "en",
    "displayText": "Definition Topic",
    "attributeValue": "935000030",
    "displayOrder": "30"
  },
  {
    "languageTag": "en",
    "displayText": "Detected Issue",
    "attributeValue": "935000031",
    "displayOrder": "31"
  },
  {
    "languageTag": "en",
    "displayText": "Encounter Type",
    "attributeValue": "935000044",
    "displayOrder": "44"
  },
  {
    "languageTag": "en",
    "displayText": "Endpoint Payload Type",
    "attributeValue": "935000045",
    "displayOrder": "45"
  },
  {
    "languageTag": "en",
    "displayText": "Enteral Formula Additive Type Code",
    "attributeValue": "935000046",
    "displayOrder": "46"
  },
  {
    "languageTag": "en",
    "displayText": "Device Safety",
    "attributeValue": "935000035",
    "displayOrder": "35"
  },
  {
    "languageTag": "en",
    "displayText": "Device Specification Spec Type",
    "attributeValue": "935000036",
    "displayOrder": "36"
  },
  {
    "languageTag": "en",
    "displayText": "Device Type",
    "attributeValue": "935000037",
    "displayOrder": "37"
  },
  {
    "languageTag": "en",
    "displayText": "Event History",
    "attributeValue": "935000050",
    "displayOrder": "50"
  },
  {
    "languageTag": "en",
    "displayText": "Family History Not Done Reason",
    "attributeValue": "935000051",
    "displayOrder": "51"
  },
  {
    "languageTag": "en",
    "displayText": "Family Member",
    "attributeValue": "935000053",
    "displayOrder": "52"
  },
  {
    "languageTag": "en",
    "displayText": "Diet Code",
    "attributeValue": "935000041",
    "displayOrder": "41"
  },
  {
    "languageTag": "en",
    "displayText": "Discharge Disposition",
    "attributeValue": "935000042",
    "displayOrder": "42"
  },
  {
    "languageTag": "en",
    "displayText": "Encounter Reason Code",
    "attributeValue": "935000043",
    "displayOrder": "43"
  },
  {
    "languageTag": "en",
    "displayText": "Food Type Code",
    "attributeValue": "935000057",
    "displayOrder": "56"
  },
  {
    "languageTag": "en",
    "displayText": "Form Code",
    "attributeValue": "935000058",
    "displayOrder": "57"
  },
  {
    "languageTag": "en",
    "displayText": "Goal Category",
    "attributeValue": "935000059",
    "displayOrder": "58"
  },
  {
    "languageTag": "en",
    "displayText": "Enteral Formula Type Code",
    "attributeValue": "935000047",
    "displayOrder": "47"
  },
  {
    "languageTag": "en",
    "displayText": "Enteral Route Code",
    "attributeValue": "935000048",
    "displayOrder": "48"
  },
  {
    "languageTag": "en",
    "displayText": "Episode Of Care Type",
    "attributeValue": "935000049",
    "displayOrder": "49"
  },
  {
    "languageTag": "en",
    "displayText": "Group",
    "attributeValue": "935000063",
    "displayOrder": "62"
  },
  {
    "languageTag": "en",
    "displayText": "Imaging Study",
    "attributeValue": "935000064",
    "displayOrder": "63"
  },
  {
    "languageTag": "en",
    "displayText": "Immunization Request",
    "attributeValue": "935000065",
    "displayOrder": "64"
  },
  {
    "languageTag": "en",
    "displayText": "FHIR Type",
    "attributeValue": "935000054",
    "displayOrder": "53"
  },
  {
    "languageTag": "en",
    "displayText": "Financial Account",
    "attributeValue": "935000055",
    "displayOrder": "54"
  },
  {
    "languageTag": "en",
    "displayText": "Fluid Consistency Type Code",
    "attributeValue": "935000056",
    "displayOrder": "55"
  },
  {
    "languageTag": "en",
    "displayText": "Library",
    "attributeValue": "935000070",
    "displayOrder": "68"
  },
  {
    "languageTag": "en",
    "displayText": "Link Type",
    "attributeValue": "935000071",
    "displayOrder": "69"
  },
  {
    "languageTag": "en",
    "displayText": "Location Type",
    "attributeValue": "935000072",
    "displayOrder": "70"
  },
  {
    "languageTag": "en",
    "displayText": "Goal Priority",
    "attributeValue": "935000060",
    "displayOrder": "59"
  },
  {
    "languageTag": "en",
    "displayText": "Goal Start Event",
    "attributeValue": "935000061",
    "displayOrder": "60"
  },
  {
    "languageTag": "en",
    "displayText": "Goal Target Detail",
    "attributeValue": "935000062",
    "displayOrder": "61"
  },
  {
    "languageTag": "en",
    "displayText": "Medication Code",
    "attributeValue": "935000076",
    "displayOrder": "74"
  },
  {
    "languageTag": "en",
    "displayText": "Medication Container",
    "attributeValue": "935000077",
    "displayOrder": "75"
  },
  {
    "languageTag": "en",
    "displayText": "Medication Ingredient",
    "attributeValue": "935000078",
    "displayOrder": "76"
  },
  {
    "languageTag": "en",
    "displayText": "Investigation Type",
    "attributeValue": "935000066",
    "displayOrder": "65"
  },
  {
    "languageTag": "en",
    "displayText": "Jurisdiction",
    "attributeValue": "935000067",
    "displayOrder": "66"
  },
  {
    "languageTag": "en",
    "displayText": "Language",
    "attributeValue": "935000068",
    "displayOrder": "67"
  },
  {
    "languageTag": "en",
    "displayText": "Nutrient Modifier Code",
    "attributeValue": "935000082",
    "displayOrder": "80"
  },
  {
    "languageTag": "en",
    "displayText": "Observation Category Code",
    "attributeValue": "935000083",
    "displayOrder": "81"
  },
  {
    "languageTag": "en",
    "displayText": "Observation Component Value",
    "attributeValue": "935000084",
    "displayOrder": "82"
  },
  {
    "languageTag": "en",
    "displayText": "LOINC Code",
    "attributeValue": "935000073",
    "displayOrder": "71"
  },
  {
    "languageTag": "en",
    "displayText": "Medication Administration Category",
    "attributeValue": "935000074",
    "displayOrder": "72"
  },
  {
    "languageTag": "en",
    "displayText": "Medication As Needed Reason Code",
    "attributeValue": "935000075",
    "displayOrder": "73"
  },
  {
    "languageTag": "en",
    "displayText": "Observation Reference Range Meaning Code",
    "attributeValue": "935000088",
    "displayOrder": "86"
  },
  {
    "languageTag": "en",
    "displayText": "Observation Value Absent Reason",
    "attributeValue": "935000089",
    "displayOrder": "87"
  },
  {
    "languageTag": "en",
    "displayText": "Observation Value Code",
    "attributeValue": "935000090",
    "displayOrder": "88"
  },
  {
    "languageTag": "en",
    "displayText": "Medication Package Content",
    "attributeValue": "935000079",
    "displayOrder": "77"
  },
  {
    "languageTag": "en",
    "displayText": "Medication Request Category",
    "attributeValue": "935000080",
    "displayOrder": "78"
  },
  {
    "languageTag": "en",
    "displayText": "Medication Statement",
    "attributeValue": "935000081",
    "displayOrder": "79"
  },
  {
    "languageTag": "en",
    "displayText": "Patient Referral Type",
    "attributeValue": "935000094",
    "displayOrder": "92"
  },
  {
    "languageTag": "en",
    "displayText": "Patient Relationship Type",
    "attributeValue": "935000095",
    "displayOrder": "93"
  },
  {
    "languageTag": "en",
    "displayText": "Plan Definition Action Code",
    "attributeValue": "935000096",
    "displayOrder": "94"
  },
  {
    "languageTag": "en",
    "displayText": "Observation Interpretation Code",
    "attributeValue": "935000085",
    "displayOrder": "83"
  },
  {
    "languageTag": "en",
    "displayText": "Observation Method",
    "attributeValue": "935000086",
    "displayOrder": "84"
  },
  {
    "languageTag": "en",
    "displayText": "Observation Reference Range Applies To Code",
    "attributeValue": "935000087",
    "displayOrder": "85"
  },
  {
    "languageTag": "en",
    "displayText": "Practitioner Role",
    "attributeValue": "935000100",
    "displayOrder": "98"
  },
  {
    "languageTag": "en",
    "displayText": "Practitioner Specialty",
    "attributeValue": "935000101",
    "displayOrder": "99"
  },
  {
    "languageTag": "en",
    "displayText": "Priority",
    "attributeValue": "935000102",
    "displayOrder": "100"
  },
  {
    "languageTag": "en",
    "displayText": "Participant Role",
    "attributeValue": "935000091",
    "displayOrder": "89"
  },
  {
    "languageTag": "en",
    "displayText": "Participant Type",
    "attributeValue": "935000092",
    "displayOrder": "90"
  },
  {
    "languageTag": "en",
    "displayText": "Participation Mode",
    "attributeValue": "935000093",
    "displayOrder": "91"
  },
  {
    "languageTag": "en",
    "displayText": "Procedure Follow up Code",
    "attributeValue": "935000106",
    "displayOrder": "104"
  },
  {
    "languageTag": "en",
    "displayText": "Procedure Outcome Code",
    "attributeValue": "935000107",
    "displayOrder": "105"
  },
  {
    "languageTag": "en",
    "displayText": "Procedure Performer Role Code",
    "attributeValue": "935000108",
    "displayOrder": "106"
  },
  {
    "languageTag": "en",
    "displayText": "Plan Definition Action Reason",
    "attributeValue": "935000097",
    "displayOrder": "95"
  },
  {
    "languageTag": "en",
    "displayText": "Plan Definition Goal Target",
    "attributeValue": "935000098",
    "displayOrder": "96"
  },
  {
    "languageTag": "en",
    "displayText": "Practice Setting Code",
    "attributeValue": "935000099",
    "displayOrder": "97"
  },
  {
    "languageTag": "en",
    "displayText": "Questionnaire",
    "attributeValue": "935000112",
    "displayOrder": "110"
  },
  {
    "languageTag": "en",
    "displayText": "Questionnaire Response",
    "attributeValue": "935000113",
    "displayOrder": "111"
  },
  {
    "languageTag": "en",
    "displayText": "Re-Admission Indicator",
    "attributeValue": "935000114",
    "displayOrder": "112"
  },
  {
    "languageTag": "en",
    "displayText": "Procedure Category Code",
    "attributeValue": "935000103",
    "displayOrder": "101"
  },
  {
    "languageTag": "en",
    "displayText": "Procedure Code",
    "attributeValue": "935000104",
    "displayOrder": "102"
  },
  {
    "languageTag": "en",
    "displayText": "Procedure Device Action Code",
    "attributeValue": "935000105",
    "displayOrder": "103"
  },
  {
    "languageTag": "en",
    "displayText": "Request Group Action Code",
    "attributeValue": "935000119",
    "displayOrder": "116"
  },
  {
    "languageTag": "en",
    "displayText": "Request Group Reason Code",
    "attributeValue": "935000120",
    "displayOrder": "117"
  },
  {
    "languageTag": "en",
    "displayText": "Request Intent",
    "attributeValue": "935000121",
    "displayOrder": "118"
  },
  {
    "languageTag": "en",
    "displayText": "Procedure Reason Code",
    "attributeValue": "935000109",
    "displayOrder": "107"
  },
  {
    "languageTag": "en",
    "displayText": "Provenance",
    "attributeValue": "935000110",
    "displayOrder": "108"
  },
  {
    "languageTag": "en",
    "displayText": "Quantity Unit Code",
    "attributeValue": "935000111",
    "displayOrder": "109"
  },
  {
    "languageTag": "en",
    "displayText": "Risk Assessment Outcome",
    "attributeValue": "935000125",
    "displayOrder": "122"
  },
  {
    "languageTag": "en",
    "displayText": "Risk Assessment Reason Code",
    "attributeValue": "935000126",
    "displayOrder": "123"
  },
  {
    "languageTag": "en",
    "displayText": "Route Code",
    "attributeValue": "935000127",
    "displayOrder": "124"
  },
  {
    "languageTag": "en",
    "displayText": "Reason Medication Given Code",
    "attributeValue": "935000116",
    "displayOrder": "113"
  },
  {
    "languageTag": "en",
    "displayText": "Reason Medication Not Given Code",
    "attributeValue": "935000117",
    "displayOrder": "114"
  },
  {
    "languageTag": "en",
    "displayText": "Referral Method",
    "attributeValue": "935000118",
    "displayOrder": "115"
  },
  {
    "languageTag": "en",
    "displayText": "Service Delivery Location Role Type",
    "attributeValue": "935000131",
    "displayOrder": "128"
  },
  {
    "languageTag": "en",
    "displayText": "Service Eligibility",
    "attributeValue": "935000132",
    "displayOrder": "129"
  },
  {
    "languageTag": "en",
    "displayText": "Service Provision Condition",
    "attributeValue": "935000133",
    "displayOrder": "130"
  },
  {
    "languageTag": "en",
    "displayText": "Resource Type",
    "attributeValue": "935000122",
    "displayOrder": "119"
  },
  {
    "languageTag": "en",
    "displayText": "Risk Assessment Code",
    "attributeValue": "935000123",
    "displayOrder": "120"
  },
  {
    "languageTag": "en",
    "displayText": "Risk Assessment Method",
    "attributeValue": "935000124",
    "displayOrder": "121"
  },
  {
    "languageTag": "en",
    "displayText": "Special Courtesy",
    "attributeValue": "935000137",
    "displayOrder": "134"
  },
  {
    "languageTag": "en",
    "displayText": "Specialty",
    "attributeValue": "935000138",
    "displayOrder": "135"
  },
  {
    "languageTag": "en",
    "displayText": "Specimen Collection Method",
    "attributeValue": "935000139",
    "displayOrder": "136"
  },
  {
    "languageTag": "en",
    "displayText": "Sequence",
    "attributeValue": "935000128",
    "displayOrder": "125"
  },
  {
    "languageTag": "en",
    "displayText": "Service Category",
    "attributeValue": "935000129",
    "displayOrder": "126"
  },
  {
    "languageTag": "en",
    "displayText": "Service Characteristic",
    "attributeValue": "935000130",
    "displayOrder": "127"
  },
  {
    "languageTag": "en",
    "displayText": "Structure Map",
    "attributeValue": "935000143",
    "displayOrder": "140"
  },
  {
    "languageTag": "en",
    "displayText": "Substance Admin Substitution Reason",
    "attributeValue": "935000144",
    "displayOrder": "141"
  },
  {
    "languageTag": "en",
    "displayText": "Substance Category Code",
    "attributeValue": "935000145",
    "displayOrder": "142"
  },
  {
    "languageTag": "en",
    "displayText": "Service Type",
    "attributeValue": "935000134",
    "displayOrder": "131"
  },
  {
    "languageTag": "en",
    "displayText": "Snomed CT Medication Codes",
    "attributeValue": "935000135",
    "displayOrder": "132"
  },
  {
    "languageTag": "en",
    "displayText": "Special Arrangement",
    "attributeValue": "935000136",
    "displayOrder": "133"
  },
  {
    "languageTag": "en",
    "displayText": "Task Business Status",
    "attributeValue": "935000149",
    "displayOrder": "146"
  },
  {
    "languageTag": "en",
    "displayText": "Task Code",
    "attributeValue": "935000150",
    "displayOrder": "147"
  },
  {
    "languageTag": "en",
    "displayText": "Task Input Parameter Type",
    "attributeValue": "935000151",
    "displayOrder": "148"
  },
  {
    "languageTag": "en",
    "displayText": "Specimen Container",
    "attributeValue": "935000140",
    "displayOrder": "137"
  },
  {
    "languageTag": "en",
    "displayText": "Specimen Processing Procedure",
    "attributeValue": "935000141",
    "displayOrder": "138"
  },
  {
    "languageTag": "en",
    "displayText": "Specimen Type",
    "attributeValue": "935000142",
    "displayOrder": "139"
  },
  {
    "languageTag": "en",
    "displayText": "Task Status Reason",
    "attributeValue": "935000155",
    "displayOrder": "152"
  },
  {
    "languageTag": "en",
    "displayText": "Texture Modified Food Type Code",
    "attributeValue": "935000156",
    "displayOrder": "153"
  },
  {
    "languageTag": "en",
    "displayText": "Texture Modifier Code",
    "attributeValue": "935000157",
    "displayOrder": "154"
  },
  {
    "languageTag": "en",
    "displayText": "Substance Code",
    "attributeValue": "935000146",
    "displayOrder": "143"
  },
  {
    "languageTag": "en",
    "displayText": "Supplement Type Code",
    "attributeValue": "935000147",
    "displayOrder": "144"
  },
  {
    "languageTag": "en",
    "displayText": "Symptom Code",
    "attributeValue": "935000148",
    "displayOrder": "145"
  },
  {
    "languageTag": "en",
    "displayText": "Value Set",
    "attributeValue": "935000160",
    "displayOrder": "157"
  },
  {
    "languageTag": "en",
    "displayText": "Vision Prescription Product Code",
    "attributeValue": "935000161",
    "displayOrder": "158"
  },
  {
    "languageTag": "en",
    "displayText": "Vision Prescription Reason Code",
    "attributeValue": "935000162",
    "displayOrder": "159"
  },
  {
    "languageTag": "en",
    "displayText": "Task Output Parameter Type",
    "attributeValue": "935000152",
    "displayOrder": "149"
  },
  {
    "languageTag": "en",
    "displayText": "Task Performer Type",
    "attributeValue": "935000153",
    "displayOrder": "150"
  },
  {
    "languageTag": "en",
    "displayText": "Task Reason",
    "attributeValue": "935000154",
    "displayOrder": "151"
  },
  {
    "languageTag": "en",
    "displayText": "Topic",
    "attributeValue": "935000158",
    "displayOrder": "155"
  },
  {
    "languageTag": "en",
    "displayText": "Use Context",
    "attributeValue": "935000159",
    "displayOrder": "156"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Additional Dosage Instruction</td><td>935000003</td><td>3</td></tr>
<tr><td>en</td><td>Additive Code</td><td>935000004</td><td>4</td></tr>
<tr><td>en</td><td>Allergy Intolerance</td><td>935000008</td><td>8</td></tr>
<tr><td>en</td><td>Animal Breed</td><td>935000009</td><td>9</td></tr>
<tr><td>en</td><td>Animal Gender</td><td>935000010</td><td>10</td></tr>
<tr><td>en</td><td>Action Participant Role</td><td>935000000</td><td>0</td></tr>
<tr><td>en</td><td>Action Reason</td><td>935000001</td><td>1</td></tr>
<tr><td>en</td><td>Activity Reason</td><td>935000002</td><td>2</td></tr>
<tr><td>en</td><td>Care Plan Activity Category</td><td>935000014</td><td>14</td></tr>
<tr><td>en</td><td>Care Plan Activity Outcome</td><td>935000015</td><td>15</td></tr>
<tr><td>en</td><td>Care Plan Category</td><td>935000016</td><td>16</td></tr>
<tr><td>en</td><td>Administration Method Code</td><td>935000005</td><td>5</td></tr>
<tr><td>en</td><td>Administration Site Code</td><td>935000006</td><td>6</td></tr>
<tr><td>en</td><td>Admit Source</td><td>935000007</td><td>7</td></tr>
<tr><td>en</td><td>Clinical Impression Prognosis</td><td>935000020</td><td>20</td></tr>
<tr><td>en</td><td>Communication Category</td><td>935000021</td><td>21</td></tr>
<tr><td>en</td><td>Condition Category Code</td><td>935000022</td><td>22</td></tr>
<tr><td>en</td><td>Animal Species</td><td>935000011</td><td>11</td></tr>
<tr><td>en</td><td>As Needed Reason Code</td><td>935000012</td><td>12</td></tr>
<tr><td>en</td><td>Care Plan Activity</td><td>935000013</td><td>13</td></tr>
<tr><td>en</td><td>Condition Stage</td><td>935000026</td><td>26</td></tr>
<tr><td>en</td><td>Contact Entity Type</td><td>935000027</td><td>27</td></tr>
<tr><td>en</td><td>Contact Role</td><td>935000028</td><td>28</td></tr>
<tr><td>en</td><td>Care Team Category</td><td>935000017</td><td>17</td></tr>
<tr><td>en</td><td>Clinical Finding</td><td>935000018</td><td>18</td></tr>
<tr><td>en</td><td>Clinical Impression Code</td><td>935000019</td><td>19</td></tr>
<tr><td>en</td><td>Device Component Operational Status</td><td>935000032</td><td>32</td></tr>
<tr><td>en</td><td>Device Component Parameter Group</td><td>935000033</td><td>33</td></tr>
<tr><td>en</td><td>Device Metric Type</td><td>935000034</td><td>34</td></tr>
<tr><td>en</td><td>Condition Code</td><td>935000023</td><td>23</td></tr>
<tr><td>en</td><td>Condition Outcome Code</td><td>935000024</td><td>24</td></tr>
<tr><td>en</td><td>Condition Severity</td><td>935000025</td><td>25</td></tr>
<tr><td>en</td><td>Diagnosis Role</td><td>935000038</td><td>38</td></tr>
<tr><td>en</td><td>Diagnostic Report</td><td>935000039</td><td>39</td></tr>
<tr><td>en</td><td>Diet</td><td>935000040</td><td>40</td></tr>
<tr><td>en</td><td>Data Requirement Code Filter Value Code</td><td>935000029</td><td>29</td></tr>
<tr><td>en</td><td>Definition Topic</td><td>935000030</td><td>30</td></tr>
<tr><td>en</td><td>Detected Issue</td><td>935000031</td><td>31</td></tr>
<tr><td>en</td><td>Encounter Type</td><td>935000044</td><td>44</td></tr>
<tr><td>en</td><td>Endpoint Payload Type</td><td>935000045</td><td>45</td></tr>
<tr><td>en</td><td>Enteral Formula Additive Type Code</td><td>935000046</td><td>46</td></tr>
<tr><td>en</td><td>Device Safety</td><td>935000035</td><td>35</td></tr>
<tr><td>en</td><td>Device Specification Spec Type</td><td>935000036</td><td>36</td></tr>
<tr><td>en</td><td>Device Type</td><td>935000037</td><td>37</td></tr>
<tr><td>en</td><td>Event History</td><td>935000050</td><td>50</td></tr>
<tr><td>en</td><td>Family History Not Done Reason</td><td>935000051</td><td>51</td></tr>
<tr><td>en</td><td>Family Member</td><td>935000053</td><td>52</td></tr>
<tr><td>en</td><td>Diet Code</td><td>935000041</td><td>41</td></tr>
<tr><td>en</td><td>Discharge Disposition</td><td>935000042</td><td>42</td></tr>
<tr><td>en</td><td>Encounter Reason Code</td><td>935000043</td><td>43</td></tr>
<tr><td>en</td><td>Food Type Code</td><td>935000057</td><td>56</td></tr>
<tr><td>en</td><td>Form Code</td><td>935000058</td><td>57</td></tr>
<tr><td>en</td><td>Goal Category</td><td>935000059</td><td>58</td></tr>
<tr><td>en</td><td>Enteral Formula Type Code</td><td>935000047</td><td>47</td></tr>
<tr><td>en</td><td>Enteral Route Code</td><td>935000048</td><td>48</td></tr>
<tr><td>en</td><td>Episode Of Care Type</td><td>935000049</td><td>49</td></tr>
<tr><td>en</td><td>Group</td><td>935000063</td><td>62</td></tr>
<tr><td>en</td><td>Imaging Study</td><td>935000064</td><td>63</td></tr>
<tr><td>en</td><td>Immunization Request</td><td>935000065</td><td>64</td></tr>
<tr><td>en</td><td>FHIR Type</td><td>935000054</td><td>53</td></tr>
<tr><td>en</td><td>Financial Account</td><td>935000055</td><td>54</td></tr>
<tr><td>en</td><td>Fluid Consistency Type Code</td><td>935000056</td><td>55</td></tr>
<tr><td>en</td><td>Library</td><td>935000070</td><td>68</td></tr>
<tr><td>en</td><td>Link Type</td><td>935000071</td><td>69</td></tr>
<tr><td>en</td><td>Location Type</td><td>935000072</td><td>70</td></tr>
<tr><td>en</td><td>Goal Priority</td><td>935000060</td><td>59</td></tr>
<tr><td>en</td><td>Goal Start Event</td><td>935000061</td><td>60</td></tr>
<tr><td>en</td><td>Goal Target Detail</td><td>935000062</td><td>61</td></tr>
<tr><td>en</td><td>Medication Code</td><td>935000076</td><td>74</td></tr>
<tr><td>en</td><td>Medication Container</td><td>935000077</td><td>75</td></tr>
<tr><td>en</td><td>Medication Ingredient</td><td>935000078</td><td>76</td></tr>
<tr><td>en</td><td>Investigation Type</td><td>935000066</td><td>65</td></tr>
<tr><td>en</td><td>Jurisdiction</td><td>935000067</td><td>66</td></tr>
<tr><td>en</td><td>Language</td><td>935000068</td><td>67</td></tr>
<tr><td>en</td><td>Nutrient Modifier Code</td><td>935000082</td><td>80</td></tr>
<tr><td>en</td><td>Observation Category Code</td><td>935000083</td><td>81</td></tr>
<tr><td>en</td><td>Observation Component Value</td><td>935000084</td><td>82</td></tr>
<tr><td>en</td><td>LOINC Code</td><td>935000073</td><td>71</td></tr>
<tr><td>en</td><td>Medication Administration Category</td><td>935000074</td><td>72</td></tr>
<tr><td>en</td><td>Medication As Needed Reason Code</td><td>935000075</td><td>73</td></tr>
<tr><td>en</td><td>Observation Reference Range Meaning Code</td><td>935000088</td><td>86</td></tr>
<tr><td>en</td><td>Observation Value Absent Reason</td><td>935000089</td><td>87</td></tr>
<tr><td>en</td><td>Observation Value Code</td><td>935000090</td><td>88</td></tr>
<tr><td>en</td><td>Medication Package Content</td><td>935000079</td><td>77</td></tr>
<tr><td>en</td><td>Medication Request Category</td><td>935000080</td><td>78</td></tr>
<tr><td>en</td><td>Medication Statement</td><td>935000081</td><td>79</td></tr>
<tr><td>en</td><td>Patient Referral Type</td><td>935000094</td><td>92</td></tr>
<tr><td>en</td><td>Patient Relationship Type</td><td>935000095</td><td>93</td></tr>
<tr><td>en</td><td>Plan Definition Action Code</td><td>935000096</td><td>94</td></tr>
<tr><td>en</td><td>Observation Interpretation Code</td><td>935000085</td><td>83</td></tr>
<tr><td>en</td><td>Observation Method</td><td>935000086</td><td>84</td></tr>
<tr><td>en</td><td>Observation Reference Range Applies To Code</td><td>935000087</td><td>85</td></tr>
<tr><td>en</td><td>Practitioner Role</td><td>935000100</td><td>98</td></tr>
<tr><td>en</td><td>Practitioner Specialty</td><td>935000101</td><td>99</td></tr>
<tr><td>en</td><td>Priority</td><td>935000102</td><td>100</td></tr>
<tr><td>en</td><td>Participant Role</td><td>935000091</td><td>89</td></tr>
<tr><td>en</td><td>Participant Type</td><td>935000092</td><td>90</td></tr>
<tr><td>en</td><td>Participation Mode</td><td>935000093</td><td>91</td></tr>
<tr><td>en</td><td>Procedure Follow up Code</td><td>935000106</td><td>104</td></tr>
<tr><td>en</td><td>Procedure Outcome Code</td><td>935000107</td><td>105</td></tr>
<tr><td>en</td><td>Procedure Performer Role Code</td><td>935000108</td><td>106</td></tr>
<tr><td>en</td><td>Plan Definition Action Reason</td><td>935000097</td><td>95</td></tr>
<tr><td>en</td><td>Plan Definition Goal Target</td><td>935000098</td><td>96</td></tr>
<tr><td>en</td><td>Practice Setting Code</td><td>935000099</td><td>97</td></tr>
<tr><td>en</td><td>Questionnaire</td><td>935000112</td><td>110</td></tr>
<tr><td>en</td><td>Questionnaire Response</td><td>935000113</td><td>111</td></tr>
<tr><td>en</td><td>Re-Admission Indicator</td><td>935000114</td><td>112</td></tr>
<tr><td>en</td><td>Procedure Category Code</td><td>935000103</td><td>101</td></tr>
<tr><td>en</td><td>Procedure Code</td><td>935000104</td><td>102</td></tr>
<tr><td>en</td><td>Procedure Device Action Code</td><td>935000105</td><td>103</td></tr>
<tr><td>en</td><td>Request Group Action Code</td><td>935000119</td><td>116</td></tr>
<tr><td>en</td><td>Request Group Reason Code</td><td>935000120</td><td>117</td></tr>
<tr><td>en</td><td>Request Intent</td><td>935000121</td><td>118</td></tr>
<tr><td>en</td><td>Procedure Reason Code</td><td>935000109</td><td>107</td></tr>
<tr><td>en</td><td>Provenance</td><td>935000110</td><td>108</td></tr>
<tr><td>en</td><td>Quantity Unit Code</td><td>935000111</td><td>109</td></tr>
<tr><td>en</td><td>Risk Assessment Outcome</td><td>935000125</td><td>122</td></tr>
<tr><td>en</td><td>Risk Assessment Reason Code</td><td>935000126</td><td>123</td></tr>
<tr><td>en</td><td>Route Code</td><td>935000127</td><td>124</td></tr>
<tr><td>en</td><td>Reason Medication Given Code</td><td>935000116</td><td>113</td></tr>
<tr><td>en</td><td>Reason Medication Not Given Code</td><td>935000117</td><td>114</td></tr>
<tr><td>en</td><td>Referral Method</td><td>935000118</td><td>115</td></tr>
<tr><td>en</td><td>Service Delivery Location Role Type</td><td>935000131</td><td>128</td></tr>
<tr><td>en</td><td>Service Eligibility</td><td>935000132</td><td>129</td></tr>
<tr><td>en</td><td>Service Provision Condition</td><td>935000133</td><td>130</td></tr>
<tr><td>en</td><td>Resource Type</td><td>935000122</td><td>119</td></tr>
<tr><td>en</td><td>Risk Assessment Code</td><td>935000123</td><td>120</td></tr>
<tr><td>en</td><td>Risk Assessment Method</td><td>935000124</td><td>121</td></tr>
<tr><td>en</td><td>Special Courtesy</td><td>935000137</td><td>134</td></tr>
<tr><td>en</td><td>Specialty</td><td>935000138</td><td>135</td></tr>
<tr><td>en</td><td>Specimen Collection Method</td><td>935000139</td><td>136</td></tr>
<tr><td>en</td><td>Sequence</td><td>935000128</td><td>125</td></tr>
<tr><td>en</td><td>Service Category</td><td>935000129</td><td>126</td></tr>
<tr><td>en</td><td>Service Characteristic</td><td>935000130</td><td>127</td></tr>
<tr><td>en</td><td>Structure Map</td><td>935000143</td><td>140</td></tr>
<tr><td>en</td><td>Substance Admin Substitution Reason</td><td>935000144</td><td>141</td></tr>
<tr><td>en</td><td>Substance Category Code</td><td>935000145</td><td>142</td></tr>
<tr><td>en</td><td>Service Type</td><td>935000134</td><td>131</td></tr>
<tr><td>en</td><td>Snomed CT Medication Codes</td><td>935000135</td><td>132</td></tr>
<tr><td>en</td><td>Special Arrangement</td><td>935000136</td><td>133</td></tr>
<tr><td>en</td><td>Task Business Status</td><td>935000149</td><td>146</td></tr>
<tr><td>en</td><td>Task Code</td><td>935000150</td><td>147</td></tr>
<tr><td>en</td><td>Task Input Parameter Type</td><td>935000151</td><td>148</td></tr>
<tr><td>en</td><td>Specimen Container</td><td>935000140</td><td>137</td></tr>
<tr><td>en</td><td>Specimen Processing Procedure</td><td>935000141</td><td>138</td></tr>
<tr><td>en</td><td>Specimen Type</td><td>935000142</td><td>139</td></tr>
<tr><td>en</td><td>Task Status Reason</td><td>935000155</td><td>152</td></tr>
<tr><td>en</td><td>Texture Modified Food Type Code</td><td>935000156</td><td>153</td></tr>
<tr><td>en</td><td>Texture Modifier Code</td><td>935000157</td><td>154</td></tr>
<tr><td>en</td><td>Substance Code</td><td>935000146</td><td>143</td></tr>
<tr><td>en</td><td>Supplement Type Code</td><td>935000147</td><td>144</td></tr>
<tr><td>en</td><td>Symptom Code</td><td>935000148</td><td>145</td></tr>
<tr><td>en</td><td>Value Set</td><td>935000160</td><td>157</td></tr>
<tr><td>en</td><td>Vision Prescription Product Code</td><td>935000161</td><td>158</td></tr>
<tr><td>en</td><td>Vision Prescription Reason Code</td><td>935000162</td><td>159</td></tr>
<tr><td>en</td><td>Task Output Parameter Type</td><td>935000152</td><td>149</td></tr>
<tr><td>en</td><td>Task Performer Type</td><td>935000153</td><td>150</td></tr>
<tr><td>en</td><td>Task Reason</td><td>935000154</td><td>151</td></tr>
<tr><td>en</td><td>Topic</td><td>935000158</td><td>155</td></tr>
<tr><td>en</td><td>Use Context</td><td>935000159</td><td>156</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type of: Code-ableConcept represents a value that is usually supplied by providing a reference to one or more terminologies or ontologies, but may also be defined by the provision of text.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>msemr_type</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>34</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="type_display">type_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CodeableConcept.cdm.json/CodeableConcept

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>type</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>


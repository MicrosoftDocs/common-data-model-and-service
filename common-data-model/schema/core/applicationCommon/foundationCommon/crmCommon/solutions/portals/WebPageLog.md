---
title: WebPageLog
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/5/2019
ms.author: tpalmer
---

# Web Page Log

## Properties

Display Name: Web Page Log

Description: A record of a user viewing a Web Page

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json)

## Instances

[/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog](WebPageLog.md)

## Attributes - Summary

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|[portals/WebPageLog](WebPageLog.md)|
|[createdBy](#createdBy)|Shows who created the record.|[portals/WebPageLog](WebPageLog.md)|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|[portals/WebPageLog](WebPageLog.md)|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|[portals/WebPageLog](WebPageLog.md)|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|[portals/WebPageLog](WebPageLog.md)|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|[portals/WebPageLog](WebPageLog.md)|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|[portals/WebPageLog](WebPageLog.md)|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|[portals/WebPageLog](WebPageLog.md)|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|[portals/WebPageLog](WebPageLog.md)|
|[ownerId](#ownerId)|Owner Id|[portals/WebPageLog](WebPageLog.md)|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|[portals/WebPageLog](WebPageLog.md)|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|[portals/WebPageLog](WebPageLog.md)|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|[portals/WebPageLog](WebPageLog.md)|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|[portals/WebPageLog](WebPageLog.md)|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|[portals/WebPageLog](WebPageLog.md)|
|[versionNumber](#versionNumber)|Version Number|[portals/WebPageLog](WebPageLog.md)|
|[webpagelogId](#webpagelogId)|Shows the entity instance.|[portals/WebPageLog](WebPageLog.md)|
|[stateCode](#stateCode)|Status of the Web Page Log|[portals/WebPageLog](WebPageLog.md)|
|[stateCode_display](#stateCode_display)||[portals/WebPageLog](WebPageLog.md)|
|[statusCode](#statusCode)|Select the webpage log's status.|[portals/WebPageLog](WebPageLog.md)|
|[statusCode_display](#statusCode_display)||[portals/WebPageLog](WebPageLog.md)|
|[name](#name)|Type the name of the custom entity.|[portals/WebPageLog](WebPageLog.md)|
|[contactId](#contactId)|Unique identifier of the Contact associated with the Web Page Log|[portals/WebPageLog](WebPageLog.md)|
|[date](#date)|Shows the date and time that the request was made to download the page.|[portals/WebPageLog](WebPageLog.md)|
|[IpAddress](#IpAddress)|Shows the IP address of the computer of the user who requested the file download.|[portals/WebPageLog](WebPageLog.md)|
|[webPageId](#webPageId)|Unique identifier of the Web Page associated with the Web Page Log|[portals/WebPageLog](WebPageLog.md)|

## Attribute - Details

### <a name="createdOn">createdOn</a>

Date and time when the record was created.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

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

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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

</details>

### <a name="createdBy">createdBy</a>

Shows who created the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created By</td></tr>
<tr><td>description</td><td>Shows who created the record.</td></tr>
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

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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
<tr><td>en</td><td>Shows who created the record.</td></tr>
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

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "createdBy",
  "appliedTraits": [
    "is.CDS.standard",
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
                "Shows who created the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By",
  "description": "Shows who created the record.",
  "isNullable": true,
  "sourceName": "createdby"
}
```

</details>

### <a name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

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

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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

</details>

### <a name="modifiedBy">modifiedBy</a>

Shows who last updated the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified By</td></tr>
<tr><td>description</td><td>Shows who last updated the record.</td></tr>
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

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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
<tr><td>en</td><td>Shows who last updated the record.</td></tr>
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

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "modifiedBy",
  "appliedTraits": [
    "is.CDS.standard",
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
                "Shows who last updated the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By",
  "description": "Shows who last updated the record.",
  "isNullable": true,
  "sourceName": "modifiedby"
}
```

</details>

### <a name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created By (Delegate)</td></tr>
<tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr>
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

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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
<tr><td>en</td><td>Shows who created the record on behalf of another user.</td></tr>
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

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "createdOnBehalfBy",
  "appliedTraits": [
    "is.CDS.standard",
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
                "Shows who created the record on behalf of another user."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By (Delegate)",
  "description": "Shows who created the record on behalf of another user.",
  "isNullable": true,
  "sourceName": "createdonbehalfby"
}
```

</details>

### <a name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified By (Delegate)</td></tr>
<tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr>
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

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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
<tr><td>en</td><td>Shows who last updated the record on behalf of another user.</td></tr>
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

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "modifiedOnBehalfBy",
  "appliedTraits": [
    "is.CDS.standard",
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
                "Shows who last updated the record on behalf of another user."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By (Delegate)",
  "description": "Shows who last updated the record on behalf of another user.",
  "isNullable": true,
  "sourceName": "modifiedonbehalfby"
}
```

</details>

### <a name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

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

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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

</details>

### <a name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Import Sequence Number</td></tr>
<tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr>
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
<tr><td>en</td><td>Unique identifier of the data import or data migration that created this record.</td></tr>
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

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owner Type</td></tr>
<tr><td>description</td><td>The type of owner, either User or Team.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
<tr><td>sourceName</td><td>owneridtype</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.entityName

##### is.readOnly

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owner Type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The type of owner, either User or Team.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owneridtype</td><td>string</td><td></td></tr>
</table>

##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.

##### is.CDS.owner

contains a User or Team ID

</details>

### <a name="ownerId">ownerId</a>

Owner Id

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owner</td></tr>
<tr><td>description</td><td>Owner Id</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>sourceName</td><td>ownerid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owner</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owner Id</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>ownerid</td><td>string</td><td></td></tr>
</table>

##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.

##### is.CDS.owner

contains a User or Team ID

</details>

### <a name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owning Business Unit</td></tr>
<tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>owningbusinessunit</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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
<tr><td>en</td><td>Owning Business Unit</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier for the business unit that owns the record</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owningbusinessunit</td><td>string</td><td></td></tr>
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
  "name": "owningBusinessUnit",
  "appliedTraits": [
    "is.CDS.standard",
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
                "Owning Business Unit"
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
                "Unique identifier for the business unit that owns the record"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning Business Unit",
  "description": "Unique identifier for the business unit that owns the record",
  "isNullable": true,
  "sourceName": "owningbusinessunit"
}
```

</details>

### <a name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owning User</td></tr>
<tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>owninguser</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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
<tr><td>en</td><td>Owning User</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the user that owns the activity.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owninguser</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "owningUser",
  "appliedTraits": [
    "is.CDS.standard",
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
                "Owning User"
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
                "Unique identifier for the user that owns the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning User",
  "description": "Unique identifier for the user that owns the record.",
  "isNullable": true,
  "sourceName": "owninguser"
}
```

</details>

### <a name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owning Team</td></tr>
<tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>owningteam</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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
<tr><td>en</td><td>Owning Team</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier for the team that owns the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owningteam</td><td>string</td><td></td></tr>
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
  "name": "owningTeam",
  "appliedTraits": [
    "is.CDS.standard",
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
                "Owning Team"
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
                "Unique identifier for the team that owns the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning Team",
  "description": "Unique identifier for the team that owns the record.",
  "isNullable": true,
  "sourceName": "owningteam"
}
```

</details>

### <a name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

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

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

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

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="versionNumber">versionNumber</a>

Version Number

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

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

##### means.measurement.version

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

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

</details>

### <a name="webpagelogId">webpagelogId</a>

Shows the entity instance.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Webpage Log</td></tr>
<tr><td>description</td><td>Shows the entity instance.</td></tr>
<tr><td>isPrimaryKey</td><td>true</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>sourceName</td><td>adx_webpagelogid</td></tr>
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
<tr><td>attribute</td><td>"WebPageLog_/hasAttributes/webpagelogId"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"WebPageLog_/hasAttributes/webpagelogId"
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
<tr><td>en</td><td>Webpage Log</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the entity instance.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_webpagelogid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>1</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="stateCode">stateCode</a>

Status of the Web Page Log

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Status</td></tr>
<tr><td>description</td><td>Status of the Web Page Log</td></tr>
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
<tr><td>attribute</td><td>"WebPageLog_/hasAttributes/stateCode"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"WebPageLog_/hasAttributes/stateCode"
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
<tr><td>en</td><td>Status of the Web Page Log</td></tr>
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
<tr><td>ordinal</td><td>24</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="stateCode_display">stateCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

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

Select the webpage log's status.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Status Reason</td></tr>
<tr><td>description</td><td>Select the webpage log's status.</td></tr>
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
<tr><td>en</td><td>Select the webpage log's status.</td></tr>
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
<tr><td>ordinal</td><td>26</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="statusCode_display">statusCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

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

### <a name="name">name</a>

Type the name of the custom entity.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Name</td></tr>
<tr><td>description</td><td>Type the name of the custom entity.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_name</td></tr>
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
<tr><td>en</td><td>Type the name of the custom entity.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_name</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>33</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="contactId">contactId</a>

Unique identifier of the Contact associated with the Web Page Log

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>User</td></tr>
<tr><td>description</td><td>Unique identifier of the Contact associated with the Web Page Log</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_contactid</td></tr>
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
<tr><td>en</td><td>User</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the Contact associated with the Web Page Log</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_contactid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>34</td><td>integer</td><td></td></tr>
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
  "name": "contactId",
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
                "User"
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
                "Unique identifier of the Contact associated with the Web Page Log"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "User",
  "description": "Unique identifier of the Contact associated with the Web Page Log",
  "isNullable": true,
  "sourceName": "adx_contactid",
  "sourceOrdering": 34
}
```

</details>

### <a name="date">date</a>

Shows the date and time that the request was made to download the page.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Date</td></tr>
<tr><td>description</td><td>Shows the date and time that the request was made to download the page.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_date</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Date</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the date and time that the request was made to download the page.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_date</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>35</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="IpAddress">IpAddress</a>

Shows the IP address of the computer of the user who requested the file download.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>IP Address</td></tr>
<tr><td>description</td><td>Shows the IP address of the computer of the user who requested the file download.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>30</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_ipaddress</td></tr>
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
<tr><td>en</td><td>IP Address</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the IP address of the computer of the user who requested the file download.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_ipaddress</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>36</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>30</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="webPageId">webPageId</a>

Unique identifier of the Web Page associated with the Web Page Log

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/WebPageLog.cdm.json/WebPageLog

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Web Page</td></tr>
<tr><td>description</td><td>Unique identifier of the Web Page associated with the Web Page Log</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_webpageid</td></tr>
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
<tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Web Page</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the Web Page associated with the Web Page Log</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_webpageid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>37</td><td>integer</td><td></td></tr>
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
  "name": "webPageId",
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
          "value": "required"
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
                "Web Page"
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
                "Unique identifier of the Web Page associated with the Web Page Log"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Web Page",
  "description": "Unique identifier of the Web Page associated with the Web Page Log",
  "isNullable": true,
  "sourceName": "adx_webpageid",
  "sourceOrdering": 37
}
```

</details>


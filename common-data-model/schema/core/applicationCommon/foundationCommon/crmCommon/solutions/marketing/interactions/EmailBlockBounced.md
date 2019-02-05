---
title: EmailBlockBounced
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/5/2019
ms.author: tpalmer
---

# Email block bounced

## Properties

Display Name: Email block bounced

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json)

## Instances

[/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced](EmailBlockBounced.md)

## Attributes - Summary

|Name|Description|First Included in Instance|
|---|---|---|
|[interactionId](#interactionId)|Unique identifier of the interaction.|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[contactId](#contactId)|Contact|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[accountId](#accountId)|Account|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[messageId](#messageId)|Message|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[customerJourneyId](#customerJourneyId)|Customer journey|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[organizationId](#organizationId)|Organization ID|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[sendingId](#sendingId)|Sending ID|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[customerJourneyIterationId](#customerJourneyIterationId)|Customer journey iteration ID|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[usageType](#usageType)|Usage type|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[interactionType](#interactionType)|Interaction type|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[timestamp](#timestamp)|Timestamp|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[bounceCategory](#bounceCategory)|Bounce category|[interactions/EmailBlockBounced](EmailBlockBounced.md)|
|[activityId](#activityId)|Activity ID|[interactions/EmailBlockBounced](EmailBlockBounced.md)|

## Attribute - Details

### <a name="interactionId">interactionId</a>

Unique identifier of the interaction.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Interaction Id</td></tr>
<tr><td>description</td><td>Unique identifier of the interaction.</td></tr>
<tr><td>isPrimaryKey</td><td>true</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>sourceName</td><td>interactionId</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the interactionId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>attribute</td><td>"EmailBlockBounced_/hasAttributes/interactionId"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"EmailBlockBounced_/hasAttributes/interactionId"
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
<tr><td>en</td><td>Interaction Id</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the interaction.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>interactionId</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>1</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="contactId">contactId</a>

Contact

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Contact</td></tr>
<tr><td>description</td><td>Contact</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>ContactId</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the contactId attribute are listed below.</summary>

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
<tr><td>en</td><td>Contact</td></tr>
<tr><td>en</td><td>Contact ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contact</td></tr>
<tr><td>en</td><td>Contact ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>ContactId</td><td>string</td><td></td></tr>
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
                "Contact"
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
                "Contact"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Contact",
  "description": "Contact",
  "isNullable": true,
  "sourceName": "ContactId"
}
```

</details>

### <a name="accountId">accountId</a>

Account

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Account</td></tr>
<tr><td>description</td><td>Account</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>AccountId</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the accountId attribute are listed below.</summary>

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
<tr><td>en</td><td>Account</td></tr>
<tr><td>en</td><td>Account ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Account</td></tr>
<tr><td>en</td><td>Account ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>AccountId</td><td>string</td><td></td></tr>
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
  "name": "accountId",
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
                "Account"
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
                "Account"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Account",
  "description": "Account",
  "isNullable": true,
  "sourceName": "AccountId"
}
```

</details>

### <a name="messageId">messageId</a>

Message

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Message</td></tr>
<tr><td>description</td><td>Message</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>MessageId</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the messageId attribute are listed below.</summary>

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
<tr><td>en</td><td>Message</td></tr>
<tr><td>en</td><td>Message ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Message</td></tr>
<tr><td>en</td><td>Message ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>MessageId</td><td>string</td><td></td></tr>
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
  "name": "messageId",
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
                "Message"
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
                "Message"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Message",
  "description": "Message",
  "isNullable": true,
  "sourceName": "MessageId"
}
```

</details>

### <a name="customerJourneyId">customerJourneyId</a>

Customer journey

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Customer journey</td></tr>
<tr><td>description</td><td>Customer journey</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>CustomerJourneyId</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the customerJourneyId attribute are listed below.</summary>

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
<tr><td>en</td><td>Customer journey</td></tr>
<tr><td>en</td><td>Customer Journey ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Customer journey</td></tr>
<tr><td>en</td><td>Customer Journey ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>CustomerJourneyId</td><td>string</td><td></td></tr>
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
  "name": "customerJourneyId",
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
                "Customer journey"
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
                "Customer journey"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Customer journey",
  "description": "Customer journey",
  "isNullable": true,
  "sourceName": "CustomerJourneyId"
}
```

</details>

### <a name="organizationId">organizationId</a>

Organization ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Organization ID</td></tr>
<tr><td>description</td><td>Organization ID</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the organizationId attribute are listed below.</summary>

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
<tr><td>en</td><td>Organization ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Organization ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="sendingId">sendingId</a>

Sending ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Sending ID</td></tr>
<tr><td>description</td><td>Sending ID</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the sendingId attribute are listed below.</summary>

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
<tr><td>en</td><td>Sending ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Sending ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="customerJourneyIterationId">customerJourneyIterationId</a>

Customer journey iteration ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Customer journey iteration ID</td></tr>
<tr><td>description</td><td>Customer journey iteration ID</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the customerJourneyIterationId attribute are listed below.</summary>

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
<tr><td>en</td><td>Customer journey iteration ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Customer journey iteration ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="usageType">usageType</a>

Usage type

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Usage type</td></tr>
<tr><td>description</td><td>Usage type</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the usageType attribute are listed below.</summary>

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
<tr><td>en</td><td>Usage type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Usage type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="interactionType">interactionType</a>

Interaction type

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Interaction type</td></tr>
<tr><td>description</td><td>Interaction type</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the interactionType attribute are listed below.</summary>

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
<tr><td>en</td><td>Interaction type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Interaction type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="timestamp">timestamp</a>

Timestamp

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Timestamp</td></tr>
<tr><td>description</td><td>Timestamp</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the timestamp attribute are listed below.</summary>

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
<tr><td>en</td><td>Timestamp</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Timestamp</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="bounceCategory">bounceCategory</a>

Bounce category

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Bounce category</td></tr>
<tr><td>description</td><td>Bounce category</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the bounceCategory attribute are listed below.</summary>

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
<tr><td>en</td><td>Bounce category</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Bounce category</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="activityId">activityId</a>

Activity ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/EmailBlockBounced.cdm.json/EmailBlockBounced

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Activity ID</td></tr>
<tr><td>description</td><td>Activity ID</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the activityId attribute are listed below.</summary>

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
<tr><td>en</td><td>Activity ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Activity ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

</details>


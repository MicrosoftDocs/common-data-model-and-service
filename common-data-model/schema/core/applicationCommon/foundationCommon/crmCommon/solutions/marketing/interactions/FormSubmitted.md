---
title: FormSubmitted
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/5/2019
ms.author: tpalmer
---

# Form submitted

## Properties

Display Name: Form submitted

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json)

## Instances

[/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted](FormSubmitted.md)

## Attributes - Summary

|Name|Description|First Included in Instance|
|---|---|---|
|[interactionId](#interactionId)|Unique identifier of the interaction.|[interactions/FormSubmitted](FormSubmitted.md)|
|[formId](#formId)|Form|[interactions/FormSubmitted](FormSubmitted.md)|
|[pageId](#pageId)|Marketing page|[interactions/FormSubmitted](FormSubmitted.md)|
|[messageId](#messageId)|Message|[interactions/FormSubmitted](FormSubmitted.md)|
|[contactId](#contactId)|Contact|[interactions/FormSubmitted](FormSubmitted.md)|
|[accountId](#accountId)|Account|[interactions/FormSubmitted](FormSubmitted.md)|
|[customerJourneyId](#customerJourneyId)|Customer journey|[interactions/FormSubmitted](FormSubmitted.md)|
|[formName](#formName)|Form name|[interactions/FormSubmitted](FormSubmitted.md)|
|[formSubmissionId](#formSubmissionId)|Form submission ID|[interactions/FormSubmitted](FormSubmitted.md)|
|[customerJourneyIterationId](#customerJourneyIterationId)|Customer journey iteration ID|[interactions/FormSubmitted](FormSubmitted.md)|
|[result](#result)|Result|[interactions/FormSubmitted](FormSubmitted.md)|
|[visitorId](#visitorId)|Visitor ID|[interactions/FormSubmitted](FormSubmitted.md)|
|[sessionId](#sessionId)|Session ID|[interactions/FormSubmitted](FormSubmitted.md)|
|[contactMatchingResult](#contactMatchingResult)|Contact matching result|[interactions/FormSubmitted](FormSubmitted.md)|
|[leadMatchingResult](#leadMatchingResult)|Lead matching result|[interactions/FormSubmitted](FormSubmitted.md)|
|[countryIsoCode](#countryIsoCode)|Country ISO code|[interactions/FormSubmitted](FormSubmitted.md)|
|[state](#state)|State|[interactions/FormSubmitted](FormSubmitted.md)|
|[city](#city)|City|[interactions/FormSubmitted](FormSubmitted.md)|
|[postalCode](#postalCode)|Postal code|[interactions/FormSubmitted](FormSubmitted.md)|
|[browserId](#browserId)|Browser ID|[interactions/FormSubmitted](FormSubmitted.md)|
|[browserVersion](#browserVersion)|Browser version|[interactions/FormSubmitted](FormSubmitted.md)|
|[operatingSystemId](#operatingSystemId)|Operating system ID|[interactions/FormSubmitted](FormSubmitted.md)|
|[operatingSystemVersion](#operatingSystemVersion)|Operating system version|[interactions/FormSubmitted](FormSubmitted.md)|
|[referrerUri](#referrerUri)|Referrer URL|[interactions/FormSubmitted](FormSubmitted.md)|
|[sendingId](#sendingId)|Sending ID|[interactions/FormSubmitted](FormSubmitted.md)|
|[searchPhrase](#searchPhrase)|Search phrase|[interactions/FormSubmitted](FormSubmitted.md)|
|[searchEngineName](#searchEngineName)|Search engine name|[interactions/FormSubmitted](FormSubmitted.md)|
|[visitDuration](#visitDuration)|Visit duration|[interactions/FormSubmitted](FormSubmitted.md)|
|[visitorReturningStatus](#visitorReturningStatus)|Visitor returning status|[interactions/FormSubmitted](FormSubmitted.md)|
|[contactFailureMessage](#contactFailureMessage)|Contact failure message|[interactions/FormSubmitted](FormSubmitted.md)|
|[leadFailureMessage](#leadFailureMessage)|Lead failure message|[interactions/FormSubmitted](FormSubmitted.md)|
|[timestamp](#timestamp)|Timestamp|[interactions/FormSubmitted](FormSubmitted.md)|
|[visitorAnonymousStatus](#visitorAnonymousStatus)|Visitor anonymous status|[interactions/FormSubmitted](FormSubmitted.md)|
|[leadId](#leadId)|Lead ID|[interactions/FormSubmitted](FormSubmitted.md)|

## Attribute - Details

### <a name="interactionId">interactionId</a>

Unique identifier of the interaction.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

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

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>attribute</td><td>"FormSubmitted_/hasAttributes/interactionId"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"FormSubmitted_/hasAttributes/interactionId"
```

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Interaction Id</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the interaction.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>interactionId</td><td>string</td><td></td></tr>
</table>

- ##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>1</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="formId">formId</a>

Form

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Form</td></tr>
<tr><td>description</td><td>Form</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>FormId</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the formId attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.dataFormat.guid

- ##### means.identity.entityId

- ##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Form</td></tr>
<tr><td>en</td><td>Form ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Form</td></tr>
<tr><td>en</td><td>Form ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

- ##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>FormId</td><td>string</td><td></td></tr>
</table>

- ##### does.referenceEntity

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
  "name": "formId",
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
                "Form"
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
                "Form"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Form",
  "description": "Form",
  "isNullable": true,
  "sourceName": "FormId"
}
```

</details>

### <a name="pageId">pageId</a>

Marketing page

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Marketing page</td></tr>
<tr><td>description</td><td>Marketing page</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>PageId</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the pageId attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.dataFormat.guid

- ##### means.identity.entityId

- ##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Marketing page</td></tr>
<tr><td>en</td><td>Page ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Marketing page</td></tr>
<tr><td>en</td><td>Page ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

- ##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>PageId</td><td>string</td><td></td></tr>
</table>

- ##### does.referenceEntity

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
  "name": "pageId",
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
                "Marketing page"
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
                "Marketing page"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Marketing page",
  "description": "Marketing page",
  "isNullable": true,
  "sourceName": "PageId"
}
```

</details>

### <a name="messageId">messageId</a>

Message

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

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

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.dataFormat.guid

- ##### means.identity.entityId

- ##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Message</td></tr>
<tr><td>en</td><td>Message ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Message</td></tr>
<tr><td>en</td><td>Message ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

- ##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>MessageId</td><td>string</td><td></td></tr>
</table>

- ##### does.referenceEntity

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

### <a name="contactId">contactId</a>

Contact

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

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

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.dataFormat.guid

- ##### means.identity.entityId

- ##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contact</td></tr>
<tr><td>en</td><td>Contact ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contact</td></tr>
<tr><td>en</td><td>Contact ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

- ##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>ContactId</td><td>string</td><td></td></tr>
</table>

- ##### does.referenceEntity

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

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

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

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.dataFormat.guid

- ##### means.identity.entityId

- ##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Account</td></tr>
<tr><td>en</td><td>Account ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Account</td></tr>
<tr><td>en</td><td>Account ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

- ##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>AccountId</td><td>string</td><td></td></tr>
</table>

- ##### does.referenceEntity

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

### <a name="customerJourneyId">customerJourneyId</a>

Customer journey

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

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

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.dataFormat.guid

- ##### means.identity.entityId

- ##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Customer journey</td></tr>
<tr><td>en</td><td>Customer Journey ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Customer journey</td></tr>
<tr><td>en</td><td>Customer Journey ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

- ##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>CustomerJourneyId</td><td>string</td><td></td></tr>
</table>

- ##### does.referenceEntity

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

### <a name="formName">formName</a>

Form name

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Form name</td></tr>
<tr><td>description</td><td>Form name</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the formName attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Form name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Form name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="formSubmissionId">formSubmissionId</a>

Form submission ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Form submission ID</td></tr>
<tr><td>description</td><td>Form submission ID</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the formSubmissionId attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Form submission ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Form submission ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="customerJourneyIterationId">customerJourneyIterationId</a>

Customer journey iteration ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

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

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Customer journey iteration ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Customer journey iteration ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="result">result</a>

Result

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Result</td></tr>
<tr><td>description</td><td>Result</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the result attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Result</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Result</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="visitorId">visitorId</a>

Visitor ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Visitor ID</td></tr>
<tr><td>description</td><td>Visitor ID</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the visitorId attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Visitor ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Visitor ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="sessionId">sessionId</a>

Session ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Session ID</td></tr>
<tr><td>description</td><td>Session ID</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the sessionId attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Session ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Session ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="contactMatchingResult">contactMatchingResult</a>

Contact matching result

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Contact matching result</td></tr>
<tr><td>description</td><td>Contact matching result</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the contactMatchingResult attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contact matching result</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contact matching result</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="leadMatchingResult">leadMatchingResult</a>

Lead matching result

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Lead matching result</td></tr>
<tr><td>description</td><td>Lead matching result</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the leadMatchingResult attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Lead matching result</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Lead matching result</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="countryIsoCode">countryIsoCode</a>

Country ISO code

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Country ISO code</td></tr>
<tr><td>description</td><td>Country ISO code</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the countryIsoCode attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Country ISO code</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Country ISO code</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="state">state</a>

State

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>State</td></tr>
<tr><td>description</td><td>State</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the state attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>State</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>State</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="city">city</a>

City

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>City</td></tr>
<tr><td>description</td><td>City</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the city attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>City</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>City</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="postalCode">postalCode</a>

Postal code

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Postal code</td></tr>
<tr><td>description</td><td>Postal code</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the postalCode attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Postal code</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Postal code</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="browserId">browserId</a>

Browser ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Browser ID</td></tr>
<tr><td>description</td><td>Browser ID</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the browserId attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Browser ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Browser ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="browserVersion">browserVersion</a>

Browser version

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Browser version</td></tr>
<tr><td>description</td><td>Browser version</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the browserVersion attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Browser version</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Browser version</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="operatingSystemId">operatingSystemId</a>

Operating system ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Operating system ID</td></tr>
<tr><td>description</td><td>Operating system ID</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the operatingSystemId attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Operating system ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Operating system ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="operatingSystemVersion">operatingSystemVersion</a>

Operating system version

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Operating system version</td></tr>
<tr><td>description</td><td>Operating system version</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the operatingSystemVersion attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Operating system version</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Operating system version</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="referrerUri">referrerUri</a>

Referrer URL

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Referrer URL</td></tr>
<tr><td>description</td><td>Referrer URL</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the referrerUri attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Referrer URL</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Referrer URL</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="sendingId">sendingId</a>

Sending ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

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

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Sending ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Sending ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="searchPhrase">searchPhrase</a>

Search phrase

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Search phrase</td></tr>
<tr><td>description</td><td>Search phrase</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the searchPhrase attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Search phrase</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Search phrase</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="searchEngineName">searchEngineName</a>

Search engine name

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Search engine name</td></tr>
<tr><td>description</td><td>Search engine name</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the searchEngineName attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Search engine name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Search engine name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="visitDuration">visitDuration</a>

Visit duration

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Visit duration</td></tr>
<tr><td>description</td><td>Visit duration</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the visitDuration attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Visit duration</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Visit duration</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="visitorReturningStatus">visitorReturningStatus</a>

Visitor returning status

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Visitor returning status</td></tr>
<tr><td>description</td><td>Visitor returning status</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the visitorReturningStatus attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Visitor returning status</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Visitor returning status</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="contactFailureMessage">contactFailureMessage</a>

Contact failure message

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Contact failure message</td></tr>
<tr><td>description</td><td>Contact failure message</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the contactFailureMessage attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contact failure message</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contact failure message</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="leadFailureMessage">leadFailureMessage</a>

Lead failure message

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Lead failure message</td></tr>
<tr><td>description</td><td>Lead failure message</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the leadFailureMessage attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Lead failure message</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Lead failure message</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="timestamp">timestamp</a>

Timestamp

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

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

- ##### is.dataFormat.date

- ##### means.measurement.date

- ##### is.dataFormat.time

- ##### means.measurement.time

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Timestamp</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Timestamp</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="visitorAnonymousStatus">visitorAnonymousStatus</a>

Visitor anonymous status

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Visitor anonymous status</td></tr>
<tr><td>description</td><td>Visitor anonymous status</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the visitorAnonymousStatus attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Visitor anonymous status</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Visitor anonymous status</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>

### <a name="leadId">leadId</a>

Lead ID

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/interactions/FormSubmitted.cdm.json/FormSubmitted

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Lead ID</td></tr>
<tr><td>description</td><td>Lead ID</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the leadId attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Lead ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Lead ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.nullable

The attribute value may be set to NULL.

</details>


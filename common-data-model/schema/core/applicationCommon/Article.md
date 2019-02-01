---
title: Article_
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/1/2019
ms.author: tpalmer
---
# Article

## Properties

Display Name: Article

Description: Structured content that is part of the knowledge base.

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Article.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Article.cdm.json)

## Instances

## Attributes - Summary

<table><tr><th>Name</th><th>Description</th><th>First Included in Instance</th></tr><tr><td>kbArticleId</td><td>Shows the ID of the article.</td><td> </td></tr><tr><td>kbArticleTemplateId</td><td>Choose the template that you want to use as a base for creating the new article.</td><td> </td></tr><tr><td>organizationId</td><td>Unique identifier of the organization associated with the article.</td><td> </td></tr><tr><td>subjectId</td><td>Choose the subject of the article to assist with article searches. You can configure subjects under Business Management in the Settings area.</td><td> </td></tr><tr><td>articleXml</td><td>Shows the article content and formatting, stored as XML.</td><td> </td></tr><tr><td>title</td><td>Type a subject or descriptive name for the article to assist with article searches.</td><td> </td></tr><tr><td>number</td><td>Knowledge base article number.</td><td> </td></tr><tr><td>content</td><td>Description of the content of the knowledge base article.</td><td> </td></tr><tr><td>description</td><td>Type additional information that describes the knowledge base article.</td><td> </td></tr><tr><td>comments</td><td>Comments regarding the knowledge base article.</td><td> </td></tr><tr><td>createdOn</td><td>Date and time when the knowledge base article was created.</td><td> </td></tr><tr><td>createdBy</td><td>Unique identifier of the user who created the knowledge base article.</td><td> </td></tr><tr><td>modifiedBy</td><td>Unique identifier of the user who last modified the knowledge base article.</td><td> </td></tr><tr><td>modifiedOn</td><td>Date and time when the knowledge base article was last modified.</td><td> </td></tr><tr><td>stateCode</td><td>Shows whether the knowledge base article is in draft, unapproved, or published status. Published articles are read-only and can't be edited unless they are unpublished.</td><td> </td></tr><tr><td>stateCode_display</td><td>undefined</td><td> </td></tr><tr><td>statusCode</td><td>Select the article's status.</td><td> </td></tr><tr><td>statusCode_display</td><td>undefined</td><td> </td></tr><tr><td>versionNumber</td><td>Title of the knowledge base article.</td><td> </td></tr><tr><td>keyWords</td><td>Keywords to be used for searches in knowledge base articles.</td><td> </td></tr><tr><td>importSequenceNumber</td><td>Unique identifier of the data import or data migration that created this record.</td><td> </td></tr><tr><td>overriddenCreatedOn</td><td>Date and time that the record was migrated.</td><td> </td></tr><tr><td>createdOnBehalfBy</td><td>Unique identifier of the delegate user who created the article.</td><td> </td></tr><tr><td>modifiedOnBehalfBy</td><td>Unique identifier of the delegate user who last modified the kbarticle.</td><td> </td></tr><tr><td>languageCode</td><td>Select which language the article must be available in. This list is based on the list of language packs that are installed in your Microsoft Dynamics 365 environment.</td><td> </td></tr><tr><td>exchangeRate</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td><td> </td></tr><tr><td>transactionCurrencyId</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td><td> </td></tr><tr><td>entityImageId</td><td>For internal use only.</td><td> </td></tr></table>

## Attribute - Details

### kbArticleId

Shows the ID of the article.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Article</td></tr><tr><td>description</td><td>Shows the ID of the article.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>kbarticleid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"Article_/hasAttributes/kbArticleId"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"Article_/hasAttributes/kbArticleId"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Article</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the ID of the article.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>kbarticleid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>1</td><td>integer</td><td>undefined</td></tr></table>


### kbArticleTemplateId

Choose the template that you want to use as a base for creating the new article.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base Template</td></tr><tr><td>description</td><td>Choose the template that you want to use as a base for creating the new article.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>kbarticletemplateid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Base Template</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the template that you want to use as a base for creating the new article.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>kbarticletemplateid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>2</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "kbArticleTemplateId",
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
          "value": "systemrequired"
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
                "Base Template"
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
                "Choose the template that you want to use as a base for creating the new article."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Base Template",
  "description": "Choose the template that you want to use as a base for creating the new article.",
  "sourceName": "kbarticletemplateid",
  "sourceOrdering": 2
}
```

### organizationId

Unique identifier of the organization associated with the article.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the article.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>organizationid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organization</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the organization associated with the article.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>organizationid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>3</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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
          "value": "systemrequired"
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
                "Organization"
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
                "Unique identifier of the organization associated with the article."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Organization",
  "description": "Unique identifier of the organization associated with the article.",
  "sourceName": "organizationid",
  "sourceOrdering": 3
}
```

### subjectId

Choose the subject of the article to assist with article searches. You can configure subjects under Business Management in the Settings area.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Choose the subject of the article to assist with article searches. You can configure subjects under Business Management in the Settings area.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>subjectid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>subject</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subject</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the subject of the article to assist with article searches. You can configure subjects under Business Management in the Settings area.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>subjectid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>4</td><td>integer</td><td>undefined</td></tr></table>


### articleXml

Shows the article content and formatting, stored as XML.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Article XML</td></tr><tr><td>description</td><td>Shows the article content and formatting, stored as XML.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>articlexml</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Article XML</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the article content and formatting, stored as XML.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>articlexml</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>5</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>1073741823</td><td>integer</td><td>undefined</td></tr></table>


### title

Type a subject or descriptive name for the article to assist with article searches.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Type a subject or descriptive name for the article to assist with article searches.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Title</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type a subject or descriptive name for the article to assist with article searches.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>title</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>7</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>500</td><td>integer</td><td>undefined</td></tr></table>


### number

Knowledge base article number.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number</td></tr><tr><td>description</td><td>Knowledge base article number.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>number</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Knowledge base article number.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>number</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>8</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td>undefined</td></tr></table>


### content

Description of the content of the knowledge base article.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Content</td></tr><tr><td>description</td><td>Description of the content of the knowledge base article.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>content</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Content</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description of the content of the knowledge base article.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>content</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>9</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>1073741823</td><td>integer</td><td>undefined</td></tr></table>


### description

Type additional information that describes the knowledge base article.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information that describes the knowledge base article.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type additional information that describes the knowledge base article.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>description</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>2000</td><td>integer</td><td>undefined</td></tr></table>


### comments

Comments regarding the knowledge base article.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comments</td></tr><tr><td>description</td><td>Comments regarding the knowledge base article.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>comments</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Comments</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Comments regarding the knowledge base article.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>comments</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>11</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100000</td><td>integer</td><td>undefined</td></tr></table>


### createdOn

Date and time when the knowledge base article was created.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the knowledge base article was created.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### means.measurement.date.creation


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the knowledge base article was created.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>createdon</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>12</td><td>integer</td><td>undefined</td></tr></table>


### createdBy

Unique identifier of the user who created the knowledge base article.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the knowledge base article.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the user who created the knowledge base article.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>createdby</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>13</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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
                "Unique identifier of the user who created the knowledge base article."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By",
  "description": "Unique identifier of the user who created the knowledge base article.",
  "isNullable": true,
  "sourceName": "createdby",
  "sourceOrdering": 13
}
```

### modifiedBy

Unique identifier of the user who last modified the knowledge base article.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the knowledge base article.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the user who last modified the knowledge base article.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedby</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>14</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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
                "Unique identifier of the user who last modified the knowledge base article."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By",
  "description": "Unique identifier of the user who last modified the knowledge base article.",
  "isNullable": true,
  "sourceName": "modifiedby",
  "sourceOrdering": 14
}
```

### modifiedOn

Date and time when the knowledge base article was last modified.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the knowledge base article was last modified.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### means.measurement.date.modify


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the knowledge base article was last modified.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedon</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>15</td><td>integer</td><td>undefined</td></tr></table>


### stateCode

Shows whether the knowledge base article is in draft, unapproved, or published status. Published articles are read-only and can't be edited unless they are unpublished.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status </td></tr><tr><td>description</td><td>Shows whether the knowledge base article is in draft, unapproved, or published status. Published articles are read-only and can't be edited unless they are unpublished.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Draft",
    "attributeValue": "1",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Unapproved",
    "attributeValue": "2",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Published",
    "attributeValue": "3",
    "displayOrder": "2"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>Draft</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Unapproved</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Published</td><td>3</td><td>2</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### means.entityState

the attribute represents the current state of the entity.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"Article_/hasAttributes/stateCode"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"Article_/hasAttributes/stateCode"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status </td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows whether the knowledge base article is in draft, unapproved, or published status. Published articles are read-only and can't be edited unless they are unpublished.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>statecode</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>16</td><td>integer</td><td>undefined</td></tr></table>


### stateCode_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>stateCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### statusCode

Select the article's status.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the article's status.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Draft",
    "attributeValue": "1",
    "displayOrder": "0",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Unapproved",
    "attributeValue": "2",
    "displayOrder": "1",
    "correlatedValue": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Published",
    "attributeValue": "3",
    "displayOrder": "2",
    "correlatedValue": "3"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>1</td><td>0</td><td>1</td></tr><tr><td>en</td><td>Unapproved</td><td>2</td><td>1</td><td>2</td></tr><tr><td>en</td><td>Published</td><td>3</td><td>2</td><td>3</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.correlatedWith

the attribute value is correlated with the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>stateCode</td><td>attributeName</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status Reason</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select the article's status.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>statuscode</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>18</td><td>integer</td><td>undefined</td></tr></table>


### statusCode_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>statusCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### versionNumber

Title of the knowledge base article.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Title of the knowledge base article.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.dataFormat.big


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Title</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Title of the knowledge base article.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>versionnumber</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>19</td><td>integer</td><td>undefined</td></tr></table>


### keyWords

Keywords to be used for searches in knowledge base articles.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Key Words</td></tr><tr><td>description</td><td>Keywords to be used for searches in knowledge base articles.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>keywords</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Key Words</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Keywords to be used for searches in knowledge base articles.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>keywords</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>20</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100000</td><td>integer</td><td>undefined</td></tr></table>


### importSequenceNumber

Unique identifier of the data import or data migration that created this record.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the data import or data migration that created this record.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>importsequencenumber</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>33</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### overriddenCreatedOn

Date and time that the record was migrated.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### means.measurement.date.creation


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>overriddencreatedon</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>34</td><td>integer</td><td>undefined</td></tr></table>


### createdOnBehalfBy

Unique identifier of the delegate user who created the article.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the article.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By (Delegate)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the delegate user who created the article.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>createdonbehalfby</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>37</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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
                "Unique identifier of the delegate user who created the article."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By (Delegate)",
  "description": "Unique identifier of the delegate user who created the article.",
  "isNullable": true,
  "sourceName": "createdonbehalfby",
  "sourceOrdering": 37
}
```

### modifiedOnBehalfBy

Unique identifier of the delegate user who last modified the kbarticle.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the kbarticle.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By (Delegate)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the delegate user who last modified the kbarticle.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedonbehalfby</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>41</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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
                "Unique identifier of the delegate user who last modified the kbarticle."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By (Delegate)",
  "description": "Unique identifier of the delegate user who last modified the kbarticle.",
  "isNullable": true,
  "sourceName": "modifiedonbehalfby",
  "sourceOrdering": 41
}
```

### languageCode

Select which language the article must be available in. This list is based on the list of language packs that are installed in your Microsoft Dynamics 365 environment.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language</td></tr><tr><td>description</td><td>Select which language the article must be available in. This list is based on the list of language packs that are installed in your Microsoft Dynamics 365 environment.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>languagecode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.language


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Language</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select which language the article must be available in. This list is based on the list of language packs that are installed in your Microsoft Dynamics 365 environment.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>languagecode</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>45</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### exchangeRate

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exchange Rate</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>exchangerate</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>46</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>1E-10</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td>undefined</td></tr></table>


### transactionCurrencyId

Choose the local currency for the record to make sure budgets are reported in the correct currency.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Currency</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>transactioncurrencyid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>47</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "transactionCurrencyId",
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
                "Currency"
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
                "Choose the local currency for the record to make sure budgets are reported in the correct currency."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Currency",
  "description": "Choose the local currency for the record to make sure budgets are reported in the correct currency.",
  "isNullable": true,
  "sourceName": "transactioncurrencyid",
  "sourceOrdering": 47
}
```

### entityImageId

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Image Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Entity Image Id</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>entityimageid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>49</td><td>integer</td><td>undefined</td></tr></table>



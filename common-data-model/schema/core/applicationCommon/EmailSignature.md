---
title: EmailSignature_
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/1/2019
ms.author: tpalmer
---
# Email Signature

## Properties

Display Name: Email Signature

Description: Signature for email message

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/EmailSignature.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/EmailSignature.cdm.json)

## Instances

## Attributes - Summary

<table><tr><th>Name</th><th>Description</th><th>First Included in Instance</th></tr><tr><td>emailSignatureId</td><td>Unique identifier of the email signature.</td><td> </td></tr><tr><td>owningBusinessUnit</td><td>Unique identifier of the business unit that owns the email signature.</td><td> </td></tr><tr><td>isPersonal</td><td>Information about whether the email signature is personal or is available to all users.</td><td> </td></tr><tr><td>mimeType</td><td>MIME type of the email signature.</td><td> </td></tr><tr><td>body</td><td>Body text of the email signature.</td><td> </td></tr><tr><td>title</td><td>Title of the email signature.</td><td> </td></tr><tr><td>description</td><td>Description of the email signature.</td><td> </td></tr><tr><td>owningUser</td><td>Unique identifier of the user who owns the email signature.</td><td> </td></tr><tr><td>createdBy</td><td>Unique identifier of the user who created the email signature.</td><td> </td></tr><tr><td>presentationXml</td><td>XML data for the body of the email signature.</td><td> </td></tr><tr><td>createdOn</td><td>Date and time when the email signature was created.</td><td> </td></tr><tr><td>modifiedBy</td><td>Unique identifier of the user who last modified the email signature.</td><td> </td></tr><tr><td>modifiedOn</td><td>Date and time when the email signature was last modified.</td><td> </td></tr><tr><td>ownerIdType</td><td>The type of owner, either User or Team.</td><td> </td></tr><tr><td>ownerId</td><td>Owner Id</td><td> </td></tr><tr><td>generationTypeCode</td><td>For internal use only.</td><td> </td></tr><tr><td>languageCode</td><td>Language of the email signature.</td><td> </td></tr><tr><td>importSequenceNumber</td><td>Unique identifier of the data import or data migration that created this record.</td><td> </td></tr><tr><td>overwriteTime</td><td>For internal use only.</td><td> </td></tr><tr><td>componentState</td><td>For internal use only.</td><td> </td></tr><tr><td>componentState_display</td><td>undefined</td><td> </td></tr><tr><td>createdOnBehalfBy</td><td>Unique identifier of the delegate user who created the email signature.</td><td> </td></tr><tr><td>modifiedOnBehalfBy</td><td>Unique identifier of the delegate user who last modified the email signature.</td><td> </td></tr><tr><td>owningTeam</td><td>Unique identifier of the team who owns the email signature.</td><td> </td></tr><tr><td>isCustomizable</td><td>Information that specifies whether this component can be customized.</td><td> </td></tr><tr><td>overriddenCreatedOn</td><td>Date and time that the record was migrated.</td><td> </td></tr><tr><td>isDefault</td><td>Information that specifies whether the email signature is default to the user.</td><td> </td></tr></table>

## Attribute - Details

### emailSignatureId

Unique identifier of the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Signature</td></tr><tr><td>description</td><td>Unique identifier of the email signature.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>emailsignatureid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"EmailSignature_/hasAttributes/emailSignatureId"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"EmailSignature_/hasAttributes/emailSignatureId"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email Signature</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>emailsignatureid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>1</td><td>integer</td><td>undefined</td></tr></table>


### owningBusinessUnit

Unique identifier of the business unit that owns the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit that owns the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Business Unit</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the business unit that owns the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owningbusinessunit</td><td>string</td><td>undefined</td></tr></table>


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
  "name": "owningBusinessUnit",
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
                "Unique identifier of the business unit that owns the email signature."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning Business Unit",
  "description": "Unique identifier of the business unit that owns the email signature.",
  "isNullable": true,
  "sourceName": "owningbusinessunit",
  "sourceOrdering": 3
}
```

### isPersonal

Information about whether the email signature is personal or is available to all users.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Viewable By</td></tr><tr><td>description</td><td>Information about whether the email signature is personal or is available to all users.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ispersonal</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Viewable By</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Information about whether the email signature is personal or is available to all users.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>ispersonal</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>4</td><td>integer</td><td>undefined</td></tr></table>


### mimeType

MIME type of the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mime Type</td></tr><tr><td>description</td><td>MIME type of the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mimetype</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Mime Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>MIME type of the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>mimetype</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>7</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>256</td><td>integer</td><td>undefined</td></tr></table>


### body

Body text of the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Body</td></tr><tr><td>description</td><td>Body text of the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>body</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Body</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Body text of the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>body</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>9</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>1073741823</td><td>integer</td><td>undefined</td></tr></table>


### title

Title of the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Title of the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Title of the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>title</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>200</td><td>integer</td><td>undefined</td></tr></table>


### description

Description of the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description of the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>description</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>11</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>2000</td><td>integer</td><td>undefined</td></tr></table>


### owningUser

Unique identifier of the user who owns the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user who owns the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning User</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the user who owns the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owninguser</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>12</td><td>integer</td><td>undefined</td></tr></table>


### createdBy

Unique identifier of the user who created the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the user who created the email signature.</td></tr></table>
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
                "Unique identifier of the user who created the email signature."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By",
  "description": "Unique identifier of the user who created the email signature.",
  "isNullable": true,
  "sourceName": "createdby",
  "sourceOrdering": 13
}
```

### presentationXml

XML data for the body of the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Presentation XML</td></tr><tr><td>description</td><td>XML data for the body of the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>presentationxml</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Presentation XML</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>XML data for the body of the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>presentationxml</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>14</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>1073741823</td><td>integer</td><td>undefined</td></tr></table>


### createdOn

Date and time when the email signature was created.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the email signature was created.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the email signature was created.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>createdon</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>15</td><td>integer</td><td>undefined</td></tr></table>


### modifiedBy

Unique identifier of the user who last modified the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the user who last modified the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedby</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>16</td><td>integer</td><td>undefined</td></tr></table>


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
                "Unique identifier of the user who last modified the email signature."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By",
  "description": "Unique identifier of the user who last modified the email signature.",
  "isNullable": true,
  "sourceName": "modifiedby",
  "sourceOrdering": 16
}
```

### modifiedOn

Date and time when the email signature was last modified.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the email signature was last modified.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the email signature was last modified.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedon</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>17</td><td>integer</td><td>undefined</td></tr></table>


### ownerIdType

The type of owner, either User or Team.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.entityName


##### is.readOnly


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The type of owner, either User or Team.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owneridtype</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.


##### is.CDS.owner

contains a User or Team ID


### ownerId

Owner Id

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>ownerid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Id</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>ownerid</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.


##### is.CDS.owner

contains a User or Team ID


### generationTypeCode

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generation Type Code</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>generationtypecode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Generation Type Code</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>generationtypecode</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>31</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### languageCode

Language of the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language</td></tr><tr><td>description</td><td>Language of the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>languagecode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.language


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Language</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Language of the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>languagecode</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>32</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


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


### overwriteTime

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Overwrite Time</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>overwritetime</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Overwrite Time</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>overwritetime</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>37</td><td>integer</td><td>undefined</td></tr></table>


### componentState

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Component State</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>componentstate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Published",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Unpublished",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Deleted",
    "attributeValue": "2",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Deleted Unpublished",
    "attributeValue": "3",
    "displayOrder": "3"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>Published</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Unpublished</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Deleted</td><td>2</td><td>2</td></tr><tr><td>en</td><td>Deleted Unpublished</td><td>3</td><td>3</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Component State</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>componentstate</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>38</td><td>integer</td><td>undefined</td></tr></table>


### componentState_display

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>componentState</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### createdOnBehalfBy

Unique identifier of the delegate user who created the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the delegate user who created the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>createdonbehalfby</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>42</td><td>integer</td><td>undefined</td></tr></table>


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
                "Unique identifier of the delegate user who created the email signature."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By (Delegate)",
  "description": "Unique identifier of the delegate user who created the email signature.",
  "isNullable": true,
  "sourceName": "createdonbehalfby",
  "sourceOrdering": 42
}
```

### modifiedOnBehalfBy

Unique identifier of the delegate user who last modified the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the delegate user who last modified the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedonbehalfby</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>46</td><td>integer</td><td>undefined</td></tr></table>


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
                "Unique identifier of the delegate user who last modified the email signature."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By (Delegate)",
  "description": "Unique identifier of the delegate user who last modified the email signature.",
  "isNullable": true,
  "sourceName": "modifiedonbehalfby",
  "sourceOrdering": 46
}
```

### owningTeam

Unique identifier of the team who owns the email signature.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier of the team who owns the email signature.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Team</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the team who owns the email signature.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owningteam</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>50</td><td>integer</td><td>undefined</td></tr></table>


### isCustomizable

Information that specifies whether this component can be customized.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customizable</td></tr><tr><td>description</td><td>Information that specifies whether this component can be customized.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>iscustomizable</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customizable</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Information that specifies whether this component can be customized.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>iscustomizable</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>52</td><td>integer</td><td>undefined</td></tr></table>


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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>55</td><td>integer</td><td>undefined</td></tr></table>


### isDefault

Information that specifies whether the email signature is default to the user.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Default</td></tr><tr><td>description</td><td>Information that specifies whether the email signature is default to the user.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isdefault</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is Default</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Information that specifies whether the email signature is default to the user.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>isdefault</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>56</td><td>integer</td><td>undefined</td></tr></table>



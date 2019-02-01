---
title: CampaignItem_
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/1/2019
ms.author: tpalmer
---
# Campaign Item

## Properties

Display Name: Campaign Item

Description: Work item in a campaign, a list or sales literature.

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/CampaignItem.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/CampaignItem.cdm.json)

## Instances

## Attributes - Summary

<table><tr><th>Name</th><th>Description</th><th>First Included in Instance</th></tr><tr><td>campaignItemId</td><td>Unique identifier of the campaign item.</td><td> </td></tr><tr><td>versionNumber</td><td>Version Number</td><td> </td></tr><tr><td>importSequenceNumber</td><td>Sequence number of the import that created this record.</td><td> </td></tr><tr><td>overriddenCreatedOn</td><td>Date and time that the record was migrated.</td><td> </td></tr><tr><td>timeZoneRuleVersionNumber</td><td>For internal use only.</td><td> </td></tr><tr><td>UTCConversionTimeZoneCode</td><td>Time zone code that was in use when the record was created.</td><td> </td></tr><tr><td>name</td><td>name</td><td> </td></tr><tr><td>campaignId</td><td>Unique identifier of the campaign that is associated with the individual item.</td><td> </td></tr><tr><td>entityId</td><td>Unique identifier of the entity for the campaign item.</td><td> </td></tr><tr><td>entityType</td><td>Object type of entity for the campaign item.</td><td> </td></tr><tr><td>ownerIdType</td><td>The type of owner, either User or Team.</td><td> </td></tr><tr><td>ownerId</td><td>Owner Id</td><td> </td></tr><tr><td>owningBusinessUnit</td><td>Unique identifier of the business unit that owns the campaign item.</td><td> </td></tr><tr><td>owningUser</td><td>Unique identifier of the user that owns the campaign item.</td><td> </td></tr></table>

## Attribute - Details

### campaignItemId

Unique identifier of the campaign item.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the campaign item.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>campaignitemid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"CampaignItem_/hasAttributes/campaignItemId"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"CampaignItem_/hasAttributes/campaignItemId"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the campaign item.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>campaignitemid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10000</td><td>integer</td><td>undefined</td></tr></table>


### versionNumber

Version Number

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.dataFormat.big


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>versionnumber</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10001</td><td>integer</td><td>undefined</td></tr></table>


### importSequenceNumber

Sequence number of the import that created this record.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence number of the import that created this record.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>importsequencenumber</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10002</td><td>integer</td><td>undefined</td></tr></table>


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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10003</td><td>integer</td><td>undefined</td></tr></table>


### timeZoneRuleVersionNumber

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>timezoneruleversionnumber</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10004</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-1</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### UTCConversionTimeZoneCode

Time zone code that was in use when the record was created.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>utcconversiontimezonecode</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10005</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-1</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### name

name

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>name</td></tr><tr><td>description</td><td>name</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.identity.name


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>name</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>name</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>name</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10006</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td>undefined</td></tr></table>


### campaignId

Unique identifier of the campaign that is associated with the individual item.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the campaign that is associated with the individual item.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>campaignid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

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


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the campaign that is associated with the individual item.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>campaignid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10007</td><td>integer</td><td>undefined</td></tr></table>


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
  "name": "campaignId",
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
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier of the campaign that is associated with the individual item."
              ]
            ]
          }
        }
      ]
    }
  ],
  "description": "Unique identifier of the campaign that is associated with the individual item.",
  "sourceName": "campaignid",
  "sourceOrdering": 10007
}
```

### entityId

Unique identifier of the entity for the campaign item.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the entity for the campaign item.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>entityid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the entity for the campaign item.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>entityid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10008</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "guid",
...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "guid",
  "name": "entityId",
  "appliedTraits": [
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
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier of the entity for the campaign item."
              ]
            ]
          }
        }
      ]
    }
  ],
  "description": "Unique identifier of the entity for the campaign item.",
  "sourceName": "entityid",
  "sourceOrdering": 10008
}
```

### entityType

Object type of entity for the campaign item.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Object type of entity for the campaign item.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>entitytype</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Object type of entity for the campaign item.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>entitytype</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10009</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


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


### owningBusinessUnit

Unique identifier of the business unit that owns the campaign item.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the business unit that owns the campaign item.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the business unit that owns the campaign item.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owningbusinessunit</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10011</td><td>integer</td><td>undefined</td></tr></table>


### owningUser

Unique identifier of the user that owns the campaign item.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the user that owns the campaign item.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the user that owns the campaign item.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owninguser</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10012</td><td>integer</td><td>undefined</td></tr></table>



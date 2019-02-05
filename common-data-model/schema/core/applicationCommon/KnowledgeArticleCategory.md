---
title: KnowledgeArticleCategory
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/5/2019
ms.author: tpalmer
---

# Knowledge Article Category

## Properties

Display Name: Knowledge Article Category

Description: Category for a Knowledge Article.

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/KnowledgeArticleCategory.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/KnowledgeArticleCategory.cdm.json)

## Instances

[/core/applicationCommon/KnowledgeArticleCategory.cdm.json/KnowledgeArticleCategory](KnowledgeArticleCategory.md)

## Attributes - Summary

|Name|Description|First Included in Instance|
|---|---|---|
|[knowledgeArticleId](#knowledgeArticleId)||[applicationCommon/KnowledgeArticleCategory](KnowledgeArticleCategory.md)|
|[categoryId](#categoryId)||[applicationCommon/KnowledgeArticleCategory](KnowledgeArticleCategory.md)|
|[knowledgeArticleCategoryId](#knowledgeArticleCategoryId)|Unique identifier of the Category for the knowledge article.|[applicationCommon/KnowledgeArticleCategory](KnowledgeArticleCategory.md)|
|[versionNumber](#versionNumber)||[applicationCommon/KnowledgeArticleCategory](KnowledgeArticleCategory.md)|

## Attribute - Details

### <a name="knowledgeArticleId">knowledgeArticleId</a>

First included in: /core/applicationCommon/KnowledgeArticleCategory.cdm.json/KnowledgeArticleCategory

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>sourceName</td><td>knowledgearticleid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the knowledgeArticleId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>knowledgearticleid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>1</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "guid",
...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "guid",
  "name": "knowledgeArticleId",
  "appliedTraits": [
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "systemrequired"
        }
      ]
    }
  ],
  "sourceName": "knowledgearticleid",
  "sourceOrdering": 1
}
```

</details>

### <a name="categoryId">categoryId</a>

First included in: /core/applicationCommon/KnowledgeArticleCategory.cdm.json/KnowledgeArticleCategory

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>sourceName</td><td>categoryid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the categoryId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>categoryid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>2</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="knowledgeArticleCategoryId">knowledgeArticleCategoryId</a>

Unique identifier of the Category for the knowledge article.

First included in: /core/applicationCommon/KnowledgeArticleCategory.cdm.json/KnowledgeArticleCategory

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>description</td><td>Unique identifier of the Category for the knowledge article.</td></tr>
<tr><td>isPrimaryKey</td><td>true</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>sourceName</td><td>knowledgearticlecategoryid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the knowledgeArticleCategoryId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>attribute</td><td>"KnowledgeArticleCategory_/hasAttributes/knowledge...(see Definition below)</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"KnowledgeArticleCategory_/hasAttributes/knowledgeArticleCategoryId"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the Category for the knowledge article.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>knowledgearticlecategoryid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>3</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="versionNumber">versionNumber</a>

First included in: /core/applicationCommon/KnowledgeArticleCategory.cdm.json/KnowledgeArticleCategory

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>Int64</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>versionnumber</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the versionNumber attribute are listed below.</summary>

##### is.dataFormat.integer

##### is.dataFormat.big

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
<tr><td>name</td><td>versionnumber</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>4</td><td>integer</td><td></td></tr>
</table>

</details>


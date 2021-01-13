---
title: List of Common Data Model traits | Microsoft Docs
description: Lists the traits that are available in Common Data Model and describes the inheritance and properties of the traits.
author: matgos
ms.service: common-data-model
ms.reviewer: v-iap
ms.topic: article
ms.date: 12/14/2020
ms.author: matgos
---

# List of Common Data Model traits
This page lists the traits that are available in Common Data Model.

## <b>is</b>
**Description**

The root 'trait' from which all others derive.

### **Inheritance**
None

### **Properties**
None

## <b>is.application</b>
**Description**

Root trait for application information

### **Inheritance**
| |
|--|
|is -> is.application|

### **Properties**
None

## <b>is.application.releaseVersion</b>
### **Inheritance**
| |
|--|
|is -> is.application -> is.application.releaseVersion|

### **Properties**
None

## <b>is.CDM</b>
**Description**

Root trait for information about the CDM itself.

### **Inheritance**
| |
|--|
|is -> is.CDM|

### **Properties**
None

## <b>is.CDM.entityVersion</b>
### **Inheritance**
| |
|--|
|is -> is.CDM -> is.CDM.entityVersion|

### **Properties**
| |
|--|
|<b>version</b>|

## <b>is.CDM.attributeGroup</b>
**Description**

Identifies standard groups of attributes in CDM entities.

### **Inheritance**
| |
|--|
|is -> is.CDM -> is.CDM.attributeGroup|

### **Properties**
| |
|--|
|<b>cdmSchemas</b>|

## <b>is.localized</b>
**Description**

Associates a list of localized string with an object

### **Inheritance**
| |
|--|
|is -> is.localized|

### **Properties**
None

## <b>is.localized.displayedAs</b>
**Description**

Holds the list of language specific display text for an object.

### **Inheritance**
| |
|--|
|is -> is.localized -> is.localized.displayedAs|

### **Properties**
| |
|--|
|<b>displayName</b>|

## <b>is.localized.describedAs</b>
**Description**

Holds the list of language specific descriptive text for an object.

### **Inheritance**
| |
|--|
|is -> is.localized -> is.localized.describedAs|

### **Properties**
| |
|--|
|<b>description</b>|

## <b>is.nullable</b>
**Description**

The attribute value may be set to NULL.

### **Inheritance**
| |
|--|
|is -> is.nullable|

### **Properties**
| |
|--|
|<b>isNullable</b>|

## <b>is.readOnly</b>
### **Inheritance**
| |
|--|
|is -> is.readOnly|

### **Properties**
| |
|--|
|<b>isReadOnly</b>|

## <b>is.requiredAtLevel</b>
**Description**

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

### **Inheritance**
| |
|--|
|is -> is.requiredAtLevel|

### **Properties**
None

## <b>is.constrained</b>
**Description**

Maximum length or value constraints

### **Inheritance**
| |
|--|
|is -> is.constrained|

### **Properties**
| |
|--|
|<b>maximumValue</b>|
|<b>minimumValue</b>|
|<b>maximumLength</b>|

## <b>is.constrainedList</b>
**Description**

The values of an attribute are taken from or looked up from a fixed list of possibilities

### **Inheritance**
| |
|--|
|is -> is.constrainedList|

### **Properties**
| |
|--|
|<b>valueConstrainedToList</b>|

## <b>is.constrainedList.correlated</b>
**Description**

The values of an attribute are taken from or looked up from a fixed list of possibilities that represent correlated status

### **Inheritance**
| |
|--|
|is -> is.constrainedList.correlated|

### **Properties**
| |
|--|
|<b>valueConstrainedToList</b>|

## <b>is.constrainedList.string</b>
**Description**

The values of an attribute are taken from or looked up from a fixed list of possibilities

### **Inheritance**
| |
|--|
|is -> is.constrainedList.string|

### **Properties**
| |
|--|
|<b>valueConstrainedToList</b>|

## <b>is.constrainedList.wellKnown</b>
**Description**

The values of an attribute are taken from or looked up from a fixed list of possibilities which are defined in an identified public location.

### **Inheritance**
| |
|--|
|is -> is.constrainedList.wellKnown|

### **Properties**
| |
|--|
|<b>valueConstrainedToList</b>|

## <b>is.correlatedWith</b>
**Description**

The attribute value is correlated with the sourceAttribute

### **Inheritance**
| |
|--|
|is -> is.correlatedWith|

### **Properties**
None

## <b>is.calculationOf</b>
**Description**

The attribute value is the result of a calculation on the sourceAttribute

### **Inheritance**
| |
|--|
|is -> is.correlatedWith -> is.calculationOf|

### **Properties**
None

## <b>is.partition</b>
**Description**

The base trait for partition specific traits.

### **Inheritance**
| |
|--|
|is -> is.partition|

### **Properties**
None

## <b>is.partition.format</b>
### **Inheritance**
| |
|--|
|is -> is.partition -> is.partition.format|

### **Properties**
None

## <b>is.partition.format.CSV</b>
**Description**

The value is the file format settings of a partition CSV file.

### **Inheritance**
| |
|--|
|is -> is.partition -> is.partition.format -> is.partition.format.CSV|

### **Properties**
None

## <b>is.partition.format.parquet</b>
**Description**

The value is the file format settings of a partition parquet file.

### **Inheritance**
| |
|--|
|is -> is.partition -> is.partition.format -> is.partition.format.parquet|

### **Properties**
None

## <b>is.partition.format.deltaLake</b>
**Description**

The partition path points to one complete folder of Spark Delta Lake data. Options allow for time travel access to the data.

### **Inheritance**
| |
|--|
|is -> is.partition -> is.partition.format -> is.partition.format.deltaLake|

### **Properties**
None

## <b>is.partition.culture</b>
**Description**

The value denotes culture in the partition files.

### **Inheritance**
| |
|--|
|is -> is.partition -> is.partition.culture|

### **Properties**
None

## <b>is.modelConversion</b>
**Description**

Represents a correlation with model.json to CDM model conversion.

### **Inheritance**
| |
|--|
|is -> is.modelConversion|

### **Properties**
None

## <b>is.modelConversion.modelVersion</b>
**Description**

The value denotes the version number set in a converted model.json file

### **Inheritance**
| |
|--|
|is -> is.modelConversion -> is.modelConversion.modelVersion|

### **Properties**
None

## <b>is.modelConversion.otherAnnotations</b>
**Description**

The value denotes model.json annotations which have not been recognized.

### **Inheritance**
| |
|--|
|is -> is.modelConversion -> is.modelConversion.otherAnnotations|

### **Properties**
None

## <b>is.modelConversion.referenceModelMap</b>
**Description**

The value denotes a reference model map containing multiple id-location pairs used for reference entity resolution.

### **Inheritance**
| |
|--|
|is -> is.modelConversion -> is.modelConversion.referenceModelMap|

### **Properties**
None

## <b>is.managedBy</b>
**Description**

The value denotes information about a service/entity who is owning a model.

### **Inheritance**
| |
|--|
|is -> is.managedBy|

### **Properties**
None

## <b>does</b>
**Description**

A root with a more meaningful base name for certain exhibited traits

### **Inheritance**
| |
|--|
|is -> does|

### **Properties**
None

## <b>does.haveDefault</b>
**Description**

An attribute has a default value

### **Inheritance**
| |
|--|
|is -> does -> does.haveDefault|

### **Properties**
| |
|--|
|<b>defaultValue</b>|

## <b>does.elevateAttribute</b>
**Description**

Elevates (up to a entity) a trait that describes a specific attribute

### **Inheritance**
| |
|--|
|is -> does -> does.elevateAttribute|

### **Properties**
None

## <b>means.entityState</b>
**Description**

The attribute represents the current state of the entity.

### **Inheritance**
| |
|--|
|is -> does -> does.elevateAttribute -> means.entityState|

### **Properties**
None

## <b>is.identifiedBy</b>
**Description**

Names a specifc identity attribute to use with an entity

### **Inheritance**
| |
|--|
|is -> does -> does.elevateAttribute -> is.identifiedBy|

### **Properties**
| |
|--|
|<b>primaryKey</b>|
|<b>isPrimaryKey</b>|

## <b>is.named</b>
### **Inheritance**
| |
|--|
|is -> does -> does.elevateAttribute -> is.named|

### **Properties**
None

## <b>is.ordered</b>
### **Inheritance**
| |
|--|
|is -> does -> does.elevateAttribute -> is.ordered|

### **Properties**
None

## <b>is.locatable</b>
### **Inheritance**
| |
|--|
|is -> does -> does.elevateAttribute -> is.locatable|

### **Properties**
None

## <b>means</b>
**Description**

A root with a more meaningful base name for certain semantic meaning traits

### **Inheritance**
| |
|--|
|is -> means|

### **Properties**
None

## <b>means.identity</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity|

### **Properties**
None

## <b>means.identity.entityId</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.entityId|

### **Properties**
None

## <b>means.identity.barCode</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.barCode|

### **Properties**
None

## <b>means.identity.brand</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.brand|

### **Properties**
None

## <b>means.identity.governmentID</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.governmentID|

### **Properties**
None

## <b>means.identity.name</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.name|

### **Properties**
None

## <b>means.identity.company.name</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.name -> means.identity.company.name|

### **Properties**
None

## <b>means.identity.person.prefix</b>
**Description**

A salutation such as a title, rank or honorific to place before a person's name

### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.name -> means.identity.person.prefix|

### **Properties**
None

## <b>means.identity.person.firstName</b>
**Description**

A person's given or first name.

### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.name -> means.identity.person.firstName|

### **Properties**
None

## <b>means.identity.person.middleName</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.name -> means.identity.person.middleName|

### **Properties**
None

## <b>means.identity.person.lastName</b>
**Description**

A person's surname, family name or last name.

### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.name -> means.identity.person.lastName|

### **Properties**
None

## <b>means.identity.person.suffix</b>
**Description**

Follows a person's name and provides additional information about their position, education or honorific

### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.name -> means.identity.person.suffix|

### **Properties**
None

## <b>means.identity.person.fullName</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.name -> means.identity.person.fullName|

### **Properties**
None

## <b>means.identity.rowNumber</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.rowNumber|

### **Properties**
None

## <b>means.identity.scd.originalIdentity</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.scd.originalIdentity|

### **Properties**
None

## <b>means.identity.scd.surogateIdentity</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.scd.surogateIdentity|

### **Properties**
None

## <b>means.identity.service</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.service|

### **Properties**
None

## <b>means.identity.service.email</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.service.email|

### **Properties**
None

## <b>means.identity.service.facebook</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.service.facebook|

### **Properties**
None

## <b>means.identity.service.phone</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.service.phone|

### **Properties**
None

## <b>means.identity.service.phone.cell</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.service.phone.cell|

### **Properties**
None

## <b>means.identity.service.phone.fax</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.service.phone.fax|

### **Properties**
None

## <b>means.identity.service.twitter</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.service.twitter|

### **Properties**
None

## <b>means.identity.SKU</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.SKU|

### **Properties**
None

## <b>means.identity.tickerSymbol</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.tickerSymbol|

### **Properties**
None

## <b>means.identity.title</b>
### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.title|

### **Properties**
None

## <b>means.identity.IP4Address</b>
**Description**

Internet Protocol V4 Address

### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.IP4Address|

### **Properties**
None

## <b>means.identity.IP6Address</b>
**Description**

Internet Protocol V6 Address

### **Inheritance**
| |
|--|
|is -> means -> means.identity -> means.identity.IP6Address|

### **Properties**
None

## <b>means.fileName</b>
### **Inheritance**
| |
|--|
|is -> means -> means.fileName|

### **Properties**
None

## <b>means.entityName</b>
**Description**

A string value is the name of a CDM entity.

### **Inheritance**
| |
|--|
|is -> means -> means.entityName|

### **Properties**
None

## <b>means.entityName.specific</b>
**Description**

Holds the name of specific CDM entity as a parameter of the trait.

### **Inheritance**
| |
|--|
|is -> means -> means.entityName -> means.entityName.specific|

### **Properties**
None

## <b>means.content</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content|

### **Properties**
None

## <b>means.content.text</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.text|

### **Properties**
None

## <b>means.content.text.HTML</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.text -> means.content.text.HTML|

### **Properties**
None

## <b>means.content.text.JSON</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.text -> means.content.text.JSON|

### **Properties**
None

## <b>means.content.text.XML</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.text -> means.content.text.XML|

### **Properties**
None

## <b>means.content.text.CSV</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.text -> means.content.text.CSV|

### **Properties**
None

## <b>means.content.binary</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.binary|

### **Properties**
None

## <b>means.content.binary.image</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.binary -> means.content.binary.image|

### **Properties**
None

## <b>means.content.binary.image.BMP</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.binary -> means.content.binary.image -> means.content.binary.image.BMP|

### **Properties**
None

## <b>means.content.binary.image.GIF</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.binary -> means.content.binary.image -> means.content.binary.image.GIF|

### **Properties**
None

## <b>means.content.binary.image.JPG</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.binary -> means.content.binary.image -> means.content.binary.image.JPG|

### **Properties**
None

## <b>means.content.binary.image.PNG</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.binary -> means.content.binary.image -> means.content.binary.image.PNG|

### **Properties**
None

## <b>means.content.binary.image.TIFF</b>
### **Inheritance**
| |
|--|
|is -> means -> means.content -> means.content.binary -> means.content.binary.image -> means.content.binary.image.TIFF|

### **Properties**
None

## <b>means.idea</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea|

### **Properties**
None

## <b>means.idea.account</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.account|

### **Properties**
None

## <b>means.idea.accountLeads</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.accountLeads|

### **Properties**
None

## <b>means.idea.activityParty</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.activityParty|

### **Properties**
None

## <b>means.idea.activityPointer</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.activityPointer|

### **Properties**
None

## <b>means.idea.annotation</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.annotation|

### **Properties**
None

## <b>means.idea.appointment</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.appointment|

### **Properties**
None

## <b>means.idea.brand</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.brand|

### **Properties**
None

## <b>means.idea.businessUnit</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.businessUnit|

### **Properties**
None

## <b>means.idea.campaign</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.campaign|

### **Properties**
None

## <b>means.idea.campaignActivity</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.campaignActivity|

### **Properties**
None

## <b>means.idea.campaignItem</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.campaignItem|

### **Properties**
None

## <b>means.idea.campaignResponse</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.campaignResponse|

### **Properties**
None

## <b>means.idea.channel</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.channel|

### **Properties**
None

## <b>means.idea.characteristic</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.characteristic|

### **Properties**
None

## <b>means.idea.company</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.company|

### **Properties**
None

## <b>means.idea.competitor</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.competitor|

### **Properties**
None

## <b>means.idea.competitorAddress</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.competitorAddress|

### **Properties**
None

## <b>means.idea.competitorProduct</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.competitorProduct|

### **Properties**
None

## <b>means.idea.connection</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.connection|

### **Properties**
None

## <b>means.idea.connectionRole</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.connectionRole|

### **Properties**
None

## <b>means.idea.contract</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.contract|

### **Properties**
None

## <b>means.idea.contractDetail</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.contractDetail|

### **Properties**
None

## <b>means.idea.customer</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.customer|

### **Properties**
None

## <b>means.idea.customerAddress</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.customerAddress|

### **Properties**
None

## <b>means.idea.customerRelationship</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.customerRelationship|

### **Properties**
None

## <b>means.idea.discount</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.discount|

### **Properties**
None

## <b>means.idea.discountType</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.discountType|

### **Properties**
None

## <b>means.idea.email</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.email|

### **Properties**
None

## <b>means.idea.entitlement</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.entitlement|

### **Properties**
None

## <b>means.idea.equipment</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.equipment|

### **Properties**
None

## <b>means.idea.fax</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.fax|

### **Properties**
None

## <b>means.idea.feedback</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.feedback|

### **Properties**
None

## <b>means.idea.goal</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.goal|

### **Properties**
None

## <b>means.idea.incident</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.incident|

### **Properties**
None

## <b>means.idea.invoice</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.invoice|

### **Properties**
None

## <b>means.idea.invoiceDetail</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.invoiceDetail|

### **Properties**
None

## <b>means.idea.KbArticle</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.KbArticle|

### **Properties**
None

## <b>means.idea.knowledgeArticle</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.knowledgeArticle|

### **Properties**
None

## <b>means.idea.lead</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.lead|

### **Properties**
None

## <b>means.idea.leadAddress</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.leadAddress|

### **Properties**
None

## <b>means.idea.letter</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.letter|

### **Properties**
None

## <b>means.idea.metric</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.metric|

### **Properties**
None

## <b>means.idea.opportunity</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.opportunity|

### **Properties**
None

## <b>means.idea.organization</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.organization|

### **Properties**
None

## <b>means.idea.organization.unit</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.organization.unit|

### **Properties**
None

## <b>means.idea.owner</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.owner|

### **Properties**
None

## <b>means.idea.person</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.person|

### **Properties**
None

## <b>means.idea.person.contact</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.person -> means.idea.person.contact|

### **Properties**
None

## <b>means.idea.person.employee</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.person -> means.idea.person.employee|

### **Properties**
None

## <b>means.idea.person.representative</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.person -> means.idea.person.representative|

### **Properties**
None

## <b>means.idea.phoneCall</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.phoneCall|

### **Properties**
None

## <b>means.idea.place</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.place|

### **Properties**
None

## <b>means.idea.position</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.position|

### **Properties**
None

## <b>means.idea.priceLevel</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.priceLevel|

### **Properties**
None

## <b>means.idea.product</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.product|

### **Properties**
None

## <b>means.idea.productGroup</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.productGroup|

### **Properties**
None

## <b>means.idea.project</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.project|

### **Properties**
None

## <b>means.idea.promotion</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.promotion|

### **Properties**
None

## <b>means.idea.quote</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.quote|

### **Properties**
None

## <b>means.idea.ratingModel</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.ratingModel|

### **Properties**
None

## <b>means.idea.resource</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.resource|

### **Properties**
None

## <b>means.idea.resourceGroup</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.resourceGroup|

### **Properties**
None

## <b>means.idea.salesLiterature</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.salesLiterature|

### **Properties**
None

## <b>means.idea.salesOrder</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.salesOrder|

### **Properties**
None

## <b>means.idea.scenario</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.scenario|

### **Properties**
None

## <b>means.idea.schedule</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.schedule|

### **Properties**
None

## <b>means.idea.service</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.service|

### **Properties**
None

## <b>means.idea.service </b>
**Description**

Deprecated. extra space at the end was an error.

### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.service -> means.idea.service |

### **Properties**
None

## <b>means.idea.serviceAppointment</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.serviceAppointment|

### **Properties**
None

## <b>means.idea.site</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.site|

### **Properties**
None

## <b>means.idea.SLA</b>
**Description**

A Service Level Agreement

### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.SLA|

### **Properties**
None

## <b>means.idea.socialActivity</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.socialActivity|

### **Properties**
None

## <b>means.idea.socialProfile</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.socialProfile|

### **Properties**
None

## <b>means.idea.systemUser</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.systemUser|

### **Properties**
None

## <b>means.idea.task</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.task|

### **Properties**
None

## <b>means.idea.team</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.team|

### **Properties**
None

## <b>means.idea.territory</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.territory|

### **Properties**
None

## <b>means.idea.UoM</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.UoM|

### **Properties**
None

## <b>means.idea.utility</b>
### **Inheritance**
| |
|--|
|is -> means -> means.idea -> means.idea.utility|

### **Properties**
None

## <b>means.category</b>
### **Inheritance**
| |
|--|
|is -> means -> means.category|

### **Properties**
None

## <b>means.relationship</b>
### **Inheritance**
| |
|--|
|is -> means -> means.relationship|

### **Properties**
None

## <b>means.relationship.parent</b>
### **Inheritance**
| |
|--|
|is -> means -> means.relationship -> means.relationship.parent|

### **Properties**
None

## <b>means.relationship.child</b>
### **Inheritance**
| |
|--|
|is -> means -> means.relationship -> means.relationship.child|

### **Properties**
None

## <b>means.reference</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference|

### **Properties**
None

## <b>means.reference.caption</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.caption|

### **Properties**
None

## <b>means.reference.displayText</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.displayText|

### **Properties**
None

## <b>means.reference.documentation</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.documentation|

### **Properties**
None

## <b>means.reference.description</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.description|

### **Properties**
None

## <b>means.reference.definition</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.definition|

### **Properties**
None

## <b>means.reference.phonetic</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.phonetic|

### **Properties**
None

## <b>means.reference.regarding</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.regarding|

### **Properties**
None

## <b>means.reference.URL</b>
**Description**

A Uniform Resource Locator. A web address.

### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.URL|

### **Properties**
None

## <b>means.reference.URL.image</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.URL -> means.reference.URL.image|

### **Properties**
None

## <b>means.reference.URI</b>
**Description**

A Uniform Resource Identifier

### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.URI|

### **Properties**
None

## <b>means.reference.language</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.language|

### **Properties**
None

## <b>means.reference.language.tag</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.language -> means.reference.language.tag|

### **Properties**
None

## <b>means.reference.culture</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.culture|

### **Properties**
None

## <b>means.reference.culture.tag</b>
### **Inheritance**
| |
|--|
|is -> means -> means.reference -> means.reference.culture -> means.reference.culture.tag|

### **Properties**
None

## <b>means.calendar</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar|

### **Properties**
None

## <b>means.calendar.fiscal</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.fiscal|

### **Properties**
None

## <b>means.calendar.ISO8601</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.ISO8601|

### **Properties**
None

## <b>means.calendar.manufacturing</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.manufacturing|

### **Properties**
None

## <b>means.calendar.reporting</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.reporting|

### **Properties**
None

## <b>means.calendar.day</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.day|

### **Properties**
None

## <b>means.calendar.dayOfWeek</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.day -> means.calendar.dayOfWeek|

### **Properties**
None

## <b>means.calendar.dayOfTendays</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.day -> means.calendar.dayOfTendays|

### **Properties**
None

## <b>means.calendar.dayOfMonth</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.day -> means.calendar.dayOfMonth|

### **Properties**
None

## <b>means.calendar.dayOfMonthOrPeriod</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.day -> means.calendar.dayOfMonthOrPeriod|

### **Properties**
None

## <b>means.calendar.dayOfQuarter</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.day -> means.calendar.dayOfQuarter|

### **Properties**
None

## <b>means.calendar.dayOfTrimester</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.day -> means.calendar.dayOfTrimester|

### **Properties**
None

## <b>means.calendar.dayOfHalfyear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.day -> means.calendar.dayOfHalfyear|

### **Properties**
None

## <b>means.calendar.dayOfYear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.day -> means.calendar.dayOfYear|

### **Properties**
None

## <b>means.calendar.week</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.week|

### **Properties**
None

## <b>means.calendar.weekOfMonth</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.week -> means.calendar.weekOfMonth|

### **Properties**
None

## <b>means.calendar.weekOfQuarter</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.week -> means.calendar.weekOfQuarter|

### **Properties**
None

## <b>means.calendar.weekOfTrimester</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.week -> means.calendar.weekOfTrimester|

### **Properties**
None

## <b>means.calendar.weekOfHalfyear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.week -> means.calendar.weekOfHalfyear|

### **Properties**
None

## <b>means.calendar.weekOfYear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.week -> means.calendar.weekOfYear|

### **Properties**
None

## <b>means.calendar.tenday</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.tenday|

### **Properties**
None

## <b>means.calendar.tendayOfMonth</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.tenday -> means.calendar.tendayOfMonth|

### **Properties**
None

## <b>means.calendar.tendayOfQuarter</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.tenday -> means.calendar.tendayOfQuarter|

### **Properties**
None

## <b>means.calendar.tendayOfTrimester</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.tenday -> means.calendar.tendayOfTrimester|

### **Properties**
None

## <b>means.calendar.tendayOfHalfyear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.tenday -> means.calendar.tendayOfHalfyear|

### **Properties**
None

## <b>means.calendar.tendayOfYear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.tenday -> means.calendar.tendayOfYear|

### **Properties**
None

## <b>means.calendar.month</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.month|

### **Properties**
None

## <b>means.calendar.monthOfQuarter</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.month -> means.calendar.monthOfQuarter|

### **Properties**
None

## <b>means.calendar.monthOfTrimester</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.month -> means.calendar.monthOfTrimester|

### **Properties**
None

## <b>means.calendar.monthOfHalfyear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.month -> means.calendar.monthOfHalfyear|

### **Properties**
None

## <b>means.calendar.monthOfYear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.month -> means.calendar.monthOfYear|

### **Properties**
None

## <b>means.calendar.quarter</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.quarter|

### **Properties**
None

## <b>means.calendar.quarterOfHalfyear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.quarter -> means.calendar.quarterOfHalfyear|

### **Properties**
None

## <b>means.calendar.quarterOfYear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.quarter -> means.calendar.quarterOfYear|

### **Properties**
None

## <b>means.calendar.trimester</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.trimester|

### **Properties**
None

## <b>means.calendar.trimesterOfYear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.trimester -> means.calendar.trimesterOfYear|

### **Properties**
None

## <b>means.calendar.year</b>
### **Inheritance**
| |
|--|
|is -> means -> means.calendar -> means.calendar.year|

### **Properties**
None

## <b>means.measurement</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement|

### **Properties**
None

## <b>means.measurement.dimension</b>
**Description**

Measurement of some physical dimension

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension|

### **Properties**
None

## <b>means.measurement.dimension.time</b>
**Description**

Measurement of time

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.time|

### **Properties**
None

## <b>means.measurement.dimension.length</b>
**Description**

Measurement of length

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.length|

### **Properties**
None

## <b>means.measurement.distance</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.length -> means.measurement.distance|

### **Properties**
None

## <b>means.measurement.distance.inches</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.length -> means.measurement.distance -> means.measurement.distance.inches|

### **Properties**
None

## <b>means.measurement.distance.cm</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.length -> means.measurement.distance -> means.measurement.distance.cm|

### **Properties**
None

## <b>means.measurement.dimension.mass</b>
**Description**

Measurement of mass

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.mass|

### **Properties**
None

## <b>means.measurement.dimension.electricCurrent</b>
**Description**

Measurement of electic current

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.electricCurrent|

### **Properties**
None

## <b>means.measurement.dimension.temperature</b>
**Description**

Measurement of thermodynamic temperature

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.temperature|

### **Properties**
None

## <b>means.measurement.temperature</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.temperature -> means.measurement.temperature|

### **Properties**
None

## <b>means.measurement.dimension.amount</b>
**Description**

Measurement of amount of substance

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.amount|

### **Properties**
None

## <b>means.measurement.dimension.luminousIntensity</b>
**Description**

Measurement of electic current

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.luminousIntensity|

### **Properties**
None

## <b>means.measurement.dimension.frequency</b>
**Description**

Measurement of frequency

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.frequency|

### **Properties**
None

## <b>means.measurement.dimension.angle</b>
**Description**

Measurement of geometric angle

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.angle|

### **Properties**
None

## <b>means.measurement.dimension.force</b>
**Description**

Measurement of force

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.force|

### **Properties**
None

## <b>means.measurement.weight</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.force -> means.measurement.weight|

### **Properties**
None

## <b>means.measurement.dimension.pressure</b>
**Description**

Measurement of pressure or stress

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.pressure|

### **Properties**
None

## <b>means.measurement.dimension.energy</b>
**Description**

Measurement of energy, work, heat

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.energy|

### **Properties**
None

## <b>means.measurement.dimension.power</b>
**Description**

Measurement of power, radiant flex

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.power|

### **Properties**
None

## <b>means.measurement.dimension.electricCharge</b>
**Description**

Measurement of electric charge, quantity of electricity

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.electricCharge|

### **Properties**
None

## <b>means.measurement.dimension.electromotiveForce</b>
**Description**

Measurement of volatage, EMF, electrical potential difference

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.electromotiveForce|

### **Properties**
None

## <b>means.measurement.dimension.capacitance</b>
**Description**

Measurement of electical capacitance

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.capacitance|

### **Properties**
None

## <b>means.measurement.dimension.resistance</b>
**Description**

Measurement of electrical resistance, impedance, reactance

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.resistance|

### **Properties**
None

## <b>means.measurement.dimension.dataRate</b>
**Description**

Measurement of data rate

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.dimension -> means.measurement.dimension.dataRate|

### **Properties**
None

## <b>has.measurement.fundamentalComponent</b>
**Description**

Description of one fundamental component of a derived unit

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> has.measurement.fundamentalComponent|

### **Properties**
None

## <b>has.measurement.fundamentalComponent.second</b>
**Description**

A fundamental component expressing time in seconds

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> has.measurement.fundamentalComponent -> has.measurement.fundamentalComponent.second|

### **Properties**
None

## <b>has.measurement.fundamentalComponent.meter</b>
**Description**

A fundamental component expressing length in meters

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> has.measurement.fundamentalComponent -> has.measurement.fundamentalComponent.meter|

### **Properties**
None

## <b>has.measurement.fundamentalComponent.kilogram</b>
**Description**

A fundamental component expressing mass in kilogram

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> has.measurement.fundamentalComponent -> has.measurement.fundamentalComponent.kilogram|

### **Properties**
None

## <b>has.measurement.fundamentalComponent.ampere</b>
**Description**

A fundamental component expressing electric current in amperes

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> has.measurement.fundamentalComponent -> has.measurement.fundamentalComponent.ampere|

### **Properties**
None

## <b>has.measurement.fundamentalComponent.kelvin</b>
**Description**

A fundamental component expressing thermodynamic temperature in degrees kelvin

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> has.measurement.fundamentalComponent -> has.measurement.fundamentalComponent.kelvin|

### **Properties**
None

## <b>has.measurement.fundamentalComponent.mole</b>
**Description**

A fundamental component expressing amount in moles

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> has.measurement.fundamentalComponent -> has.measurement.fundamentalComponent.mole|

### **Properties**
None

## <b>has.measurement.fundamentalComponent.candela</b>
**Description**

A fundamental component expressing luminous intensity in candelas

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> has.measurement.fundamentalComponent -> has.measurement.fundamentalComponent.candela|

### **Properties**
None

## <b>means.measurement.prefix</b>
**Description**

Unit prefixes denoting a factor of one thousandth

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.prefix|

### **Properties**
None

## <b>means.measurement.prefix.giga</b>
**Description**

Denotes one thousanth of the unit; 10E9

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.prefix -> means.measurement.prefix.giga|

### **Properties**
None

## <b>means.measurement.prefix.mega</b>
**Description**

Denotes one thousanth of the unit; 10E6

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.prefix -> means.measurement.prefix.mega|

### **Properties**
None

## <b>means.measurement.prefix.kilo</b>
**Description**

Denotes one thousanth of the unit; 10E3

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.prefix -> means.measurement.prefix.kilo|

### **Properties**
None

## <b>means.measurement.prefix.centi</b>
**Description**

Denotes one thousanth of the unit; 10E-2

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.prefix -> means.measurement.prefix.centi|

### **Properties**
None

## <b>means.measurement.prefix.milli</b>
**Description**

Denotes one thousanth of the unit; 10E-3

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.prefix -> means.measurement.prefix.milli|

### **Properties**
None

## <b>means.measurement.prefix.micro</b>
**Description**

Denotes one thousanth of the unit; 10E-6

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.prefix -> means.measurement.prefix.micro|

### **Properties**
None

## <b>means.measurement.prefix.nano</b>
**Description**

Denotes one thousanth of the unit; 10E-9

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.prefix -> means.measurement.prefix.nano|

### **Properties**
None

## <b>means.measurement.prefix.pico</b>
**Description**

Denotes one thousanth of the unit; 10E-12

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.prefix -> means.measurement.prefix.pico|

### **Properties**
None

## <b>means.measurement.units.degree</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.units.degree|

### **Properties**
None

## <b>means.measurement.age</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.age|

### **Properties**
None

## <b>means.measurement.code</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.code|

### **Properties**
None

## <b>means.measurement.color</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.color|

### **Properties**
None

## <b>means.measurement.density</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.density|

### **Properties**
None

## <b>means.measurement.sequence</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.sequence|

### **Properties**
None

## <b>means.measurement.version</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.version|

### **Properties**
None

## <b>means.measurement.currency</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.currency|

### **Properties**
None

## <b>means.measurement.currency.cost</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.currency -> means.measurement.currency.cost|

### **Properties**
None

## <b>means.measurement.currency.price</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.currency -> means.measurement.currency.price|

### **Properties**
None

## <b>means.measurement.currency.revenue</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.currency -> means.measurement.currency.revenue|

### **Properties**
None

## <b>means.measurement.currency.iSOCode</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.currency.iSOCode|

### **Properties**
None

## <b>means.measurement.currency.type</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.currency.type|

### **Properties**
None

## <b>means.measurement.currency.type.destination</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.currency.type -> means.measurement.currency.type.destination|

### **Properties**
None

## <b>means.measurement.currency.type.source</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.currency.type -> means.measurement.currency.type.source|

### **Properties**
None

## <b>means.measurement.time</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.time|

### **Properties**
None

## <b>means.measurement.date</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.date|

### **Properties**
None

## <b>means.measurement.date.completion</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.date -> means.measurement.date.completion|

### **Properties**
None

## <b>means.measurement.date.creation</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.date -> means.measurement.date.creation|

### **Properties**
None

## <b>means.measurement.date.end</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.date -> means.measurement.date.end|

### **Properties**
None

## <b>means.measurement.date.end.scd</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.date -> means.measurement.date.end.scd|

### **Properties**
None

## <b>means.measurement.date.modify</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.date -> means.measurement.date.modify|

### **Properties**
None

## <b>means.measurement.date.occurrence</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.date -> means.measurement.date.occurrence|

### **Properties**
None

## <b>means.measurement.date.remove</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.date -> means.measurement.date.remove|

### **Properties**
None

## <b>means.measurement.date.start</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.date -> means.measurement.date.start|

### **Properties**
None

## <b>means.measurement.date.start.scd</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.date -> means.measurement.date.start.scd|

### **Properties**
None

## <b>means.measurement.date.target</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.date -> means.measurement.date.target|

### **Properties**
None

## <b>means.measurement.duration</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.duration|

### **Properties**
None

## <b>means.measurement.duration.seconds</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.duration -> means.measurement.duration.seconds|

### **Properties**
None

## <b>means.measurement.duration.minutes</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.duration -> means.measurement.duration.minutes|

### **Properties**
None

## <b>means.measurement.duration.hours</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.duration -> means.measurement.duration.hours|

### **Properties**
None

## <b>means.measurement.duration.days</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.duration -> means.measurement.duration.days|

### **Properties**
None

## <b>means.measurement.duration.months</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.duration -> means.measurement.duration.months|

### **Properties**
None

## <b>means.measurement.duration.weeks</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.duration -> means.measurement.duration.weeks|

### **Properties**
None

## <b>means.measurement.duration.quarters</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.duration -> means.measurement.duration.quarters|

### **Properties**
None

## <b>means.measurement.duration.trimesters</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.duration -> means.measurement.duration.trimesters|

### **Properties**
None

## <b>means.measurement.duration.years</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.duration -> means.measurement.duration.years|

### **Properties**
None

## <b>means.measurement.probability</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.probability|

### **Properties**
None

## <b>means.measurement.count</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.count|

### **Properties**
None

## <b>means.measurement.percent</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.percent|

### **Properties**
None

## <b>means.measurement.percent.ownership</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.percent.ownership|

### **Properties**
None

## <b>means.measurement.percent.voterright</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.percent.voterright|

### **Properties**
None

## <b>means.measurement.range</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.range|

### **Properties**
None

## <b>means.measurement.range.high</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.range -> means.measurement.range.high|

### **Properties**
None

## <b>means.measurement.range.low</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.range -> means.measurement.range.low|

### **Properties**
None

## <b>means.measurement.rate</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.rate|

### **Properties**
None

## <b>means.measurement.rate.type</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.rate.type|

### **Properties**
None

## <b>means.measurement.size</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.size|

### **Properties**
None

## <b>means.measurement.size.depth</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.size -> means.measurement.size.depth|

### **Properties**
None

## <b>means.measurement.size.height</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.size -> means.measurement.size.height|

### **Properties**
None

## <b>means.measurement.size.volume</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.size -> means.measurement.size.volume|

### **Properties**
None

## <b>means.measurement.size.width</b>
### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.size -> means.measurement.size.width|

### **Properties**
None

## <b>means.measurement.currencyCode</b>
**Description**

Indicates this value represents an ISO 4217 currency code

### **Inheritance**
| |
|--|
|is -> means -> means.measurement -> means.measurement.currencyCode|

### **Properties**
None

## <b>means.measurement.units.si</b>
**Description**

Measurments in international system of units

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si|

### **Properties**
None

## <b>means.measurement.units.si.second</b>
**Description**

Measurement of time in seconds

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.second|

### **Properties**
None

## <b>means.measurement.units.si.meter</b>
**Description**

Measurement of length in meters

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.meter|

### **Properties**
None

## <b>means.measurement.units.si.kilogram</b>
**Description**

Measurement of mass in kilogram

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.kilogram|

### **Properties**
None

## <b>means.measurement.units.si.ampere</b>
**Description**

Measurement of electric current in amperes

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.ampere|

### **Properties**
None

## <b>means.measurement.units.si.kelvin</b>
**Description**

Measurement of thermodynamic temperature in degrees kelvin

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.kelvin|

### **Properties**
None

## <b>means.measurement.units.si.mole</b>
**Description**

Measurement of amount in moles

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.mole|

### **Properties**
None

## <b>means.measurement.units.si.candela</b>
**Description**

Measurement of luminous intensity in candelas

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.candela|

### **Properties**
None

## <b>means.measurement.units.si.hertz</b>
**Description**

Measurement of frequency in hertz

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.hertz|

### **Properties**
None

## <b>means.measurement.units.si.radian</b>
**Description**

Measurement of angle in radians

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.radian|

### **Properties**
None

## <b>means.measurement.units.si.newton</b>
**Description**

Measurement of force or weight in newtons

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.newton|

### **Properties**
None

## <b>means.measurement.units.si.pascal</b>
**Description**

Measurement of pressure or stress in pascals

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.pascal|

### **Properties**
None

## <b>means.measurement.units.si.joule</b>
**Description**

Measurement of energy, work or heat in joules

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.joule|

### **Properties**
None

## <b>means.measurement.units.si.watt</b>
**Description**

Measurement of power or radiant flux in watts

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.watt|

### **Properties**
None

## <b>means.measurement.units.si.coulomb</b>
**Description**

Measurement of electric charge or amount of electricity in coulombs

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.coulomb|

### **Properties**
None

## <b>means.measurement.units.si.volt</b>
**Description**

Measurement of voltage, EMF, electrical potantial difference in volts

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.volt|

### **Properties**
None

## <b>means.measurement.units.si.farad</b>
**Description**

Measurement of electric capacitance in farads

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.farad|

### **Properties**
None

## <b>means.measurement.units.si.ohm</b>
**Description**

Measurement of electrical resistance, impedance, reactance in ohms

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.ohm|

### **Properties**
None

## <b>means.measurement.units.si.celsius</b>
**Description**

Measurement of temperature in degrees celsius

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.celsius|

### **Properties**
None

## <b>means.measurement.units.si.gram</b>
**Description**

Measurement of mass in grams

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.gram|

### **Properties**
None

## <b>means.measurement.units.si.bitPerSecond</b>
**Description**

Measurement of data rate in bits per second

### **Inheritance**
| |
|--|
|is -> means -> means.measurement.units.si -> means.measurement.units.si.bitPerSecond|

### **Properties**
None

## <b>means.formatting</b>
### **Inheritance**
| |
|--|
|is -> means -> means.formatting|

### **Properties**
None

## <b>means.formatting.color</b>
### **Inheritance**
| |
|--|
|is -> means -> means.formatting -> means.formatting.color|

### **Properties**
None

## <b>means.formatting.font</b>
### **Inheritance**
| |
|--|
|is -> means -> means.formatting -> means.formatting.font|

### **Properties**
None

## <b>means.formatting.font.size</b>
### **Inheritance**
| |
|--|
|is -> means -> means.formatting -> means.formatting.font -> means.formatting.font.size|

### **Properties**
None

## <b>means.formatting.font.effects</b>
### **Inheritance**
| |
|--|
|is -> means -> means.formatting -> means.formatting.font -> means.formatting.font.effects|

### **Properties**
None

## <b>means.formatting.heading</b>
### **Inheritance**
| |
|--|
|is -> means -> means.formatting -> means.formatting.heading|

### **Properties**
None

## <b>means.formatting.order</b>
### **Inheritance**
| |
|--|
|is -> means -> means.formatting -> means.formatting.order|

### **Properties**
None

## <b>means.formatting.stringFormat</b>
**Description**

Indicates this value represents the format of a string

### **Inheritance**
| |
|--|
|is -> means -> means.formatting -> means.formatting.stringFormat|

### **Properties**
None

## <b>means.qualification</b>
**Description**

Augments the meaning of entities or attributes with a qualification

### **Inheritance**
| |
|--|
|is -> means -> means.qualification|

### **Properties**
None

## <b>means.qualification.estimate</b>
**Description**

Values are an estimate only.

### **Inheritance**
| |
|--|
|is -> means -> means.qualification -> means.qualification.estimate|

### **Properties**
None

## <b>means.demographic</b>
### **Inheritance**
| |
|--|
|is -> means -> means.demographic|

### **Properties**
None

## <b>means.demographic.age</b>
### **Inheritance**
| |
|--|
|is -> means -> means.demographic -> means.demographic.age|

### **Properties**
None

## <b>means.demographic.gender</b>
### **Inheritance**
| |
|--|
|is -> means -> means.demographic -> means.demographic.gender|

### **Properties**
None

## <b>means.demographic.ethnicity</b>
### **Inheritance**
| |
|--|
|is -> means -> means.demographic -> means.demographic.ethnicity|

### **Properties**
None

## <b>means.demographic.maritalStatus</b>
### **Inheritance**
| |
|--|
|is -> means -> means.demographic -> means.demographic.maritalStatus|

### **Properties**
None

## <b>means.demographic.birthDate</b>
### **Inheritance**
| |
|--|
|is -> means -> means.demographic -> means.demographic.birthDate|

### **Properties**
None

## <b>means.demographic.income</b>
### **Inheritance**
| |
|--|
|is -> means -> means.demographic -> means.demographic.income|

### **Properties**
None

## <b>means.demographic.education</b>
### **Inheritance**
| |
|--|
|is -> means -> means.demographic -> means.demographic.education|

### **Properties**
None

## <b>means.location</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location|

### **Properties**
None

## <b>means.location.address</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.address|

### **Properties**
None

## <b>means.location.address.building</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.address -> means.location.address.building|

### **Properties**
None

## <b>means.location.address.floor</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.address -> means.location.address.floor|

### **Properties**
None

## <b>means.location.address.house</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.address -> means.location.address.house|

### **Properties**
None

## <b>means.location.address.room</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.address -> means.location.address.room|

### **Properties**
None

## <b>means.location.address.street</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.address -> means.location.address.street|

### **Properties**
None

## <b>means.location.address.street.line1</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.address -> means.location.address.street -> means.location.address.street.line1|

### **Properties**
None

## <b>means.location.address.street.line2</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.address -> means.location.address.street -> means.location.address.street.line2|

### **Properties**
None

## <b>means.location.address.street.line3</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.address -> means.location.address.street -> means.location.address.street.line3|

### **Properties**
None

## <b>means.location.county</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.address -> means.location.county|

### **Properties**
None

## <b>means.location.city</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.city|

### **Properties**
None

## <b>means.location.continent</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.continent|

### **Properties**
None

## <b>means.location.country</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.country|

### **Properties**
None

## <b>means.location.latitude</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.latitude|

### **Properties**
None

## <b>means.location.longitude</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.longitude|

### **Properties**
None

## <b>means.location.point</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.point|

### **Properties**
None

## <b>means.location.postalCode</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.postalCode|

### **Properties**
None

## <b>means.location.province</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.province|

### **Properties**
None

## <b>means.location.region</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.region|

### **Properties**
None

## <b>means.location.stateOrProvince</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.stateOrProvince|

### **Properties**
None

## <b>means.location.timezone</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.timezone|

### **Properties**
None

## <b>means.location.geo</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo|

### **Properties**
None

## <b>means.location.geo.boundary</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.boundary|

### **Properties**
None

## <b>means.location.geo.boundary.bottom</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.boundary -> means.location.geo.boundary.bottom|

### **Properties**
None

## <b>means.location.geo.boundary.front</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.boundary -> means.location.geo.boundary.front|

### **Properties**
None

## <b>means.location.geo.boundary.left</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.boundary -> means.location.geo.boundary.left|

### **Properties**
None

## <b>means.location.geo.boundary.polygon</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.boundary -> means.location.geo.boundary.polygon|

### **Properties**
None

## <b>means.location.geo.boundary.rear</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.boundary -> means.location.geo.boundary.rear|

### **Properties**
None

## <b>means.location.geo.boundary.right</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.boundary -> means.location.geo.boundary.right|

### **Properties**
None

## <b>means.location.geo.boundary.top</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.boundary -> means.location.geo.boundary.top|

### **Properties**
None

## <b>means.location.geo.centroid</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.centroid|

### **Properties**
None

## <b>means.location.geo.centroid.X</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.centroid -> means.location.geo.centroid.X|

### **Properties**
None

## <b>means.location.geo.centroid.y</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.centroid -> means.location.geo.centroid.y|

### **Properties**
None

## <b>means.location.geo.centroid.z</b>
### **Inheritance**
| |
|--|
|is -> means -> means.location -> means.location.geo -> means.location.geo.centroid -> means.location.geo.centroid.z|

### **Properties**
None

## <b>has</b>
**Description**

A root for traits that describe properties of an object

### **Inheritance**
| |
|--|
|is -> has|

### **Properties**
None

## <b>has.entitySchemaAbstractionLevel</b>
**Description**

A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or re-states parts of logical schemas to produce one resolved schema.

### **Inheritance**
| |
|--|
|is -> has -> has.entitySchemaAbstractionLevel|

### **Properties**
None

## <b>has.category</b>
**Description**

The root trait for the system of traits of hierarchical categorization

### **Inheritance**
| |
|--|
|is -> has -> has.category|

### **Properties**
None

## <b>has.category.level1</b>
**Description**

Common explanation for level1 category items

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level1|

### **Properties**
None

## <b>has.category.sourceSystem</b>
**Description**

A level1 hierarchy item explaining the source system for entities. Entities from a given source system are expected to be self-consistent on identifiers and similar data domains.

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level1 -> has.category.sourceSystem|

### **Properties**
None

## <b>has.category.sourceSystem.Dynamics365</b>
**Description**

Entities from the Dynamics365 source system

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level1 -> has.category.sourceSystem -> has.category.sourceSystem.Dynamics365|

### **Properties**
None

## <b>has.category.level2</b>
**Description**

Common explanation for level2 category items

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level2|

### **Properties**
None

## <b>has.category.subjectArea</b>
**Description**

A level2 hierarchy item explaining the subject area entities. Subject areas can represent broad business categories such as Finance, Sales and Human Resouces

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level2 -> has.category.subjectArea|

### **Properties**
None

## <b>has.category.subjectArea.HumanResources</b>
**Description**

Entities from Human Resources subject area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level2 -> has.category.subjectArea -> has.category.subjectArea.HumanResources|

### **Properties**
None

## <b>has.category.subjectArea.Commerce</b>
**Description**

Entities from Commerce subject area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level2 -> has.category.subjectArea -> has.category.subjectArea.Commerce|

### **Properties**
None

## <b>has.category.subjectArea.SupplyChain</b>
**Description**

Entities from Supply Chain subject area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level2 -> has.category.subjectArea -> has.category.subjectArea.SupplyChain|

### **Properties**
None

## <b>has.category.subjectArea.Finance</b>
**Description**

Entities from Finance subject area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level2 -> has.category.subjectArea -> has.category.subjectArea.Finance|

### **Properties**
None

## <b>has.category.level3</b>
**Description**

Common explanation for level3 category items

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level3|

### **Properties**
None

## <b>has.category.functionalArea</b>
**Description**

A level3 hierarchy item explaining the functional area for entities. Functional areas can divide entities by their purpose or use case such as auditing, reporting, recruiting, budgeting

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level3 -> has.category.functionalArea|

### **Properties**
None

## <b>has.category.functionalArea.Recruitment</b>
**Description**

Entities from Recruitment functional area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level3 -> has.category.functionalArea -> has.category.functionalArea.Recruitment|

### **Properties**
None

## <b>has.category.functionalArea.Terminations</b>
**Description**

Entities from Terminations functional area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level3 -> has.category.functionalArea -> has.category.functionalArea.Terminations|

### **Properties**
None

## <b>has.category.functionalArea.Suppliers</b>
**Description**

Entities from Suppliers functional area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level3 -> has.category.functionalArea -> has.category.functionalArea.Suppliers|

### **Properties**
None

## <b>has.category.functionalArea.Warehousing</b>
**Description**

Entities from Warehousing functional area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level3 -> has.category.functionalArea -> has.category.functionalArea.Warehousing|

### **Properties**
None

## <b>has.category.functionalArea.GeneralLedger</b>
**Description**

Entities from GeneralLedger functional area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level3 -> has.category.functionalArea -> has.category.functionalArea.GeneralLedger|

### **Properties**
None

## <b>has.category.functionalArea.AccountsReceivable</b>
**Description**

Entities from AccountsReceivable functional area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level3 -> has.category.functionalArea -> has.category.functionalArea.AccountsReceivable|

### **Properties**
None

## <b>has.category.functionalArea.Auditing</b>
**Description**

Entities from Auditing functional area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level3 -> has.category.functionalArea -> has.category.functionalArea.Auditing|

### **Properties**
None

## <b>has.category.functionalArea.Budgeting</b>
**Description**

Entities from Budgeting functional area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level3 -> has.category.functionalArea -> has.category.functionalArea.Budgeting|

### **Properties**
None

## <b>has.category.functionalArea.Reporting</b>
**Description**

Entities from Reporting functional area

### **Inheritance**
| |
|--|
|is -> has -> has.category -> has.category.level3 -> has.category.functionalArea -> has.category.functionalArea.Reporting|

### **Properties**
None

## <b>is.dataFormat</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.integer</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.integer|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.big</b>
**Description**

Indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.

### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.big|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.small</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.small|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.floatingPoint</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.floatingPoint|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.array</b>
**Description**

Indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object

### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.array|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.character</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.character|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.byte</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.byte|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.numeric</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.numeric|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.numeric.shaped</b>
**Description**

For setting the exact precision and scale of numeric values

### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.numeric -> is.dataFormat.numeric.shaped|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.date</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.date|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.time</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.time|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.boolean</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.boolean|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.guid</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.guid|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.timeOffset</b>
### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.timeOffset|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.dataFormat.JSInteger</b>
**Description**

Represents the 54 bit integer numbers compatible with javascript

### **Inheritance**
| |
|--|
|is -> is.dataFormat -> is.dataFormat.JSInteger|

### **Properties**
| |
|--|
|<b>dataFormat</b>|

## <b>is.secret</b>
### **Inheritance**
| |
|--|
|is -> is.secret|

### **Properties**
None

## <b>is.required</b>
### **Inheritance**
| |
|--|
|is -> is.required|

### **Properties**
None

## <b>is.sensitive</b>
### **Inheritance**
| |
|--|
|is -> is.sensitive|

### **Properties**
None

## <b>is.addedInSupportOf</b>
### **Inheritance**
| |
|--|
|is -> is.addedInSupportOf|

### **Properties**
None

## <b>is.inCurrency</b>
**Description**

The data represents an amount of the specified currency

### **Inheritance**
| |
|--|
|is -> is.inCurrency|

### **Properties**
None

## <b>is.formatted</b>
**Description**

A root for traits that describe how data is formatted

### **Inheritance**
| |
|--|
|is -> is.formatted|

### **Properties**
None

## <b>is.formatted.forCulture</b>
**Description**

Values are stored using the specified culture

### **Inheritance**
| |
|--|
|is -> is.formatted -> is.formatted.forCulture|

### **Properties**
None

## <b>is.formatted.text</b>
**Description**

String data is formatted according to the format parameter

### **Inheritance**
| |
|--|
|is -> is.formatted -> is.formatted.text|

### **Properties**
None

## <b>is.formatted.dateTime</b>
**Description**

DateTime data formatted as a string in ISO 8601 format

### **Inheritance**
| |
|--|
|is -> is.formatted -> is.formatted.dateTime|

### **Properties**
None

## <b>is.formatted.date</b>
**Description**

Date data formatted as a string in ISO 8601 format

### **Inheritance**
| |
|--|
|is -> is.formatted -> is.formatted.date|

### **Properties**
None

## <b>is.formatted.time</b>
**Description**

Time data formatted as a string in ISO 8601 format

### **Inheritance**
| |
|--|
|is -> is.formatted -> is.formatted.time|

### **Properties**
None

## <b>is.inTimeZone</b>
**Description**

The associated data is assumed to be in the specified time zone

### **Inheritance**
| |
|--|
|is -> is.inTimeZone|

### **Properties**
None

## <b>is.inTimeZone.MicrosoftFormat</b>
**Description**

The associated data is assumed to be in the specified time zone. timeZoneName value is a Microsoft standard time zone name. see https://support.microsoft.com/en-us/help/973627

### **Inheritance**
| |
|--|
|is -> is.inTimeZone -> is.inTimeZone.MicrosoftFormat|

### **Properties**
None

## <b>is.inTimeZone.tzDatabaseFormat</b>
**Description**

The associated data is assumed to be in the specified time zone. timeZoneName value is a Time Zone Database standard time zone name. see https://www.iana.org/time-zones

### **Inheritance**
| |
|--|
|is -> is.inTimeZone -> is.inTimeZone.tzDatabaseFormat|

### **Properties**
None

## <b>is.hidden</b>
**Description**

All attributes with this trait should be hidden from view of the entity consumer.

### **Inheritance**
None

### **Properties**
None

## <b>is.linkedEntity</b>
**Description**

Base for traits that are used to decorate the attributes and artifacts created by the traits on the hasFlexibleRelationshipWithEntity relationship.

### **Inheritance**
None

### **Properties**
None

## <b>is.linkedEntity.identifier</b>
**Description**

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.

### **Inheritance**
| |
|--|
|is.linkedEntity -> is.linkedEntity.identifier|

### **Properties**
None

## <b>is.linkedEntity.name</b>
**Description**

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.

### **Inheritance**
| |
|--|
|is.linkedEntity -> is.linkedEntity.name|

### **Properties**
None

## <b>is.linkedEntity.array</b>
**Description**

Identifies the case when one entity links to (uses as an attribute) an array of other entities.

### **Inheritance**
None

### **Properties**
None

## <b>is.linkedEntity.array.count</b>
**Description**

Marks an attribute that contains the count of items in the array of linked (used as an attribute) entities

### **Inheritance**
None

### **Properties**
None

## <b>means.userId</b>
**Description**

Contains a userId

### **Inheritance**
None

### **Properties**
None

## <b>privacy</b>
**Description**

A privacy related trait.

### **Inheritance**
None

### **Properties**
None

## <b>privacy.dataSubjectAction</b>
**Description**

The set of actions a data subject must be able to take on a set of data.

### **Inheritance**
| |
|--|
|privacy -> privacy.dataSubjectAction|

### **Properties**
None

## <b>privacy.dataSubjectAction.view</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataSubjectAction -> privacy.dataSubjectAction.view|

### **Properties**
None

## <b>privacy.dataSubjectAction.delete</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataSubjectAction -> privacy.dataSubjectAction.delete|

### **Properties**
None

## <b>privacy.dataSubjectAction.edit</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataSubjectAction -> privacy.dataSubjectAction.edit|

### **Properties**
None

## <b>privacy.dataSubjectAction.export</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataSubjectAction -> privacy.dataSubjectAction.export|

### **Properties**
None

## <b>privacy.dataIdentifiablity</b>
**Description**

The root trait for the set explaining how data value may identity an individual.

### **Inheritance**
| |
|--|
|privacy -> privacy.dataIdentifiablity|

### **Properties**
None

## <b>privacy.dataIdentifiablity.identified</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataIdentifiablity -> privacy.dataIdentifiablity.identified|

### **Properties**
None

## <b>privacy.dataIdentifiablity.pseudonimized</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataIdentifiablity -> privacy.dataIdentifiablity.pseudonimized|

### **Properties**
None

## <b>privacy.dataIdentifiablity.pseudonimizedNotLinked</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataIdentifiablity -> privacy.dataIdentifiablity.pseudonimizedNotLinked|

### **Properties**
None

## <b>privacy.dataIdentifiablity.anonymized</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataIdentifiablity -> privacy.dataIdentifiablity.anonymized|

### **Properties**
None

## <b>privacy.dataIdentifiablity.aggregated</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataIdentifiablity -> privacy.dataIdentifiablity.aggregated|

### **Properties**
None

## <b>privacy.dataCategory</b>
**Description**

The root trait for expressing 'Controller' data categories

### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned</b>
**Description**

The root trait for expressing 'Processor' data categories

### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.content</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.content|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.content.provided</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.content -> privacy.dataCategory.customerOwned.content.provided|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.content.credentials</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.content -> privacy.dataCategory.customerOwned.content.credentials|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.content.contactList</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.content -> privacy.dataCategory.customerOwned.content.contactList|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.endUserIdentifying</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.endUserIdentifying|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.support</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.support|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.support.content</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.support -> privacy.dataCategory.customerOwned.support.content|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.support.interaction</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.support -> privacy.dataCategory.customerOwned.support.interaction|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.account</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.account|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.account.customerContact</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.account -> privacy.dataCategory.customerOwned.account.customerContact|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.account.licensingAndPurchase</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.account -> privacy.dataCategory.customerOwned.account.licensingAndPurchase|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.account.paymentInstrument</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.account -> privacy.dataCategory.customerOwned.account.paymentInstrument|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.publicPersonalData</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.publicPersonalData|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.financeAccountingAndRecords</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.financeAccountingAndRecords|

### **Properties**
None

## <b>privacy.dataCategory.customerOwned.corporateCommunication</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.customerOwned -> privacy.dataCategory.customerOwned.corporateCommunication|

### **Properties**
None

## <b>privacy.dataCategory.endUser</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser|

### **Properties**
None

## <b>privacy.dataCategory.endUser.content</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.content|

### **Properties**
None

## <b>privacy.dataCategory.endUser.content.provided</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.content -> privacy.dataCategory.endUser.content.provided|

### **Properties**
None

## <b>privacy.dataCategory.endUser.content.credentials</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.content -> privacy.dataCategory.endUser.content.credentials|

### **Properties**
None

## <b>privacy.dataCategory.endUser.content.contactList</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.content -> privacy.dataCategory.endUser.content.contactList|

### **Properties**
None

## <b>privacy.dataCategory.endUser.attributes</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.attributes|

### **Properties**
None

## <b>privacy.dataCategory.endUser.attributes.demographic</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.attributes -> privacy.dataCategory.endUser.attributes.demographic|

### **Properties**
None

## <b>privacy.dataCategory.endUser.attributes.feedbackAndRatings</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.attributes -> privacy.dataCategory.endUser.attributes.feedbackAndRatings|

### **Properties**
None

## <b>privacy.dataCategory.endUser.attributes.interestsAndFavorites</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.attributes -> privacy.dataCategory.endUser.attributes.interestsAndFavorites|

### **Properties**
None

## <b>privacy.dataCategory.endUser.attributes.socialActivity</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.attributes -> privacy.dataCategory.endUser.attributes.socialActivity|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.browsingHistory</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.browsingHistory|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.cloudService</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.cloudService|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.contentConsumption</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.contentConsumption|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.searchRequests</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.searchRequests|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.deviceConnectivityAndConfiguration</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.deviceConnectivityAndConfiguration|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.environmentalSensor</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.environmentalSensor|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.fitnessAndActivity</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.fitnessAndActivity|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.inkingTypingAndSpeach</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.inkingTypingAndSpeach|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.preciceLocation</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.preciceLocation|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.productAndServicePerformance</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.productAndServicePerformance|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.productAndServiceUsage</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.productAndServiceUsage|

### **Properties**
None

## <b>privacy.dataCategory.endUser.interactions.softwareSetAndInventory</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.interactions -> privacy.dataCategory.endUser.interactions.softwareSetAndInventory|

### **Properties**
None

## <b>privacy.dataCategory.endUser.support</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.support|

### **Properties**
None

## <b>privacy.dataCategory.endUser.support.content</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.support -> privacy.dataCategory.endUser.support.content|

### **Properties**
None

## <b>privacy.dataCategory.endUser.support.interaction</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.support -> privacy.dataCategory.endUser.support.interaction|

### **Properties**
None

## <b>privacy.dataCategory.endUser.account</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.account|

### **Properties**
None

## <b>privacy.dataCategory.endUser.account.customerContact</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.account -> privacy.dataCategory.endUser.account.customerContact|

### **Properties**
None

## <b>privacy.dataCategory.endUser.account.licensingAndPurchase</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.account -> privacy.dataCategory.endUser.account.licensingAndPurchase|

### **Properties**
None

## <b>privacy.dataCategory.endUser.account.paymentInstrument</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.endUser -> privacy.dataCategory.endUser.account -> privacy.dataCategory.endUser.account.paymentInstrument|

### **Properties**
None

## <b>privacy.dataCategory.employment</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.employment|

### **Properties**
None

## <b>privacy.dataCategory.employment.commuteAndTravel</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.employment -> privacy.dataCategory.employment.commuteAndTravel|

### **Properties**
None

## <b>privacy.dataCategory.employment.compensationAndBenefits</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.employment -> privacy.dataCategory.employment.compensationAndBenefits|

### **Properties**
None

## <b>privacy.dataCategory.employment.learningAndDevelopment</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.employment -> privacy.dataCategory.employment.learningAndDevelopment|

### **Properties**
None

## <b>privacy.dataCategory.employment.profesionalAndPersonalProfile</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.employment -> privacy.dataCategory.employment.profesionalAndPersonalProfile|

### **Properties**
None

## <b>privacy.dataCategory.employment.recruitment</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.employment -> privacy.dataCategory.employment.recruitment|

### **Properties**
None

## <b>privacy.dataCategory.employment.workContacts</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.employment -> privacy.dataCategory.employment.workContacts|

### **Properties**
None

## <b>privacy.dataCategory.employment.workProfile</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.employment -> privacy.dataCategory.employment.workProfile|

### **Properties**
None

## <b>privacy.dataCategory.employment.workRecognition</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.employment -> privacy.dataCategory.employment.workRecognition|

### **Properties**
None

## <b>privacy.dataCategory.employment.workTime</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.employment -> privacy.dataCategory.employment.workTime|

### **Properties**
None

## <b>privacy.dataCategory.employment.workplaceInteractions</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.employment -> privacy.dataCategory.employment.workplaceInteractions|

### **Properties**
None

## <b>privacy.dataCategory.bizOps</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.bizOps|

### **Properties**
None

## <b>privacy.dataCategory.bizOps.financeAccountingAndRecords</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.bizOps -> privacy.dataCategory.bizOps.financeAccountingAndRecords|

### **Properties**
None

## <b>privacy.dataCategory.bizOps.corporateCommunication</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataCategory -> privacy.dataCategory.bizOps -> privacy.dataCategory.bizOps.corporateCommunication|

### **Properties**
None

## <b>privacy.dataUsage</b>
**Description**

The purpose for a sepcific usage of a set of data

### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage|

### **Properties**
None

## <b>privacy.dataUsage.provide</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage -> privacy.dataUsage.provide|

### **Properties**
None

## <b>privacy.dataUsage.personalize</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage -> privacy.dataUsage.personalize|

### **Properties**
None

## <b>privacy.dataUsage.recommend</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage -> privacy.dataUsage.recommend|

### **Properties**
None

## <b>privacy.dataUsage.improve</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage -> privacy.dataUsage.improve|

### **Properties**
None

## <b>privacy.dataUsage.research</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage -> privacy.dataUsage.research|

### **Properties**
None

## <b>privacy.dataUsage.advertising</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage -> privacy.dataUsage.advertising|

### **Properties**
None

## <b>privacy.dataUsage.advertising.directMarketing</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage -> privacy.dataUsage.advertising -> privacy.dataUsage.advertising.directMarketing|

### **Properties**
None

## <b>privacy.dataUsage.advertising.adPlatform</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage -> privacy.dataUsage.advertising -> privacy.dataUsage.advertising.adPlatform|

### **Properties**
None

## <b>privacy.dataUsage.share</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage -> privacy.dataUsage.share|

### **Properties**
None

## <b>privacy.dataUsage.share.processor</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage -> privacy.dataUsage.share -> privacy.dataUsage.share.processor|

### **Properties**
None

## <b>privacy.dataUsage.share.controller</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.dataUsage -> privacy.dataUsage.share -> privacy.dataUsage.share.controller|

### **Properties**
None

## <b>privacy.consentRequirements</b>
**Description**

The consent requirements or consent settings for data

### **Inheritance**
| |
|--|
|privacy -> privacy.consentRequirements|

### **Properties**
None

## <b>privacy.consentRequirements.notice</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.consentRequirements -> privacy.consentRequirements.notice|

### **Properties**
None

## <b>privacy.consentRequirements.notice.discoverable</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.consentRequirements -> privacy.consentRequirements.notice -> privacy.consentRequirements.notice.discoverable|

### **Properties**
None

## <b>privacy.consentRequirements.notice.prominent</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.consentRequirements -> privacy.consentRequirements.notice -> privacy.consentRequirements.notice.prominent|

### **Properties**
None

## <b>privacy.consentRequirements.legitimateInterest</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.consentRequirements -> privacy.consentRequirements.legitimateInterest|

### **Properties**
None

## <b>privacy.consentRequirements.optIn</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.consentRequirements -> privacy.consentRequirements.optIn|

### **Properties**
None

## <b>privacy.consentRequirements.optOut</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.consentRequirements -> privacy.consentRequirements.optOut|

### **Properties**
None

## <b>privacy.consentRequirements.customerControls</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.consentRequirements -> privacy.consentRequirements.customerControls|

### **Properties**
None

## <b>privacy.consentRequirements.customerControls.notRequired</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.consentRequirements -> privacy.consentRequirements.customerControls -> privacy.consentRequirements.customerControls.notRequired|

### **Properties**
None

## <b>privacy.consentRequirements.customerControls.required</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.consentRequirements -> privacy.consentRequirements.customerControls -> privacy.consentRequirements.customerControls.required|

### **Properties**
None

## <b>privacy.consentRequirements.notPermitted</b>
### **Inheritance**
| |
|--|
|privacy -> privacy.consentRequirements -> privacy.consentRequirements.notPermitted|

### **Properties**
None

## <b>privacy.expresses</b>
**Description**

The root meta trait that indicates how to interpret a group of co-ascribed privacy traits.

### **Inheritance**
| |
|--|
|privacy -> privacy.expresses|

### **Properties**
None

## <b>privacy.expresses.data</b>
**Description**

The assumed default behavior, if privacy.expresses.metaData is not set, then this trait is implicit. When a group of traits are ascribed to an entity or attribute, The other privacy traits describe the aspects of data values held by the entity or attribute.

### **Inheritance**
| |
|--|
|privacy -> privacy.expresses -> privacy.expresses.data|

### **Properties**
None

## <b>privacy.expresses.metaData</b>
**Description**

When this trait and a group of other privacy traits are ascribed to an entity or attribute, The other privacy traits describe the aspects of the metatdata for the data values held by the entity or attribute. That is, the entity itself may contain privacy or policy descriptions, rules, settings.

### **Inheritance**
| |
|--|
|privacy -> privacy.expresses -> privacy.expresses.metaData|

### **Properties**
None

## <b>privacy.expresses.useAllowed</b>
**Description**

Use is allowed for the condition using the combined meanings of all other privacy traits in a set.

### **Inheritance**
| |
|--|
|privacy -> privacy.expresses -> privacy.expresses.useAllowed|

### **Properties**
None

## <b>privacy.expresses.useRestricted</b>
**Description**

Use is dis-allowed for the condition formed using the combined meanings of all other privacy traits in a set.

### **Inheritance**
| |
|--|
|privacy -> privacy.expresses -> privacy.expresses.useRestricted|

### **Properties**
None


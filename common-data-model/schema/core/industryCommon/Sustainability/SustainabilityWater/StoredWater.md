---
title: StoredWater in Cloud for Sustainability water data model - Common Data Model | Microsoft Docs
description: The entity stores data related to the water stored within a facility.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: anbichse
ms.topic: article
ms.date: 10/24/2023
ms.author: anbichse
---

# Stored water in Cloud for Sustainability water data model (StoredWater)

The entity stores data related to the water stored within a facility.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/Sustainability\CloudforSustainabilityWaterDataModel/StoredWater.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[StoredWater/(resolvedAttributes)/storedwaterId](#storedwaterId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/Sustainability<br>/CloudforSustainabilityWaterDataModel<br>/StoredWater.cdm.json/StoredWater/hasAttributes<br>/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The entity stores data related to the water stored within a facility.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Stored water</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_storedwater"</td><td>string</td><td></td></tr></table>

**has.entitySchemaAbstractionLevel**  
  A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or re-states parts of logical schemas to produce one resolved schema.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"resolved"</td><td>string</td><td>Possible values: logical, composition, resolved</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[storedwaterId](#storedwaterId)|Unique identifier for entity instances|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[TTLInSeconds](#TTLInSeconds)|Time to live in seconds.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[partitionId](#partitionId)|Logical partition id. A logical partition consists of a set of records with same partition id.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[name](#name)|The name of the custom entity.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[actualstorage](#actualstorage)|Field to store the actual stored water quantity measurement value.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[description](#description)|Optional field to describe the entity.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[facility](#facility)|Field to store the facility information associated with the stored water quantity measurement.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[measurementdate](#measurementdate)|Field to store the date and time at which the stored water quantity was measured.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[organizationalunit](#organizationalunit)|Optional field to store the organizational unit associated with the stored water quantity measurement.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[origincorrelationid](#origincorrelationid)|Optional field to store alternate key for the entity.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[storagecontainerid](#storagecontainerid)|Optional field to store unique identifier for a storage container.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[storagecontainertype](#storagecontainertype)|Optional field to classify a storage container as belonging to a type.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[totalstorage](#totalstorage)|Optional field to store the maximum possible storage quantity within the storage container.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|
|[unit](#unit)|Field to store the unit of measurement for the water quantity values.|<a href="StoredWater.md" target="_blank">Sustainability\CloudforSustainabilityWaterDataModel/StoredWater</a>|

### <a href=#storedwaterId name="storedwaterId">storedwaterId</a>

Unique identifier for entity instances  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stored water</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>sourceName</td><td>msdyn_storedwaterid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the storedwaterId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **means.identity.entityId**  
  **is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[StoredWater/(resolvedAttributes)/storedwaterId](#storedwaterId)</td><td>attribute</td><td></td></tr></table>

**is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for entity instances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Stored water</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_storedwaterid"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"1"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#TTLInSeconds name="TTLInSeconds">TTLInSeconds</a>

Time to live in seconds.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time to live</td></tr><tr><td>description</td><td>Time to live in seconds.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ttlinseconds</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TTLInSeconds attribute are listed below.</summary>

**is.dataFormat.integer**  
  **is.dataFormat.signed**  
  indicates the capability to represent values less than zero.  

**is.dataFormat.numeric**  
  **is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time to live in seconds.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time to live</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.constrained**  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"ttlinseconds"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"2"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.integer**  
  </details>

### <a href=#partitionId name="partitionId">partitionId</a>

Logical partition id. A logical partition consists of a set of records with same partition id.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Partition Id</td></tr><tr><td>description</td><td>Logical partition id. A logical partition consists of a set of records with same partition id.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>partitionid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the partitionId attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Logical partition id. A logical partition consists of a set of records with same partition id.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Partition Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.constrained**  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"partitionid"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"3"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

**is.dataFormat.date**  
  **means.measurement.date**  
  **is.dataFormat.time**  
  **means.measurement.time**  
  **is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdon"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"4"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.time**  
  **is.dataFormat.date**  
  </details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

**is.dataFormat.date**  
  **means.measurement.date**  
  **is.dataFormat.time**  
  **means.measurement.time**  
  **is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedon"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"6"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.time**  
  **is.dataFormat.date**  
  </details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
  **is.dataFormat.signed**  
  indicates the capability to represent values less than zero.  

**is.dataFormat.numeric**  
  **is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence number of the import that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.constrained**  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"importsequencenumber"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"28"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.integer**  
  </details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

**is.dataFormat.date**  
  **means.measurement.date**  
  **is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"overriddencreatedon"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"29"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.date**  
  </details>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the custom entity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.constrained**  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_name"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"30"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#actualstorage name="actualstorage">actualstorage</a>

Field to store the actual stored water quantity measurement value.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual storage</td></tr><tr><td>description</td><td>Field to store the actual stored water quantity measurement value.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualstorage</td></tr></table>

#### Traits

<details>
<summary>List of traits for the actualstorage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
  for setting the exact precision and scale of numeric values  

**is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Field to store the actual stored water quantity measurement value.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual storage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.constrained**  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_actualstorage"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"31"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.numeric.shaped**  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#description name="description">description</a>

Optional field to describe the entity.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Optional field to describe the entity.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

#### Traits

<details>
<summary>List of traits for the description attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Optional field to describe the entity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.constrained**  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_description"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"32"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#facility name="facility">facility</a>

Field to store the facility information associated with the stored water quantity measurement.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Facility</td></tr><tr><td>description</td><td>Field to store the facility information associated with the stored water quantity measurement.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the facility attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **means.identity.entityId**  
  **is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Field to store the facility information associated with the stored water quantity measurement.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Facility</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.lookup**  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.linkedEntity.identifier**  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="Facility.md" target="_blank">Facility.cdm.json/Facility</a></td><td><a href="Facility.md#facilityId" target="_blank">facilityId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#measurementdate name="measurementdate">measurementdate</a>

Field to store the date and time at which the stored water quantity was measured.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Measurement date</td></tr><tr><td>description</td><td>Field to store the date and time at which the stored water quantity was measured.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_measurementdate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the measurementdate attribute are listed below.</summary>

**is.dataFormat.date**  
  **means.measurement.date**  
  **is.dataFormat.time**  
  **means.measurement.time**  
  **is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Field to store the date and time at which the stored water quantity was measured.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Measurement date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_measurementdate"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"34"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.time**  
  **is.dataFormat.date**  
  </details>

### <a href=#organizationalunit name="organizationalunit">organizationalunit</a>

Optional field to store the organizational unit associated with the stored water quantity measurement.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organizational unit</td></tr><tr><td>description</td><td>Optional field to store the organizational unit associated with the stored water quantity measurement.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the organizationalunit attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **means.identity.entityId**  
  **is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Optional field to store the organizational unit associated with the stored water quantity measurement.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organizational unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.lookup**  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.linkedEntity.identifier**  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="../OrganizationalUnit.md" target="_blank">../OrganizationalUnit.cdm.json/OrganizationalUnit</a></td><td><a href="../OrganizationalUnit.md#sustainabilityorganizationalunitId" target="_blank">sustainabilityorganizationalunitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#origincorrelationid name="origincorrelationid">origincorrelationid</a>

Optional field to store alternate key for the entity.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Origin correlation ID</td></tr><tr><td>description</td><td>Optional field to store alternate key for the entity.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_origincorrelationid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the origincorrelationid attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Optional field to store alternate key for the entity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Origin correlation ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.constrained**  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_origincorrelationid"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"36"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#storagecontainerid name="storagecontainerid">storagecontainerid</a>

Optional field to store unique identifier for a storage container.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Storage container ID</td></tr><tr><td>description</td><td>Optional field to store unique identifier for a storage container.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_storagecontainerid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the storagecontainerid attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Optional field to store unique identifier for a storage container.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Storage container ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.constrained**  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_storagecontainerid"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"37"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#storagecontainertype name="storagecontainertype">storagecontainertype</a>

Optional field to classify a storage container as belonging to a type.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Storage container type</td></tr><tr><td>description</td><td>Optional field to classify a storage container as belonging to a type.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_storagecontainertype</td></tr></table>

#### Traits

<details>
<summary>List of traits for the storagecontainertype attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Optional field to classify a storage container as belonging to a type.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Storage container type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.constrained**  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_storagecontainertype"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"38"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#totalstorage name="totalstorage">totalstorage</a>

Optional field to store the maximum possible storage quantity within the storage container.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total storage</td></tr><tr><td>description</td><td>Optional field to store the maximum possible storage quantity within the storage container.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalstorage</td></tr></table>

#### Traits

<details>
<summary>List of traits for the totalstorage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
  for setting the exact precision and scale of numeric values  

**is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Optional field to store the maximum possible storage quantity within the storage container.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total storage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.constrained**  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.nullable**  
  The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_totalstorage"</td><td>string</td><td></td></tr></table>

**is.CDS.ordered**  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"39"</td><td>integer</td><td></td></tr></table>

**is.dataFormat.numeric.shaped**  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#unit name="unit">unit</a>

Field to store the unit of measurement for the water quantity values.  
First included in: Sustainability\\CloudforSustainabilityWaterDataModel/StoredWater (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Field to store the unit of measurement for the water quantity values.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the unit attribute are listed below.</summary>

**is.dataFormat.character**  
  **is.dataFormat.big**  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
  **means.identity.entityId**  
  **is.requiredAtLevel**  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Field to store the unit of measurement for the water quantity values.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.lookup**  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.linkedEntity.identifier**  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="../Unit.md" target="_blank">../Unit.cdm.json/Unit</a></td><td><a href="../Unit.md#unitId" target="_blank">unitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
  **is.dataFormat.character**  
  **is.dataFormat.array**  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

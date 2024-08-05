---
title: WasteQualityTestResult in Cloud for Sustainability waste data model - Common Data Model | Microsoft Docs
description: Stores information on the result of the tests for tracking chemical/contaminant levels.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/2/2024
ms.author: cdmditeam
---

# Waste quality test result in Cloud for Sustainability waste data model(WasteQualityTestResult)

Stores information on the result of the tests for tracking chemical/contaminant levels.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.identifiedBy**  
  names a specific identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WasteQualityTestResult/(resolvedAttributes)/wastequalitytestresultId](#wastequalitytestresultId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/Sustainability<br>/CloudforSustainabilityWasteDataModel<br>/WasteQualityTestResult.cdm.json<br>/WasteQualityTestResult/hasAttributes<br>/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Stores information on the result of the tests for tracking chemical/contaminant levels.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Waste quality test result</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_wastequalitytestresult"</td><td>string</td><td></td></tr></table>

**has.entitySchemaAbstractionLevel**  
  A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or re-states parts of logical schemas to produce one resolved schema.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"resolved"</td><td>string</td><td>Possible values: logical, composition, resolved</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[wastequalitytestresultId](#wastequalitytestresultId)|Unique identifier for entity instances.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[TTLInSeconds](#TTLInSeconds)|Time to live in seconds.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[partitionId](#partitionId)|Logical partition identifier. A logical partition consists of a set of records with same partition ID.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[name](#name)|The name of the custom entity.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[comments](#comments)|Optional field to provide comments on the waste quality test result.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[description](#description)|Optional description that provides additional detail about the entity or attribute.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[evidence](#evidence)|Optional field where evidence can be linked to an entity or attribute, if required.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[facility](#facility)|Unique identifier of the facility where the waste sample was collected for testing.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[industrialprocesstype](#industrialprocesstype)|Type of industrial process where the waste sample was collected for testing.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[measuredvalue](#measuredvalue)|The reportable measured value of a characteristic being tested.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[organizationalunit](#organizationalunit)|Unique identifier for the organizational unit associated with the waste sample collected for testing.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[origincorrelationid](#origincorrelationid)|Optional field to store source unique identifier for the waste quality test result.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[precision](#precision)|Indicates how the measurements for a property has been prescribed.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[resultstatus](#resultstatus)|Indicates whether the measure of the pollutant is within the permissible range.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[unit](#unit)|The unit of measurement of the measure value in the test result.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[wastequalitycharacteristic](#wastequalitycharacteristic)|Indicates the quality characterisitic of the contaminant or chemical being tracked.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[wastetestmethod](#wastetestmethod)|Indicates the test method and related details for the waste quality characteristic.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[wastequalitytestdate](#wastequalitytestdate)|The actual date and time at which the waste quality test was carried out.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|
|[reportingdate](#reportingdate)|Date used to parameterize reports.|<a href="WasteQualityTestResult.md" target="_blank">Sustainability\CloudforSustainabilityWasteDataModel/WasteQualityTestResult</a>|

### <a href=#wastequalitytestresultId name="wastequalitytestresultId">wastequalitytestresultId</a>

Unique identifier for entity instances.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Waste quality test result</td></tr><tr><td>description</td><td>Unique identifier for entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>sourceName</td><td>msdyn_wastequalitytestresultid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wastequalitytestresultId attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.identifiedBy*  
  names a specific identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WasteQualityTestResult/(resolvedAttributes)/wastequalitytestresultId](#wastequalitytestresultId)</td><td>attribute</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for entity instances.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Waste quality test result</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_wastequalitytestresultid"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"1"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#TTLInSeconds name="TTLInSeconds">TTLInSeconds</a>

Time to live in seconds.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time to live</td></tr><tr><td>description</td><td>Time to live in seconds.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ttlinseconds</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TTLInSeconds attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time to live in seconds.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time to live</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"ttlinseconds"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"2"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#partitionId name="partitionId">partitionId</a>

Logical partition identifier. A logical partition consists of a set of records with same partition ID.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Partition Id</td></tr><tr><td>description</td><td>Logical partition identifier. A logical partition consists of a set of records with same partition ID.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>partitionid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the partitionId attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Logical partition identifier. A logical partition consists of a set of records with same partition ID.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Partition Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"partitionid"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"3"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.dataFormat.time*  
  *means.measurement.time*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdon"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"4"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.time*  
  *is.dataFormat.date*  
  </details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.dataFormat.time*  
  *means.measurement.time*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedon"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"6"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.time*  
  *is.dataFormat.date*  
  </details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence number of the import that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"importsequencenumber"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"28"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"overriddencreatedon"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"29"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.date*  
  </details>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the custom entity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_name"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"30"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#comments name="comments">comments</a>

Optional field to provide comments on the waste quality test result.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comments</td></tr><tr><td>description</td><td>Optional field to provide comments on the waste quality test result.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_comments</td></tr></table>

#### Traits

<details>
<summary>List of traits for the comments attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Optional field to provide comments on the waste quality test result.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Comments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_comments"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"31"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#description name="description">description</a>

Optional description that provides additional detail about the entity or attribute.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Optional description that provides additional detail about the entity or attribute.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

#### Traits

<details>
<summary>List of traits for the description attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Optional description that provides additional detail about the entity or attribute.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_description"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"32"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#evidence name="evidence">evidence</a>

Optional field where evidence can be linked to an entity or attribute, if required.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Evidence</td></tr><tr><td>description</td><td>Optional field where evidence can be linked to an entity or attribute, if required.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_evidence</td></tr></table>

#### Traits

<details>
<summary>List of traits for the evidence attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Optional field where evidence can be linked to an entity or attribute, if required.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Evidence</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_evidence"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"33"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#facility name="facility">facility</a>

Unique identifier of the facility where the waste sample was collected for testing.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Facility</td></tr><tr><td>description</td><td>Unique identifier of the facility where the waste sample was collected for testing.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the facility attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the facility where the waste sample was collected for testing.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Facility</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="../SustainabilityShared/Facility.md" target="_blank">/SustainabilityShared/Facility.cdm.json/Facility</a></td><td><a href="../SustainabilityShared/Facility.md#facilityId" target="_blank">facilityId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#industrialprocesstype name="industrialprocesstype">industrialprocesstype</a>

Type of industrial process where the waste sample was collected for testing.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Industrial process type</td></tr><tr><td>description</td><td>Type of industrial process where the waste sample was collected for testing.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the industrialprocesstype attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type of industrial process where the waste sample was collected for testing.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Industrial process type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="../SustainabilityShared/IndustrialProcessType.md" target="_blank">/SustainabilityShared/IndustrialProcessType.cdm.json/IndustrialProcessType</a></td><td><a href="../SustainabilityShared/IndustrialProcessType.md#industrialprocesstypeId" target="_blank">industrialprocesstypeId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#measuredvalue name="measuredvalue">measuredvalue</a>

The reportable measured value of a characteristic being tested.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Measured value</td></tr><tr><td>description</td><td>The reportable measured value of a characteristic being tested.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_measuredvalue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the measuredvalue attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The reportable measured value of a characteristic being tested.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Measured value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_measuredvalue"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"36"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#organizationalunit name="organizationalunit">organizationalunit</a>

Unique identifier for the organizational unit associated with the waste sample collected for testing.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organizational unit</td></tr><tr><td>description</td><td>Unique identifier for the organizational unit associated with the waste sample collected for testing.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the organizationalunit attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the organizational unit associated with the waste sample collected for testing.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organizational unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="../SustainabilityShared/OrganizationalUnit.md" target="_blank">/SustainabilityShared/OrganizationalUnit.cdm.json/OrganizationalUnit</a></td><td><a href="../SustainabilityShared/OrganizationalUnit.md#sustainabilityorganizationalunitId" target="_blank">sustainabilityorganizationalunitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#origincorrelationid name="origincorrelationid">origincorrelationid</a>

Optional field to store source unique identifier for the waste quality test result.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Origin correlation id</td></tr><tr><td>description</td><td>Optional field to store source unique identifier for the waste quality test result.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_origincorrelationid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the origincorrelationid attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Optional field to store source unique identifier for the waste quality test result.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Origin correlation id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_origincorrelationid"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"38"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#precision name="precision">precision</a>

Indicates how the measurements for a property has been prescribed.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Precision</td></tr><tr><td>description</td><td>Indicates how the measurements for a property has been prescribed.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_precision</td></tr></table>

#### Traits

<details>
<summary>List of traits for the precision attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates how the measurements for a property has been prescribed.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Precision</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_precision"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"39"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#resultstatus name="resultstatus">resultstatus</a>

Indicates whether the measure of the pollutant is within the permissible range.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Result status</td></tr><tr><td>description</td><td>Indicates whether the measure of the pollutant is within the permissible range.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resultstatus</td></tr></table>

#### Traits

<details>
<summary>List of traits for the resultstatus attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates whether the measure of the pollutant is within the permissible range.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Result status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_resultstatus"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"40"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#unit name="unit">unit</a>

The unit of measurement of the measure value in the test result.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>The unit of measurement of the measure value in the test result.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the unit attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The unit of measurement of the measure value in the test result.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="../SustainabilityShared/Unit.md" target="_blank">/SustainabilityShared/Unit.cdm.json/Unit</a></td><td><a href="../SustainabilityShared/Unit.md#unitId" target="_blank">unitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#wastequalitycharacteristic name="wastequalitycharacteristic">wastequalitycharacteristic</a>

Indicates the quality characterisitic of the contaminant or chemical being tracked.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Waste quality characteristic</td></tr><tr><td>description</td><td>Indicates the quality characterisitic of the contaminant or chemical being tracked.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wastequalitycharacteristic attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates the quality characterisitic of the contaminant or chemical being tracked.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Waste quality characteristic</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="WasteQualityCharacteristic.md" target="_blank">WasteQualityCharacteristic.cdm.json/WasteQualityCharacteristic</a></td><td><a href="WasteQualityCharacteristic.md#wastequalitycharacteristicId" target="_blank">wastequalitycharacteristicId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#wastetestmethod name="wastetestmethod">wastetestmethod</a>

Indicates the test method and related details for the waste quality characteristic.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Waste test method</td></tr><tr><td>description</td><td>Indicates the test method and related details for the waste quality characteristic.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wastetestmethod attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates the test method and related details for the waste quality characteristic.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Waste test method</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="WasteTestMethod.md" target="_blank">WasteTestMethod.cdm.json/WasteTestMethod</a></td><td><a href="WasteTestMethod.md#wastetestmethodId" target="_blank">wastetestmethodId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#wastequalitytestdate name="wastequalitytestdate">wastequalitytestdate</a>

The actual date and time at which the waste quality test was carried out.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Waste quality test date</td></tr><tr><td>description</td><td>The actual date and time at which the waste quality test was carried out.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_wastequalitytestdate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wastequalitytestdate attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.dataFormat.time*  
  *means.measurement.time*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The actual date and time at which the waste quality test was carried out.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Waste quality test date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_wastequalitytestdate"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"44"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.time*  
  *is.dataFormat.date*  
  </details>

### <a href=#reportingdate name="reportingdate">reportingdate</a>

Date used to parameterize reports.  
First included in: Sustainability/SustainabilityWaste/WasteQualityTestResult (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reporting date</td></tr><tr><td>description</td><td>Date used to parameterize reports.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_reportingdate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the reportingdate attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.dataFormat.time*  
  *means.measurement.time*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date used to parameterize reports.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reporting date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_reportingdate"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"45"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.time*  
  *is.dataFormat.date*  
  </details>

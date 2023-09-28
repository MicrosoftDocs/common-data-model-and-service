---
title: DocumentPartyContract in PropertyandCasualtyDataModel - Common Data Model | Microsoft Docs
description: Information about the relationship between the contract (e.g., Policy) and a party, including the party role relating to the document.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/5/2023
ms.author: cdmditeam
---

# Document Party/Contract in PropertyandCasualtyDataModel(DocumentPartyContract)

Information about the relationship between the contract \(e.g., Policy\) and a party, including the party role relating to the document.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/FinancialServices/PropertyandCasualtyDataModel/DocumentPartyContract.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DocumentPartyContract/(resolvedAttributes)/documentpartycontractId](#documentpartycontractId)</td><td>attribute</td><td></td></tr></table>

**means.entityState**  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DocumentPartyContract/(resolvedAttributes)/statecode](#statecode)</td><td>attribute</td><td></td></tr></table>

**is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/FinancialServices/PropertyandCasualtyDataModel<br>/DocumentPartyContract.cdm.json<br>/DocumentPartyContract/hasAttributes<br>/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Information about the relationship between the contract (e.g., Policy) and a party, including the party role relating to the document.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document Party/Contract</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_documentpartycontract"</td><td>string</td><td></td></tr></table>

**has.entitySchemaAbstractionLevel**  
  A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or re-states parts of logical schemas to produce one resolved schema.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"resolved"</td><td>string</td><td>Possible values: logical, composition, resolved</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[documentpartycontractId](#documentpartycontractId)|Unique identifier for entity instances.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[statecode](#statecode)|Status of the Ins entity doc correspondence|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[statuscode](#statuscode)|Reason for the status of the Ins entity doc correspondence|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[name](#name)|Required name field.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[contractpart](#contractpart)|Reference to a contract part.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[contractpartType](#contractpartType)|Reference to a contract part.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[document](#document)|Reference to a document.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[party](#party)|Reference a party the document relates to.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[partyType](#partyType)|Reference a party the document relates to.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[partyrole](#partyrole)|Defines the party role for the related document.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|
|[reason](#reason)|Purpose of the document.|<a href="DocumentPartyContract.md" target="_blank">PropertyandCasualtyDataModel/DocumentPartyContract</a>|

### <a href=#documentpartycontractId name="documentpartycontractId">documentpartycontractId</a>

Unique identifier for entity instances.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document Party/Contract</td></tr><tr><td>description</td><td>Unique identifier for entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>sourceName</td><td>msfsi_documentpartycontractid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the documentpartycontractId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*means.identity.entityId\*\*  
  \*\*is.identifiedBy\*\*  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DocumentPartyContract/(resolvedAttributes)/documentpartycontractId](#documentpartycontractId)</td><td>attribute</td><td></td></tr></table>

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for entity instances.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document Party/Contract</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_documentpartycontractid"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"1"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

\*\*is.dataFormat.date\*\*  
  \*\*means.measurement.date\*\*  
  \*\*is.dataFormat.time\*\*  
  \*\*means.measurement.time\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdon"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"2"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.time\*\*  
  \*\*is.dataFormat.date\*\*  
  </details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

\*\*is.dataFormat.date\*\*  
  \*\*means.measurement.date\*\*  
  \*\*is.dataFormat.time\*\*  
  \*\*means.measurement.time\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedon"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"4"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.time\*\*  
  \*\*is.dataFormat.date\*\*  
  </details>

### <a href=#statecode name="statecode">statecode</a>

Status of the Ins entity doc correspondence  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Ins entity doc correspondence</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statecode attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*does.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*means.entityState\*\*  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DocumentPartyContract/(resolvedAttributes)/statecode](#statecode)</td><td>attribute</td><td></td></tr></table>

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status of the Ins entity doc correspondence</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statecode"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"25"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#statuscode name="statuscode">statuscode</a>

Reason for the status of the Ins entity doc correspondence  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Ins entity doc correspondence</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>2</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statuscode attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*does.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>2</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is.correlatedWith\*\*  
  the attribute value is correlated with the sourceAttribute  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>"statecode"</td><td>attributeName</td><td></td></tr></table>

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason for the status of the Ins entity doc correspondence</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status Reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statuscode"</td><td>string</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"27"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence number of the import that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"importsequencenumber"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"30"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

\*\*is.dataFormat.date\*\*  
  \*\*means.measurement.date\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"overriddencreatedon"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"31"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.date\*\*  
  </details>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeZoneRuleVersionNumber attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"timezoneruleversionnumber"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"32"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCConversionTimeZoneCode attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"utcconversiontimezonecode"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"33"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#name name="name">name</a>

Required name field.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Required name field.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Required name field.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_name"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"34"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#contractpart name="contractpart">contractpart</a>

Reference to a contract part.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract part</td></tr><tr><td>description</td><td>Reference to a contract part.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the contractpart attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*means.identity.entityId\*\*  
  \*\*is.linkedEntity.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="Claim.md" target="_blank">Claim.cdm.json/Claim</a></td><td><a href="Claim.md#claimId" target="_blank">claimId</a></td></tr><tr><td><a href="InsuredAssetLocation.md" target="_blank">InsuredAssetLocation.cdm.json/InsuredAssetLocation</a></td><td><a href="InsuredAssetLocation.md#insuredassetlocationId" target="_blank">insuredassetlocationId</a></td></tr><tr><td><a href="InsuredAutoAsset.md" target="_blank">InsuredAutoAsset.cdm.json/InsuredAutoAsset</a></td><td><a href="InsuredAutoAsset.md#insuredautoassetId" target="_blank">insuredautoassetId</a></td></tr><tr><td><a href="InsuredGenericAsset.md" target="_blank">InsuredGenericAsset.cdm.json/InsuredGenericAsset</a></td><td><a href="InsuredGenericAsset.md#insuredgenericassetId" target="_blank">insuredgenericassetId</a></td></tr><tr><td><a href="InsuredHomeAsset.md" target="_blank">InsuredHomeAsset.cdm.json/InsuredHomeAsset</a></td><td><a href="InsuredHomeAsset.md#insuredhomeassetId" target="_blank">insuredhomeassetId</a></td></tr><tr><td><a href="Policy.md" target="_blank">Policy.cdm.json/Policy</a></td><td><a href="Policy.md#policyId" target="_blank">policyId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reference to a contract part.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contract part</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#contractpartType name="contractpartType">contractpartType</a>

Reference to a contract part.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract part</td></tr><tr><td>description</td><td>Reference to a contract part.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the contractpartType attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*means.entityName\*\*  
  a string value is the name of a CDM entity.  

\*\*is.linkedEntity.name\*\*  
  Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.  

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reference to a contract part.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contract part</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#document name="document">document</a>

Reference to a document.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document</td></tr><tr><td>description</td><td>Reference to a document.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the document attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*means.identity.entityId\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reference to a document.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.CDS.lookup\*\*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

\*\*is.linkedEntity.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="Document.md" target="_blank">Document.cdm.json/Document</a></td><td><a href="Document.md#documentId" target="_blank">documentId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#party name="party">party</a>

Reference a party the document relates to.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Party</td></tr><tr><td>description</td><td>Reference a party the document relates to.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the party attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*means.identity.entityId\*\*  
  \*\*is.linkedEntity.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="Account.md" target="_blank">Account.cdm.json/Account</a></td><td><a href="Account.md#accountId" target="_blank">accountId</a></td></tr><tr><td><a href="Contact.md" target="_blank">Contact.cdm.json/Contact</a></td><td><a href="Contact.md#contactId" target="_blank">contactId</a></td></tr><tr><td><a href="Agency.md" target="_blank">Agency.cdm.json/Agency</a></td><td><a href="Agency.md#agencyId" target="_blank">agencyId</a></td></tr><tr><td><a href="Agent.md" target="_blank">Agent.cdm.json/Agent</a></td><td><a href="Agent.md#agentId" target="_blank">agentId</a></td></tr><tr><td><a href="Insurer.md" target="_blank">Insurer.cdm.json/Insurer</a></td><td><a href="Insurer.md#insurerId" target="_blank">insurerId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reference a party the document relates to.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Party</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#partyType name="partyType">partyType</a>

Reference a party the document relates to.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Party</td></tr><tr><td>description</td><td>Reference a party the document relates to.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the partyType attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*means.entityName\*\*  
  a string value is the name of a CDM entity.  

\*\*is.linkedEntity.name\*\*  
  Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.  

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reference a party the document relates to.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Party</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#partyrole name="partyrole">partyrole</a>

Defines the party role for the related document.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Party role</td></tr><tr><td>description</td><td>Defines the party role for the related document.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_partyrole</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Sender</td><td>104800000</td></tr><tr><td>en</td><td>Reciever</td><td>104800001</td></tr><tr><td>en</td><td>Primary subject</td><td>104800002</td></tr><tr><td>en</td><td>Secondary subject</td><td>104800003</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the partyrole attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*does.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Sender</td><td>104800000</td></tr><tr><td>en</td><td>Reciever</td><td>104800001</td></tr><tr><td>en</td><td>Primary subject</td><td>104800002</td></tr><tr><td>en</td><td>Secondary subject</td><td>104800003</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Defines the party role for the related document.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Party role</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_partyrole"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"38"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#reason name="reason">reason</a>

Purpose of the document.  
First included in: PropertyandCasualtyDataModel/DocumentPartyContract \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason</td></tr><tr><td>description</td><td>Purpose of the document.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_reason</td></tr></table>

#### Traits

<details>
<summary>List of traits for the reason attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purpose of the document.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_reason"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"40"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

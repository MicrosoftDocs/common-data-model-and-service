---
title: MarketingFormField in MarketingSolution - Common Data Model | Microsoft Docs
description: undefined
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/6/2024
ms.author: cdmditeam
---

# Marketing Form Field in MarketingSolution

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/Marketing\MarketingSolution/MarketingFormField.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsCreationModificationDatesAndIds</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsOwnershipInfo</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsTimeZoneInfo</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsVersionTracking</td></tr><tr><td>/Marketing/MarketingSolution<br>/MarketingFormField.cdm.json/MarketingFormField<br>/hasAttributes/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

**is.identifiedBy**  
  names a specific identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MarketingFormField/(resolvedAttributes)/marketingFormFieldId](#marketingFormFieldId)</td><td>attribute</td><td></td></tr></table>

**means.entityState**  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MarketingFormField/(resolvedAttributes)/stateCode](#stateCode)</td><td>attribute</td><td></td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Marketing Form Field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_marketingformfield"</td><td>string</td><td></td></tr></table>

**has.entitySchemaAbstractionLevel**  
  A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or re-states parts of logical schemas to produce one resolved schema.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"resolved"</td><td>string</td><td>Possible values: logical, composition, resolved</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[ownerId](#ownerId)|Owner Id|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[contactMapping](#contactMapping)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[defaultformlabel](#defaultformlabel)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[defaultformplaceholder](#defaultformplaceholder)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[marketingFormFieldId](#marketingFormFieldId)|Unique ID for entity instances|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[marketingformfieldtype](#marketingformfieldtype)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[marketingformfieldtype_display](#marketingformfieldtype_display)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[format](#format)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[format_display](#format_display)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[leadMapping](#leadMapping)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[name](#name)|The name of the custom entity|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[renderas](#renderas)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[renderas_display](#renderas_display)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[ownerIdName](#ownerIdName)|Name of the owner|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[ownerIdYomiName](#ownerIdYomiName)|Yomi name of the owner|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[stateCode](#stateCode)|Status of the marketing form field|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[stateCode_display](#stateCode_display)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[statusCode](#statusCode)|Reason for the status of the marketing form field|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[statusCode_display](#statusCode_display)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[marketingProvided](#marketingProvided)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[contactmappingTarget](#contactmappingTarget)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[leadmappingTarget](#leadmappingTarget)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[lookupTarget](#lookupTarget)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[prototypeAttribute](#prototypeAttribute)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[prototypeEntity](#prototypeEntity)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[prototypeTarget](#prototypeTarget)||<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|
|[publicVisibility](#publicVisibility)|I acknowledge the select lookup will be visible to public|<a href="MarketingFormField.md" target="_blank">Marketing\MarketingSolution/MarketingFormField</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.dataFormat.time*  
  *means.measurement.time*  
  *means.measurement.date.creation*  
  *is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdon"</td><td>string</td><td></td></tr></table>

*is.dataFormat.time*  
  *is.dataFormat.date*  
  </details>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdBy attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *means.userId*  
  contains a userId  

*is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdby"</td><td>string</td><td></td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.dataFormat.time*  
  *means.measurement.time*  
  *means.measurement.date.modify*  
  *is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedon"</td><td>string</td><td></td></tr></table>

*is.dataFormat.time*  
  *is.dataFormat.date*  
  </details>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedBy attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *means.userId*  
  contains a userId  

*is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedby"</td><td>string</td><td></td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOnBehalfBy attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *means.userId*  
  contains a userId  

*is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record on behalf of another user.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdonbehalfby"</td><td>string</td><td></td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOnBehalfBy attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *means.userId*  
  contains a userId  

*is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record on behalf of another user.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedonbehalfby"</td><td>string</td><td></td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.dataFormat.time*  
  *means.measurement.time*  
  *means.measurement.date.creation*  
  *is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"overriddencreatedon"</td><td>string</td><td></td></tr></table>

*is.dataFormat.time*  
  *is.dataFormat.date*  
  </details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the data import or data migration that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"importsequencenumber"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerId attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr><tr><td><a href="../../../../Team.md" target="_blank">/core/applicationCommon/Team.cdm.json/Team</a></td><td><a href="../../../../Team.md#teamId" target="_blank">teamId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"ownerid"</td><td>string</td><td></td></tr></table>

*is.CDS.owner*  
  contains a User or Team ID  

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerIdType attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*means.entityName*  
  a string value is the name of a CDM entity.  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The type of owner, either User or Team.</td></tr><tr><td>en</td><td>Owner Id Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.linkedEntity.name*  
  Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.  

*is.readOnly*  
  *is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owneridtype"</td><td>string</td><td></td></tr></table>

*is.CDS.owner*  
  contains a User or Team ID  

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

*is.dataFormat.integer*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

</details>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningBusinessUnit attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Business Unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the business unit that owns the record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../BusinessUnit.md" target="_blank">/core/applicationCommon/BusinessUnit.cdm.json/BusinessUnit</a></td><td><a href="../../../../BusinessUnit.md#businessUnitId" target="_blank">businessUnitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owningbusinessunit"</td><td>string</td><td></td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningUser attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *means.userId*  
  contains a userId  

*is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning User</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the user that owns the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owninguser"</td><td>string</td><td></td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningTeam attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Team</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the team that owns the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Team.md" target="_blank">/core/applicationCommon/Team.cdm.json/Team</a></td><td><a href="../../../../Team.md#teamId" target="_blank">teamId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owningteam"</td><td>string</td><td></td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeZoneRuleVersionNumber attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"timezoneruleversionnumber"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCConversionTimeZoneCode attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"utcconversiontimezonecode"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the versionNumber attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*means.measurement.version*  
  *is.CDS.standard*  
  identifies attributes that are part of the cdsStandard base set.  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"versionnumber"</td><td>string</td><td></td></tr></table>

*is.dataFormat.integer*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

</details>

### <a href=#contactMapping name="contactMapping">contactMapping</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact mapping</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_contactmapping</td></tr></table>

#### Traits

<details>
<summary>List of traits for the contactMapping attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_contactmapping"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contact mapping</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#defaultformlabel name="defaultformlabel">defaultformlabel</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Label</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_defaultformlabel</td></tr></table>

#### Traits

<details>
<summary>List of traits for the defaultformlabel attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_defaultformlabel"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Label</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#defaultformplaceholder name="defaultformplaceholder">defaultformplaceholder</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Placeholder</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_defaultformplaceholder</td></tr></table>

#### Traits

<details>
<summary>List of traits for the defaultformplaceholder attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_defaultformplaceholder"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Placeholder</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#marketingFormFieldId name="marketingFormFieldId">marketingFormFieldId</a>

Unique ID for entity instances  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing form field</td></tr><tr><td>description</td><td>Unique ID for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>sourceName</td><td>msdyncrm_marketingformfieldid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the marketingFormFieldId attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.identifiedBy*  
  names a specific identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MarketingFormField/(resolvedAttributes)/marketingFormFieldId](#marketingFormFieldId)</td><td>attribute</td><td></td></tr></table>

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_marketingformfieldid"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Marketing form field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique ID for entity instances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#marketingformfieldtype name="marketingformfieldtype">marketingformfieldtype</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Field type</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>sourceName</td><td>msdyncrm_marketingformfieldtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Single line of text</td><td>1</td></tr><tr><td>en</td><td>Multiple lines of text</td><td>2</td></tr><tr><td>en</td><td>Option set</td><td>3</td></tr><tr><td>en</td><td>Two options</td><td>4</td></tr><tr><td>en</td><td>Whole number</td><td>5</td></tr><tr><td>en</td><td>Floating point number</td><td>6</td></tr><tr><td>en</td><td>Decimal number</td><td>7</td></tr><tr><td>en</td><td>Date and time</td><td>8</td></tr><tr><td>en</td><td>Currency</td><td>9</td></tr><tr><td>en</td><td>Multi-select option set</td><td>10</td></tr><tr><td>en</td><td>Lookup</td><td>11</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the marketingformfieldtype attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Single line of text</td><td>1</td></tr><tr><td>en</td><td>Multiple lines of text</td><td>2</td></tr><tr><td>en</td><td>Option set</td><td>3</td></tr><tr><td>en</td><td>Two options</td><td>4</td></tr><tr><td>en</td><td>Whole number</td><td>5</td></tr><tr><td>en</td><td>Floating point number</td><td>6</td></tr><tr><td>en</td><td>Decimal number</td><td>7</td></tr><tr><td>en</td><td>Date and time</td><td>8</td></tr><tr><td>en</td><td>Currency</td><td>9</td></tr><tr><td>en</td><td>Multi-select option set</td><td>10</td></tr><tr><td>en</td><td>Lookup</td><td>11</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_marketingformfieldtype"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"required"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Field type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#marketingformfieldtype_display name="marketingformfieldtype_display">marketingformfieldtype_display</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the marketingformfieldtype_display attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*means.reference.displayText*  
  *is.readOnly*  
  *is.addedInSupportOf*  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"marketingformfieldtype"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#format name="format">format</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Format</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_format</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Text</td><td>1</td></tr><tr><td>en</td><td>Text area</td><td>2</td></tr><tr><td>en</td><td>Email</td><td>3</td></tr><tr><td>en</td><td>URL</td><td>4</td></tr><tr><td>en</td><td>Phone</td><td>5</td></tr><tr><td>en</td><td>Date</td><td>6</td></tr><tr><td>en</td><td>Date and time</td><td>7</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the format attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Text</td><td>1</td></tr><tr><td>en</td><td>Text area</td><td>2</td></tr><tr><td>en</td><td>Email</td><td>3</td></tr><tr><td>en</td><td>URL</td><td>4</td></tr><tr><td>en</td><td>Phone</td><td>5</td></tr><tr><td>en</td><td>Date</td><td>6</td></tr><tr><td>en</td><td>Date and time</td><td>7</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_format"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.integer*  
  </details>

### <a href=#format_display name="format_display">format_display</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the format_display attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*means.reference.displayText*  
  *is.readOnly*  
  *is.nullable*  
  The attribute value may be set to NULL.  

*is.addedInSupportOf*  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"format"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#leadMapping name="leadMapping">leadMapping</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead mapping</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_leadmapping</td></tr></table>

#### Traits

<details>
<summary>List of traits for the leadMapping attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_leadmapping"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lead mapping</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#name name="name">name</a>

The name of the custom entity  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*means.identity.name*  
  *is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_name"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"required"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the custom entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#renderas name="renderas">renderas</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rendering control</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_renderas</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Text box</td><td>1</td></tr><tr><td>en</td><td>Email input</td><td>2</td></tr><tr><td>en</td><td>URL input</td><td>3</td></tr><tr><td>en</td><td>Phone input</td><td>4</td></tr><tr><td>en</td><td>Number input</td><td>5</td></tr><tr><td>en</td><td>Text area</td><td>6</td></tr><tr><td>en</td><td>Checkbox</td><td>7</td></tr><tr><td>en</td><td>Drop-down</td><td>8</td></tr><tr><td>en</td><td>Radio buttons</td><td>9</td></tr><tr><td>en</td><td>Date picker</td><td>10</td></tr><tr><td>en</td><td>Date time picker</td><td>11</td></tr><tr><td>en</td><td>Checkbox list</td><td>12</td></tr><tr><td>en</td><td>Lookup</td><td>13</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the renderas attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Text box</td><td>1</td></tr><tr><td>en</td><td>Email input</td><td>2</td></tr><tr><td>en</td><td>URL input</td><td>3</td></tr><tr><td>en</td><td>Phone input</td><td>4</td></tr><tr><td>en</td><td>Number input</td><td>5</td></tr><tr><td>en</td><td>Text area</td><td>6</td></tr><tr><td>en</td><td>Checkbox</td><td>7</td></tr><tr><td>en</td><td>Drop-down</td><td>8</td></tr><tr><td>en</td><td>Radio buttons</td><td>9</td></tr><tr><td>en</td><td>Date picker</td><td>10</td></tr><tr><td>en</td><td>Date time picker</td><td>11</td></tr><tr><td>en</td><td>Checkbox list</td><td>12</td></tr><tr><td>en</td><td>Lookup</td><td>13</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_renderas"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rendering control</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.integer*  
  </details>

### <a href=#renderas_display name="renderas_display">renderas_display</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the renderas_display attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*means.reference.displayText*  
  *is.readOnly*  
  *is.nullable*  
  The attribute value may be set to NULL.  

*is.addedInSupportOf*  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"renderas"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ownerIdName name="ownerIdName">ownerIdName</a>

Name of the owner  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Name of the owner</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>owneridname</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerIdName attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*means.identity.name*  
  *is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owneridname"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name of the owner</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ownerIdYomiName name="ownerIdYomiName">ownerIdYomiName</a>

Yomi name of the owner  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Yomi name of the owner</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>owneridyominame</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerIdYomiName attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*means.identity.name*  
  *is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owneridyominame"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Yomi name of the owner</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the marketing form field  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the marketing form field</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*means.entityState*  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MarketingFormField/(resolvedAttributes)/stateCode](#stateCode)</td><td>attribute</td><td></td></tr></table>

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statecode"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status of the marketing form field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode_display attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*means.reference.displayText*  
  *is.readOnly*  
  *is.addedInSupportOf*  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"stateCode"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the marketing form field  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status reason</td></tr><tr><td>description</td><td>Reason for the status of the marketing form field</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*is.correlatedWith*  
  the attribute value is correlated with the sourceAttribute  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>"stateCode"</td><td>attributeName</td><td></td></tr></table>

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statuscode"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason for the status of the marketing form field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.integer*  
  </details>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode_display attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*means.reference.displayText*  
  *is.readOnly*  
  *is.nullable*  
  The attribute value may be set to NULL.  

*is.addedInSupportOf*  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"statusCode"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#marketingProvided name="marketingProvided">marketingProvided</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing Provided</td></tr><tr><td>dataFormat</td><td>boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_marketingprovided</td></tr></table>

#### Traits

<details>
<summary>List of traits for the marketingProvided attribute are listed below.</summary>

*is.dataFormat.boolean*  
  *is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_marketingprovided"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Marketing Provided</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.boolean*  
  </details>

### <a href=#contactmappingTarget name="contactmappingTarget">contactmappingTarget</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact mapping targets</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_contactmapping_target</td></tr></table>

#### Traits

<details>
<summary>List of traits for the contactmappingTarget attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_contactmapping_target"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contact mapping targets</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#leadmappingTarget name="leadmappingTarget">leadmappingTarget</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead mapping targets</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_leadmapping_target</td></tr></table>

#### Traits

<details>
<summary>List of traits for the leadmappingTarget attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_leadmapping_target"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lead mapping targets</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#lookupTarget name="lookupTarget">lookupTarget</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lookup targets</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_lookup_target</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lookupTarget attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_lookup_target"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lookup targets</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#prototypeAttribute name="prototypeAttribute">prototypeAttribute</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unmapped attribute</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_prototype_attribute</td></tr></table>

#### Traits

<details>
<summary>List of traits for the prototypeAttribute attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_prototype_attribute"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unmapped attribute</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#prototypeEntity name="prototypeEntity">prototypeEntity</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unmapped entity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_prototype_entity</td></tr></table>

#### Traits

<details>
<summary>List of traits for the prototypeEntity attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_prototype_entity"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unmapped entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#prototypeTarget name="prototypeTarget">prototypeTarget</a>

First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unmapped targets</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_prototype_target</td></tr></table>

#### Traits

<details>
<summary>List of traits for the prototypeTarget attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_prototype_target"</td><td>string</td><td></td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unmapped targets</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#publicVisibility name="publicVisibility">publicVisibility</a>

I acknowledge the select lookup will be visible to public  
First included in: Marketing\\MarketingSolution/MarketingFormField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lookup will be visible to public</td></tr><tr><td>description</td><td>I acknowledge the select lookup will be visible to public</td></tr><tr><td>dataFormat</td><td>boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_publicvisibility</td></tr></table>

#### Traits

<details>
<summary>List of traits for the publicVisibility attribute are listed below.</summary>

*is.dataFormat.boolean*  
  *is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyncrm_publicvisibility"</td><td>string</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lookup will be visible to public</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>I acknowledge the select lookup will be visible to public</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.dataFormat.boolean*  
  </details>

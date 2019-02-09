---
title: Website
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/9/2019
ms.author: tpalmer
---

# Website

  
Latest version (0.8.1) of the json entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

- **is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>0.8.1</td><td>string</td><td>semantic version number of the entity</td></tr></table>

- **is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsCreationModificationDatesAndIds</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsOwnershipInfo</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsTimeZoneInfo</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsVersionTracking</td></tr><tr><td>/core/applicationCommon/foundationCommon<br>/crmCommon/solutions/marketing/Website.cdm.json<br>/Website/hasAttributes/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

- **is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[Website/hasAttributes/websiteId](#websiteId)</td><td>attribute</td><td></td></tr></table>

- **means.entityState**  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[Website/hasAttributes/stateCode](#stateCode)</td><td>attribute</td><td></td></tr></table>

- **is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Website</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msdyncrm_website</td><td>string</td><td></td></tr></table>

</details>

## Instances

Instances of this entity are listed below:  

marketing/Website  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Website.md" target="_blank">marketing/Website</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Website.md" target="_blank">marketing/Website</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Website.md" target="_blank">marketing/Website</a>|
|[websiteId](#websiteId)|Unique ID for entity instances.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[stateCode](#stateCode)|Status of the Website|<a href="Website.md" target="_blank">marketing/Website</a>|
|[stateCode_display](#stateCode_display)||<a href="Website.md" target="_blank">marketing/Website</a>|
|[statusCode](#statusCode)|Website status reason|<a href="Website.md" target="_blank">marketing/Website</a>|
|[statusCode_display](#statusCode_display)||<a href="Website.md" target="_blank">marketing/Website</a>|
|[name](#name)|The name of the website.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[description](#description)||<a href="Website.md" target="_blank">marketing/Website</a>|
|[insightsPlaceholder](#insightsPlaceholder)||<a href="Website.md" target="_blank">marketing/Website</a>|
|[javascriptcode](#javascriptcode)||<a href="Website.md" target="_blank">marketing/Website</a>|
|[remoteWebsiteID](#remoteWebsiteID)|Unique ID for remote entity instances.|<a href="Website.md" target="_blank">marketing/Website</a>|
|[shouldBeRemoved](#shouldBeRemoved)||<a href="Website.md" target="_blank">marketing/Website</a>|
|[timeout](#timeout)||<a href="Website.md" target="_blank">marketing/Website</a>|
|[url](#url)||<a href="Website.md" target="_blank">marketing/Website</a>|
|[purpose](#purpose)||<a href="Website.md" target="_blank">marketing/Website</a>|
|[purpose_display](#purpose_display)||<a href="Website.md" target="_blank">marketing/Website</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

- **is.dataFormat.date**  
- **means.measurement.date**  
- **is.dataFormat.time**  
- **means.measurement.time**  
- **means.measurement.date.creation**  
- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>createdon</td><td>string</td><td></td></tr></table>

</details>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdBy attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **means.userId**  
contains a userId  

- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>createdby</td><td>string</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

- **is.dataFormat.date**  
- **means.measurement.date**  
- **is.dataFormat.time**  
- **means.measurement.time**  
- **means.measurement.date.modify**  
- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedon</td><td>string</td><td></td></tr></table>

</details>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedBy attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **means.userId**  
contains a userId  

- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedby</td><td>string</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOnBehalfBy attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **means.userId**  
contains a userId  

- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record on behalf of another user.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>createdonbehalfby</td><td>string</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOnBehalfBy attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **means.userId**  
contains a userId  

- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record on behalf of another user.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedonbehalfby</td><td>string</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

- **is.dataFormat.date**  
- **means.measurement.date**  
- **is.dataFormat.time**  
- **means.measurement.time**  
- **means.measurement.date.creation**  
- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>overriddencreatedon</td><td>string</td><td></td></tr></table>

</details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the data import or data migration that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>importsequencenumber</td><td>string</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr></table>

</details>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerIdType attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **means.entityName**  
- **is.readOnly**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The type of owner, either User or Team.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>owneridtype</td><td>string</td><td></td></tr></table>

- **is.linkedEntity.name**  
Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.  

- **is.CDS.owner**  
contains a User or Team ID  

</details>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerId attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>ownerid</td><td>string</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr><tr><td><a href="../../../../Team.md" target="_blank">/core/applicationCommon/Team.cdm.json/Team</a></td><td><a href="../../../../Team.md#teamId" target="_blank">teamId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

- **is.CDS.owner**  
contains a User or Team ID  

</details>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningBusinessUnit attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Business Unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the business unit that owns the record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>owningbusinessunit</td><td>string</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../BusinessUnit.md" target="_blank">/core/applicationCommon/BusinessUnit.cdm.json/BusinessUnit</a></td><td><a href="../../../../BusinessUnit.md#businessUnitId" target="_blank">businessUnitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningUser attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **means.userId**  
contains a userId  

- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning User</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the user that owns the activity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>owninguser</td><td>string</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr><tr><td><a href="../../service/User.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User</a></td><td><a href="../../service/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningTeam attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Team</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the team that owns the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>owningteam</td><td>string</td><td></td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Team.md" target="_blank">/core/applicationCommon/Team.cdm.json/Team</a></td><td><a href="../../../../Team.md#teamId" target="_blank">teamId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

</details>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeZoneRuleVersionNumber attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>timezoneruleversionnumber</td><td>string</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr></table>

</details>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCConversionTimeZoneCode attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>utcconversiontimezonecode</td><td>string</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr></table>

</details>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the versionNumber attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **is.dataFormat.big**  
- **means.measurement.version**  
- **is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>versionnumber</td><td>string</td><td></td></tr></table>

</details>

### <a href=#websiteId name="websiteId">websiteId</a>

Unique ID for entity instances.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Unique ID for entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_websiteid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the websiteId attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.dataFormat.guid**  
- **means.identity.entityId**  
- **is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[Website/hasAttributes/websiteId](#websiteId)</td><td>attribute</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Website</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique ID for entity instances.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msdyncrm_websiteid</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>1</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Website  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Website</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

- **is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

- **means.entityState**  
the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[Website/hasAttributes/stateCode](#stateCode)</td><td>attribute</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status of the Website</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>statecode</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>24</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode_display attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **means.reference.displayText**  
- **is.readOnly**  
- **is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>stateCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

</details>

### <a href=#statusCode name="statusCode">statusCode</a>

Website status reason  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status reason</td></tr><tr><td>description</td><td>Website status reason</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>1</td></tr><tr><td>en</td><td>Inactive</td><td>2</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>displayOrder</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

- **is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

- **is.correlatedWith**  
the attribute value is correlated with the sourceAttribute  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>stateCode</td><td>attributeName</td><td></td></tr></table>

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Website status reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>statuscode</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>26</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode_display attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **means.reference.displayText**  
- **is.readOnly**  
- **is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>statusCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

</details>

### <a href=#name name="name">name</a>

The name of the website.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the website.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **means.identity.name**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the website.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msdyncrm_name</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>33</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#description name="description">description</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_description</td></tr></table>

#### Traits

<details>
<summary>List of traits for the description attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msdyncrm_description</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>34</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>2000</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#insightsPlaceholder name="insightsPlaceholder">insightsPlaceholder</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insights</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_insights_placeholder</td></tr></table>

#### Traits

<details>
<summary>List of traits for the insightsPlaceholder attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insights</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msdyncrm_insights_placeholder</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>35</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#javascriptcode name="javascriptcode">javascriptcode</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>JavaScript code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_javascriptcode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the javascriptcode attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>JavaScript code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msdyncrm_javascriptcode</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>36</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>5000</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#remoteWebsiteID name="remoteWebsiteID">remoteWebsiteID</a>

Unique ID for remote entity instances.  
First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remote website ID</td></tr><tr><td>description</td><td>Unique ID for remote entity instances.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_remote_websiteid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the remoteWebsiteID attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remote website ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique ID for remote entity instances.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msdyncrm_remote_websiteid</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>37</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#shouldBeRemoved name="shouldBeRemoved">shouldBeRemoved</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Should be removed</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_shouldberemoved</td></tr></table>

#### Traits

<details>
<summary>List of traits for the shouldBeRemoved attribute are listed below.</summary>

- **is.dataFormat.boolean**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Should be removed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msdyncrm_shouldberemoved</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>38</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#timeout name="timeout">timeout</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Timeout</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_timeout</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeout attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **means.measurement.duration**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Timeout</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msdyncrm_timeout</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>40</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr></table>

</details>

### <a href=#url name="url">url</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_url</td></tr></table>

#### Traits

<details>
<summary>List of traits for the url attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **means.reference.URL**  
- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>URL</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msdyncrm_url</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>41</td><td>integer</td><td></td></tr></table>

- **is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>500</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#purpose name="purpose">purpose</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purpose</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_purpose</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>General</td><td>192350000</td></tr><tr><td>en</td><td>Marketing page</td><td>192350001</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the purpose attribute are listed below.</summary>

- **is.dataFormat.integer**  
- **does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>General</td><td>192350000</td></tr><tr><td>en</td><td>Marketing page</td><td>192350001</td></tr></table></td><td>any</td><td></td></tr></table>

- **is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

- **is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purpose</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.nullable**  
The attribute value may be set to NULL.  

- **is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>msdyncrm_purpose</td><td>string</td><td></td></tr></table>

- **is.CDS.ordered**  
the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>42</td><td>integer</td><td></td></tr></table>

</details>

### <a href=#purpose_display name="purpose_display">purpose_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Website.cdm.json/Website  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the purpose_display attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **means.reference.displayText**  
- **is.readOnly**  
- **is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>purpose</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

</details>

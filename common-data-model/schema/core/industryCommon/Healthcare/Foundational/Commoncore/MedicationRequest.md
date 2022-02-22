---
title: MedicationRequest in Commoncore - Common Data Model | Microsoft Docs
description: An order or request for both supply of the medication and the instructions for administration of the medication to a patient.
author: matgos

ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Medication Request in Commoncore

An order or request for both supply of the medication and the instructions for administration of the medication to a patient.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/Healthcare/Foundational/Commoncore/MedicationRequest.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsCreationModificationDatesAndIds</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsOwnershipInfo</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsTimeZoneInfo</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsVersionTracking</td></tr><tr><td>/Healthcare/Foundational/Commoncore<br>/MedicationRequest.cdm.json/MedicationRequest<br>/hasAttributes/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MedicationRequest/(resolvedAttributes)/medicationRequestId](#medicationRequestId)</td><td>attribute</td><td></td></tr></table>

**means.entityState**  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MedicationRequest/(resolvedAttributes)/stateCode](#stateCode)</td><td>attribute</td><td></td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Medication Request</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>An order or request for both supply of the medication and the instructions for administration of the medication to a patient.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_medicationrequest"</td><td>string</td><td></td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[ownerId](#ownerId)|Owner Id|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[authoredOn](#authoredOn)|The date (and perhaps time) when the prescription was initially written or authored on.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[categoryId](#categoryId)|Indicates the type of medication request (for example, where the medication is expected to be consumed or administered or the type of treatment.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[contextType](#contextType)|A link to an encounter, or episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[contextType_display](#contextType_display)||<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[contextTypeEncounterId](#contextTypeEncounterId)|A link to an encounter that identifies the particular occurrence or set occurrences of contact between patient and health care provider.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[contextTypeEpisodeOfCareId](#contextTypeEpisodeOfCareId)|A link to an episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[dispenseRequestNumberOfRepeatsAllowed](#dispenseRequestNumberOfRepeatsAllowed)|An integer indicating the number of times, in addition to the original dispense, (aka refills or repeats) that the patient can receive the prescribed medication.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[dispenseRequestPerformerId](#dispenseRequestPerformerId)|Indicates the intended dispensing Organization specified by the Prescriber.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[dispenseRequestQuantity](#dispenseRequestQuantity)|The amount that is to be dispensed for one fill.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[dispenseRequestValidityPeriodEndDate](#dispenseRequestValidityPeriodEndDate)|This indicates the validity period of a prescription (stale dating the Prescription).|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[dispenseRequestValidityPeriodStartDate](#dispenseRequestValidityPeriodStartDate)|This indicates the validity period of a prescription (stale dating the Prescription).|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[expectedSupplyDuration](#expectedSupplyDuration)|Identifies the period time over which the supplied product is expected to be used, or the length of time the dispense is expected to last.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[groupIdentifier](#groupIdentifier)|A shared identifier common to all requests that were authorized more or less simultaneously by a single author, representing the identifier of the requisition or prescription.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[identifier](#identifier)|This records identifiers associated with this medication request that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[intent](#intent)|Whether the request is a proposal, plan, or an original order.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[intent_display](#intent_display)||<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[medicationReferenceNewId](#medicationReferenceNewId)||<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[medicationRequestId](#medicationRequestId)|Unique identifier for entity instances|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[medicationType](#medicationType)|Identifies the medication being requested.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[medicationType_display](#medicationType_display)||<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[medicationTypeCodeableConceptId](#medicationTypeCodeableConceptId)|Identifies the medication being requested.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[name](#name)|The name of the custom entity.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[priority](#priority)|Indicates how quickly the Medication Request should be addressed with respect to other requests.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[priority_display](#priority_display)||<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[priorPrescriptionId](#priorPrescriptionId)|A link to a resource representing an earlier order related order or prescription.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[recorderId](#recorderId)|The person who entered the order on behalf of another individual for example in the case of a verbal or a telephone order.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[requesterAgentType](#requesterAgentType)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[requesterAgentType_display](#requesterAgentType_display)||<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[requesterAgentTypeDeviceId](#requesterAgentTypeDeviceId)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[requesterAgentTypeOrganizationId](#requesterAgentTypeOrganizationId)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[requesterAgentTypePatientId](#requesterAgentTypePatientId)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[requesterAgentTypePractitionerId](#requesterAgentTypePractitionerId)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[requesterAgentTypeRelatedPersonId](#requesterAgentTypeRelatedPersonId)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[requesterOnBehalfOfId](#requesterOnBehalfOfId)|The organization the device or practitioner was acting on behalf of.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[status](#status)|A code specifying the current state of the order. Generally, this will be active or completed state.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[status_display](#status_display)||<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[subjectType](#subjectType)|A link to a resource representing the person or set of individuals to whom the medication will be given.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[subjectType_display](#subjectType_display)||<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[subjectTypeGroupId](#subjectTypeGroupId)|A link to a resource representing the person or set of individuals to whom the medication will be given.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[subjectTypePatientId](#subjectTypePatientId)|A link to a resource representing the person or set of individuals to whom the medication will be given.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[substitutionAllowed](#substitutionAllowed)|True if the Prescriber allows a different drug to be dispensed from what was prescribed.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[substitutionReasonId](#substitutionReasonId)|Indicates the reason for the substitution, or why substitution must or must not be performed.|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[stateCode](#stateCode)|Status of the Medication Request|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[stateCode_display](#stateCode_display)||<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[statusCode](#statusCode)|Reason for the status of the Medication Request|<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|
|[statusCode_display](#statusCode_display)||<a href="MedicationRequest.md" target="_blank">Commoncore/MedicationRequest</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**means.measurement.date.creation**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdon"</td><td>string</td><td></td></tr></table>

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record.</td></tr><tr><td>en</td><td>Unique identifier of the user who created the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../core/applicationCommon/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**means.measurement.date.modify**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedon"</td><td>string</td><td></td></tr></table>

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record.</td></tr><tr><td>en</td><td>Unique identifier of the user who modified the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../core/applicationCommon/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOnBehalfBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>en</td><td>Unique identifier of the delegate user who created the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../core/applicationCommon/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdonbehalfby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOnBehalfBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>en</td><td>Unique identifier of the delegate user who modified the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../core/applicationCommon/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedonbehalfby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**means.measurement.date.creation**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"overriddencreatedon"</td><td>string</td><td></td></tr></table>

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>en</td><td>Sequence number of the import that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"importsequencenumber"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../core/applicationCommon/User.md#systemUserId" target="_blank">systemUserId</a></td></tr><tr><td><a href="../../../../../core/applicationCommon/Team.md" target="_blank">/core/applicationCommon/Team.cdm.json/Team</a></td><td><a href="../../../../../core/applicationCommon/Team.md#teamId" target="_blank">teamId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"ownerid"</td><td>string</td><td></td></tr></table>

**is.CDS.owner**  
contains a User or Team ID  

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerIdType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**means.entityName**  
a string value is the name of a CDM entity.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The type of owner, either User or Team.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.name**  
Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.  

**is.readOnly**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owneridtype"</td><td>string</td><td></td></tr></table>

**is.CDS.owner**  
contains a User or Team ID  

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningBusinessUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Business Unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the business unit that owns the record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/BusinessUnit.md" target="_blank">/core/applicationCommon/BusinessUnit.cdm.json/BusinessUnit</a></td><td><a href="../../../../../core/applicationCommon/BusinessUnit.md#businessUnitId" target="_blank">businessUnitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owningbusinessunit"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning User</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the user that owns the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../core/applicationCommon/User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owninguser"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningTeam attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Team</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the team that owns the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/Team.md" target="_blank">/core/applicationCommon/Team.cdm.json/Team</a></td><td><a href="../../../../../core/applicationCommon/Team.md#teamId" target="_blank">teamId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owningteam"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeZoneRuleVersionNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"timezoneruleversionnumber"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCConversionTimeZoneCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"utcconversiontimezonecode"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the versionNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**means.measurement.version**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"versionnumber"</td><td>string</td><td></td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

</details>

### <a href=#authoredOn name="authoredOn">authoredOn</a>

The date (and perhaps time) when the prescription was initially written or authored on.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Authored On</td></tr><tr><td>description</td><td>The date (and perhaps time) when the prescription was initially written or authored on.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_authoredon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the authoredOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_authoredon"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Authored On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The date (and perhaps time) when the prescription was initially written or authored on.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#categoryId name="categoryId">categoryId</a>

Indicates the type of medication request (for example, where the medication is expected to be consumed or administered or the type of treatment.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Indicates the type of medication request (for example, where the medication is expected to be consumed or administered or the type of treatment.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_category</td></tr></table>

#### Traits

<details>
<summary>List of traits for the categoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates the type of medication request (for example, where the medication is expected to be consumed or administered or the type of treatment.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CodeableConcept.md" target="_blank">/Healthcare/Foundational/Commoncore/CodeableConcept.cdm.json/CodeableConcept</a></td><td><a href="CodeableConcept.md#codeableConceptId" target="_blank">codeableConceptId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_category"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#contextType name="contextType">contextType</a>

A link to an encounter, or episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context Type</td></tr><tr><td>description</td><td>A link to an encounter, or episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Encounter</td><td>935000000</td></tr><tr><td>en</td><td>Episode of Care</td><td>935000001</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the contextType attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Encounter</td><td>935000000</td></tr><tr><td>en</td><td>Episode of Care</td><td>935000001</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_contexttype"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Context Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A link to an encounter, or episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#contextType_display name="contextType_display">contextType_display</a>

First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the contextType_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**means.reference.displayText**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"contextType"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#contextTypeEncounterId name="contextTypeEncounterId">contextTypeEncounterId</a>

A link to an encounter that identifies the particular occurrence or set occurrences of contact between patient and health care provider.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>A link to an encounter that identifies the particular occurrence or set occurrences of contact between patient and health care provider.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttypeencounter</td></tr></table>

#### Traits

<details>
<summary>List of traits for the contextTypeEncounterId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Encounter</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A link to an encounter that identifies the particular occurrence or set occurrences of contact between patient and health care provider.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="Encounter.md" target="_blank">/Healthcare/Foundational/Commoncore/Encounter.cdm.json/Encounter</a></td><td><a href="Encounter.md#encounterId" target="_blank">encounterId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_contexttypeencounter"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#contextTypeEpisodeOfCareId name="contextTypeEpisodeOfCareId">contextTypeEpisodeOfCareId</a>

A link to an episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode of Care</td></tr><tr><td>description</td><td>A link to an episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttypeepisodeofcare</td></tr></table>

#### Traits

<details>
<summary>List of traits for the contextTypeEpisodeOfCareId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Episode of Care</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A link to an episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EpisodeOfCare.md" target="_blank">/Healthcare/Foundational/Commoncore/EpisodeOfCare.cdm.json/EpisodeOfCare</a></td><td><a href="EpisodeOfCare.md#episodeOfCareId" target="_blank">episodeOfCareId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_contexttypeepisodeofcare"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#dispenseRequestNumberOfRepeatsAllowed name="dispenseRequestNumberOfRepeatsAllowed">dispenseRequestNumberOfRepeatsAllowed</a>

An integer indicating the number of times, in addition to the original dispense, (aka refills or repeats) that the patient can receive the prescribed medication.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dispense Request Number of Repeats Allowed</td></tr><tr><td>description</td><td>An integer indicating the number of times, in addition to the original dispense, (aka refills or repeats) that the patient can receive the prescribed medication.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dispenserequestnumberofrepeatsallowed</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dispenseRequestNumberOfRepeatsAllowed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_dispenserequestnumberofrepeatsallowed"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dispense Request Number of Repeats Allowed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>An integer indicating the number of times, in addition to the original dispense, (aka refills or repeats) that the patient can receive the prescribed medication.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#dispenseRequestPerformerId name="dispenseRequestPerformerId">dispenseRequestPerformerId</a>

Indicates the intended dispensing Organization specified by the Prescriber.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performer</td></tr><tr><td>description</td><td>Indicates the intended dispensing Organization specified by the Prescriber.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dispenserequestperformer</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dispenseRequestPerformerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Performer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates the intended dispensing Organization specified by the Prescriber.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/Account.md" target="_blank">/core/applicationCommon/Account.cdm.json/Account</a></td><td><a href="../../../../../core/applicationCommon/Account.md#accountId" target="_blank">accountId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_dispenserequestperformer"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#dispenseRequestQuantity name="dispenseRequestQuantity">dispenseRequestQuantity</a>

The amount that is to be dispensed for one fill.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dispense Request Quantity</td></tr><tr><td>description</td><td>The amount that is to be dispensed for one fill.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dispenserequestquantity</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dispenseRequestQuantity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_dispenserequestquantity"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dispense Request Quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The amount that is to be dispensed for one fill.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#dispenseRequestValidityPeriodEndDate name="dispenseRequestValidityPeriodEndDate">dispenseRequestValidityPeriodEndDate</a>

This indicates the validity period of a prescription (stale dating the Prescription).  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dispense Request Validity Period End Date</td></tr><tr><td>description</td><td>This indicates the validity period of a prescription (stale dating the Prescription).</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dispenserequestvalidityperiodenddate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dispenseRequestValidityPeriodEndDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_dispenserequestvalidityperiodenddate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dispense Request Validity Period End Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>This indicates the validity period of a prescription (stale dating the Prescription).</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#dispenseRequestValidityPeriodStartDate name="dispenseRequestValidityPeriodStartDate">dispenseRequestValidityPeriodStartDate</a>

This indicates the validity period of a prescription (stale dating the Prescription).  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dispense Request Validity Period Start Date</td></tr><tr><td>description</td><td>This indicates the validity period of a prescription (stale dating the Prescription).</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dispenserequestvalidityperiodstartdate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dispenseRequestValidityPeriodStartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_dispenserequestvalidityperiodstartdate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dispense Request Validity Period Start Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>This indicates the validity period of a prescription (stale dating the Prescription).</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#expectedSupplyDuration name="expectedSupplyDuration">expectedSupplyDuration</a>

Identifies the period time over which the supplied product is expected to be used, or the length of time the dispense is expected to last.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Supply Duration</td></tr><tr><td>description</td><td>Identifies the period time over which the supplied product is expected to be used, or the length of time the dispense is expected to last.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_expectedsupplyduration</td></tr></table>

#### Traits

<details>
<summary>List of traits for the expectedSupplyDuration attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_expectedsupplyduration"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-100000000000"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expected Supply Duration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Identifies the period time over which the supplied product is expected to be used, or the length of time the dispense is expected to last.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#groupIdentifier name="groupIdentifier">groupIdentifier</a>

A shared identifier common to all requests that were authorized more or less simultaneously by a single author, representing the identifier of the requisition or prescription.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group Identifier</td></tr><tr><td>description</td><td>A shared identifier common to all requests that were authorized more or less simultaneously by a single author, representing the identifier of the requisition or prescription.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_groupidentifier</td></tr></table>

#### Traits

<details>
<summary>List of traits for the groupIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_groupidentifier"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Group Identifier</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A shared identifier common to all requests that were authorized more or less simultaneously by a single author, representing the identifier of the requisition or prescription.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#identifier name="identifier">identifier</a>

This records identifiers associated with this medication request that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Request Number</td></tr><tr><td>description</td><td>This records identifiers associated with this medication request that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_identifier</td></tr></table>

#### Traits

<details>
<summary>List of traits for the identifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_identifier"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Medication Request Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>This records identifiers associated with this medication request that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#intent name="intent">intent</a>

Whether the request is a proposal, plan, or an original order.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Intent</td></tr><tr><td>description</td><td>Whether the request is a proposal, plan, or an original order.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_intent</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the intent attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Proposal</td><td>935000000</td></tr><tr><td>en</td><td>Plan</td><td>935000001</td></tr><tr><td>en</td><td>Order</td><td>935000002</td></tr><tr><td>en</td><td>Instance Order</td><td>935000003</td></tr><tr><td>en</td><td>Original-Order</td><td>645490001</td></tr><tr><td>en</td><td>Reflect-Order</td><td>645490002</td></tr><tr><td>en</td><td>Option</td><td>645490003</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_intent"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intent</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Whether the request is a proposal, plan, or an original order.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#intent_display name="intent_display">intent_display</a>

First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the intent_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**means.reference.displayText**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"intent"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#medicationReferenceNewId name="medicationReferenceNewId">medicationReferenceNewId</a>

First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Reference</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_medicationreferencenew</td></tr></table>

#### Traits

<details>
<summary>List of traits for the medicationReferenceNewId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Medication Reference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="Medication.md" target="_blank">/Healthcare/Foundational/Commoncore/Medication.cdm.json/Medication</a></td><td><a href="Medication.md#medicationId" target="_blank">medicationId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_medicationreferencenew"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#medicationRequestId name="medicationRequestId">medicationRequestId</a>

Unique identifier for entity instances  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Request</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>sourceName</td><td>msemr_medicationrequestid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the medicationRequestId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MedicationRequest/(resolvedAttributes)/medicationRequestId](#medicationRequestId)</td><td>attribute</td><td></td></tr></table>

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_medicationrequestid"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Medication Request</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for entity instances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#medicationType name="medicationType">medicationType</a>

Identifies the medication being requested.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Type</td></tr><tr><td>description</td><td>Identifies the medication being requested.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_medicationtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the medicationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Medication Code</td><td>935000000</td></tr><tr><td>en</td><td>Medication Reference</td><td>935000001</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_medicationtype"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Medication Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Identifies the medication being requested.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#medicationType_display name="medicationType_display">medicationType_display</a>

First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the medicationType_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**means.reference.displayText**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"medicationType"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#medicationTypeCodeableConceptId name="medicationTypeCodeableConceptId">medicationTypeCodeableConceptId</a>

Identifies the medication being requested.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Code</td></tr><tr><td>description</td><td>Identifies the medication being requested.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_medicationtypecodeableconcept</td></tr></table>

#### Traits

<details>
<summary>List of traits for the medicationTypeCodeableConceptId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Medication Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Identifies the medication being requested.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CodeableConcept.md" target="_blank">/Healthcare/Foundational/Commoncore/CodeableConcept.cdm.json/CodeableConcept</a></td><td><a href="CodeableConcept.md#codeableConceptId" target="_blank">codeableConceptId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_medicationtypecodeableconcept"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**means.identity.name**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_name"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the custom entity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#priority name="priority">priority</a>

Indicates how quickly the Medication Request should be addressed with respect to other requests.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Indicates how quickly the Medication Request should be addressed with respect to other requests.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_priority</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the priority attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Routine</td><td>935000000</td></tr><tr><td>en</td><td>Urgent</td><td>935000001</td></tr><tr><td>en</td><td>Stat</td><td>935000002</td></tr><tr><td>en</td><td>ASAP</td><td>935000003</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_priority"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Priority</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates how quickly the Medication Request should be addressed with respect to other requests.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#priority_display name="priority_display">priority_display</a>

First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the priority_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**means.reference.displayText**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"priority"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#priorPrescriptionId name="priorPrescriptionId">priorPrescriptionId</a>

A link to a resource representing an earlier order related order or prescription.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prior Prescription</td></tr><tr><td>description</td><td>A link to a resource representing an earlier order related order or prescription.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_priorprescription</td></tr></table>

#### Traits

<details>
<summary>List of traits for the priorPrescriptionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prior Prescription</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A link to a resource representing an earlier order related order or prescription.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="MedicationRequest.md" target="_blank">/Healthcare/Foundational/Commoncore/MedicationRequest.cdm.json/MedicationRequest</a></td><td><a href="MedicationRequest.md#medicationRequestId" target="_blank">medicationRequestId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_priorprescription"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#recorderId name="recorderId">recorderId</a>

The person who entered the order on behalf of another individual for example in the case of a verbal or a telephone order.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recorder</td></tr><tr><td>description</td><td>The person who entered the order on behalf of another individual for example in the case of a verbal or a telephone order.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_recorder</td></tr></table>

#### Traits

<details>
<summary>List of traits for the recorderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Recorder</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The person who entered the order on behalf of another individual for example in the case of a verbal or a telephone order.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/Contact.md" target="_blank">/core/applicationCommon/Contact.cdm.json/Contact</a></td><td><a href="../../../../../core/applicationCommon/Contact.md#contactId" target="_blank">contactId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_recorder"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#requesterAgentType name="requesterAgentType">requesterAgentType</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester Agent Type</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the requesterAgentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Practitioner</td><td>935000000</td></tr><tr><td>en</td><td>Organization</td><td>935000001</td></tr><tr><td>en</td><td>Patient</td><td>935000002</td></tr><tr><td>en</td><td>Related Person</td><td>935000003</td></tr><tr><td>en</td><td>Device</td><td>935000004</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_requesteragenttype"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requester Agent Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#requesterAgentType_display name="requesterAgentType_display">requesterAgentType_display</a>

First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the requesterAgentType_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**means.reference.displayText**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"requesterAgentType"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#requesterAgentTypeDeviceId name="requesterAgentTypeDeviceId">requesterAgentTypeDeviceId</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttypedevice</td></tr></table>

#### Traits

<details>
<summary>List of traits for the requesterAgentTypeDeviceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Device</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="Device.md" target="_blank">/Healthcare/Foundational/Commoncore/Device.cdm.json/Device</a></td><td><a href="Device.md#deviceId" target="_blank">deviceId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_requesteragenttypedevice"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#requesterAgentTypeOrganizationId name="requesterAgentTypeOrganizationId">requesterAgentTypeOrganizationId</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttypeorganization</td></tr></table>

#### Traits

<details>
<summary>List of traits for the requesterAgentTypeOrganizationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organization</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/Account.md" target="_blank">/core/applicationCommon/Account.cdm.json/Account</a></td><td><a href="../../../../../core/applicationCommon/Account.md#accountId" target="_blank">accountId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_requesteragenttypeorganization"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#requesterAgentTypePatientId name="requesterAgentTypePatientId">requesterAgentTypePatientId</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester Agent (Patient)</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttypepatient</td></tr></table>

#### Traits

<details>
<summary>List of traits for the requesterAgentTypePatientId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requester Agent (Patient)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/Contact.md" target="_blank">/core/applicationCommon/Contact.cdm.json/Contact</a></td><td><a href="../../../../../core/applicationCommon/Contact.md#contactId" target="_blank">contactId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_requesteragenttypepatient"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#requesterAgentTypePractitionerId name="requesterAgentTypePractitionerId">requesterAgentTypePractitionerId</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Practitoner</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttypepractitioner</td></tr></table>

#### Traits

<details>
<summary>List of traits for the requesterAgentTypePractitionerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Practitoner</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/Contact.md" target="_blank">/core/applicationCommon/Contact.cdm.json/Contact</a></td><td><a href="../../../../../core/applicationCommon/Contact.md#contactId" target="_blank">contactId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_requesteragenttypepractitioner"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#requesterAgentTypeRelatedPersonId name="requesterAgentTypeRelatedPersonId">requesterAgentTypeRelatedPersonId</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related Person</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttyperelatedperson</td></tr></table>

#### Traits

<details>
<summary>List of traits for the requesterAgentTypeRelatedPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Related Person</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/Contact.md" target="_blank">/core/applicationCommon/Contact.cdm.json/Contact</a></td><td><a href="../../../../../core/applicationCommon/Contact.md#contactId" target="_blank">contactId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_requesteragenttyperelatedperson"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#requesterOnBehalfOfId name="requesterOnBehalfOfId">requesterOnBehalfOfId</a>

The organization the device or practitioner was acting on behalf of.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Behalf Of</td></tr><tr><td>description</td><td>The organization the device or practitioner was acting on behalf of.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteronbehalfof</td></tr></table>

#### Traits

<details>
<summary>List of traits for the requesterOnBehalfOfId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>On Behalf Of</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The organization the device or practitioner was acting on behalf of.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/Account.md" target="_blank">/core/applicationCommon/Account.cdm.json/Account</a></td><td><a href="../../../../../core/applicationCommon/Account.md#accountId" target="_blank">accountId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_requesteronbehalfof"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#status name="status">status</a>

A code specifying the current state of the order. Generally, this will be active or completed state.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>A code specifying the current state of the order. Generally, this will be active or completed state.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the status attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>935000000</td></tr><tr><td>en</td><td>On Hold</td><td>935000001</td></tr><tr><td>en</td><td>Cancelled</td><td>935000002</td></tr><tr><td>en</td><td>Completed</td><td>935000003</td></tr><tr><td>en</td><td>Entered In Error</td><td>935000004</td></tr><tr><td>en</td><td>Stopped</td><td>935000005</td></tr><tr><td>en</td><td>Draft</td><td>935000006</td></tr><tr><td>en</td><td>Unknown</td><td>935000007</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_status"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A code specifying the current state of the order. Generally, this will be active or completed state.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#status_display name="status_display">status_display</a>

First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the status_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**means.reference.displayText**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"status"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#subjectType name="subjectType">subjectType</a>

A link to a resource representing the person or set of individuals to whom the medication will be given.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject Type</td></tr><tr><td>description</td><td>A link to a resource representing the person or set of individuals to whom the medication will be given.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the subjectType attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Device</td><td>935000002</td></tr><tr><td>en</td><td>Group</td><td>935000001</td></tr><tr><td>en</td><td>Location</td><td>935000003</td></tr><tr><td>en</td><td>Patient</td><td>935000000</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_subjecttype"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subject Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A link to a resource representing the person or set of individuals to whom the medication will be given.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#subjectType_display name="subjectType_display">subjectType_display</a>

First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the subjectType_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**means.reference.displayText**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"subjectType"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#subjectTypeGroupId name="subjectTypeGroupId">subjectTypeGroupId</a>

A link to a resource representing the person or set of individuals to whom the medication will be given.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>description</td><td>A link to a resource representing the person or set of individuals to whom the medication will be given.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypegroup</td></tr></table>

#### Traits

<details>
<summary>List of traits for the subjectTypeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A link to a resource representing the person or set of individuals to whom the medication will be given.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CodeableConcept.md" target="_blank">/Healthcare/Foundational/Commoncore/CodeableConcept.cdm.json/CodeableConcept</a></td><td><a href="CodeableConcept.md#codeableConceptId" target="_blank">codeableConceptId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_subjecttypegroup"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#subjectTypePatientId name="subjectTypePatientId">subjectTypePatientId</a>

A link to a resource representing the person or set of individuals to whom the medication will be given.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject Type (Patient)</td></tr><tr><td>description</td><td>A link to a resource representing the person or set of individuals to whom the medication will be given.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypepatient</td></tr></table>

#### Traits

<details>
<summary>List of traits for the subjectTypePatientId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subject Type (Patient)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A link to a resource representing the person or set of individuals to whom the medication will be given.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../core/applicationCommon/Contact.md" target="_blank">/core/applicationCommon/Contact.cdm.json/Contact</a></td><td><a href="../../../../../core/applicationCommon/Contact.md#contactId" target="_blank">contactId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_subjecttypepatient"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#substitutionAllowed name="substitutionAllowed">substitutionAllowed</a>

True if the Prescriber allows a different drug to be dispensed from what was prescribed.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Substitution Allowed</td></tr><tr><td>description</td><td>True if the Prescriber allows a different drug to be dispensed from what was prescribed.</td></tr><tr><td>dataFormat</td><td>boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_substitutionallowed</td></tr></table>

#### Traits

<details>
<summary>List of traits for the substitutionAllowed attribute are listed below.</summary>

**is.dataFormat.boolean**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_substitutionallowed"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Substitution Allowed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>True if the Prescriber allows a different drug to be dispensed from what was prescribed.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.boolean**  
</details>

### <a href=#substitutionReasonId name="substitutionReasonId">substitutionReasonId</a>

Indicates the reason for the substitution, or why substitution must or must not be performed.  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Substitution Reason</td></tr><tr><td>description</td><td>Indicates the reason for the substitution, or why substitution must or must not be performed.</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_substitutionreason</td></tr></table>

#### Traits

<details>
<summary>List of traits for the substitutionReasonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Substitution Reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates the reason for the substitution, or why substitution must or must not be performed.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CodeableConcept.md" target="_blank">/Healthcare/Foundational/Commoncore/CodeableConcept.cdm.json/CodeableConcept</a></td><td><a href="CodeableConcept.md#codeableConceptId" target="_blank">codeableConceptId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msemr_substitutionreason"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Medication Request  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Medication Request</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**means.entityState**  
the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MedicationRequest/(resolvedAttributes)/stateCode](#stateCode)</td><td>attribute</td><td></td></tr></table>

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statecode"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status of the Medication Request</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"stateCode"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Medication Request  
First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Medication Request</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.correlatedWith**  
the attribute value is correlated with the sourceAttribute  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>"stateCode"</td><td>attributeName</td><td></td></tr></table>

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statuscode"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status Reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason for the status of the Medication Request</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: Commoncore/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

**means.reference.displayText**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"statusCode"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

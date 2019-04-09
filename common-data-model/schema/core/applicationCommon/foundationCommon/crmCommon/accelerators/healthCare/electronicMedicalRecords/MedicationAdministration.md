---
title: MedicationAdministration - Common Data Model | Microsoft Docs
description: Describes the event of a patient consuming or otherwise being administered a medication.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Medication Administration

Describes the event of a patient consuming or otherwise being administered a medication.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/MedicationAdministration.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/MedicationAdministration  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[ownerId](#ownerId)|Owner Id|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[medicationAdministrationId](#medicationAdministrationId)|Unique identifier for entity instances|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[stateCode](#stateCode)|Status of the Medication Administration|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[stateCode_display](#stateCode_display)||<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[statusCode](#statusCode)|Reason for the status of the Medication Administration|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[statusCode_display](#statusCode_display)||<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[name](#name)|The name of the custom entity.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[category](#category)|Indicates the type of medication administration and where the medication is expected to be consumed or administered.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[contextType](#contextType)|The visit, admission or other contact between patient and health care provider the medication administration was performed as part of.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[contextType_display](#contextType_display)||<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[contextTypeEncounter](#contextTypeEncounter)|The visit, admission or other contact between patient and health care provider the medication administration was performed as part of.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[contextTypeEpisodeOfCare](#contextTypeEpisodeOfCare)|The visit, admission or other contact between patient and health care provider the medication administration was performed as part of.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[dosageDose](#dosageDose)|The amount of the medication given at one administration event. Use this value when the administration is essentially an instantaneous event such as a swallowing a tablet or giving an injection.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[dosageMethod](#dosageMethod)|A coded value indicating the method by which the medication is intended to be or was introduced into or on the body. This attribute will most often NOT be populated.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[dosageRateQuantity](#dosageRateQuantity)|Identifies the speed with which the medication was or will be introduced into the patient.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[dosageRateType](#dosageRateType)|Identifies the speed with which the medication was or will be introduced into the patient. Typically the rate for an infusion e.g. 100 ml per 1 hour or 100 ml/hr.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[dosageRateType_display](#dosageRateType_display)||<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[dosageRoute](#dosageRoute)|A code specifying the route or physiological path of administration of a therapeutic agent into or onto the patient. For example, topical, intravenous, etc.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[dosageSite](#dosageSite)|A coded specification of the anatomic site where the medication first entered the body. For example, "left arm".|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[dosageText](#dosageText)|"Free text dosage can be used for cases where the dosage administered is too complex to code. When coded dosage is present, the free text dosage may still be present for display to humans.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[effectiveDatetime](#effectiveDatetime)|A specific date/time or interval of time during which the administration took place (or did not take place, when the 'notGiven' attribute is true).|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[effectivePeriodEndDate](#effectivePeriodEndDate)|A specific date/time or interval of time during which the administration took place|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[effectivePeriodStartDate](#effectivePeriodStartDate)|A specific date/time or interval of time during which the administration took place|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[effectiveType](#effectiveType)|A specific date/time or interval of time during which the administration took place (or did not take place, when the 'notGiven' attribute is true).|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[effectiveType_display](#effectiveType_display)||<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[medicationAdministrationNumber](#medicationAdministrationNumber)|External identifier - FHIR will generate its own internal identifiers (probably URLs) which do not need to be explicitly managed by the resource.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[medicationCodeableConcept](#medicationCodeableConcept)|Identifies the medication that was administered.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[medicationReference](#medicationReference)|A specific date/time or interval of time during which the administration took place|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[medicationType](#medicationType)|Identifies the medication that was administered.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[medicationType_display](#medicationType_display)||<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[notGiven](#notGiven)|Set this to true if the record is saying that the medication was NOT administered.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[prescription](#prescription)|The original request, instruction or authority to perform the administration.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[rateRatioQuantityDenominatorComparator](#rateRatioQuantityDenominatorComparator)|How the value should be understood and represented|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[rateRatioQuantityDenominatorComparator_display](#rateRatioQuantityDenominatorComparator_display)||<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[rateRatioQuantityDenominatorUnit](#rateRatioQuantityDenominatorUnit)|A human-readable form of the unit.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[rateRatioQuantityDenominatorValue](#rateRatioQuantityDenominatorValue)|The value of the measured amount. The value includes an implicit precision in the presentation of the value.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[rateRatioQuantityNumeratorCode](#rateRatioQuantityNumeratorCode)|A computer processable form of the unit in some unit representation system.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[rateRatioQuantityNumeratorComparator](#rateRatioQuantityNumeratorComparator)|How the value should be understood and represented|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[rateRatioQuantityNumeratorComparator_display](#rateRatioQuantityNumeratorComparator_display)||<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[rateRatioQuantityNumeratorSystem](#rateRatioQuantityNumeratorSystem)|The identification of the system that provides the coded form of the unit.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[rateRatioQuantityNumeratorUnit](#rateRatioQuantityNumeratorUnit)|A human-readable form of the unit.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[rateRatioQuantityNumeratorValue](#rateRatioQuantityNumeratorValue)|The value of the measured amount. The value includes an implicit precision in the presentation of the value.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[rateRatiotQuantityDenominatorSystem](#rateRatiotQuantityDenominatorSystem)|The identification of the system that provides the coded form of the unit.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[ratioDenominatorCode](#ratioDenominatorCode)|A computer processable form of the unit in some unit representation system.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[status](#status)|Will generally be set to show that the administration has been completed.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[status_display](#status_display)||<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[subjectType](#subjectType)|The person or animal or group receiving the medication.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[subjectType_display](#subjectType_display)||<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[subjectTypeGroup](#subjectTypeGroup)|The group receiving the medication.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|
|[subjectTypePatient](#subjectTypePatient)|he person receiving the medication.|<a href="MedicationAdministration.md" target="_blank">electronicMedicalRecords/MedicationAdministration</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#medicationAdministrationId name="medicationAdministrationId">medicationAdministrationId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Administration</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_medicationadministrationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Medication Administration  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Medication Administration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Medication Administration  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Medication Administration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#category name="category">category</a>

Indicates the type of medication administration and where the medication is expected to be consumed or administered.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Indicates the type of medication administration and where the medication is expected to be consumed or administered.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_category</td></tr></table>

### <a href=#contextType name="contextType">contextType</a>

The visit, admission or other contact between patient and health care provider the medication administration was performed as part of.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context Type</td></tr><tr><td>description</td><td>The visit, admission or other contact between patient and health care provider the medication administration was performed as part of.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Encounter</td><td>935000000</td></tr><tr><td>en</td><td>Episode Of Care</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#contextType_display name="contextType_display">contextType_display</a>

First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#contextTypeEncounter name="contextTypeEncounter">contextTypeEncounter</a>

The visit, admission or other contact between patient and health care provider the medication administration was performed as part of.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>The visit, admission or other contact between patient and health care provider the medication administration was performed as part of.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttypeencounter</td></tr></table>

### <a href=#contextTypeEpisodeOfCare name="contextTypeEpisodeOfCare">contextTypeEpisodeOfCare</a>

The visit, admission or other contact between patient and health care provider the medication administration was performed as part of.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode Of Care</td></tr><tr><td>description</td><td>The visit, admission or other contact between patient and health care provider the medication administration was performed as part of.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttypeepisodeofcare</td></tr></table>

### <a href=#dosageDose name="dosageDose">dosageDose</a>

The amount of the medication given at one administration event. Use this value when the administration is essentially an instantaneous event such as a swallowing a tablet or giving an injection.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dosage Dose</td></tr><tr><td>description</td><td>The amount of the medication given at one administration event. Use this value when the administration is essentially an instantaneous event such as a swallowing a tablet or giving an injection.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dosagedose</td></tr></table>

### <a href=#dosageMethod name="dosageMethod">dosageMethod</a>

A coded value indicating the method by which the medication is intended to be or was introduced into or on the body. This attribute will most often NOT be populated.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dosage Method</td></tr><tr><td>description</td><td>A coded value indicating the method by which the medication is intended to be or was introduced into or on the body. This attribute will most often NOT be populated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dosagemethod</td></tr></table>

### <a href=#dosageRateQuantity name="dosageRateQuantity">dosageRateQuantity</a>

Identifies the speed with which the medication was or will be introduced into the patient.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dosage Quantity</td></tr><tr><td>description</td><td>Identifies the speed with which the medication was or will be introduced into the patient.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dosageratequantity</td></tr></table>

### <a href=#dosageRateType name="dosageRateType">dosageRateType</a>

Identifies the speed with which the medication was or will be introduced into the patient. Typically the rate for an infusion e.g. 100 ml per 1 hour or 100 ml/hr.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dosage Rate Type</td></tr><tr><td>description</td><td>Identifies the speed with which the medication was or will be introduced into the patient. Typically the rate for an infusion e.g. 100 ml per 1 hour or 100 ml/hr.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dosageratetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Ratio</td><td>935000000</td></tr><tr><td>en</td><td>Quantity</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#dosageRateType_display name="dosageRateType_display">dosageRateType_display</a>

First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#dosageRoute name="dosageRoute">dosageRoute</a>

A code specifying the route or physiological path of administration of a therapeutic agent into or onto the patient. For example, topical, intravenous, etc.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dosage Route</td></tr><tr><td>description</td><td>A code specifying the route or physiological path of administration of a therapeutic agent into or onto the patient. For example, topical, intravenous, etc.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dosageroute</td></tr></table>

### <a href=#dosageSite name="dosageSite">dosageSite</a>

A coded specification of the anatomic site where the medication first entered the body. For example, "left arm".  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dosage Site</td></tr><tr><td>description</td><td>A coded specification of the anatomic site where the medication first entered the body. For example, "left arm".</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dosagesite</td></tr></table>

### <a href=#dosageText name="dosageText">dosageText</a>

"Free text dosage can be used for cases where the dosage administered is too complex to code. When coded dosage is present, the free text dosage may still be present for display to humans.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dosage Text</td></tr><tr><td>description</td><td>"Free text dosage can be used for cases where the dosage administered is too complex to code. When coded dosage is present, the free text dosage may still be present for display to humans.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dosagetext</td></tr></table>

### <a href=#effectiveDatetime name="effectiveDatetime">effectiveDatetime</a>

A specific date/time or interval of time during which the administration took place (or did not take place, when the 'notGiven' attribute is true).  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective Date time</td></tr><tr><td>description</td><td>A specific date/time or interval of time during which the administration took place (or did not take place, when the 'notGiven' attribute is true).</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_effectivedatetime</td></tr></table>

### <a href=#effectivePeriodEndDate name="effectivePeriodEndDate">effectivePeriodEndDate</a>

A specific date/time or interval of time during which the administration took place  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective Period End Date</td></tr><tr><td>description</td><td>A specific date/time or interval of time during which the administration took place</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_effectiveperiodenddate</td></tr></table>

### <a href=#effectivePeriodStartDate name="effectivePeriodStartDate">effectivePeriodStartDate</a>

A specific date/time or interval of time during which the administration took place  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective Period Start Date</td></tr><tr><td>description</td><td>A specific date/time or interval of time during which the administration took place</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_effectiveperiodstartdate</td></tr></table>

### <a href=#effectiveType name="effectiveType">effectiveType</a>

A specific date/time or interval of time during which the administration took place (or did not take place, when the 'notGiven' attribute is true).  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective Type</td></tr><tr><td>description</td><td>A specific date/time or interval of time during which the administration took place (or did not take place, when the 'notGiven' attribute is true).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_effectivetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Date time</td><td>935000000</td></tr><tr><td>en</td><td>Period</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#effectiveType_display name="effectiveType_display">effectiveType_display</a>

First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#medicationAdministrationNumber name="medicationAdministrationNumber">medicationAdministrationNumber</a>

External identifier - FHIR will generate its own internal identifiers (probably URLs) which do not need to be explicitly managed by the resource.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Administration Number</td></tr><tr><td>description</td><td>External identifier - FHIR will generate its own internal identifiers (probably URLs) which do not need to be explicitly managed by the resource.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_medicationadministrationnumber</td></tr></table>

### <a href=#medicationCodeableConcept name="medicationCodeableConcept">medicationCodeableConcept</a>

Identifies the medication that was administered.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Codeable Concept</td></tr><tr><td>description</td><td>Identifies the medication that was administered.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_medicationcodeableconcept</td></tr></table>

### <a href=#medicationReference name="medicationReference">medicationReference</a>

A specific date/time or interval of time during which the administration took place  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Reference</td></tr><tr><td>description</td><td>A specific date/time or interval of time during which the administration took place</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_medicationreference</td></tr></table>

### <a href=#medicationType name="medicationType">medicationType</a>

Identifies the medication that was administered.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Type</td></tr><tr><td>description</td><td>Identifies the medication that was administered.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_medicationtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Codeable Concept</td><td>935000000</td></tr><tr><td>en</td><td>Reference</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#medicationType_display name="medicationType_display">medicationType_display</a>

First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#notGiven name="notGiven">notGiven</a>

Set this to true if the record is saying that the medication was NOT administered.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not Given</td></tr><tr><td>description</td><td>Set this to true if the record is saying that the medication was NOT administered.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_notgiven</td></tr></table>

### <a href=#prescription name="prescription">prescription</a>

The original request, instruction or authority to perform the administration.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prescription</td></tr><tr><td>description</td><td>The original request, instruction or authority to perform the administration.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_prescription</td></tr></table>

### <a href=#rateRatioQuantityDenominatorComparator name="rateRatioQuantityDenominatorComparator">rateRatioQuantityDenominatorComparator</a>

How the value should be understood and represented  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Denominator Comparator</td></tr><tr><td>description</td><td>How the value should be understood and represented</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_rateratioquantitydenominatorcomparator</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td><</td><td>935000000</td></tr><tr><td>en</td><td><=</td><td>935000001</td></tr><tr><td>en</td><td>>=</td><td>935000002</td></tr><tr><td>en</td><td>></td><td>935000003</td></tr></table></td></tr></table>

### <a href=#rateRatioQuantityDenominatorComparator_display name="rateRatioQuantityDenominatorComparator_display">rateRatioQuantityDenominatorComparator_display</a>

First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#rateRatioQuantityDenominatorUnit name="rateRatioQuantityDenominatorUnit">rateRatioQuantityDenominatorUnit</a>

A human-readable form of the unit.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Denominator Unit</td></tr><tr><td>description</td><td>A human-readable form of the unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_rateratioquantitydenominatorunit</td></tr></table>

### <a href=#rateRatioQuantityDenominatorValue name="rateRatioQuantityDenominatorValue">rateRatioQuantityDenominatorValue</a>

The value of the measured amount. The value includes an implicit precision in the presentation of the value.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Denominator Value</td></tr><tr><td>description</td><td>The value of the measured amount. The value includes an implicit precision in the presentation of the value.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_rateratioquantitydenominatorvalue</td></tr></table>

### <a href=#rateRatioQuantityNumeratorCode name="rateRatioQuantityNumeratorCode">rateRatioQuantityNumeratorCode</a>

A computer processable form of the unit in some unit representation system.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Numerator Code</td></tr><tr><td>description</td><td>A computer processable form of the unit in some unit representation system.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_rateratioquantitynumeratorcode</td></tr></table>

### <a href=#rateRatioQuantityNumeratorComparator name="rateRatioQuantityNumeratorComparator">rateRatioQuantityNumeratorComparator</a>

How the value should be understood and represented  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Numerator Comparator</td></tr><tr><td>description</td><td>How the value should be understood and represented</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_rateratioquantitynumeratorcomparator</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td><</td><td>935000000</td></tr><tr><td>en</td><td><=</td><td>935000001</td></tr><tr><td>en</td><td>>=</td><td>935000002</td></tr><tr><td>en</td><td>></td><td>935000003</td></tr></table></td></tr></table>

### <a href=#rateRatioQuantityNumeratorComparator_display name="rateRatioQuantityNumeratorComparator_display">rateRatioQuantityNumeratorComparator_display</a>

First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#rateRatioQuantityNumeratorSystem name="rateRatioQuantityNumeratorSystem">rateRatioQuantityNumeratorSystem</a>

The identification of the system that provides the coded form of the unit.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Numerator System</td></tr><tr><td>description</td><td>The identification of the system that provides the coded form of the unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_rateratioquantitynumeratorsystem</td></tr></table>

### <a href=#rateRatioQuantityNumeratorUnit name="rateRatioQuantityNumeratorUnit">rateRatioQuantityNumeratorUnit</a>

A human-readable form of the unit.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Numerator Unit</td></tr><tr><td>description</td><td>A human-readable form of the unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_rateratioquantitynumeratorunit</td></tr></table>

### <a href=#rateRatioQuantityNumeratorValue name="rateRatioQuantityNumeratorValue">rateRatioQuantityNumeratorValue</a>

The value of the measured amount. The value includes an implicit precision in the presentation of the value.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Numerator Value</td></tr><tr><td>description</td><td>The value of the measured amount. The value includes an implicit precision in the presentation of the value.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_rateratioquantitynumeratorvalue</td></tr></table>

### <a href=#rateRatiotQuantityDenominatorSystem name="rateRatiotQuantityDenominatorSystem">rateRatiotQuantityDenominatorSystem</a>

The identification of the system that provides the coded form of the unit.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Denominator System</td></tr><tr><td>description</td><td>The identification of the system that provides the coded form of the unit.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_rateratiotquantitydenominatorsystem</td></tr></table>

### <a href=#ratioDenominatorCode name="ratioDenominatorCode">ratioDenominatorCode</a>

A computer processable form of the unit in some unit representation system.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Denominator Code</td></tr><tr><td>description</td><td>A computer processable form of the unit in some unit representation system.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_ratiodenominatorcode</td></tr></table>

### <a href=#status name="status">status</a>

Will generally be set to show that the administration has been completed.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Will generally be set to show that the administration has been completed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>In Progress</td><td>935000000</td></tr><tr><td>en</td><td>On Hold</td><td>935000001</td></tr><tr><td>en</td><td>Completed</td><td>935000002</td></tr><tr><td>en</td><td>Entered in Error</td><td>935000003</td></tr><tr><td>en</td><td>Item</td><td>935000004</td></tr><tr><td>en</td><td>Stopped</td><td>935000005</td></tr><tr><td>en</td><td>Unknown</td><td>935000006</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectType name="subjectType">subjectType</a>

The person or animal or group receiving the medication.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject Type</td></tr><tr><td>description</td><td>The person or animal or group receiving the medication.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Patient</td><td>935000000</td></tr><tr><td>en</td><td>Group</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#subjectType_display name="subjectType_display">subjectType_display</a>

First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectTypeGroup name="subjectTypeGroup">subjectTypeGroup</a>

The group receiving the medication.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>description</td><td>The group receiving the medication.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypegroup</td></tr></table>

### <a href=#subjectTypePatient name="subjectTypePatient">subjectTypePatient</a>

he person receiving the medication.  
First included in: electronicMedicalRecords/MedicationAdministration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>he person receiving the medication.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypepatient</td></tr></table>

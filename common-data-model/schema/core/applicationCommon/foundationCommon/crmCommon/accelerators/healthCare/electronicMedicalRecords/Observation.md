---
title: Observation - Common Data Model | Microsoft Docs
description: Measurements and simple assertions made about a patient, device or other subject.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Observation

Measurements and simple assertions made about a patient, device or other subject.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Observation.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Observation  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[observationId](#observationId)|Unique identifier for entity instances|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[stateCode](#stateCode)|Status of the Observation|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[stateCode_display](#stateCode_display)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[statusCode](#statusCode)|Reason for the status of the Observation|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[statusCode_display](#statusCode_display)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[description](#description)|The name of the custom entity.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[bodySite](#bodySite)|Indicates the site on the subject's body where the observation was made (i.e. the target site).|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[code](#code)|Describes what was observed. Sometimes this is called the observation "name".|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[comment](#comment)|May include statements about significant, unexpected or unreliable values, or information about the source of the value where this may be relevant to the interpretation of the result.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[conextTypeEncounter](#conextTypeEncounter)|The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[conextTypeEpisodeOfCare](#conextTypeEpisodeOfCare)|The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[contextType](#contextType)|The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[contextType_display](#contextType_display)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[dataAbsentReason](#dataAbsentReason)|Provides a reason why the expected value in the element Observation.value[x] is missing.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[device](#device)|The device whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[deviceType](#deviceType)|The device used to generate the observation data.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[deviceType_display](#deviceType_display)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[deviceTypeDevice](#deviceTypeDevice)|The device used to generate the observation data.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[deviceTypeDeviceMetric](#deviceTypeDeviceMetric)|The device  metric used to generate the observation data.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[effectiveEnd](#effectiveEnd)|The  End time-period the observed value is asserted as being true. For biological subjects|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[effectiveStart](#effectiveStart)|The start time-period the observed value is asserted as being true. For biological subjects|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[effectiveType](#effectiveType)|Clinically relevant time/time-period for observation.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[effectiveType_display](#effectiveType_display)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[effectiveTypeDateTime](#effectiveTypeDateTime)|Enable this field if the Effective type field is Date time.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[episodeOfCare](#episodeOfCare)|The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[identifier](#identifier)|A unique identifier assigned to this observation.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[interpretation](#interpretation)|The assessment made based on the result of the observation. Intended as a simple compact code often placed adjacent to the result value in reports and flow sheets to signal the meaning/normalcy status|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[issuedDate](#issuedDate)|The date and time this observation was made available to providers, typically after the results have been reviewed and verified.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[method](#method)|Indicates the mechanism used to perform the observation.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[observationNumber](#observationNumber)|A unique identifier assigned to this observation.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[specimen](#specimen)|The specimen that was used when this observation was made.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[status](#status)|The status of the result value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[status_display](#status_display)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[subjectType](#subjectType)|The patient, or group of patients, location, or device whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[subjectType_display](#subjectType_display)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[subjectTypeDevice](#subjectTypeDevice)|The  device whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[subjectTypeGroup](#subjectTypeGroup)|The group whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[subjectTypeLocation](#subjectTypeLocation)|The location whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[subjectTypePatient](#subjectTypePatient)|The patient whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueBoolean](#valueBoolean)|The boolean information determined as a result of making the observation, if the information has a simple value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueCodeableConcept](#valueCodeableConcept)|The codeable concept information determined as a result of making the observation, if the information has a simple value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueDateType](#valueDateType)|The date and time  information determined as a result of making the observation, if the information has a simple value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valuePeriodEndDate](#valuePeriodEndDate)|The period end date information determined as a result of making the observation, if the information has a simple value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valuePeriodStartDate](#valuePeriodStartDate)|The period start date information determined as a result of making the observation, if the information has a simple value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueQuantityCode](#valueQuantityCode)|Coded form of the unit.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueQuantitySystem](#valueQuantitySystem)|System that defines coded unit form.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueQuantityUnit](#valueQuantityUnit)|Unit representation.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRangeHighLimit](#valueRangeHighLimit)|The value high range information determined as a result of making the observation, if the information has a simple value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRangeLowLimit](#valueRangeLowLimit)|The range low value information determined as a result of making the observation, if the information has a simple value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRatioDenominatorCode](#valueRatioDenominatorCode)|The denominator code information determined as a result of making the observation, if the information has a simple value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRatioDenominatorComparator](#valueRatioDenominatorComparator)|The denominator comparator information determined as a result of making the observation, if the information has a simple value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRatioDenominatorComparator_display](#valueRatioDenominatorComparator_display)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueratioDenominatorSystem](#valueratioDenominatorSystem)|The denominator system information determined as a result of making the observation, if the information has a simple value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRatioDenominatorUnit](#valueRatioDenominatorUnit)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueratioDenominatorvalue](#valueratioDenominatorvalue)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRatioNumeratorCode](#valueRatioNumeratorCode)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRatioNumeratorComparator](#valueRatioNumeratorComparator)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRatioNumeratorComparator_display](#valueRatioNumeratorComparator_display)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRatioNumeratorSystem](#valueRatioNumeratorSystem)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRatioNumeratorUnit](#valueRatioNumeratorUnit)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueRatioNumeratorValue](#valueRatioNumeratorValue)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueSampledDataTypeData](#valueSampledDataTypeData)|Decimal values with spaces, or "E" | "U" | "L"|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueSampledDataTypeDimension](#valueSampledDataTypeDimension)|Number of sample points at each time point.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueSampledDataTypeFactor](#valueSampledDataTypeFactor)|Multiply data by this before adding to origin.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueSampledDataTypeLowerLimit](#valueSampledDataTypeLowerLimit)|Lower limit of detection|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueSampledDataTypeOrigin](#valueSampledDataTypeOrigin)|Zero value and units.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueSampledDataTypePeriod](#valueSampledDataTypePeriod)|Number of milliseconds between samples.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueSampledDataTypeUpperLimit](#valueSampledDataTypeUpperLimit)|Upper limit of detection.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueString](#valueString)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueType](#valueType)|The information determined as a result of making the observation, if the information has a simple value.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueType_display](#valueType_display)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueTypeQuantityComparator](#valueTypeQuantityComparator)|How the Quantity should be understood and represented.|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueTypeQuantityComparator_display](#valueTypeQuantityComparator_display)||<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|
|[valueTypeQuantityValue](#valueTypeQuantityValue)|Numerical value (with implicit precision).|<a href="Observation.md" target="_blank">electronicMedicalRecords/Observation</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#observationId name="observationId">observationId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Observation</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_observationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Observation  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Observation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Observation  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Observation Status</td></tr><tr><td>description</td><td>Reason for the status of the Observation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Registered</td><td>935000001</td><td>0</td></tr><tr><td>en</td><td>Preliminary</td><td>935000002</td><td>0</td></tr><tr><td>en</td><td>Final</td><td>935000003</td><td>0</td></tr><tr><td>en</td><td>Amended</td><td>935000004</td><td>0</td></tr><tr><td>en</td><td>Corrected</td><td>935000005</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Cancelled</td><td>935000006</td><td>1</td></tr><tr><td>en</td><td>Entered in Error</td><td>935000007</td><td>1</td></tr><tr><td>en</td><td>Unknown</td><td>935000008</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_description</td></tr></table>

### <a href=#bodySite name="bodySite">bodySite</a>

Indicates the site on the subject's body where the observation was made (i.e. the target site).  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Body Site</td></tr><tr><td>description</td><td>Indicates the site on the subject's body where the observation was made (i.e. the target site).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_bodysite</td></tr></table>

### <a href=#code name="code">code</a>

Describes what was observed. Sometimes this is called the observation "name".  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>description</td><td>Describes what was observed. Sometimes this is called the observation "name".</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_code</td></tr></table>

### <a href=#comment name="comment">comment</a>

May include statements about significant, unexpected or unreliable values, or information about the source of the value where this may be relevant to the interpretation of the result.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comment</td></tr><tr><td>description</td><td>May include statements about significant, unexpected or unreliable values, or information about the source of the value where this may be relevant to the interpretation of the result.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_comment</td></tr></table>

### <a href=#conextTypeEncounter name="conextTypeEncounter">conextTypeEncounter</a>

The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_conexttypeencounter</td></tr></table>

### <a href=#conextTypeEpisodeOfCare name="conextTypeEpisodeOfCare">conextTypeEpisodeOfCare</a>

The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode Of Care</td></tr><tr><td>description</td><td>The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_conexttypeepisodeofcare</td></tr></table>

### <a href=#contextType name="contextType">contextType</a>

The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context Type</td></tr><tr><td>description</td><td>The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Encounter</td><td>935000000</td></tr><tr><td>en</td><td>Episode Of Care</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#contextType_display name="contextType_display">contextType_display</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#dataAbsentReason name="dataAbsentReason">dataAbsentReason</a>

Provides a reason why the expected value in the element Observation.value[x] is missing.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Data Absent Reason</td></tr><tr><td>description</td><td>Provides a reason why the expected value in the element Observation.value[x] is missing.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dataabsentreason</td></tr></table>

### <a href=#device name="device">device</a>

The device whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject (Device)</td></tr><tr><td>description</td><td>The device whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_device</td></tr></table>

### <a href=#deviceType name="deviceType">deviceType</a>

The device used to generate the observation data.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Type</td></tr><tr><td>description</td><td>The device used to generate the observation data.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_devicetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Device</td><td>935000000</td></tr><tr><td>en</td><td>Device Metric</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#deviceType_display name="deviceType_display">deviceType_display</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#deviceTypeDevice name="deviceTypeDevice">deviceTypeDevice</a>

The device used to generate the observation data.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>The device used to generate the observation data.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_devicetypedevice</td></tr></table>

### <a href=#deviceTypeDeviceMetric name="deviceTypeDeviceMetric">deviceTypeDeviceMetric</a>

The device  metric used to generate the observation data.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Metric</td></tr><tr><td>description</td><td>The device  metric used to generate the observation data.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_devicetypedevicemetric</td></tr></table>

### <a href=#effectiveEnd name="effectiveEnd">effectiveEnd</a>

The  End time-period the observed value is asserted as being true. For biological subjects  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective End</td></tr><tr><td>description</td><td>The  End time-period the observed value is asserted as being true. For biological subjects</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_effectiveend</td></tr></table>

### <a href=#effectiveStart name="effectiveStart">effectiveStart</a>

The start time-period the observed value is asserted as being true. For biological subjects  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective Start</td></tr><tr><td>description</td><td>The start time-period the observed value is asserted as being true. For biological subjects</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_effectivestart</td></tr></table>

### <a href=#effectiveType name="effectiveType">effectiveType</a>

Clinically relevant time/time-period for observation.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective Type</td></tr><tr><td>description</td><td>Clinically relevant time/time-period for observation.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_effectivetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Date time</td><td>935000000</td></tr><tr><td>en</td><td>Period</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#effectiveType_display name="effectiveType_display">effectiveType_display</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#effectiveTypeDateTime name="effectiveTypeDateTime">effectiveTypeDateTime</a>

Enable this field if the Effective type field is Date time.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective Type Date</td></tr><tr><td>description</td><td>Enable this field if the Effective type field is Date time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_effectivetypedatetime</td></tr></table>

### <a href=#episodeOfCare name="episodeOfCare">episodeOfCare</a>

The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode of Care</td></tr><tr><td>description</td><td>The healthcare event (e.g. a patient and healthcare provider interaction) during which this observation is made.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_episodeofcare</td></tr></table>

### <a href=#identifier name="identifier">identifier</a>

A unique identifier assigned to this observation.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identifier</td></tr><tr><td>description</td><td>A unique identifier assigned to this observation.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_identifier</td></tr></table>

### <a href=#interpretation name="interpretation">interpretation</a>

The assessment made based on the result of the observation. Intended as a simple compact code often placed adjacent to the result value in reports and flow sheets to signal the meaning/normalcy status  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interpretation</td></tr><tr><td>description</td><td>The assessment made based on the result of the observation. Intended as a simple compact code often placed adjacent to the result value in reports and flow sheets to signal the meaning/normalcy status</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_interpretation</td></tr></table>

### <a href=#issuedDate name="issuedDate">issuedDate</a>

The date and time this observation was made available to providers, typically after the results have been reviewed and verified.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Issued Date</td></tr><tr><td>description</td><td>The date and time this observation was made available to providers, typically after the results have been reviewed and verified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_issueddate</td></tr></table>

### <a href=#method name="method">method</a>

Indicates the mechanism used to perform the observation.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Method</td></tr><tr><td>description</td><td>Indicates the mechanism used to perform the observation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_method</td></tr></table>

### <a href=#observationNumber name="observationNumber">observationNumber</a>

A unique identifier assigned to this observation.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Observation Number</td></tr><tr><td>description</td><td>A unique identifier assigned to this observation.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_observationnumber</td></tr></table>

### <a href=#specimen name="specimen">specimen</a>

The specimen that was used when this observation was made.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Specimen</td></tr><tr><td>description</td><td>The specimen that was used when this observation was made.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_specimen</td></tr></table>

### <a href=#status name="status">status</a>

The status of the result value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>The status of the result value.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Registered</td><td>935000000</td></tr><tr><td>en</td><td>Preliminary</td><td>935000001</td></tr><tr><td>en</td><td>Final</td><td>935000002</td></tr><tr><td>en</td><td>Amended</td><td>935000003</td></tr><tr><td>en</td><td>Corrected</td><td>935000004</td></tr><tr><td>en</td><td>Cancelled</td><td>935000005</td></tr><tr><td>en</td><td>Entered in Error</td><td>935000006</td></tr><tr><td>en</td><td>Unknown</td><td>935000007</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectType name="subjectType">subjectType</a>

The patient, or group of patients, location, or device whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject Type</td></tr><tr><td>description</td><td>The patient, or group of patients, location, or device whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Device</td><td>935000002</td></tr><tr><td>en</td><td>Group</td><td>935000001</td></tr><tr><td>en</td><td>Location</td><td>935000003</td></tr><tr><td>en</td><td>Patient</td><td>935000000</td></tr></table></td></tr></table>

### <a href=#subjectType_display name="subjectType_display">subjectType_display</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectTypeDevice name="subjectTypeDevice">subjectTypeDevice</a>

The  device whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>The  device whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypedevice</td></tr></table>

### <a href=#subjectTypeGroup name="subjectTypeGroup">subjectTypeGroup</a>

The group whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>description</td><td>The group whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypegroup</td></tr></table>

### <a href=#subjectTypeLocation name="subjectTypeLocation">subjectTypeLocation</a>

The location whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Location</td></tr><tr><td>description</td><td>The location whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypelocation</td></tr></table>

### <a href=#subjectTypePatient name="subjectTypePatient">subjectTypePatient</a>

The patient whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>The patient whose characteristics (direct or indirect) are described by the observation and into whose record the observation is placed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypepatient</td></tr></table>

### <a href=#valueBoolean name="valueBoolean">valueBoolean</a>

The boolean information determined as a result of making the observation, if the information has a simple value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Boolean</td></tr><tr><td>description</td><td>The boolean information determined as a result of making the observation, if the information has a simple value.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valueboolean</td></tr></table>

### <a href=#valueCodeableConcept name="valueCodeableConcept">valueCodeableConcept</a>

The codeable concept information determined as a result of making the observation, if the information has a simple value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Codeable Concept</td></tr><tr><td>description</td><td>The codeable concept information determined as a result of making the observation, if the information has a simple value.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuecodeableconcept</td></tr></table>

### <a href=#valueDateType name="valueDateType">valueDateType</a>

The date and time  information determined as a result of making the observation, if the information has a simple value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Date Time</td></tr><tr><td>description</td><td>The date and time  information determined as a result of making the observation, if the information has a simple value.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuedatetype</td></tr></table>

### <a href=#valuePeriodEndDate name="valuePeriodEndDate">valuePeriodEndDate</a>

The period end date information determined as a result of making the observation, if the information has a simple value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Period End Date</td></tr><tr><td>description</td><td>The period end date information determined as a result of making the observation, if the information has a simple value.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valueperiodenddate</td></tr></table>

### <a href=#valuePeriodStartDate name="valuePeriodStartDate">valuePeriodStartDate</a>

The period start date information determined as a result of making the observation, if the information has a simple value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Period Start Date</td></tr><tr><td>description</td><td>The period start date information determined as a result of making the observation, if the information has a simple value.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valueperiodstartdate</td></tr></table>

### <a href=#valueQuantityCode name="valueQuantityCode">valueQuantityCode</a>

Coded form of the unit.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Quantity Code</td></tr><tr><td>description</td><td>Coded form of the unit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuequantitycode</td></tr></table>

### <a href=#valueQuantitySystem name="valueQuantitySystem">valueQuantitySystem</a>

System that defines coded unit form.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Quantity System</td></tr><tr><td>description</td><td>System that defines coded unit form.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuequantitysystem</td></tr></table>

### <a href=#valueQuantityUnit name="valueQuantityUnit">valueQuantityUnit</a>

Unit representation.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Quantity Unit</td></tr><tr><td>description</td><td>Unit representation.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuequantityunit</td></tr></table>

### <a href=#valueRangeHighLimit name="valueRangeHighLimit">valueRangeHighLimit</a>

The value high range information determined as a result of making the observation, if the information has a simple value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Range High Limit</td></tr><tr><td>description</td><td>The value high range information determined as a result of making the observation, if the information has a simple value.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuerangehighlimit</td></tr></table>

### <a href=#valueRangeLowLimit name="valueRangeLowLimit">valueRangeLowLimit</a>

The range low value information determined as a result of making the observation, if the information has a simple value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Range Low Limit</td></tr><tr><td>description</td><td>The range low value information determined as a result of making the observation, if the information has a simple value.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuerangelowlimit</td></tr></table>

### <a href=#valueRatioDenominatorCode name="valueRatioDenominatorCode">valueRatioDenominatorCode</a>

The denominator code information determined as a result of making the observation, if the information has a simple value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Denominator  Code</td></tr><tr><td>description</td><td>The denominator code information determined as a result of making the observation, if the information has a simple value.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valueratiodenominatorcode</td></tr></table>

### <a href=#valueRatioDenominatorComparator name="valueRatioDenominatorComparator">valueRatioDenominatorComparator</a>

The denominator comparator information determined as a result of making the observation, if the information has a simple value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Denominator Comparator</td></tr><tr><td>description</td><td>The denominator comparator information determined as a result of making the observation, if the information has a simple value.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valueratiodenominatorcomparator</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td><</td><td>935000000</td></tr><tr><td>en</td><td><=</td><td>935000001</td></tr><tr><td>en</td><td>></td><td>935000002</td></tr><tr><td>en</td><td>>=</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#valueRatioDenominatorComparator_display name="valueRatioDenominatorComparator_display">valueRatioDenominatorComparator_display</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#valueratioDenominatorSystem name="valueratioDenominatorSystem">valueratioDenominatorSystem</a>

The denominator system information determined as a result of making the observation, if the information has a simple value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Denominator System</td></tr><tr><td>description</td><td>The denominator system information determined as a result of making the observation, if the information has a simple value.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valueratiodenominatorsystem</td></tr></table>

### <a href=#valueRatioDenominatorUnit name="valueRatioDenominatorUnit">valueRatioDenominatorUnit</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Denominator Unit</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valueratiodenominatorunit</td></tr></table>

### <a href=#valueratioDenominatorvalue name="valueratioDenominatorvalue">valueratioDenominatorvalue</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Denominator Value</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valueratiodenominatorvalue</td></tr></table>

### <a href=#valueRatioNumeratorCode name="valueRatioNumeratorCode">valueRatioNumeratorCode</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Numerator Code</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuerationumeratorcode</td></tr></table>

### <a href=#valueRatioNumeratorComparator name="valueRatioNumeratorComparator">valueRatioNumeratorComparator</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Numerator Comparator</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuerationumeratorcomparator</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td><</td><td>935000000</td></tr><tr><td>en</td><td><=</td><td>935000001</td></tr><tr><td>en</td><td>></td><td>935000002</td></tr><tr><td>en</td><td>>=</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#valueRatioNumeratorComparator_display name="valueRatioNumeratorComparator_display">valueRatioNumeratorComparator_display</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#valueRatioNumeratorSystem name="valueRatioNumeratorSystem">valueRatioNumeratorSystem</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Numerator  System</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuerationumeratorsystem</td></tr></table>

### <a href=#valueRatioNumeratorUnit name="valueRatioNumeratorUnit">valueRatioNumeratorUnit</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Numerator Unit</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuerationumeratorunit</td></tr></table>

### <a href=#valueRatioNumeratorValue name="valueRatioNumeratorValue">valueRatioNumeratorValue</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ratio Numerator Value</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuerationumeratorvalue</td></tr></table>

### <a href=#valueSampledDataTypeData name="valueSampledDataTypeData">valueSampledDataTypeData</a>

Decimal values with spaces, or "E" | "U" | "L"  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Sampled DataType Data</td></tr><tr><td>description</td><td>Decimal values with spaces, or "E" | "U" | "L"</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuesampleddatatypedata</td></tr></table>

### <a href=#valueSampledDataTypeDimension name="valueSampledDataTypeDimension">valueSampledDataTypeDimension</a>

Number of sample points at each time point.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Sampled Data Type Dimension</td></tr><tr><td>description</td><td>Number of sample points at each time point.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuesampleddatatypedimension</td></tr></table>

### <a href=#valueSampledDataTypeFactor name="valueSampledDataTypeFactor">valueSampledDataTypeFactor</a>

Multiply data by this before adding to origin.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Sampled Data Type Factor</td></tr><tr><td>description</td><td>Multiply data by this before adding to origin.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuesampleddatatypefactor</td></tr></table>

### <a href=#valueSampledDataTypeLowerLimit name="valueSampledDataTypeLowerLimit">valueSampledDataTypeLowerLimit</a>

Lower limit of detection  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Sampled Data Type Lower Limit</td></tr><tr><td>description</td><td>Lower limit of detection</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuesampleddatatypelowerlimit</td></tr></table>

### <a href=#valueSampledDataTypeOrigin name="valueSampledDataTypeOrigin">valueSampledDataTypeOrigin</a>

Zero value and units.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Sampled Data Type Origin</td></tr><tr><td>description</td><td>Zero value and units.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuesampleddatatypeorigin</td></tr></table>

### <a href=#valueSampledDataTypePeriod name="valueSampledDataTypePeriod">valueSampledDataTypePeriod</a>

Number of milliseconds between samples.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Sampled Data Type Period</td></tr><tr><td>description</td><td>Number of milliseconds between samples.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuesampleddatatypeperiod</td></tr></table>

### <a href=#valueSampledDataTypeUpperLimit name="valueSampledDataTypeUpperLimit">valueSampledDataTypeUpperLimit</a>

Upper limit of detection.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Sampled Data Type Upper Limit</td></tr><tr><td>description</td><td>Upper limit of detection.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuesampleddatatypeupperlimit</td></tr></table>

### <a href=#valueString name="valueString">valueString</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value String</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuestring</td></tr></table>

### <a href=#valueType name="valueType">valueType</a>

The information determined as a result of making the observation, if the information has a simple value.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value Type</td></tr><tr><td>description</td><td>The information determined as a result of making the observation, if the information has a simple value.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Quantity</td><td>935000000</td></tr><tr><td>en</td><td>Codeable Concept</td><td>935000001</td></tr><tr><td>en</td><td>String</td><td>935000002</td></tr><tr><td>en</td><td>Boolean</td><td>935000003</td></tr><tr><td>en</td><td>Range</td><td>935000004</td></tr><tr><td>en</td><td>Ratio</td><td>935000005</td></tr><tr><td>en</td><td>Sample Data</td><td>935000006</td></tr><tr><td>en</td><td>Attachment</td><td>935000007</td></tr><tr><td>en</td><td>Time</td><td>935000008</td></tr><tr><td>en</td><td>Date Time</td><td>935000009</td></tr><tr><td>en</td><td>Period</td><td>935000010</td></tr></table></td></tr></table>

### <a href=#valueType_display name="valueType_display">valueType_display</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#valueTypeQuantityComparator name="valueTypeQuantityComparator">valueTypeQuantityComparator</a>

How the Quantity should be understood and represented.  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity Comparator</td></tr><tr><td>description</td><td>How the Quantity should be understood and represented.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuetypequantitycomparator</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td><</td><td>935000000</td></tr><tr><td>en</td><td><=</td><td>935000001</td></tr><tr><td>en</td><td>>=</td><td>935000002</td></tr><tr><td>en</td><td>></td><td>935000003</td></tr></table></td></tr></table>

### <a href=#valueTypeQuantityComparator_display name="valueTypeQuantityComparator_display">valueTypeQuantityComparator_display</a>

First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#valueTypeQuantityValue name="valueTypeQuantityValue">valueTypeQuantityValue</a>

Numerical value (with implicit precision).  
First included in: electronicMedicalRecords/Observation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity Value</td></tr><tr><td>description</td><td>Numerical value (with implicit precision).</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_valuetypequantityvalue</td></tr></table>

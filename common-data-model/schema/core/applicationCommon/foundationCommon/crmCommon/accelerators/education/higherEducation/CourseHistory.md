---
title: CourseHistory - Common Data Model | Microsoft Docs
description: The course history for a student.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Course History

The course history for a student.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/education/higherEducation/CourseHistory.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/education/higherEducation/CourseHistory  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[ownerId](#ownerId)|Owner Id|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[courseHistoryId](#courseHistoryId)|Unique identifier for entity instances|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[stateCode](#stateCode)|Status of the Course History|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[stateCode_display](#stateCode_display)||<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[statusCode](#statusCode)|Reason for the status of the Course History|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[statusCode_display](#statusCode_display)||<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[name](#name)|Course History Entity|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[academicPeriodDetailsId](#academicPeriodDetailsId)|The academic period details record for the student|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[continuingEducation](#continuingEducation)|Continuing Education|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[continuingEducation_display](#continuingEducation_display)||<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[courseId](#courseId)|The course record for the student.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[courseSectionId](#courseSectionId)|Unique identifier for Course Section associated with Course History.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[creditsAttempted](#creditsAttempted)|The credits attempted received.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[creditsEarrned](#creditsEarrned)|The credits earned received.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[gradePoints](#gradePoints)|The grade points received.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[lastDateofAttendance](#lastDateofAttendance)|The last date of attendance received.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[letterGrade](#letterGrade)|The letter grade received for the course.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[midTermLetterGrade](#midTermLetterGrade)|The mid term letter grade received.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[midTermNumericGrade](#midTermNumericGrade)|The mid term numeric grade received.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[registrationStatusId](#registrationStatusId)|The registration status received.|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|
|[studentId](#studentId)|Lookup to student (Contact)|<a href="CourseHistory.md" target="_blank">higherEducation/CourseHistory</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#courseHistoryId name="courseHistoryId">courseHistoryId</a>

Unique identifier for entity instances  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Course History</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>mshied_coursehistoryid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Course History  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Course History</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Course History  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Course History</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Course History Entity  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Course History Name</td></tr><tr><td>description</td><td>Course History Entity</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_name</td></tr></table>

### <a href=#academicPeriodDetailsId name="academicPeriodDetailsId">academicPeriodDetailsId</a>

The academic period details record for the student  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Academic Period Details</td></tr><tr><td>description</td><td>The academic period details record for the student</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_academicperioddetailsid</td></tr></table>

### <a href=#continuingEducation name="continuingEducation">continuingEducation</a>

Continuing Education  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Continuing Education</td></tr><tr><td>description</td><td>Continuing Education</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_continuingeducation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>494280000</td></tr><tr><td>en</td><td>No</td><td>494280001</td></tr></table></td></tr></table>

### <a href=#continuingEducation_display name="continuingEducation_display">continuingEducation_display</a>

First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#courseId name="courseId">courseId</a>

The course record for the student.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Course</td></tr><tr><td>description</td><td>The course record for the student.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_courseid</td></tr></table>

### <a href=#courseSectionId name="courseSectionId">courseSectionId</a>

Unique identifier for Course Section associated with Course History.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Course Section</td></tr><tr><td>description</td><td>Unique identifier for Course Section associated with Course History.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_coursesectionid</td></tr></table>

### <a href=#creditsAttempted name="creditsAttempted">creditsAttempted</a>

The credits attempted received.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credits Attempted</td></tr><tr><td>description</td><td>The credits attempted received.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_creditsattempted</td></tr></table>

### <a href=#creditsEarrned name="creditsEarrned">creditsEarrned</a>

The credits earned received.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credits Earrned</td></tr><tr><td>description</td><td>The credits earned received.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_creditsearrned</td></tr></table>

### <a href=#gradePoints name="gradePoints">gradePoints</a>

The grade points received.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Grade Points</td></tr><tr><td>description</td><td>The grade points received.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_gradepoints</td></tr></table>

### <a href=#lastDateofAttendance name="lastDateofAttendance">lastDateofAttendance</a>

The last date of attendance received.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Date of Attendance</td></tr><tr><td>description</td><td>The last date of attendance received.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_lastdateofattendance</td></tr></table>

### <a href=#letterGrade name="letterGrade">letterGrade</a>

The letter grade received for the course.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Letter Grade</td></tr><tr><td>description</td><td>The letter grade received for the course.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_lettergrade</td></tr></table>

### <a href=#midTermLetterGrade name="midTermLetterGrade">midTermLetterGrade</a>

The mid term letter grade received.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mid Term Letter Grade</td></tr><tr><td>description</td><td>The mid term letter grade received.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_midtermlettergrade</td></tr></table>

### <a href=#midTermNumericGrade name="midTermNumericGrade">midTermNumericGrade</a>

The mid term numeric grade received.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mid Term Numeric Grade</td></tr><tr><td>description</td><td>The mid term numeric grade received.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>50</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_midtermnumericgrade</td></tr></table>

### <a href=#registrationStatusId name="registrationStatusId">registrationStatusId</a>

The registration status received.  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration Status</td></tr><tr><td>description</td><td>The registration status received.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_registrationstatusid</td></tr></table>

### <a href=#studentId name="studentId">studentId</a>

Lookup to student (Contact)  
First included in: higherEducation/CourseHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Student</td></tr><tr><td>description</td><td>Lookup to student (Contact)</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_studentid</td></tr></table>

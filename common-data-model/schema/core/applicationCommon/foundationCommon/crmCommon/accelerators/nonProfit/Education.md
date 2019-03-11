---
title: Education - Common Data Model | Microsoft Docs
description: This describes the Education entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Education

Biographical information about the education institutions a contact attended or is attending, the areas of study (major/minor) concentrated on, activities and roles served, preferences (football booster, patron of the on-campus art museum, etc.), and the start and end dates associated with this information.  It's particularly important for mid-level and major gift fundraisers based in the United States to understand someone's university/college alumni/alumnae network and peers in order to build a bigger qualified prospect pipeline.  University/college association is not as relevant or important in the UK, for example, compared to the US.  Nonprofit organizations with a bigger focus on major gifts care more about tracking educational information at a deeper level.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Education.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/Education  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[educationId](#educationId)|Unique identifier for entity instances|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[stateCode](#stateCode)|Status of the Education|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[stateCode_display](#stateCode_display)||<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[statusCode](#statusCode)|Reason for the status of the Education|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[statusCode_display](#statusCode_display)||<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[name](#name)||<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[classYear](#classYear)|Year in which Graduation occurred.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[completionYear](#completionYear)|Year in which Degree/Certificate was obtained.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[degreeOrCertificate](#degreeOrCertificate)|Degree/Certificate associated with Education History being entered.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[degreeOrCertificate_display](#degreeOrCertificate_display)||<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[departmentorCollegeId](#departmentorCollegeId)|Unique identifier for Account associated with Education.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[educationContactId](#educationContactId)|Contact|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[fieldOfStudy1](#fieldOfStudy1)|Major associated with Education History being entered.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[fieldOfStudy1_display](#fieldOfStudy1_display)||<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[fieldOfStudy2](#fieldOfStudy2)|Additional major or minor associated with Education History being entered.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[fieldOfStudy2_display](#fieldOfStudy2_display)||<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[firstYearAttended](#firstYearAttended)|Start year for Education History being selected.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[grade](#grade)|The grade associated with Education History being entered.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[institutionId](#institutionId)|Unique identifier for Account associated with Education.|<a href="Education.md" target="_blank">nonProfit/Education</a>|
|[lastYearAttended](#lastYearAttended)|End year for Education History being selected.|<a href="Education.md" target="_blank">nonProfit/Education</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#educationId name="educationId">educationId</a>

Unique identifier for entity instances  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Education</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_educationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Education  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Education</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Education  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Education</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#classYear name="classYear">classYear</a>

Year in which Graduation occurred.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Class Year</td></tr><tr><td>description</td><td>Year in which Graduation occurred.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_classyear</td></tr></table>

### <a href=#completionYear name="completionYear">completionYear</a>

Year in which Degree/Certificate was obtained.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Completion Year</td></tr><tr><td>description</td><td>Year in which Degree/Certificate was obtained.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_completionyear</td></tr></table>

### <a href=#degreeOrCertificate name="degreeOrCertificate">degreeOrCertificate</a>

Degree/Certificate associated with Education History being entered.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Degree Or Certificate</td></tr><tr><td>description</td><td>Degree/Certificate associated with Education History being entered.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_degreeorcertificate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>DegreeType</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#degreeOrCertificate_display name="degreeOrCertificate_display">degreeOrCertificate_display</a>

First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#departmentorCollegeId name="departmentorCollegeId">departmentorCollegeId</a>

Unique identifier for Account associated with Education.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Department or College</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Education.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_departmentorcollegeid</td></tr></table>

### <a href=#educationContactId name="educationContactId">educationContactId</a>

Contact  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_education_contactid</td></tr></table>

### <a href=#fieldOfStudy1 name="fieldOfStudy1">fieldOfStudy1</a>

Major associated with Education History being entered.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Field of Study #1</td></tr><tr><td>description</td><td>Major associated with Education History being entered.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_fieldofstudy1</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>EducationMajor</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#fieldOfStudy1_display name="fieldOfStudy1_display">fieldOfStudy1_display</a>

First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#fieldOfStudy2 name="fieldOfStudy2">fieldOfStudy2</a>

Additional major or minor associated with Education History being entered.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Field of Study #2</td></tr><tr><td>description</td><td>Additional major or minor associated with Education History being entered.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_fieldofstudy2</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>EducationMajor</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#fieldOfStudy2_display name="fieldOfStudy2_display">fieldOfStudy2_display</a>

First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#firstYearAttended name="firstYearAttended">firstYearAttended</a>

Start year for Education History being selected.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Year Attended</td></tr><tr><td>description</td><td>Start year for Education History being selected.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_firstyearattended</td></tr></table>

### <a href=#grade name="grade">grade</a>

The grade associated with Education History being entered.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Grade</td></tr><tr><td>description</td><td>The grade associated with Education History being entered.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_grade</td></tr></table>

### <a href=#institutionId name="institutionId">institutionId</a>

Unique identifier for Account associated with Education.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Institution</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Education.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_institutionid</td></tr></table>

### <a href=#lastYearAttended name="lastYearAttended">lastYearAttended</a>

End year for Education History being selected.  
First included in: nonProfit/Education (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Year Attended</td></tr><tr><td>description</td><td>End year for Education History being selected.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_lastyearattended</td></tr></table>

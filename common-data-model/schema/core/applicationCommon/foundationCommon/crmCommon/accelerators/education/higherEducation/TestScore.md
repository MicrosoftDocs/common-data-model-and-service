---
title: TestScore - Common Data Model | Microsoft Docs
description: Test scores for a Student Contact
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Test Score

Test scores for a Student Contact  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/education/higherEducation/TestScore.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/education/higherEducation/TestScore  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[ownerId](#ownerId)|Owner Id|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[testScoreId](#testScoreId)|Unique identifier for entity instances|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[stateCode](#stateCode)|Status of the Test Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[stateCode_display](#stateCode_display)||<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[statusCode](#statusCode)|Reason for the status of the Test Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[statusCode_display](#statusCode_display)||<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[name](#name)|The name of the Test Score.|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[ACTComposite](#ACTComposite)|ACT - Composite Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[ACTELA](#ACTELA)|ACT - ELA Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[ACTEnglish](#ACTEnglish)|ACT - English Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[ACTEquivalentScore](#ACTEquivalentScore)|ACT equivalent score for a given SAT Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[ACTMath](#ACTMath)|ACT - Math Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[ACTReading](#ACTReading)|ACT - Reading Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[ACTScience](#ACTScience)|ACT - Science Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[ACTSTEM](#ACTSTEM)|ACT - STEM Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[ACTWriting](#ACTWriting)|ACT - Writing Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[alevelArt](#alevelArt)|A-level Art|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[GMATAnalyticalWriting](#GMATAnalyticalWriting)|GMAT - Analytical Writing Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[GMATIntegratedReasoning](#GMATIntegratedReasoning)|GMAT - Integrated Reasoning Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[GMATQuantitativeReasoning](#GMATQuantitativeReasoning)|GMAT - Quantitative Reasoning Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[GMATTotal](#GMATTotal)|GMAT - Total Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[GMATVerbalReasoning](#GMATVerbalReasoning)|GMAT - Verbal Reasoning Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[GREAnalyticalReasoning](#GREAnalyticalReasoning)|GRE - Analytical Reasoning Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[GREQuantitativeReasoning](#GREQuantitativeReasoning)|GRE - Quantitative Reasoning Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[GRETotalScore](#GRETotalScore)|GRE - Total Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[GREVerbalReasoning](#GREVerbalReasoning)|GRE - Verbal Reasoning Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[IELTSCEFR](#IELTSCEFR)|IELTS - CEFR|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[IELTSCEFR_display](#IELTSCEFR_display)||<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[IELTSListening](#IELTSListening)|IELTS - Listening score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[IELTSOverallBandScore](#IELTSOverallBandScore)|IELTS - Overall Band Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[IELTSReading](#IELTSReading)|IELTS - Reading Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[IELTSSpeakingScore](#IELTSSpeakingScore)|IELTS - Speaking Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[IELTSWriting](#IELTSWriting)|IELTS - Writing Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[SATEssayAnalysis](#SATEssayAnalysis)|SAT - SAT Essay - Analysis Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[SATEssayReading](#SATEssayReading)|SAT - SAT Essay - Reading Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[SATEssayWriting](#SATEssayWriting)|SAT - SAT Essay - Writing Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[SATEvidenceBasedReadingandWritingSection](#SATEvidenceBasedReadingandWritingSection)|SAT - Evidence-Based Reading and Writing Section Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[SATMathSection](#SATMathSection)|SAT - Math Section Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[SATTotalScore](#SATTotalScore)|SAT - Total Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[studentID](#studentID)|Lookup to the Student (Contact Id)|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[testDate](#testDate)|Date when test was taken|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[testLocation](#testLocation)|Location where the test was taken|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[testScoreValue](#testScoreValue)|Test Score Value|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[testSource](#testSource)|Source of Test score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[testSource_display](#testSource_display)||<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[testTypeId](#testTypeId)|List of test types|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[TOEFLListeningSection](#TOEFLListeningSection)|TOEFL - Listening Section Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[TOEFLReadingSection](#TOEFLReadingSection)|TOEFL - Reading Section Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[TOEFLSpeakingSection](#TOEFLSpeakingSection)|TOEFL - Speaking Section Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[TOEFLTotalScore](#TOEFLTotalScore)|TOEFL - Total Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|
|[TOEFLWritingSection](#TOEFLWritingSection)|TOEFL - Writing Section Score|<a href="TestScore.md" target="_blank">higherEducation/TestScore</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#testScoreId name="testScoreId">testScoreId</a>

Unique identifier for entity instances  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Test Score</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>mshied_testscoreid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Test Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Test Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Test Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Test Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the Test Score.  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Test Score Name</td></tr><tr><td>description</td><td>The name of the Test Score.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_name</td></tr></table>

### <a href=#ACTComposite name="ACTComposite">ACTComposite</a>

ACT - Composite Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ACT - Composite</td></tr><tr><td>description</td><td>ACT - Composite Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>36</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_actcomposite</td></tr></table>

### <a href=#ACTELA name="ACTELA">ACTELA</a>

ACT - ELA Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ACT - ELA</td></tr><tr><td>description</td><td>ACT - ELA Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>36</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_actela</td></tr></table>

### <a href=#ACTEnglish name="ACTEnglish">ACTEnglish</a>

ACT - English Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ACT - English</td></tr><tr><td>description</td><td>ACT - English Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>36</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_actenglish</td></tr></table>

### <a href=#ACTEquivalentScore name="ACTEquivalentScore">ACTEquivalentScore</a>

ACT equivalent score for a given SAT Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ACT Equivalent Score</td></tr><tr><td>description</td><td>ACT equivalent score for a given SAT Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_actequivalentscore</td></tr></table>

### <a href=#ACTMath name="ACTMath">ACTMath</a>

ACT - Math Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ACT - Math</td></tr><tr><td>description</td><td>ACT - Math Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>36</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_actmath</td></tr></table>

### <a href=#ACTReading name="ACTReading">ACTReading</a>

ACT - Reading Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ACT - Reading</td></tr><tr><td>description</td><td>ACT - Reading Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>36</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_actreading</td></tr></table>

### <a href=#ACTScience name="ACTScience">ACTScience</a>

ACT - Science Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ACT - Science</td></tr><tr><td>description</td><td>ACT - Science Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>36</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_actscience</td></tr></table>

### <a href=#ACTSTEM name="ACTSTEM">ACTSTEM</a>

ACT - STEM Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ACT - STEM</td></tr><tr><td>description</td><td>ACT - STEM Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>36</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_actstem</td></tr></table>

### <a href=#ACTWriting name="ACTWriting">ACTWriting</a>

ACT - Writing Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ACT - Writing</td></tr><tr><td>description</td><td>ACT - Writing Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>12</td></tr><tr><td>minimumValue</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_actwriting</td></tr></table>

### <a href=#alevelArt name="alevelArt">alevelArt</a>

A-level Art  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>A-level Art</td></tr><tr><td>description</td><td>A-level Art</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>6</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_alevelart</td></tr></table>

### <a href=#GMATAnalyticalWriting name="GMATAnalyticalWriting">GMATAnalyticalWriting</a>

GMAT - Analytical Writing Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GMAT - Analytical Writing</td></tr><tr><td>description</td><td>GMAT - Analytical Writing Score</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>6</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_gmatanalyticalwriting</td></tr></table>

### <a href=#GMATIntegratedReasoning name="GMATIntegratedReasoning">GMATIntegratedReasoning</a>

GMAT - Integrated Reasoning Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GMAT - Integrated Reasoning</td></tr><tr><td>description</td><td>GMAT - Integrated Reasoning Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>8</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_gmatintegratedreasoning</td></tr></table>

### <a href=#GMATQuantitativeReasoning name="GMATQuantitativeReasoning">GMATQuantitativeReasoning</a>

GMAT - Quantitative Reasoning Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GMAT - Quantitative Reasoning</td></tr><tr><td>description</td><td>GMAT - Quantitative Reasoning Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>60</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_gmatquantitativereasoning</td></tr></table>

### <a href=#GMATTotal name="GMATTotal">GMATTotal</a>

GMAT - Total Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GMAT - Total</td></tr><tr><td>description</td><td>GMAT - Total Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>800</td></tr><tr><td>minimumValue</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_gmattotal</td></tr></table>

### <a href=#GMATVerbalReasoning name="GMATVerbalReasoning">GMATVerbalReasoning</a>

GMAT - Verbal Reasoning Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GMAT - Verbal Reasoning</td></tr><tr><td>description</td><td>GMAT - Verbal Reasoning Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>60</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_gmatverbalreasoning</td></tr></table>

### <a href=#GREAnalyticalReasoning name="GREAnalyticalReasoning">GREAnalyticalReasoning</a>

GRE - Analytical Reasoning Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GRE - Analytical Reasoning</td></tr><tr><td>description</td><td>GRE - Analytical Reasoning Score</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>6</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_greanalyticalreasoning</td></tr></table>

### <a href=#GREQuantitativeReasoning name="GREQuantitativeReasoning">GREQuantitativeReasoning</a>

GRE - Quantitative Reasoning Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GRE - Quantitative Reasoning</td></tr><tr><td>description</td><td>GRE - Quantitative Reasoning Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>170</td></tr><tr><td>minimumValue</td><td>130</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_grequantitativereasoning</td></tr></table>

### <a href=#GRETotalScore name="GRETotalScore">GRETotalScore</a>

GRE - Total Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GRE - Total Score</td></tr><tr><td>description</td><td>GRE - Total Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>340</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_gretotalscore</td></tr></table>

### <a href=#GREVerbalReasoning name="GREVerbalReasoning">GREVerbalReasoning</a>

GRE - Verbal Reasoning Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GRE - Verbal Reasoning</td></tr><tr><td>description</td><td>GRE - Verbal Reasoning Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>170</td></tr><tr><td>minimumValue</td><td>130</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_greverbalreasoning</td></tr></table>

### <a href=#IELTSCEFR name="IELTSCEFR">IELTSCEFR</a>

IELTS - CEFR  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IELTS - CEFR</td></tr><tr><td>description</td><td>IELTS - CEFR</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_ieltscefr</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>A1</td><td>494280000</td></tr><tr><td>en</td><td>A2</td><td>494280001</td></tr><tr><td>en</td><td>B1</td><td>494280002</td></tr><tr><td>en</td><td>B2</td><td>494280003</td></tr><tr><td>en</td><td>C1</td><td>494280004</td></tr><tr><td>en</td><td>C2</td><td>494280005</td></tr></table></td></tr></table>

### <a href=#IELTSCEFR_display name="IELTSCEFR_display">IELTSCEFR_display</a>

First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#IELTSListening name="IELTSListening">IELTSListening</a>

IELTS - Listening score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IELTS - Listening</td></tr><tr><td>description</td><td>IELTS - Listening score</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>9</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_ieltslistening</td></tr></table>

### <a href=#IELTSOverallBandScore name="IELTSOverallBandScore">IELTSOverallBandScore</a>

IELTS - Overall Band Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IELTS - Overall Band Score</td></tr><tr><td>description</td><td>IELTS - Overall Band Score</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>9</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_ieltsoverallbandscore</td></tr></table>

### <a href=#IELTSReading name="IELTSReading">IELTSReading</a>

IELTS - Reading Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IELTS - Reading</td></tr><tr><td>description</td><td>IELTS - Reading Score</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>9</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_ieltsreading</td></tr></table>

### <a href=#IELTSSpeakingScore name="IELTSSpeakingScore">IELTSSpeakingScore</a>

IELTS - Speaking Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IELTS - Speaking Score</td></tr><tr><td>description</td><td>IELTS - Speaking Score</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>9</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_ieltsspeakingscore</td></tr></table>

### <a href=#IELTSWriting name="IELTSWriting">IELTSWriting</a>

IELTS - Writing Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IELTS - Writing</td></tr><tr><td>description</td><td>IELTS - Writing Score</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>9</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_ieltswriting</td></tr></table>

### <a href=#SATEssayAnalysis name="SATEssayAnalysis">SATEssayAnalysis</a>

SAT - SAT Essay - Analysis Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SAT Essay - Analysis</td></tr><tr><td>description</td><td>SAT - SAT Essay - Analysis Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>8</td></tr><tr><td>minimumValue</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_satessayanalysis</td></tr></table>

### <a href=#SATEssayReading name="SATEssayReading">SATEssayReading</a>

SAT - SAT Essay - Reading Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SAT Essay - Reading</td></tr><tr><td>description</td><td>SAT - SAT Essay - Reading Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>8</td></tr><tr><td>minimumValue</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_satessayreading</td></tr></table>

### <a href=#SATEssayWriting name="SATEssayWriting">SATEssayWriting</a>

SAT - SAT Essay - Writing Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SAT Essay - Writing</td></tr><tr><td>description</td><td>SAT - SAT Essay - Writing Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>8</td></tr><tr><td>minimumValue</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_satessaywriting</td></tr></table>

### <a href=#SATEvidenceBasedReadingandWritingSection name="SATEvidenceBasedReadingandWritingSection">SATEvidenceBasedReadingandWritingSection</a>

SAT - Evidence-Based Reading and Writing Section Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SAT - Evidence-Based Reading and Writing Section</td></tr><tr><td>description</td><td>SAT - Evidence-Based Reading and Writing Section Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>600</td></tr><tr><td>minimumValue</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_satevidencebasedreadingandwritingsection</td></tr></table>

### <a href=#SATMathSection name="SATMathSection">SATMathSection</a>

SAT - Math Section Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SAT - Math Section</td></tr><tr><td>description</td><td>SAT - Math Section Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>800</td></tr><tr><td>minimumValue</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_satmathsection</td></tr></table>

### <a href=#SATTotalScore name="SATTotalScore">SATTotalScore</a>

SAT - Total Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SAT - Total Score</td></tr><tr><td>description</td><td>SAT - Total Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1600</td></tr><tr><td>minimumValue</td><td>400</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_sattotalscore</td></tr></table>

### <a href=#studentID name="studentID">studentID</a>

Lookup to the Student (Contact Id)  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Student ID</td></tr><tr><td>description</td><td>Lookup to the Student (Contact Id)</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_studentid</td></tr></table>

### <a href=#testDate name="testDate">testDate</a>

Date when test was taken  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Test Date</td></tr><tr><td>description</td><td>Date when test was taken</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_testdate</td></tr></table>

### <a href=#testLocation name="testLocation">testLocation</a>

Location where the test was taken  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Test Location</td></tr><tr><td>description</td><td>Location where the test was taken</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>400</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_testlocation</td></tr></table>

### <a href=#testScoreValue name="testScoreValue">testScoreValue</a>

Test Score Value  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Test Score Value</td></tr><tr><td>description</td><td>Test Score Value</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_testscorevalue</td></tr></table>

### <a href=#testSource name="testSource">testSource</a>

Source of Test score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Test Source</td></tr><tr><td>description</td><td>Source of Test score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_testsource</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Official - Transcript</td><td>494280000</td></tr><tr><td>en</td><td>Official - Testing Agency</td><td>494280001</td></tr><tr><td>en</td><td>Official - SIS</td><td>494280002</td></tr><tr><td>en</td><td>Self - Reported</td><td>494280003</td></tr></table></td></tr></table>

### <a href=#testSource_display name="testSource_display">testSource_display</a>

First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#testTypeId name="testTypeId">testTypeId</a>

List of test types  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Test Type</td></tr><tr><td>description</td><td>List of test types</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_testtypeid</td></tr></table>

### <a href=#TOEFLListeningSection name="TOEFLListeningSection">TOEFLListeningSection</a>

TOEFL - Listening Section Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>TOEFL - Listening Section</td></tr><tr><td>description</td><td>TOEFL - Listening Section Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>50</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_toefllisteningsection</td></tr></table>

### <a href=#TOEFLReadingSection name="TOEFLReadingSection">TOEFLReadingSection</a>

TOEFL - Reading Section Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>TOEFL - Reading Section</td></tr><tr><td>description</td><td>TOEFL - Reading Section Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>30</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_toeflreadingsection</td></tr></table>

### <a href=#TOEFLSpeakingSection name="TOEFLSpeakingSection">TOEFLSpeakingSection</a>

TOEFL - Speaking Section Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>TOEFL - Speaking Section</td></tr><tr><td>description</td><td>TOEFL - Speaking Section Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>30</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_toeflspeakingsection</td></tr></table>

### <a href=#TOEFLTotalScore name="TOEFLTotalScore">TOEFLTotalScore</a>

TOEFL - Total Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>TOEFL - Total Score</td></tr><tr><td>description</td><td>TOEFL - Total Score</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>120</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_toefltotalscore</td></tr></table>

### <a href=#TOEFLWritingSection name="TOEFLWritingSection">TOEFLWritingSection</a>

TOEFL - Writing Section Score  
First included in: higherEducation/TestScore (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>TOEFL - Writing Section</td></tr><tr><td>description</td><td>TOEFL - Writing Section Score</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>50</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mshied_toeflwritingsection</td></tr></table>

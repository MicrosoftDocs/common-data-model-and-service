---
title: "Human resources reference | Microsoft Docs"
description: "The human resources entities let you manage employment information, jobs, leaves, and positions."
author: "robinarh"
manager: "robinarh"
ms.date: "11/07/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "cfc1547f-38e5-4781-abf3-9c9da112c080"
---

# Human resources reference 

[!INCLUDE [](../../includes/new-version.md)]

## Employment (Employment) Entity 
Employment information of a worker who has been hired by an organization. 

Field | Description
---|---
AdjustedWorkerStartDate | Data: DateTime
EmployerNoticeAmount | Data: Number
EmployerUnitOfNotice | Picklist: EmploymentUnitOfNotice<br>Values: Month, Week
EmploymentEndDate | Data: DateTime
EmploymentStartDate | Data: DateTime<br>Required
LastDateWorked | Data: DateTime
Organization | Lookup: Organization<br>Required
TransitionDate | Data: DateTime
ValidFrom | Data: DateTime<br>Required
ValidTo | Data: DateTime
Worker<br>Primary key | Lookup: Worker<br>Required
WorkerNoticeAmount | Data: Number
WorkerStartDate | Data: DateTime
WorkerType | Picklist: WorkerType<br>Values: Contractor, Employee, Unspecified, Volunteer<br>Required
WorkerUnitOfNotice | Picklist: EmploymentUnitOfNotice<br>Values: Month, Week

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Organization|Organization|OneToMany|Association
Worker|Worker|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|Worker<br>Organization<br>EmploymentStartDate<br>EmploymentEndDate
DefaultCreate|DefaultCreate field group|Worker<br>Organization<br>EmploymentStartDate<br>ValidFrom<br>WorkerType
DefaultDetails|DefaultDetails field group|Worker<br>Organization<br>EmploymentStartDate<br>EmploymentEndDate<br>ValidFrom<br>ValidTo
DefaultIdentification|DefaultIdentification field group|Worker<br>Organization
DefaultList|DefaultList field group|Worker<br>Organization<br>EmploymentStartDate<br>EmploymentEndDate
DefaultLookup|DefaultLookup field group|Worker<br>Organization
DefaultReport|DefaultReport field group|Worker<br>Organization<br>EmploymentStartDate<br>EmploymentEndDate<br>ValidFrom<br>ValidTo

## Job (Job) Entity 
Role or responsibility that an employee or contractor has within an organization. 

Field | Description
---|---
AllowUnlimitedPositions | Data: Boolean
DefaultFullTimeEquivalent | Data: Number
Description | Data: Text<br>Maximum length: 2048
JobFunction | Lookup: JobFunction
JobId<br>Primary key | Number sequence: <br>Unique, Searchable
JobType | Lookup: JobType
MaximumNumberOfPositions | Data: Integer
Name | Data: Text<br>Searchable, Maximum length: 2048
Title | Picklist: JobTitle<br>Values: NotSpecified
ValidFrom | Data: DateTime<br>Required, Searchable
ValidTo | Data: DateTime

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
JobType|Job Type|OneToMany|Association
JobFunction|Job Function|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|Name<br>Title<br>ValidFrom<br>ValidTo
DefaultCreate|DefaultCreate field group|Name<br>Title<br>ValidFrom<br>ValidTo<br>JobFunction<br>JobType<br>DefaultFullTimeEquivalent
DefaultDetails|DefaultDetails field group|Name<br>Title<br>ValidFrom<br>ValidTo<br>JobFunction<br>JobType<br>DefaultFullTimeEquivalent
DefaultIdentification|DefaultIdentification field group|JobId<br>Name
DefaultList|DefaultList field group|Name<br>Title<br>ValidFrom<br>ValidTo
DefaultLookup|DefaultLookup field group|JobId<br>Name
DefaultReport|DefaultReport field group|Name<br>Title<br>ValidFrom<br>ValidTo<br>JobFunction<br>JobType<br>DefaultFullTimeEquivalent

## JobFunction (Job Function) Entity 
Classification defining the function of the job (for example, professionals, technicians, service workers). 

Field | Description
---|---
Description | Data: Text<br>Required, Maximum length: 2048
JobFunctionId<br>Primary key | Number sequence: <br>Unique, Searchable

### Relationships

This entity has no relationships.

### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|JobFunctionId<br>Description
DefaultCreate|DefaultCreate field group|JobFunctionId<br>Description
DefaultDetails|DefaultDetails field group|JobFunctionId<br>Description
DefaultIdentification|DefaultIdentification field group|JobFunctionId<br>Description
DefaultList|DefaultList field group|JobFunctionId<br>Description
DefaultLookup|DefaultLookup field group|JobFunctionId<br>Description
DefaultReport|DefaultReport field group|JobFunctionId<br>Description

## JobType (Job Type) Entity 
Secondary classification of jobs (exempt and nonexempt positions). 

Field | Description
---|---
Description | Data: Text<br>Required, Maximum length: 2048
ExemptStatus | Picklist: JobExemptStatus<br>Values: DoesNotApply, Exempt, NonExempt<br>Required
JobTypeId<br>Primary key | Number sequence: <br>Unique, Searchable

### Relationships

This entity has no relationships.

### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|JobTypeId<br>Description<br>ExemptStatus
DefaultCreate|DefaultCreate field group|JobTypeId<br>Description<br>ExemptStatus
DefaultDetails|DefaultDetails field group|JobTypeId<br>Description<br>ExemptStatus
DefaultIdentification|DefaultIdentification field group|JobTypeId<br>Description
DefaultList|DefaultList field group|JobTypeId<br>Description<br>ExemptStatus
DefaultLookup|DefaultLookup field group|JobTypeId<br>Description
DefaultReport|DefaultReport field group|JobTypeId<br>Description<br>ExemptStatus

## LeaveRequest (Leave request) Entity 
Request entered for leave or time off. 

Field | Description
---|---
Comment | Data: Text<br>Maximum length: 2048
LeaveRequestId<br>Primary key | Number sequence: <br>Unique, Searchable
Organization | Lookup: Organization
RequestDate | Data: DateTime<br>Required
Status | Picklist: LeaveRequestStatus<br>Values: Approved, Draft, InReview
Worker | Lookup: Worker<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Worker|Worker|OneToMany|Association
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|LeaveRequestId<br>Worker<br>RequestDate<br>Status
DefaultCreate|DefaultCreate field group|LeaveRequestId<br>Worker<br>RequestDate<br>Status<br>Comment
DefaultDetails|DefaultDetails field group|LeaveRequestId<br>Worker<br>RequestDate<br>Status<br>Comment
DefaultIdentification|DefaultIdentification field group|LeaveRequestId<br>Worker
DefaultList|DefaultList field group|LeaveRequestId<br>Worker<br>RequestDate<br>Status
DefaultLookup|DefaultLookup field group|LeaveRequestId<br>Worker
DefaultReport|DefaultReport field group|LeaveRequestId<br>Worker<br>RequestDate<br>Status

## LeaveRequestDetail (Leave request detail) Entity 
Details captured during the leave request process. 

Field | Description
---|---
Amount | Data: Number
LeaveDate | Data: DateTime<br>Required<br>Description: Date
LeaveRequest<br>Primary key | Lookup: LeaveRequest<br>Required
LeaveType | Lookup: LeaveType<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
LeaveType|Leave type|OneToMany|Association
LeaveRequest|Leave request|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|LeaveRequest<br>LeaveType<br>LeaveDate<br>Amount
DefaultCreate|DefaultCreate field group|LeaveRequest<br>LeaveType<br>LeaveDate<br>Amount
DefaultDetails|DefaultDetails field group|LeaveRequest<br>LeaveType<br>LeaveDate<br>Amount
DefaultIdentification|DefaultIdentification field group|LeaveRequest<br>LeaveType
DefaultList|DefaultList field group|LeaveRequest<br>LeaveType<br>LeaveDate<br>Amount
DefaultLookup|DefaultLookup field group|LeaveRequest<br>LeaveType
DefaultReport|DefaultReport field group|LeaveRequest<br>LeaveType<br>LeaveDate<br>Amount

## LeaveType (Leave type) Entity 
Classifications of different types of leave that are offered by an organization. 

Field | Description
---|---
Description | Data: Text<br>Required, Maximum length: 2048
LeaveTypeId<br>Primary key | Number sequence: <br>Unique, Searchable
Organization | Lookup: Organization

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Organization|Organization|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|LeaveTypeId<br>Description
DefaultCreate|DefaultCreate field group|LeaveTypeId<br>Description
DefaultDetails|DefaultDetails field group|LeaveTypeId<br>Description
DefaultIdentification|DefaultIdentification field group|LeaveTypeId<br>Description
DefaultList|DefaultList field group|LeaveTypeId<br>Description
DefaultLookup|DefaultLookup field group|LeaveTypeId<br>Description
DefaultReport|DefaultReport field group|LeaveTypeId<br>Description

## Position (Position) Entity 
An instance of a job. positions are assigned to workers. 

Field | Description
---|---
Activation | Data: DateTime
AvailableForAssignment | Data: DateTime
Department | Lookup: Department
Description | Data: Text<br>Maximum length: 2048
FullTimeEquivalent | Data: Number
Job | Lookup: Job
ParentPosition | Lookup: Position
PositionId<br>Primary key | Number sequence: <br>Unique, Searchable
PositionType | Lookup: PositionType
Retirement | Data: DateTime
Title | Picklist: JobTitle<br>Values: NotSpecified
ValidFrom | Data: DateTime<br>Required
ValidTo | Data: DateTime

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Position|Parent position|OneToMany|Association
Job|Job|OneToMany|Association
Department|Department|OneToMany|Association
PositionType|Position Type|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|PositionId<br>ValidFrom<br>Description<br>Job
DefaultCreate|DefaultCreate field group|PositionId<br>ValidFrom<br>ValidTo<br>PositionType<br>Job<br>Department<br>Description
DefaultDetails|DefaultDetails field group|PositionId<br>ValidFrom<br>ValidTo<br>PositionType<br>Job<br>Department<br>Description
DefaultIdentification|DefaultIdentification field group|PositionId<br>Description
DefaultList|DefaultList field group|PositionId<br>ValidFrom<br>Description<br>Job
DefaultLookup|DefaultLookup field group|PositionId<br>Description
DefaultReport|DefaultReport field group|PositionId<br>ValidFrom<br>ValidTo<br>PositionType

## PositionType (Position Type) Entity 
Classification of positions in an organization (for example, full-time, part-time, volunteer). 

Field | Description
---|---
Classification | Picklist: PositionClassification<br>Values: FullTime, NotSpecified, PartTime
Description | Data: Text<br>Required, Maximum length: 2048
PositionTypeId<br>Primary key | Number sequence: <br>Unique, Searchable

### Relationships

This entity has no relationships.

### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|PositionTypeId<br>Description<br>Classification
DefaultCreate|DefaultCreate field group|PositionTypeId<br>Description<br>Classification
DefaultDetails|DefaultDetails field group|PositionTypeId<br>Description<br>Classification
DefaultIdentification|DefaultIdentification field group|PositionTypeId<br>Description
DefaultList|DefaultList field group|PositionTypeId<br>Description<br>Classification
DefaultLookup|DefaultLookup field group|PositionTypeId<br>Description
DefaultReport|DefaultReport field group|PositionTypeId<br>Description

## PositionWorkerAssignment (Position worker assignment) Entity 
The position or job instance that an employee or contractor has been assigned. assignments are defined by a start-date and end-date. 

Field | Description
---|---
Position<br>Primary key | Lookup: Position<br>Required
ValidFrom | Data: DateTime<br>Required
ValidTo | Data: DateTime
Worker | Lookup: Worker<br>Required

### Relationships

Related entity | Description | Cardinality | Type 
---|---|---|---
Worker|Worker|OneToMany|Association
Position|Position|OneToMany|Association


### Field groups

Field group | Description | Fields
---|---|---
DefaultCard|DefaultCard field group|Position<br>ValidFrom<br>ValidTo<br>Worker
DefaultCreate|DefaultCreate field group|Position<br>ValidFrom<br>ValidTo<br>Worker
DefaultDetails|DefaultDetails field group|Position<br>ValidFrom<br>ValidTo<br>Worker
DefaultIdentification|DefaultIdentification field group|Position<br>ValidFrom
DefaultList|DefaultList field group|Position<br>ValidFrom<br>ValidTo<br>Worker
DefaultLookup|DefaultLookup field group|Position<br>ValidFrom
DefaultReport|DefaultReport field group|Position<br>ValidFrom<br>ValidTo<br>Worker


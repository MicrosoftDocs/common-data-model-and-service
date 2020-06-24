---
title: overview - Common Data Model | Microsoft Docs
description: higherEducation is a folder that contains standard entities related to the Common Data Model.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# higherEducation

CDM Solution for the 'HIGHEREDUCATION' CDS Solution  

## Entities

|Name|Description|
|---|---|
|[AcademicPeriod](AcademicPeriod.md)|The periods of time in which courses are offered by the institution,  such as a term or semester.|
|[AcademicPeriodDetail](AcademicPeriodDetail.md)|Status between student and their academic periods.|
|[Accomplishments](Accomplishments.md)|This entity is used to store the accomplishments of a particular student|
|[Account](Account.md)|Business that represents a customer or potential customer. The company that is billed in business transactions.|
|[Address](Address.md)|Address and shipping information. Used to store additional addresses for an account or contact.|
|[AreaOfInterest](AreaOfInterest.md)|The master list of all area of interests offered by an institution.  Areas of interest are higher level subject groupings like astronomy, or business.|
|[AreaOfStudy](AreaOfStudy.md)|The master list of all area of studies offered by an institution.  Areas of studies are more specific program offerings, such as Master's of Public Administration - Emergency Management.|
|[Contact](Contact.md)|Person with whom a business unit has a relationship, such as customer, supplier, and colleague.|
|[Course](Course.md)|The master list of all courses offered by an institution.|
|[CourseHistory](CourseHistory.md)|The course history for a student.|
|[CourseSection](CourseSection.md)|The relationship between an instructor and a specific course.|
|[EducationLevel](EducationLevel.md)|The master list of all education levels mapped in the external system, such as Associate of Arts, Bachelor, Certificate.|
|[ExtraCurricularActivity](ExtraCurricularActivity.md)|The master list of all extra curricular activities tracked by the institution.|
|[ExtraCurricularParticipant](ExtraCurricularParticipant.md)|The relationship between a Contact and a specific Extra Curricular Activity.|
|[Grant](Grant.md)|This entity stores the list of grants offered to a school by all business partners|
|[GrantApplicant](GrantApplicant.md)|This entity is used as an internship application form and to store the list of students who have applied to a particular internship.|
|[GrantApplicationBusinessProcessFlow](GrantApplicationBusinessProcessFlow.md)|Base entity for process Grant Application Business Process Flow|
|[Internship](Internship.md)|This entity stores the list of internships offered to a school by all business partners.|
|[InternshipApplicant](InternshipApplicant.md)|This entity is used as an internship application form and to store the list of students who have applied to a particular internship.|
|[InternshipApplicationFlow](InternshipApplicationFlow.md)|Base entity for process Internship Application Flow|
|[PreviousEducation](PreviousEducation.md)|The previous education history for a student.|
|[Program](Program.md)|The master list of all program levels offered by the institution.|
|[ProgramLevel](ProgramLevel.md)|Collection of all Program Levels offered by the institution|
|[ProgramVersion](ProgramVersion.md)|The master list of all program versions defined by the institution.|
|[ProgramVersionDetail](ProgramVersionDetail.md)|The master list of program versions start dates defined by the institution.|
|[RegistrationStatus](RegistrationStatus.md)|The master list of registration statuses tracked by the institution. The registration status is associated to the student course history.|
|[Scholarship](Scholarship.md)|This entity stores the list of scholarships offered to a school by all business partners|
|[ScholarshipApplicant](ScholarshipApplicant.md)|This entity is used as an scholarship application form and to store the list of students who have applied to a particular scholarship.|
|[ScholarshipApplicationBusinessProcessFlow](ScholarshipApplicationBusinessProcessFlow.md)|Base entity for process Scholarship Application Business Process Flow|
|[StudentProgramType](StudentProgramType.md)|The master list of program types defined by the institution, such as major, minor, or concentration.|
|[StudentStatus](StudentStatus.md)|The master list of student statuses defined by the institution.|
|[TestScore](TestScore.md)|Test scores for a Student Contact|
|[TestType](TestType.md)|Type of test taken by a Student Contact|

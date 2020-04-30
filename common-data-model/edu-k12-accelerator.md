---

title: Dynamics 365 Education Accelerator – K12 (Preview) | Microsoft Docs
description:  Dynamics 365 Education Accelerators provide a uniform platform for those who wish to connect, embed, or extend the Dynamics 365 platform and Power Platform.
author: MeenooRami
ms.service: common-data-model
ms.reviewer: v-dehaas
ms.topic: article
ms.date: 05/01/2020
ms.author: merami

---

# Dynamics 365 Education Accelerator – K-12 (Preview)

The K-12 component in the Dynamics 365 Education Accelerator sits on top of an existing Dynamics 365 instance or Power Apps instance to assist with day-to-day operations or as a standalone data model for developers. The holistic student profile, educator, and community engagement scenario contains:
- The data model
- Installable scenarios, including:
  - Standard entity attribute extensions
  - Specific education entities for K-12
  - Pre-built dashboards and portals
  - Sample data
- Other tools to help customers and partners build and deploy new solutions.

The accelerator includes the following features:

- K12 Student and Parent Portal
- Collect School paperwork and forms
- Ability to engage donors and raise funds
- Student Behavior Management Application
- Track and Report Attendance Application and Dashboard

## Site-map extensions

With the Dynamics 365 K12 scenario, schools can optimize student success through optimal understanding of data about the student journey. When the accelerator is installed into Dynamics 365, the experience is transformed into one specifically built for K12 schools and one that allows schools to quickly build Power Apps and Power BI visualizations.

## Entities and workflows

This accelerator provides these entities to support the needs of K12 schools:

### EDUCATION CORE

- Contact
- Account
- Test Type
- Test Score
- Course History
- Registration Status
- Course
- Course Section
- Extra Curricular Activity
- Extra Curricular Activity Participants
- Address / Customer Address
- Academic Period
- Program 
- Program Level
- Academic Period Details
- Student Status
- Internship
- Internship Applicants
- Accomplishments
- Area of Interest
- Area of Study
- Student Program Type
- Previous Education
- Education Level
- Scholarship
- Scholarship Applicant

### K12

- Attendance
- Grading Period
- Incident Type
- Incident Action
- Behavior Incidents
- Intervention
- Intervention Participants
- Education Content
- Assessment
- Assessment Item
- Student Assessment Response
- Learning Standards

## Forms and dashboards

To better understand and use the available forms and dashboards in this scenario, let’s look it through the personas of a parent, an administrator, or an educator.

## Parent and Student Portal

This portal allows both the parent and student access to the student’s information. From attendance to grades it facilitates clear conversations about progress made by students and caregivers/parents who support their students.

<!--note from editor: The alt text on these screenshots cannot be the same. They need to be descriptive enough for people who are using screen readers for accessibility.  -->

> [!div class="mx-imgBorder"]
> ![Parent and student portal](media/parent-student-portal-1.png "Parent and student portal")

Here students can see all their assignments and progress made with each, as well as focus on a particular subject to see only those assignments.

> [!div class="mx-imgBorder"]
> ![Parent and student portal](media/parent-student-portal-2.png "Parent and student portal")

Students can easily check grades and test scores.

<!--note from editor: Anton's name is misspelled in the last 2 rows of this image. -->

> [!div class="mx-imgBorder"]
> ![Parent and student portal](media/parent-student-portal-3.png "Parent and student portal")

They can also check other important details like attendance.

> [!div class="mx-imgBorder"]
> ![Parent and student portal](media/parent-student-portal-4.png "Parent and student portal")

They can explore extracurricular activities offered at their schools.
<!--note from editor: The email addresses in this screenshot are not approved fictitious content. Also, when does email use the format https://?  -->

> [!div class="mx-imgBorder"]
> ![Parent and student portal](media/parent-student-portal-5.png "Parent and student portal")

Parents can also easily update their family information for the school, including important medical forms.

> [!div class="mx-imgBorder"]
> ![Parent and student portal](media/parent-student-portal-6.png "Parent and student portal")

## Model-driven app

Administrators have a complete view of attendance, courses, internships, accomplishments, extracurricular activities, interventions, assessments, and behavior incidents. The administrator sees this single view to access information for their students and take informed actions to support students.

> [!div class="mx-imgBorder"]
> ![Administrator view](media/edu-admin-view.png "Administrator view")

## Donor management app

Administrators use the donor app to view and manage donors and update them on how the school is using their donations.

> [!div class="mx-imgBorder"]
> ![Donor management view](media/edu-donor-mgmt-view.png "Donor management view")

Administrators can also get a clear view of donation designations.

## Student behavior app

Administrators can easily record, track, and encourage positive behavior from students.

> [!div class="mx-imgBorder"]
> ![Student behavior view](media/behavior-view.png "Student behavior view")

They can also better understand details on how students earned recognition for positive behaviors in class.

> [!div class="mx-imgBorder"]
> ![Student behavior incident view](media/behavior-view-2.png "Student behavior incident view")

## Student attendance app

Educators can easily track and reports attendance in the Attendance application. This application can also be modified to use on a table or phone to increase ease of using it.

<!--note from editor: The email addresses in this screenshot are not approved fictitious content. When we don't use an approved one from the CELA list, we are supposed to use @example.com, not @test.com, and we're not supposed to use first and last names.-->

> [!div class="mx-imgBorder"]
> ![Student attendance view](media/attendance-app.png "Student attendance view")

## Attendance Power BI template

Attendance Power BI report dashboard allows Educators to easily view the attendance data and take action on it.

> [!div class="mx-imgBorder"]
> ![Student attendance template](media/attendance-template.png "Student attendance template")

## Additional resources

Education Accelerator data model, solutions, data samples, Power BI examples, SDK extensions, and more are provided as part of the open-source creative license and available on [Github](https://aka.ms/edugithub).

## Connect and share feedback
Do you have feedback or need support? Contact us at [dynindaccsupport@microsoft.com](mailto:dynindaccsupport@microsoft.com).

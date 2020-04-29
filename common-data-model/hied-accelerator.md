---

title: Dynamics 365 Education Accelerator – Higher Education | Microsoft Docs
description: Develop higher education solutions with the extensions to Common Data Model and the built-in forms, views, and dashboards of the Dynamics 365 Higher Education Accelerator.
author: MeenooRami
ms.service: common-data-model
ms.reviewer: Deonhe
ms.topic: article
ms.date: 05/01/2020
ms.author: merami

---

# Dynamics 365 Education Accelerator – Higher Education

With the Higher Education component in the [Dynamics 365 Education Accelerator](https://appsource.microsoft.com/product/dynamics-365/mshied.highereducationcommondatamodel?tab=Overview), you can develop solutions that are based on entities and attributes that higher-education institutions use. The component includes entities around student engagement and additional entities around internships, scholarships, grants, and accomplishments. The component also provides entities, fields, forms, views, and dashboards specific to higher education.
<!--note from editor: Shouldn't that first sentence be "With the Higher Education component in the Dynamics 365 Education Accelerator, you can develop..."? In the overview, you say the Education Accelerator has 2 components, but in this topic, you say there is a specific Higher Education Accelerator. See my proposed changes. -->

The component now includes the following features:

## Common Data Model extensions

This accelerator contains extensions to Common Data Model to include concepts for higher education, including entity definitions and relationships:

- A student portal where students can view courses and events, and see the history of courses and applications.
- A business partner dashboard to provide information about organizations that are willing to engage with the university for events, hackathons, internships, scholarships, and grants.
<!--note from editor: there was something missing here. Is the dashboard so those orgs can see into the university info? Which would be something like "...engage with the university visbility into events..." Or so the university can see a list of which orgs are their partners? Which would be something like what I edited above.  -->
- The Accomplishment extension captures any work completed by students outside of a course, such as hackathons or awards.
- The Grants phone app allows research faculty to keep track of applications and approval of grants to which they've applied.
- All personas, including students, business partners, and faculty members, have access to rich reporting on the students applying for internships, grants, and scholarships.
- System views that provide easy access to relevant areas, such as students, faculty, extracurricular activities, previous education, test scores, courses, academic periods, programs, test types, registration status, and areas of interest.
<!--note from editor: Entity names are not usually lowercase or plural. See if my edit is also accurate, without having to make that long list title case. -->
- Sample apps to show some of the possibilities of the unified interface.
- Example Dynamics 365 dashboards and Power BI dashboards that provide analytics for completed courses and allow drilling into details about student performance, instructor effectiveness, and course feedback.
- Support for building additional canvases and model-driven apps in Power Apps.
- A solution that you can deploy and install from AppSource or GitHub.

## Site-map extensions

With the Higher Education component of the Dynamics 365 Education Accelerator, institutions can optimize student and faculty engagement, improve institutional effectiveness, predict outcomes, and gain insights from analytics. When the accelerator is installed, the experience is transformed into one specifically built for higher education and one that allows institutions to quickly build Power Apps and Power BI visualizations.
<!--note from editor: Dynamics 365 is the full suite. We can't install "into" it. You could say "installed into one of the model-driven apps for Dynamics 365", but see my simpler suggested edit. -->

Higher education institutions can build their business processes on top of the entities in the accelerator. The ribbon customizations contain entities to record student, faculty, and alumni interactions, business partner interactions, appointments, events, and outreach.

## Entities and workflows

This accelerator provides these entities to support the needs of higher education institutions:

<!--note from editor: The entities in the other accelerator topics are in tables with a column per category. Suggest you do that as well for consistency -->
### Education core

- Contact
- Account
- Test Type
- Test Score
- Course History
- Registration Status
- Course
- Course Section
- Extra Curricular Activity
<!--note from editor: Extracurricular is one word. I know you are following the UI here since this is an entity name, but can they fix this before this accelerator goes live? Can someone open a bug with the product team? -->
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
<!--note from editor: In the screenshot below, these are plural. Is "Areas" also plural in the entity names? -->
- Area of Interest
- Area of Study
- Student Program Type
- Previous Education
- Education Level
- Scholarship
- Scholarship Applicant

### Higher Education
- Grant 
- Grant Applicant
- Program Version
- Program Version Detail

## Forms and dashboards

The Higher Education component combines standard Dynamics 365 entities with customized entities to make it easier to build solutions. This section describes some of the forms, apps, and dashboards that demonstrate the new entities and the data model.
<!--note from editor: Since this says the following sections are under this one, I made them all H3s until you get to Additional Resources.  -->

### Business partner dashboard

A business partner is any organization that's willing to engage with the university for events, hackathons, internships, scholarships, or grants. With the native dashboard and PowerBI dashboards, business partners gain insights into student interest in opportunities and applications for grants and scholarships.

![Business partner dashboard](media/businesspartnerdashboard.png "Business partner dashboard")

### Student internship application status form

This form tracks the status of students' internship applications.

![Student internship applications](media/studentintershipapplication.png "Student internship applications")

### Grants phone app

Research faculty can keep track of grant applications submitted by their students. See example below:

![Grants phone app](media/grantsphoneapp.png "Grants phone app")

### Student form

This Dynamics 365 form shows student information (such as contact information, course load, areas of study, degree, course history, and test scores) in the context of the app and the interface. The student record becomes the source of truth and engagement to deliver the best support throughout the student lifecycle.

!["Student form"](media/hied-student.png "Student form")

### Institutional dashboard

This accelerator includes a student dashboard in Dynamics 365 and an institutional dashboard in Power BI. With the institutional dashboard, you can gain analytics and insights into students, classes, and key metrics such as *students by program* and demographics.

![Institutional dashboard](media/hied-dashboard.png "Institutional dashboard")

## Additional resources

- Download the Dynamics 365 Higher Education Accelerator from [AppSource](https://appsource.microsoft.com/product/dynamics-365/mshied.highereducationcommondatamodel?tab=Overview).

- The higher education data model, solutions, data samples, Power BI examples, SDK extensions, and more are provided as part of the open-source creative license and available on [GitHub](https://github.com/microsoft/Industry-Accelerator-Education/releases).

- [Additional topics](https://community.dynamics.com/365/b/dynamics365isvsuccess/archive/2018/08/01/dynamics-365-brings-industry-focus-through-the-microsoft-power-platform-and-solution-accelerators) about the accelerators. 

- This [blog post](https://community.dynamics.com/365/b/dynamics365isvsuccess/archive/2018/10/30/early-isvs-building-on-the-new-higher-education-accelerator-and-the-microsoft-power-platform) shows some examples of ISVs building solutions on the Dynamics 365 Higher-Education Accelerator.

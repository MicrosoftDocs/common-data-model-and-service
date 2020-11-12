---
title: Dynamics 365 healthcare accelerator  | Microsoft Docs
description: Develop healthcare solutions with the extensions to Common Data Model and built-in forms and views of the Dynamics 365 healthcare accelerator.
author: TheresaPalmer
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 03/30/2020
ms.author: tpalmer
---

# Dynamics 365 healthcare accelerator
> Note
>
>The [Dynamics 365 healthcare accelerator](https://docs.microsoft.com/en-us/common-data-model/health-accelerator) is deprecated effective 11/13 and will no longer be available for download after Dec 30, 2020. 
>
>Customers can continue to use the accelerator but it will not be updated after 11/13 nor will there be a migration path to Microsoft Cloud for Healthcare.
>
> Microsoft Cloud for Healthcare provides a unified approach across the Microsoft Cloud and enables healthcare organizations to deliver better experiences, better insights, and better care. More information: [What is Microsoft Cloud for Healthcare?](/industry/healthcare/overview) 
>
>**Partners and Microsoft Cloud for Healthcare**
>
> Interested in building and extending Microsoft Cloud for Healthcare? Reach out to your Microsoft account manager or [go here to learn more](https://partner.microsoft.com/en-US/solutions/industry-solutions/healthcare) about the Microsoft Cloud for Healthcare partner program.


Rapidly develop healthcare solutions using [Fast Healthcare Interoperability Resources (FHIR)](https://www.hl7.org/fhir/overview.html) entities (such as patient, condition, and care plan) in the [Dynamics 365 healthcare accelerator](https://appsource.microsoft.com/product/dynamics-365/msemr.healthcarecommondatamodel?tab=Overview).

This accelerator was announced in July 2018 at Ignite, and the initial release includes these features:

- Extension of Common Data Model to include concepts for health, including entity definitions and relationships.
- **Patient**, **Practitioner**, **Related person**, and other customer-engagement forms that you can enhance or use out of the box.
- A sample app that demonstrates some possibilities of the Unified Interface.
- Support for building canvas and model-driven apps in Power Apps.
- Support for extending the model with custom entities, forms, and relationships that meet your business needs.
- Support for analytics.
- A Common Data Service solution that you can install from AppSource.

## Site-map extensions

With the healthcare accelerator plugged in to the Dynamics 365 platform, you can optimize various aspects of care coordination and segment patients and providers based on EMR data. You can also manage the care continuum of all patients by leveraging the entire customer-engagement solution within Dynamics 365.

This accelerator adds a layer to the rich feature set of the base Dynamics 365 functionality by adding a ribbon to help you manage the special needs of your health organization. This ribbon contains entities to record patient data, appointments, procedures, nutrition orders, care plans, and many other functions.

## Entities and workflows

The healthcare accelerator provides these entities in support of the FHIR HL7 (Health Level Seven) specification:

| | | | |
| ------- | -----------------|------------------| ------------|
| Patients | Healthcare Services | Care Plans | Encounters |
|Practitioners | Clinical Impression Problems | Risk Assessments |Specimens|
|Organizations | Allergy Intolerances | Observations |Medications |
|Devices | Medication Administration | Episodes of Care |Locations |
| Healthcare Services | Medication Requests | | |

The accelerator also includes these workflows:

| | | |
| ------- | -----------------|------------------|
|Tasks | Appointments (EMR) | Procedures|
|Nutrition Orders | Referral Requests |

## Forms

The healthcare accelerator combines standard CRM entities with customized entities to make it easier to build solutions on top. This section describes examples of built-in forms and views that demonstrate these entities.

### Patient/Practitioner 360

This view shows Electronic Medical Record (EMR) data directly within a patient or practitioner-specific form in Dynamics 365. The data model shows appointments, procedures, medications, and other patient/practitioner data in context and a user-friendly interface.

![Patient Practitioner 360](media/health-patientpractitioner.png)

### Patient/Provider Timeline

This view provides a sequential look at all activities that have occurred with the patient or provider. The timeline provides the ability to scale, leveraging a slider, and interact with data directly.

![Patient Provider Timeline](media/TimelineNew.PNG)

### Care Team Viewer

A clear understanding of which member of a patient's care team owns each facet of care is paramount, as this view clearly and concisely shows.

![Care Team Viewer](media/CareTeamNew.PNG)

## Additional resources

- Download the Dynamics 365 healthcare accelerator from [AppSource](https://appsource.microsoft.com/product/dynamics-365/msemr.healthcarecommondatamodel?tab=Overview).

- The healthcare data model, solutions, data samples, Power BI examples, SDK extensions, and more are provided as part of the open-source creative license and available on [GitHub](https://github.com/microsoft/Industry-Accelerator-Health).

- [More details](https://community.dynamics.com/365/b/healthaccelerator/archive/2018/07/19/dynamics-365-health-accelerator-solution-first-look) about the healthcare accelerator.

- [Additional topics](https://community.dynamics.com/365/b/dynamics365isvsuccess/archive/2018/08/01/dynamics-365-brings-industry-focus-through-the-microsoft-power-platform-and-solution-accelerators) about the industry accelerators.

- Continue your accelerator experience and engage with experts and peers, read blog articles, and find local events within the industry accelerator community. [Join us](https://community.dynamics.com/365/industry-accelerators)

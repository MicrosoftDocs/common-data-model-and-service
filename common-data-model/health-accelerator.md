---
title: Healthcare Industry Accelerator | Microsoft Docs
description: The Dynamics 365 Health Accelerator allows you to develop healthcare solutions with extensions to the Common Data Model and out of box forms and views.
author: TheresaPalmer
ms.service: powerapps
ms.reviewer: anneta
ms.topic: article
ms.date: 11/16/2018
ms.author: tpalmer
---

# The Dynamics 365 Health Accelerator

With the [Dynamics 365 Health Accelerator](https://appsource.microsoft.com/product/dynamics-365/msemr.healthcarecommondatamodel?tab=Overview), you can rapidly develop healthcare solutions using Fast Healthcare Interoperability Resources (FHIR) entities such as patient, condition, and care plan. 

The initial release of the Health Accelerator (announced in July 2018 at Ignite) provides:
-	extending the Common Data Model (CDM) to include concepts for health, including entity definitions and relationships
-	out-of-the-box customer-engagement forms such as **Patient**, **Practitioner**, and **Related person**, which you can leverage or enhance
-	an out-of-the-box app to provide a sample of what's possible on the Unified Interface
-	support for building canvas and model-driven apps in PowerApps
-	support to extend the model (new entities, forms, and relationships) to meet your business needs
-	support for analytics
-	a solution for Common Data Service for Apps that you can install from AppSource

In future releases, we'll look at enabling artificial-intelligence scenarios and providing a baseline for doing AI on Dynamics 365 Accelerators.

## Site-map extensions 
With the Health Accelerator plugged in to the Dynamics 365 platform, you can optimize various aspects of care coordination and segment patients and providers based on EMR data. You can also manage the care continuum of all patients by leveraging the entire customer-engagement solution within Dynamics 365. 

This accelerator adds another layer to the rich feature set in the base Dynamics 365 functionality by adding a ribbon to help you manage the special needs of your health organization. This ribbon contains entities to record patient data, appointments, procedures, nutrition orders, care plans, and a multitude of other functions. 
              
## Entities and workflows
The Healthcare Accelerator provides a specific set of primary entities in support of the FHIR HL7 specification. The solution provides these entities:

| | | | |
| ------- | -----------------|------------------| ------------|
| Patients | Healthcare Services | Care Plans | Encounters |
|Practitioners | Clinical Impression Problems | Risk Assessments |Specimens|
|Organizations | Allergy Intolerances | Observations |Medications |
|Devices | Medication Administration | Episodes of care |Locations |
| Healthcare Services | Medication Requests | | |


The accelerator also includes these workflows:

| | | | 
| ------- | -----------------|------------------| 
|Tasks |	Appointments (EMR) |	Procedures|
|Nutrition Orders |	Referral Requests 	|

## Accelerator forms 
The Dynamics 365 Health Accelerator uses standard CRM entities along with customized entities to make it easier to build solutions on top. Later in this topic, you can find examples of some out-of-the-box forms and views that demonstrate these entities. 

## Patient/Practitioner 360 

The ability to see EMR data directly within a patient or practitioner-specific form in Dynamics. The data model shows appointment, procedure, medication, and other patient/practitioner data in context in a user-friendly interface. 

![Patient Practitioner 360 ](media/health-patientpractitioner.png)
                                             
### Patient/Provider Timeline 
The Dynamics 365 Health Accelerator includes a built-in patient/provider timeline, which displays a sequential view of all activities that have occurred with the patient or provider. The timeline provides the ability to scale, leveraging a slider, and allows you to interact with data directly within the timeline.     

![Patient Provider Timeline](media/health-timeline.png)
 
### Care Team Viewer 
A clear view into which member of a patient's care team owns each facet of care is paramount. Therefore, in the Dynamics Health 365 Accelerator, a clear and concise care-team viewer shows users who’s responsible for the patient’s care.  

![Care Team Viewer ](media/health-careteam.png)
 
## Additional Resources
- Download the Healthcare Accelerator from [AppSource](https://appsource.microsoft.com/product/dynamics-365/msemr.healthcarecommondatamodel?tab=Overview) 
- The Healthcare data model, solutions, data samples, Power BI examples, SDK extensions, and more are provided as part of the open-source creative license and available on [GitHub](https://github.com/Microsoft/Dynamics-365-Industry-Accelerators/tree/master/health). 
- More details about the Health Accelerator can be found [here](https://community.dynamics.com/365/b/healthaccelerator/archive/2018/07/19/dynamics-365-health-accelerator-solution-first-look)
- Additional support topics on the accelerators can be found [here](https://community.dynamics.com/365/b/dynamics365isvsuccess/archive/2018/08/01/dynamics-365-brings-industry-focus-through-the-microsoft-power-platform-and-solution-accelerators).
- This [blog post](https://community.dynamics.com/365/b/dynamics365isvsuccess/archive/2018/10/30/early-isvs-building-on-the-new-higher-education-accelerator-and-the-microsoft-power-platform) shows some examples of ISVs building solutions on the Higher Education Accelerator.

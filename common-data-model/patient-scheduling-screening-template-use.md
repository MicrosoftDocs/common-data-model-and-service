---
title: Use the Dynamics 365 healthcare accelerator Patient Scheduling and Screening template | Microsoft Docs
description: Use healthcare solutions with the extensions to Common Data Model and built-in forms and views of the Dynamics 365 healthcare accelerator.
author: edgarwilsonjr2
ms.service: common-data-model
ms.reviewer: anbichse
ms.topic: article
ms.date: 04/06/2020
ms.author: edwilson
---

# Use the Patient Scheduling and Screening template

In an effort to streamline patient scheduling and screening measures to help
more efficiently combat the COVID-19 pandemic, the Patient Scheduling and
Screening template provides a robust, yet easy-to-use baseline for providing
these capabilities to organizations.

## Prerequisites

To get started with the app, you need to ensure the following has been
done for users of the solutions within the template:

-   Ensure **Patient Outreach** users have either **Marketing Manager** or **Marketing
    Professional** security role in your environment.

    ![Manage security roles](media/security-role1.png "Manage security roles")

-   Ensure **Omnichannel Contact Center** users have **Customer Service app
    access** and **Customer Service Representative** roles. Along with this, the users
    will need **Omnichannel administrator**, **Omnichannel agent**, or **Omnichannel supervisor** roles.

    ![Manage security roles](media/security-role2.png "Manage security roles")

To get started with the **Screening app** included in the solution, you need to
download Power Apps Mobile on your device using the device's app store.

-   **Download** [Power Apps
    Mobile](https://powerapps.microsoft.com/downloads).

-   For **Apple** devices with iOS such as iPhone and iPad, use [App
    store](https://aka.ms/powerappsios).

-   For **Android** devices, use [Google Play](https://aka.ms/powerappsandroid).

After you install Power Apps Mobile, open the app from your device and sign
in with your company's Azure Active Directory account. You can view all apps
shared to you by your organization once you sign in. For more information, see
[Power Apps mobile device sign
in](https://docs.microsoft.com/powerapps/user/run-app-client#open-power-apps-and-sign-in).

## Demo: Patient Scheduling and Screening template

Watch a quick demo on how to use the Patient Screening and Scheduling template.

> [!VIDEO https://www.youtube.com/embed/iDLWFAlxZOY]

## Patient Outreach

![Patient Outreach](media/patient-outreach.jpg "Patient Outreach")

To provide tools to allow for organizations to proactively provide outreach to
at-risk patient populations, the **Patient Outreach** module in the Patient
Scheduling and Screening template will encompass template patient segments for
organizations to compile a marketing segment in order to reach out to these
patients. Leveraging the core healthcare accelerator solution to store patient
clinical data in Dataverse, we are able to utilize conditions and the corresponding
ICD-10 code in order to formulate the segment. The Patient Segments included
within the solution are as follows:

-   Respiratory Patients over 60

-   Cardiac Patients over 60

-   Compromised Immune System

These templates are meant to provide a baseline to be expanded upon or
configured to meet the organization's individual needs for patient outreach.

## Patient Journeys email templates

![Patient Journeys](media/patient-journeys.jpg "Patient Journeys")

*Patient Journeys*


![Email templates](media/email-templates.jpg "Email templates")

*Email templates*

Also included with the **Patient Outreach** module is a Crisis Management Journey
and baseline marketing email template to provide the proactive outreach to the
predefined or newly created patient segments. This provides patient outreach
specialists the ability to utilize a multitude of channels including email, SMS,
surveys, and social channels for proactive outreach and ongoing communications.

## Patient portal and assessments

As a part of the Patient Scheduling and Screening template, it is paramount to have
a landing spot for patients to be able to search knowledge base articles for
information regarding COVID-19 as well as take a self-assessment to understand
their risk. The template provides a baseline portal that an organization can
take and configure to meet their individual needs. It also encompasses the ability
to embed Microsoft Healthbot Service to perform an assessment leveraging the
COVID-19 CDC template embedded in the Healthbot.

![Crisis management](media/crisis-management.png "crisis-management")

## Omnichannel contact center

The Microsoft Healthbot Service provides a simple mechanism to transfer at-risk
patients to Omnichannel for Customer Service to receive additional care. From
within Omnichannel for Customer Service, call center agents have the ability to
view the full transcript of the patient interaction as well as built-in
sentiment analysis. Also included in the template is a mechanism to perform a
search via zip code to find the closest testing center as well as providing the
slots that are open for booking at the location.

## Patient 360 in Omnichannel test scheduling

![Patient 360](media/patient-360.png "Patient 360")

*Patient 360 in Omnichannel*


![Test scheduling](media/test-scheduling.png "Test scheduling")

*Test scheduling*

## Appointment automation

After the appointment is booked, the template provides automation that sends the
patient a text or email (based on their preferred method of communication) with
details of the appointment and a QR/Bar Code for entry at the testing center.

This ensures that patients and testing centers are provided a secure mechanism
to receive screening.

![Appointment automation](media/appointment-automation.png "Appointment automation")

## Screening app

Utilizing a purpose-built canvas app, the test technician can search for the
patient record by last name or by scanning the QR/bar code that was provided
through the automation workflow above. Once the appointment and patient
information are retrieved, the technician can create a new observation and
capture necessary information while collecting a specimen for testing. Once the
specimen is in a container, the technician can scan the bar code on the specimen to
link the observation, patient, and specimen.

![Screening app](media/screening-app.png "Screening app")

## Issues and feedback

-   To report an issue with the Patient Scheduling and Screening sample app
    template, visit this
    [link](mailto:dynindaccsupport@microsoft.com?subject=Assistance%20for%20Health%20Care%20Accelerator%20from%20Appsource).

-   If you would like to engage with us to build on the accelerator, visit this [link](https://aka.ms/cdmengage).


---
title: Dynamics 365 nonprofit accelerator  | Microsoft Docs
description: Rapidly develop nonprofit fundraising, grant/award, program delivery, and impact-tracking solutions by using nonprofit entities in the Dynamics 365 nonprofit accelerator. 
author: lponti
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 12/16/2020
ms.author: lponti
---

# Dynamics 365 nonprofit accelerator

The Dynamics 365 nonprofit accelerator and Common Data Model for Nonprofits help organizations eliminate data silos, enabling powerful insights into their data. Microsoft is dedicated to working with nonprofits and partners to develop solutions based on entities and attributes that nonprofits commonly use for constituent management, fundraising, awards, program delivery, and impact tracking. 

These entities include, donor commitments, designations, transactions, awards, disbursements, delivery frameworks, results, indicators, benefit recipients, and more. The nonprofit accelerator provides a uniform platform for customers who wish to connect, embed, or extend the Dynamics 365 platform and Microsoft Power Platform and benefit from integration with Common Data Model for Nonprofits.

Since the initial release in November 2018 at the NetHope Global Summit we've had additional extensions and enhancements in six updated releases: 

- [April 2019](https://blogs.microsoft.com/on-the-issues/2018/04/20/new-solutions-to-help-nonprofits-drive-impact/) 
- [July 2019](https://cloudblogs.microsoft.com/dynamics365/bdm/2019/07/11/accelerating-opportunities-for-isvs-with-new-programs-and-technology/)
- [November 2019](https://www.linkedin.com/pulse/announcing-general-availability-dynamics-365-nonprofit-erik-arnold) 
- January 2020
- [June 2020](https://www.linkedin.com/pulse/latest-release-dynamics-365-nonprofit-accelerator-includes-arnold/)
- December 2020

The nonprofit accelerator provides the following to partners and nonprofit organizations:
- Extensions to Common Data Model for Nonprofits that include industry-standard definitions of constituent management, fundraising, awards, program delivery, and impact tracking data. The model includes 90+ entity data definitions and relationships.
- A Program design template application that partners can evolve to help nonprofit program and country managers to: 
  - Create and browse logframes (logical frameworks, the building blocks of effective program design).
- Connect logframes to internal, external, and standard indicators like the United Nations Sustainable Development Goals (SDGs) in order to improve program measurement and outcome tracking.
- Eight unique sample model-driven applications to help partners rapidly develop UI, workflows, and business logic to automate the following areas: 

  - Awards
  - Case management
  - Constituents
  - Delivery frameworks
  - Fundraising
  - IATI Hub
  - Project management & program design
  - Assessment management

- Support for extending the model with custom entities, forms, and relationships that meet nonprofit needs.
- Support for building canvas apps in Power Apps.
- Sample dashboards featuring fundraising and program delivery analytics that can be extended.
- Deployable sample data to bring the sample apps to life.
- A test drive experience through AppSource with walkthroughs, reference guides, mapping guides, entity-relationship diagrams, and metadata documentation on the data model.
- Data integrator templates and mappings to integrate data from the nonprofit accelerator in Dynamics 365.
- IATI add-on Common Data Model, sample model-driven app, sample data, flows, and documentation.

## What's new?

As part of the December 2020 v3.0 release, the nonprofit accelerator is enhanced in three critical nonprofit areas: assessment management, volunteer management and frontline humanitarian logistics. Our assessment management enhancements include extensions to Common Data Model, sample applications, and supporting sample data to enable partners to develop and launch solutions easily.

The nonprofit areas include:

1. Our assessment management Common Data Model extensions, sample app and sample data provide partners with a foundation to enable frontline workers to accurately, consistently, rapidly and efficiently record detailed observations and answer the "who," "where," "what," "how," and "when" questions critical to delivering nimble services. These investments allow disaster organizations to evaluate damage and assess on-the-ground needs to enable easier coordinated field response. The assessment management extensions support nonprofit program and beneficiary management and can be leveraged in tandem with the program management and case management data schema already included in the Common Data Model for Nonprofits. 

2. Convened by NetHope, the Frontline Humanitarian Logistics (FHL) initiative was created to reduce the time and cost involved in implementing IT solutions within humanitarian supply chains and encourage interoperability of data, service delivery, and systems across the sector. NetHope convened a cross-sector group of 24 collaborating academic, public, and private sector organizations which resulted in the development of a [Frontline Humanitarian Logistics Data Standard](https://solutionscenter.nethope.org/resources/initiatives/frontline-humanitarian-logistics). With this release, we are aligning item requests, types, and groups to that standard to further ease collaboration between nonprofits responding to the same crisis to ensure faster delivery of needed services. The Frontline Humanitarian Logistics data schema also provides nonprofits and partners with the foundation to provide donors with exact information about what items are in demand, where the supplies they helped fund with their donations were delivered, and the subsequent impact made to beneficiaries. The ability to report back on donor impact is critical at this time of increased demand for transparency.

3. The Frontline Humanitarian Logistics Mapping Guide provides guidance to nonprofits and partners on how to put the NetHope convened and sector-developed Frontline Humanitarian Logistics Data Standard into practice. This Guide maps the FHL Data Standard to the Common Data Model for Nonprofits to support organizations who align to these valuable industry standards.

4. Additional volunteer management extensions to the Common Data Model for Nonprofits will aid partners in building affordable solutions for nonprofits at a time when recruiting and retaining critical volunteers is essential. Organizations can track and recruit for a broad range of engagement opportunities, while volunteers themselves can align their time, talents, and qualifications with available volunteer opportunities. The new volunteer data extensions remove any dependency on Dynamics Project Service Automation (PSA). Now partners can build directly on PowerApps to lower the total cost of ownership to support volunteer engagement.

5. Streamlined Nonprofit Accelerator Architecture: As we continue to rapidly scale the Nonprofit Accelerator, we seek ways to increase friction-free innovation among our partner community. In line with this goal, we have brought all Nonprofit Accelerator data packages (with the exception of IATI data standard package) into the Nonprofit Core data schema layer. Streamlining data packages into a single Core package reduces dependencies on additional platform licenses, eliminates the tax of introducing additional data schema packages, ensures that partners have a one-stop shop for extending all Common Data Model for Nonprofit data schema.  

## Site map extensions

With the Dynamics 365 nonprofit accelerator, nonprofits can streamline their operational management of constituents, fundraising, grant and award management, program delivery, and impact tracking. The nonprofit accelerator can be used with Microsoft Dynamics 365 or independently with Common Data Model for Nonprofits core solution layer that is not dependent on Microsoft Dynamics 365. This independent solution layer can be leveraged to build Power Apps and Power BI visualizations, or to serve as a foundational layer to Modern Workplace and Azure solutions.

Nonprofits, ISVs, and others in the nonprofit sector can build their solutions and business processes on top of the new and existing entities and templates found within the nonprofit accelerator. The current data model supports common nonprofit activities but has been designed to allow flexibility to support other use cases and extensions.

The nonprofit accelerator and Common Data Model for Nonprofits are developed in collaboration with nonprofits, partners, industry experts, and open initiatives to ensure interoperability and accelerate impact to the nonprofit sector.

## Entities and workflows

The solutions in the nonprofit accelerator leverage Common Data Model for Nonprofits and can be leveraged to build solutions on the Microsoft Power Platform and/or Microsoft Dynamics 365. Depending on the partner and organization needs, the nonprofit accelerator can be implemented in multiple ways with dependencies to consider with each solution. These solution packages can be referenced on [GitHub](https://github.com/microsoft/Industry-Accelerator-Nonprofit/releases). The following explains the differences:

### Data schema

- Nonprofit core – This data schema contains the essentials for the nonprofit accelerator including views, forms, and data entities. It has no dependency on Microsoft Dynamics 365 and is only dependent on Microsoft Dataverse.
- Nonprofit IATI – This data schema creates efficiencies in IATI reporting compliance and depends on nonprofit core, and Microsoft Dataverse. 

### Functionality

- Program design – In order to support this application, this solution depends on nonprofit core and nonprofit measurement data schemas. 
- Nonprofit operations toolkit - In order to support this application, this solution depends on the nonprofit core data schema. 
- Common Data Model for Nonprofits sample apps - In order to support this application, this solution depends on the nonprofit core data schema.

The following illustration explains the solution layer dependencies. 

![Nonprofit accelerator solution layer dependencies](./media/nfp-accelerator/30Architecture.png)

For details about the entities and attributes, see the entity relationship diagrams and Admin Guide available on [GitHub](https://github.com/microsoft/Industry-Accelerator-Nonprofit).

## Forms, dashboards, and applications

The nonprofit accelerator combines standard Common Data Model entities with customized nonprofit entities. This section describes the forms, views, and dashboards that demonstrate the entities in the data model as well as applications that build out business rules.

This includes the following: 

Entities shown in the sample model-driven applications:

- Constituent management 
- Donation management 
- Fundraising 
- Awards management 
- Program delivery 
- Membership management 
- IATI processes  
- Finance and CRM data integrator 
- Case management 
- Project management & program design
- Assessment management

Applications using entities with built-out process and business rules:

- Program design application 
- Nonprofit operations toolkit

### Constituent management

Complete constituent profiles for individuals, households, and organizations, including biographical details, communication methods, preferences, relationships, salutations, employment and education history, donations, and awards management.

![Constituent management](./media/nfp-accelerator/constituent-management.png)

### Donation management

The sample dashboard for donations includes gift acknowledgements, tracking of individual and organizational pledges and gifts, one-time and recurring gifts, gifts in kind, and grant disbursements.

![Donation management](./media/nfp-accelerator/donation-management.png)

### Fundraising

The nonprofit accelerator can track all major stages of high-touch fundraising. 

![Tack major stages of high-touch fundraising](./media/nfp-accelerator/fundraising.png)

### Awards management

Awards management data model and sample application including dockets, inquiries, requests, awards recommendations, reviews, reports, budgets, and disbursements.

![Awards management](./media/nfp-accelerator/awards-management.png)

### Program delivery 

Outcome and result model enables nonprofits to efficiently deliver on their missions, measure results, and communicate impact that includes aligning beneficiaries and funds to the results framework.

![Program delivery](./media/nfp-accelerator/program-delivery.png)

### Membership management

The Membership Category entity establishes membership levels and Membership entity that links Constituents to Membership Category, enabling the creation and tracking of membership over time.

![Membership management](./media/nfp-accelerator/membership-management.png)

### IATI processes

[IATI](https://iatistandard.org) is a global campaign to create transparency in the records of how aid money is spent. The initiative hopes to ensure that aid money reaches its intended recipients with goals of improving standards of living worldwide and reducing poverty globally. Nonprofits can now record their fundraising and programmatic activities according to the IATI Organizational and Activity Standards, sync IATI non-embedded code lists with the nonprofit accelerator, and generate IATI Organization and Activity XML files from the nonprofit accelerator.  

![IATI processes](./media/nfp-accelerator/iati-processes.png)

### Finance and CRM data integrator

Template data integrator tasks to connect nonprofit accelerator constituents, donations, awards, and programs to Finance and Operations.

![Finance and CRM data integrator](./media/nfp-accelerator/finance-crm-data-integrator.png)

### Case management

Provides building blocks for partners to aid program staff in tracking clients and cases tying cases to specific program goals. 

![Case management](./media/nfp-accelerator/case-management.png)

### Project management & program design

Build a complete delivery framework that tracks activities and progress to a theory of change assuring delivery of programs aligned to indicators and program objectives, budgets, and results.

![Project management & program design](./media/nfp-accelerator/project-management-program-design.png)

### Assessment management

Accurately, consistently, rapidly and efficiently record detailed observations and answer the "who," "where," "what," "how," and "when" questions critical to delivering nimble services

![Assessment management](./media/nfp-accelerator/assessmentscreenshot.png)

### Nonprofit operations toolkit

Small nonprofits are able to centrally manage their award budgets, have workers enter time and expenses through a mobile application, approve submitted time and expenses, and track costs to the budget.

![Nonprofit operations toolkit](./media/nfp-accelerator/nonprofit-operations-toolkit.png)

Mobile application

![Mobile application](./media/nfp-accelerator/nonprofit-operations-toolkit-mobile-app.png)

## Additional resources

- Download the [Dynamics 365 nonprofit accelerator](https://appsource.microsoft.com/product/dynamics-365/msnfp.msftnonprofitcommondatamodel?src=office&tab=Overview) from AppSource.

- The nonprofit data model, solutions, data samples, data samples, SDK extensions, and more are provided as part of the open-source creative license and available on [GitHub](https://github.com/microsoft/Industry-Accelerator-Nonprofit/releases).

- [Additional topics](https://community.dynamics.com/365/b/dynamics365isvsuccess/archive/2018/08/01/dynamics-365-brings-industry-focus-through-the-microsoft-power-platform-and-solution-accelerators) about the accelerators.

- Continue your accelerator experience and engage with experts and peers, read blog articles, and find local events within the industry accelerator community. [Join us](https://community.dynamics.com/365/industry-accelerators).


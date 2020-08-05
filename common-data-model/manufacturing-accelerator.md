---

title: Dynamics 365 manufacturing accelerator | Microsoft Docs
description:  Develop manufacturing solutions with extensions to Common Data Model. Connect to built-in forms and Dynamics 365 manufacturing accelerator views.
author: MeenooRami
ms.service: common-data-model
ms.reviewer: v-dehaas
ms.topic: article
ms.date: 07/15/2020
ms.author: merami

---

# Dynamics 365 manufacturing accelerator

The Dynamics 365 manufacturing accelerator release enables manufacturers to quickly develop solutions or extend sample applications tailored to business needs. This accelerator helps facilitate intelligent supplier relationship management and onboarding.

We provide a manufacturing data model, sample power portal, sample apps, automated templates, and Power BI dashboards. This creates a seamless role-based supplier qualification, API onboarding, and supplier management console experience. This accelerator helps manufacturing organizations to digitize this process within hours using our low-code, no-code platform capabilities.

The accelerator includes the following features via Power Apps portals:

- Enable new suppliers to contact a manufacturer.
- Qualify a new supplier.
- Enable API data integration onboarding.
- Maintain and provide ongoing visibility into supplier transactions.
- Maintain and provide ongoing visibility into API data exchange.

The accelerator includes the following features via a model-driven app:

- Manage and approve access requests.
- Manage and approve supplier requests.
- Manage and track supplier health.

The supplier relationship-management scenario as part of the manufacturing accelerator puts the full strength of Microsoft Power Platform to use, helping manufacturing organizations to optimize their supplier and sales relationships and enabling them to more effectively manage those important supplier relationships.

## Site-map extensions

You can use the manufacturing accelerator with a model-driven app for Microsoft Dynamics 365, or independently using the core solution layer that is not dependent on Dynamics 365. You can use the independent solution layer to build model-driven and canvas-based Power Apps applications.

When the accelerator is installed into a model-driven app for Dynamics 365, it enables you to optimize supplier operational processes including purchase orders (POs), expected receipts, and invoicing based on the IATI standard. You can also leverage the entire solution within the Dynamics 365 app.

The manufacturing data model is developed in collaboration with partners, industry experts, and open initiatives to ensure interoperability and to accelerate supplier impact.

## Entities and workflows
This accelerator includes these entities to support the supplier relationship management scenario:


|**Supplier onboarding**|**Questionnaire framework**|**Electronic communication**|**Workflow**|**Process**|**Power Automate**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
Account|Question|Account Communication Configuration|Assign Supplier Web Role|Approval process|Add External User
Contact|Questionnaire Question| |Populate decision fields| | 
Access Request|Questionnaire Template| | | | 
Access Request Approval|Questionnaire Template Question| | | | 
Capability Type|Vendor Questionnaire| | | | 
Certification Type| | | | | 
Credit Rating| | | | | 
Department| | | | | 
Identifier| | | | | 
Product Classification| | | | | 
Vendor Capability| | | | | 
Vendor Certification| | | | | 

## Forms and dashboards

The Dynamics 365 manufacturing accelerator combines standard Dynamics 365 entities with customized entities to make it easier to build solutions. This section describes some of the forms, views, and dashboards that demonstrate the new entities and the data model.

The initial access request from a registration form is to initiate the conversation with a manufacturing organization regarding the intent to be a new supplier of parts or products. The accelerator includes an extensible model for a manufacturing organization to enable Azure Active Directory authentication or replace this with any other authentication type.

The portal experience focuses on supporting two personas, a business development manager from a potential new supplier and the supplier's IT administration team. If you are  seeking to be a new supplier, then you start a new registration process. However, if you are currently an existing supplier and would like to get your development team connected, you can do so via API data integration through the portal.

The model-driven experience focuses on the manufacturer's administrative needs and the procurement department largely manages the suppliers.

This section provides examples of the forms and dashboards that demonstrate the entities in the data model for this accelerator.

## New supplier registration

The supplier management functionality of the portal will allow new suppliers to access the site. To apply as a new supplier and to proceed with the approval process, the supplier selects **Register**.

> [!div class="mx-imgBorder"]
> ![Supplier management screen](media/mfg-supplier-mgmt-screen.png "Supplier management screen")

After they select **Register**, they fill out the basic information on a registration form to begin the approval process.

> [!div class="mx-imgBorder"]
> ![Supplier information screen](media/mfg-supplier-info-screen.png "Supplier information screen")

## Model-driven app
The manufacturing organization reviews the form, and can approve or reject the new supplier’s request.

> [!div class="mx-imgBorder"]
> ![Supplier request screen](media/mfg-review-request.png "Supplier request screen")

Upon approval, the supplier receives an invitation link in email to complete the onboarding process.

> [!div class="mx-imgBorder"]
> ![Supplier invitation screen](media/mfg-invite.png "Supplier invitation screen")

## Dashboard

Here is some of the available standard, predefined dashboard information. This view shows the status of a specific supplier's functions.

> [!div class="mx-imgBorder"]
> ![Supplier dashboard screen](media/mfg-dashboard.png "Supplier dashboard screen")

## Supplier qualification

Once approved, the supplier can easily onboard within the portal. They select **Supplier Onboarding**, and then select **Continue**.

> [!div class="mx-imgBorder"]
> ![Getting started screen](media/mfg-getting-started.png "Getting started screen")

Now, the newly approved supplier can add additional information about their company. They can also update their information later.

> [!div class="mx-imgBorder"]
> ![Supplier detail screen](media/mfg-supplier-detail-screen.png "Supplier detail screen")

## API onboarding
When the supplier selects **API Onboarding** from the drop-down menu on the main screen, they can add their technical team for EDI transactions and setup.

> [!div class="mx-imgBorder"]
> ![Developer onboarding screen](media/mfg-dev-onboarding.png "Developer onboarding screen")

Once the developers have been approved, they will be able to enter the EDI interface information and the testing of transactions both inbound and outbound.

> [!div class="mx-imgBorder"]
> ![Developer onboarding screen - select EDI](media/mfg-dev-edi.png "Developer onboarding screen - select EDI")

The basic information that the developer or supplier IT team needs to provide and the information they need to send a message securely to the right API end point. There are multiple tabs, as in the view below. 
<!--note from editor: There's a word missing in teh sentence above around the word "message", but I can't tell what you are trying to say. Please fix.  -->

> [!div class="mx-imgBorder"]
> ![Developer EDI details screen](media/mfg-dev-edi2.png "Developer EDI details screen")

## Business partner dashboard

The supplier has a management experience with two dashboards included in the accelerator. This helps them understand the health of the relationship. These dashboards show open purchase orders and KPIs around the health of the supplier’s relationship with the manufacturer.

> [!div class="mx-imgBorder"]
> ![Business partner dashboard](media/mfg-partner-dashboard.png "Business partner dashboard")

## Additional resources

- Download the Dynamics 365 manufacturing accelerator from [AppSource](https://aka.ms/d365manuf).

- The manufacturing data model, solutions, data samples, Power BI examples, SDK extensions, and more are provided as part of the open-source creative license available on [Github](https://github.com/microsoft/Dynamics-365-Industry-Accelerators).

- Additional  [accelerator topics](https://community.dynamics.com/365/b/dynamics365isvsuccess/archive/2018/08/01/dynamics-365-brings-industry-focus-through-the-microsoft-power-platform-and-solution-accelerators).

- Continue your accelerator experience and engage with experts and peers, read blog articles, and find local events within the industry accelerator community. [Join us](https://community.dynamics.com/365/industry-accelerators)

## Connect and share feedback

Do you have feedback or need support? Contact us at [dynindaccsupport@microsoft.com](mailto:dynindaccsupport@microsoft.com).

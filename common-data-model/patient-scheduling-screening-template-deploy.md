---
title: Deploy and configure the Patient Scheduling and Screening Template - Dynamics 365 | Microsoft Docs
description: Develop healthcare solutions with the extensions to the Common Data Model and built-in forms and views of the Dynamics 365 Healthcare Accelerator.
author: andreabichsel
ms.service: common-data-model
ms.reviewer: anbichse
ms.topic: article
ms.date: 04/01/2020
ms.author: anbichse
---

# Deploy and configure the Patient Scheduling and Screening Template

The Patient Scheduling and Screening Template requires a small amount of setup to adapt to your needs. This article provides step-by-step instructions for hospital IT admins and/or partners to deploy and configure the application for their organization. 

> [!NOTE]
> The instructions below have been divided by the individual use-cases encompassed in the Crisis Management Template.

Estimated time to complete these steps: 35–40 minutes.

Please browse to the following location in order to download the files/solutions needed to install the solutions:

## Prerequisite Files 

- To import the Main Solutions, acquire the following managed solution files: 
  - Dynamics365ElectronicMedicalRecords_2_2_0_3_managed.zip 
  - MicrosoftDynamicsHealthcareCustomerService_3_0_3_0_managed.zip 
  - MicrosoftDynamics365PatientSegmentation_3_0_3_0_managed.zip 
  - SpatialSolution_1_4_0.zip
  - MicrosoftDynamicsHealthcareCrisisManagement_1_0_0_0_managed.zip)
  - CrisisManagementPortalDataPackage.zip
  - SampleDataPackage.zip
  - MarketingDataPackage.zip
- To import the Additional Solutions, you’ll need to acquire the Configuration Migration Tool and following data files: 
  - Configuration Migration Tool folder 
  - Crisis Portal - DataPackage.zip 
  - Marketing Data Package - DataPackage.zip 

## Additional Solutions 

To import, follow steps in the “Import Additional Solutions with Configuration Migration Tool” section below. 

1. Crisis Portal 
   1. Stand up new Portal with Portal Template = Portal from Blank 
   2. Use Configuration Migration Tool to import Crisis Portal - DataPackage.zip 
   3. *Import Outcome: Successful after clearing all search history/cache. 

2. Marketing Data Package 
   1. Data package contains customer journeys, segments and marketing emails entities. 
   2. Use Configuration Migration Tool to import Marketing Data Package - DataPackage.zip 

## Omni Channel Capabilities

For steps on how to create your Healthcare Bot in Azure, create a bot user in Dynamics 365 and embed the Healthcare Bot onto a portal, please access the Healthcare Bot and Omni Channel guide amongst the included documentation.  

### Dependencies 

1. OmniChannel: Install OmniChannel in environment following these steps: https://docs.microsoft.com/en-us/dynamics365/omnichannel/administrator/omnichannel-provision-license 
   - Provisioning takes an Admin Role 
   - Needed to run through setup twice for it to work 
   - Took about 2 hours. 

2. Productivity Pack: Install Productivity Pack in environment through Appsource: https://appsource.microsoft.com/en-us/product/dynamics-365/mscrm.d365_productivity_tools?tab=Overview 
   - Dependency on OmniChannel 

## Setup HealthBot Service

### Create your Healthcare bot in Azure:

1. Navigate to Azure Marketplace.
2. Sign in, and search for "Microsoft Healthcare Bot"
3. Click create
4. Configure with appropriate name, subscription, resource group, etc.
5. Click Subscribe
6. One deploy is complete, click "Go to Resource"
7. Click "Configure Account"
8. Once configured, it should be ready.
9. Navigate to the bot in azure, and you should be able to click "Browse" and see the URL for your particular bot.
10. You can also access the Healthcare Bot admins portal here: https://admin.healthbot.microsoft.com 
11. Further Info: https://docs.microsoft.com/en-us/healthbot/quickstart-createyourhealthcarebot 

### Enable Omni Channel for bot:

1. Navigate to Healthcare Bot admins portal
2. Go to configuration -> Conversation -> Human handoff
3. Set "Dynamics 365 OmniChannel "Bridge Messages" to "Enabled", and save

### Obtain Bot ID:

1. To get your Healthcare bot id, which you need later, navigate to the Healthcare Bot management portal (https://us.healthbot.microsoft.com/account/ia_dev_healthcare-tunapir/scenarios/manage)
2. Go to Integration -> Channels and enable the "Teams" channel if not already. Click the "View" option and copy the Bot ID. You will need it later.
3. Bot ID:

### Create Bot User in Dynamics 365:

Assumption is that you have Omni Channel installed for the particular Dynamics org

1. Navigate to the Dynamics org that the portal is under
2. Go to Settings -> Security -> Users
3. Click “New”, and make sure the Application User view for the form is selected
4. Pick a Username that is appropriate
5. Application ID must be a valid, non-expired application created in the Azure AD of the same tenant. This is not used by the bot, so it can be any.
   a. Navigate to Azure -> Azure Active Directory -> App Registrations.
   b. Click new registration
   c. Enter appropriate name, set as “Microsoft only – Single tenant”
   d. Click Register
   e. Note the “Application (client) id” and use that for the Application ID field
6. Full Name is the name that will display on the chat widget
7. Primary email can be a dummy address, it is not used.
8. User type, set to “Bot application user”
9. Bot application id, the id you saved earlier.
10. Click save
11. Go to “Manage roles” and give the user the role “Omnichannel agent” and click ok
12. Further reading here: https://docs.microsoft.com/en-us/healthbot/omnichannel 
   a. Add a bot user to the queue(s)
   b. Set escalation rules
   c. Create a context variable
   d. Create routing rules
   e. Escalate a conversation to a human agent
   f. End a conversation
   g. Sample Custom Scenario for escalation

### Embed the Healthcare Bot onto a Portal:

1. This should NOT be needed unless you want to perform specific testing with the Healthcare bot and not connect through Omni Channel. Though it should be unnecessary since you can test the bot directly in the scenario editor.
2. You will need to obtain both the App secret and Web chat secret for the bot under the management portal -> Integration -> Secrets and save for later
3. Web Chat Secret: 
4. App Secret: 
5. Download the sample Healthbot container from github: https://github.com/Microsoft/HealthBotContainerSample/
6. Unzip, npm install, and configure appropriately based on the Readme on github to test to make sure you can connect to your Healthbot service with the secrets
7. Deploy this application as a App Service to Azure: https://docs.microsoft.com/en-us/azure/app-service/app-service-web-get-started-nodejs
8. In the App service configuration, add the appropriate environment variables with the Web Chat Secret and App Secret.
9. Test the app service URL, showing that it runs.
10. Healthbot deployed URL:
11. Further reading: https://docs.microsoft.com/en-us/healthbot/integrations/embed
12. Further reading: https://github.com/Microsoft/HealthBotContainerSample/ 

### How Omni Channel and Healthcare bot work together

The flow is as follows:

1. You embed the Omni Channel bot (NOT Healthcare bot) onto a site (See “Chat Widgets” In Dynamics.
2. You set the bot up in Dynamics to, by default, route to the Healthcare bot.
3. The healthcare bot now uses the Omni Channel bot to converse with the user.
4. The scenario or scenarios will run via the Healthcare bot configuration, until the chat ends, or an escalation occurs.
5. When an escalation occurs, this is passed back to Omni Channel, with appropriate context variables set.
6. Omni Channel now re runs the routing logic, and since there are context variables, you can configure Omni Channel to route this request to another queue that does NOT contain a bot, but actual agents
7. Agents can pick up the chat and continue chatting via Omni Channel.

### Install the COVID-19 Scenario templates into the Healthbot

1. COVID-19 Assessment
2. COVID-19 FAQs
   - You will need a QnA Maker Subscription Key, which can be created here: https://portal.azure.com/#create/Microsoft.CognitiveServicesQnAMaker 
3. COVID-19 Metrics
   - You will need a LUIS Prediction key, which can be created here: https://docs.microsoft.com/en-us/azure/cognitive-services/luis/get-started-portal-deploy-app 

### Install Healthbot scenario files

1. There are 2 located in the “Healthbot Scenarios” folder
2. To learn how to import scenarios: https://docs.microsoft.com/en-us/healthbot/scenario-authoring/scenario_management

### Bot Setup for Crisis Management

1. You will need to go into the 2 scenarios imported and ensure that the scenarios they called are referenced properly.
2. You will need to modify the COVID-19 Assessment scenario.
   1. Find the “Development note”
   2. Delete it and replace it with an “End Scenario With Result”
   3. Set the return value: "AgentNeeded"
3. In the Healthbot, disabled all Language models except the following:
   - COVID-19 Case Metrics
   - COVID-19 FAQs
4. Create the following Language Model and enable it
   - Name: Crisis Assessment Model
   - Description: same as above
   - Method: RegExp
   - Regular Expression: /(Assessment)/gi
   - Intent Mapping: CrisisAssessment -> crisis_assessment_entry
5. Create the following Language Model and enable it
   - Name: Crisis Talk To Agent Model
   - Description: same as above
   - Method: RegExp
   - Regular Expression: /(Agent)/gi
   - Intent Mapping: CrisisTalkToAgent -> crisis_talk_to_agent_entry
6. In Omni Channel, you will need to spin up a Chat Widget. You will then need to embed it into the Portal (there will be an existing Chat Widget in the footer web template of the Portal website, but it will need to be replaced with the one you create)
   - To learn how to do this, see: https://docs.microsoft.com/en-us/dynamics365/omnichannel/administrator/configure-live-chat
7. When creating queues and rules, one rule to note is “EscalateQueue”.
   - This text field will be set to “COVID19AssessmentQueue” when the COVID-19 Assessment scenario determines a person may be at risk of having COVID-19, and it has determined they need to speak with an agent
   - This text field will be set to “TalkToAgentQueue” when the user is forcing to talk to an agent that is not related to a scenario.

### Patient Segmentation Capabilitites

1. Marketing Application: From https://port.crm.dynamics.com/G/Applications/Index.aspx#, install “Dynamics 365 Marketing Application” in environment. 
   - Took much longer than 20 minutes to install and timed out frequently (~3 hours total) 
2. Updating Settings on Marketing Entities:  
   After the Marketing Application install completes, you will have to update two settings before you install this solution. Follow the steps below: 
   1. Navigate to the newly installed Marketing App 
   2. In the lower left-hand corner change from Marketing to Settings. 
   3. Click on Advanced Settings > Marketing data configuration 
   4. Check both “Condition (msemr_condition)” and “Procedure (msemr_procedure)”. 
   5. Scroll back up and click Publish Changes button. 

## Manually Import Main Solutions  

To manually import a main solution:

1. Navigate to https://make.powerapps.com/home  > Select your Environment > Click Solutions in left-hand Navigation. 
2. Click Import button in ribbon. 
3. Click Choose File button and select managed solution zip file. 
4. Click Open button. 
5. Click Next through all steps and then Import. 
   > [!NOTE]
   > Note: Dynamics365ElectronicMedicalRecords solution may take up to an hour to install, the rest only a couple minutes. 

## Import additional solutions with the Configuration Migration tool 

To import an additional solution using the Configuration Migration tool: 

1. Open “Configuration Migration Tool” folder (Note: Make sure folder is on Desktop so directory name is short). 
2. Right click “downloadlatest.ps1” and click “Run with Powershell”, Type 'A', click ENTER and wait for it to complete. 
3. Open the new “Tools” folder, then “ConfigurationMigration”, and run “DataMigrationUtility”. 
4. To Import: 
   1. Select “Import Data”. 
   2. Connect to the org to import the data to. 
   3. Select the appropriate data zip file (should be named “DataPackage.zip”). 
   4. Perform the import.
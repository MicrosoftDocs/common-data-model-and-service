---
title: Lead - Common Data Model | Microsoft Docs
description: This describes the Lead entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Lead

A prospect or a potential sales opportunity. Leads are converted into accounts, contacts, or opportunities when they're qualified. Otherwise, they're deleted or archived.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Lead.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/foundationCommon/crmCommon/Lead](../../Lead.md "/core/applicationCommon/foundationCommon/crmCommon/Lead.cdm.json/Lead")  
- [/foundationCommon/crmCommon/accelerators/automotive/Lead](../automotive/Lead.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/Lead.cdm.json/Lead")  
- [/foundationCommon/crmCommon/accelerators/financialServices/banking/Lead](../financialServices/banking/Lead.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/financialServices/banking/Lead.cdm.json/Lead")  
- /foundationCommon/crmCommon/accelerators/nonProfit/Lead  
- [/foundationCommon/crmCommon/projectCommon/Lead](../../projectCommon/Lead.md "/core/applicationCommon/foundationCommon/crmCommon/projectCommon/Lead.cdm.json/Lead")  
- [/foundationCommon/crmCommon/solutions/marketing/Lead](../../solutions/marketing/Lead.md "/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Lead.cdm.json/Lead")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[leadId](#leadId)|Unique identifier of the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[fullName](#fullName)|Combines and shows the lead's first and last names so the full name can be displayed in views and reports.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[parentAccountId](#parentAccountId)|Choose an account to connect this lead to, so that the relationship is visible in reports and analytics.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[parentContactId](#parentContactId)|Choose a contact to connect this lead to, so that the relationship is visible in reports and analytics.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1AddressId](#address1AddressId)|Unique identifier for address 1.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1AddressTypeCode](#address1AddressTypeCode)|Select the primary address type.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1AddressTypeCode_display](#address1AddressTypeCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1City](#address1City)|Type the city for the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Composite](#address1Composite)|Shows the complete primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Country](#address1Country)|Type the country or region for the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1County](#address1County)|Type the county for the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Fax](#address1Fax)|Type the fax number associated with the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Latitude](#address1Latitude)|Type the latitude value for the primary address for use in mapping and other applications.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Line1](#address1Line1)|Type the first line of the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Line2](#address1Line2)|Type the second line of the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Line3](#address1Line3)|Type the third line of the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Longitude](#address1Longitude)|Type the longitude value for the primary address for use in mapping and other applications.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Name](#address1Name)|Type a descriptive name for the primary address, such as Corporate Headquarters.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1PostalCode](#address1PostalCode)|Type the ZIP Code or postal code for the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1PostOfficeBox](#address1PostOfficeBox)|Type the post office box number of the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1ShippingMethodCode](#address1ShippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1ShippingMethodCode_display](#address1ShippingMethodCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1StateOrProvince](#address1StateOrProvince)|Type the state or province of the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Telephone1](#address1Telephone1)|Type the main phone number associated with the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Telephone2](#address1Telephone2)|Type a second phone number associated with the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1Telephone3](#address1Telephone3)|Type a third phone number associated with the primary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1UPSZone](#address1UPSZone)|Type the UPS zone of the primary address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address1UTCOffset](#address1UTCOffset)|Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2AddressId](#address2AddressId)|Unique identifier for address 2.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2AddressTypeCode](#address2AddressTypeCode)|Select the secondary address type.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2AddressTypeCode_display](#address2AddressTypeCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2City](#address2City)|Type the city for the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Composite](#address2Composite)|Shows the complete secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Country](#address2Country)|Type the country or region for the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2County](#address2County)|Type the county for the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Fax](#address2Fax)|Type the fax number associated with the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Latitude](#address2Latitude)|Type the latitude value for the secondary address for use in mapping and other applications.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Line1](#address2Line1)|Type the first line of the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Line2](#address2Line2)|Type the second line of the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Line3](#address2Line3)|Type the third line of the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Longitude](#address2Longitude)|Type the longitude value for the secondary address for use in mapping and other applications.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Name](#address2Name)|Type a descriptive name for the secondary address, such as Corporate Headquarters.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2PostalCode](#address2PostalCode)|Type the ZIP Code or postal code for the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2PostOfficeBox](#address2PostOfficeBox)|Type the post office box number of the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2ShippingMethodCode](#address2ShippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2ShippingMethodCode_display](#address2ShippingMethodCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2StateOrProvince](#address2StateOrProvince)|Type the state or province of the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Telephone1](#address2Telephone1)|Type the main phone number associated with the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Telephone2](#address2Telephone2)|Type a second phone number associated with the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2Telephone3](#address2Telephone3)|Type a third phone number associated with the secondary address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2UPSZone](#address2UPSZone)|Type the UPS zone of the secondary address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[address2UTCOffset](#address2UTCOffset)|Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[budgetAmount](#budgetAmount)|Information about the budget amount of the lead's company or organization.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[budgetAmountBase](#budgetAmountBase)|Value of the Budget Amount in base currency.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[budgetStatus](#budgetStatus)|Information about the budget status of the lead's company or organization.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[budgetStatus_display](#budgetStatus_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[companyName](#companyName)|Type the name of the company associated with the lead. This becomes the account name when the lead is qualified and converted to a customer account.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[confirmInterest](#confirmInterest)|Select whether the lead confirmed interest in your offerings. This helps in determining the lead quality.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[decisionMaker](#decisionMaker)|Select whether your notes include information about who makes the purchase decisions at the lead's company.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[description](#description)|Type additional information to describe the lead, such as an excerpt from the company's website.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[doNotBulkEMail](#doNotBulkEMail)|Select whether the lead accepts bulk email sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the lead can be added to marketing lists, but will be excluded from the email.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[doNotEMail](#doNotEMail)|Select whether the lead allows direct email sent from Microsoft Dynamics 365.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[doNotFax](#doNotFax)|Select whether the lead allows faxes.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[doNotPhone](#doNotPhone)|Select whether the lead allows phone calls.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[doNotPostalMail](#doNotPostalMail)|Select whether the lead allows direct mail.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[doNotSendMM](#doNotSendMM)|Select whether the lead accepts marketing materials, such as brochures or catalogs. Leads that opt out can be excluded from marketing initiatives.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[EMailAddress1](#EMailAddress1)|Type the primary email address for the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[EMailAddress2](#EMailAddress2)|Type the secondary email address for the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[EMailAddress3](#EMailAddress3)|Type a third email address for the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[estimatedAmount](#estimatedAmount)|Type the estimated revenue value that this lead will generate to assist in sales forecasting and planning.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[estimatedAmountBase](#estimatedAmountBase)|Value of the Est. Value in base currency.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[estimatedCloseDate](#estimatedCloseDate)|Enter the expected close date for the lead, so that the sales team can schedule timely follow-up meetings to move the prospect to the next sales stage.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[estimatedValue](#estimatedValue)|Type a numeric value of the lead's estimated value, such as a product quantity, if no revenue amount can be specified in the Est. Value field. This can be used for sales forecasting and planning.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[evaluateFit](#evaluateFit)|Select whether the fit between the lead's requirements and your offerings was evaluated.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[fax](#fax)|Type the fax number for the primary contact for the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[firstName](#firstName)|Type the first name of the primary contact for the lead to make sure the prospect is addressed correctly in sales calls, email, and marketing campaigns.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[industryCode](#industryCode)|Select the primary industry in which the lead's business is focused, for use in marketing segmentation and demographic analysis.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[industryCode_display](#industryCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[initialCommunication](#initialCommunication)|Choose whether someone from the sales team contacted this lead earlier.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[initialCommunication_display](#initialCommunication_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[jobTitle](#jobTitle)|Type the job title of the primary contact for this lead to make sure the prospect is addressed correctly in sales calls, email, and marketing campaigns.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[lastName](#lastName)|Type the last name of the primary contact for the lead to make sure the prospect is addressed correctly in sales calls, email, and marketing campaigns.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[lastUsedInCampaign](#lastUsedInCampaign)|Shows the date when the lead was last included in a marketing campaign or quick campaign.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[leadQualityCode](#leadQualityCode)|Select a rating value to indicate the lead's potential to become a customer.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[leadQualityCode_display](#leadQualityCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[leadSourceCode](#leadSourceCode)|Select the primary marketing source that prompted the lead to contact you.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[leadSourceCode_display](#leadSourceCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[masterId](#masterId)|Unique identifier of the master lead for merge.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[merged](#merged)|Tells whether the lead has been merged with another lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[middleName](#middleName)|Type the middle name or initial of the primary contact for the lead to make sure the prospect is addressed correctly.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[mobilePhone](#mobilePhone)|Type the mobile phone number for the primary contact for the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[need](#need)|Choose how high the level of need is for the lead's company.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[need_display](#need_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[numberOfEmployees](#numberOfEmployees)|Type the number of employees that work at the company associated with the lead, for use in marketing segmentation and demographic analysis.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[pager](#pager)|Type the pager number for the primary contact for the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[participatesInWorkflow](#participatesInWorkflow)|Shows whether the lead participates in workflow rules.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[preferredContactMethodCode](#preferredContactMethodCode)|Select the preferred method of contact.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[preferredContactMethodCode_display](#preferredContactMethodCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[priorityCode](#priorityCode)|Select the priority so that preferred customers or critical issues are handled quickly.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[priorityCode_display](#priorityCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[purchaseProcess](#purchaseProcess)|Choose whether an individual or a committee will be involved in the  purchase process for the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[purchaseProcess_display](#purchaseProcess_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[qualificationComments](#qualificationComments)|Type comments about the qualification or scoring of the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[revenue](#revenue)|Type the annual revenue of the company associated with the lead to provide an understanding of the prospect's business.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[revenueBase](#revenueBase)|Value of the Annual Revenue in base currency.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[salesStage](#salesStage)|Select the sales stage of this lead to aid the sales team in their efforts to convert this lead to an opportunity.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[salesStage_display](#salesStage_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[salesStageCode](#salesStageCode)|Select the sales process stage for the lead to help determine the probability of the lead converting to an opportunity.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[salesStageCode_display](#salesStageCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[salutation](#salutation)|Type the salutation of the primary contact for this lead to make sure the prospect is addressed correctly in sales calls, email messages, and marketing campaigns.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[scheduleFollowupProspect](#scheduleFollowupProspect)|Enter the date and time of the prospecting follow-up meeting with the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[scheduleFollowUpQualify](#scheduleFollowUpQualify)|Enter the date and time of the qualifying follow-up meeting with the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[SIC](#SIC)|Type the Standard Industrial Classification (SIC) code that indicates the lead's primary industry of business for use in marketing segmentation and demographic analysis.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[stateCode](#stateCode)|Shows whether the lead is open, qualified, or disqualified. Qualified and disqualified leads are read-only and can't be edited unless they are reactivated.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[stateCode_display](#stateCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[statusCode](#statusCode)|Select the lead's status.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[statusCode_display](#statusCode_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[subject](#subject)|Type a subject or descriptive name, such as the expected order, company name, or marketing source list, to identify the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[telephone1](#telephone1)|Type the work phone number for the primary contact for the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[telephone2](#telephone2)|Type the home phone number for the primary contact for the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[telephone3](#telephone3)|Type an alternate phone number for the primary contact for the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[purchaseTimeFrame](#purchaseTimeFrame)|Choose how long the lead will likely take to make the purchase, so the sales team will be aware.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[purchaseTimeFrame_display](#purchaseTimeFrame_display)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[webSiteUrl](#webSiteUrl)|Type the website URL for the company associated with this lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the Lead record.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this case. This field is for internal use only.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[followEmail](#followEmail)|Information about whether to allow following email activity like opens, attachment views and link clicks for emails sent to the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[timeSpentByMeOnEmailAndMeetings](#timeSpentByMeOnEmailAndMeetings)|Total time spent for emails (read and write) and meetings by me in relation to the lead record.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[entityImageId](#entityImageId)||<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[accountId](#accountId)|Unique identifier of the account with which the lead is associated.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[contactId](#contactId)|Unique identifier of the contact with which the lead is associated.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[yomiCompanyName](#yomiCompanyName)|Type the phonetic spelling of the lead's company name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[yomiFirstName](#yomiFirstName)|Type the phonetic spelling of the lead's first name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[yomiFullName](#yomiFullName)|Combines and shows the lead's Yomi first and last names so the full phonetic name can be displayed in views and reports.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[yomiLastName](#yomiLastName)|Type the phonetic spelling of the lead's last name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[yomiMiddleName](#yomiMiddleName)|Type the phonetic spelling of the lead's middle name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[campaignId](#campaignId)|Choose the campaign that the lead was generated from to track the effectiveness of marketing campaigns and identify  communications received by the lead.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[relatedObjectId](#relatedObjectId)|Related Campaign Response.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[originatingCaseId](#originatingCaseId)|This attribute is used for Sample Service Business Processes.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[qualifyingOpportunityId](#qualifyingOpportunityId)|Choose the opportunity that the lead was qualified on and then converted to.|<a href="../../Lead.md" target="_blank">crmCommon/Lead</a>|
|[GDPROptOut](#GDPROptOut)|Describes whether lead is opted out or not|<a href="../../projectCommon/Lead.md" target="_blank">projectCommon/Lead</a>|
|[orderType](#orderType)|Whether the Opportunity created when qualifying this Lead is for an Item- based or a Work-based sale|<a href="../../projectCommon/Lead.md" target="_blank">projectCommon/Lead</a>|
|[orderType_display](#orderType_display)||<a href="../../projectCommon/Lead.md" target="_blank">projectCommon/Lead</a>|
|[applicationDeadline](#applicationDeadline)|Deadline to submit application.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[deliveryFrameworkId](#deliveryFrameworkId)||<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[expectedAmountRequested](#expectedAmountRequested)|Amount requested by the Grant Seeker.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[expectedamountrequestedBase](#expectedamountrequestedBase)|Value of the Expected Amount Requested in base currency.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[expectedDuration](#expectedDuration)|Expected duration of the Grant in months.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[expectedStartDate](#expectedStartDate)|Expected start date of the Grant.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[isRenewal](#isRenewal)|Indicates if this is a renewal Grant.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[leadDocketId](#leadDocketId)|Docket|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[letterofIntentDeadline](#letterofIntentDeadline)|Deadline to submit notification to donor that organization will be competing for this grant.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[organizationalBudget](#organizationalBudget)|Total budget of the Organization.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[organizationalBudgetBase](#organizationalBudgetBase)|Value of the Organization Budget in base currency.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[organizationType](#organizationType)|Type of Account.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[organizationType_display](#organizationType_display)||<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[requestType](#requestType)|Indicates the type of Inquiry/LOI/Lead.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[requestType_display](#requestType_display)||<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[totalProjectBudget](#totalProjectBudget)|Budget defined by the Grant Seeker.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|
|[totalProjectBudgetBase](#totalProjectBudgetBase)|Value of the Total Project Budget in base currency.|<a href="Lead.md" target="_blank">nonProfit/Lead</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#leadId name="leadId">leadId</a>

Unique identifier of the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead</td></tr><tr><td>description</td><td>Unique identifier of the lead.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>leadid</td></tr></table>

### <a href=#fullName name="fullName">fullName</a>

Combines and shows the lead's first and last names so the full name can be displayed in views and reports.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Combines and shows the lead's first and last names so the full name can be displayed in views and reports.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fullname</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#parentAccountId name="parentAccountId">parentAccountId</a>

Choose an account to connect this lead to, so that the relationship is visible in reports and analytics.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Account for lead</td></tr><tr><td>description</td><td>Choose an account to connect this lead to, so that the relationship is visible in reports and analytics.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentaccountid</td></tr></table>

### <a href=#parentContactId name="parentContactId">parentContactId</a>

Choose a contact to connect this lead to, so that the relationship is visible in reports and analytics.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Contact for lead</td></tr><tr><td>description</td><td>Choose a contact to connect this lead to, so that the relationship is visible in reports and analytics.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentcontactid</td></tr></table>

### <a href=#address1AddressId name="address1AddressId">address1AddressId</a>

Unique identifier for address 1.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: ID</td></tr><tr><td>description</td><td>Unique identifier for address 1.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_addressid</td></tr></table>

### <a href=#address1AddressTypeCode name="address1AddressTypeCode">address1AddressTypeCode</a>

Select the primary address type.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Address Type</td></tr><tr><td>description</td><td>Select the primary address type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address1AddressTypeCode_display name="address1AddressTypeCode_display">address1AddressTypeCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1City name="address1City">address1City</a>

Type the city for the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>Type the city for the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_city</td></tr></table>

### <a href=#address1Composite name="address1Composite">address1Composite</a>

Shows the complete primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1</td></tr><tr><td>description</td><td>Shows the complete primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_composite</td></tr></table>

### <a href=#address1Country name="address1Country">address1Country</a>

Type the country or region for the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_country</td></tr></table>

### <a href=#address1County name="address1County">address1County</a>

Type the county for the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: County</td></tr><tr><td>description</td><td>Type the county for the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_county</td></tr></table>

### <a href=#address1Fax name="address1Fax">address1Fax</a>

Type the fax number associated with the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Fax</td></tr><tr><td>description</td><td>Type the fax number associated with the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_fax</td></tr></table>

### <a href=#address1Latitude name="address1Latitude">address1Latitude</a>

Type the latitude value for the primary address for use in mapping and other applications.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Latitude</td></tr><tr><td>description</td><td>Type the latitude value for the primary address for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_latitude</td></tr></table>

### <a href=#address1Line1 name="address1Line1">address1Line1</a>

Type the first line of the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 1</td></tr><tr><td>description</td><td>Type the first line of the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line1</td></tr></table>

### <a href=#address1Line2 name="address1Line2">address1Line2</a>

Type the second line of the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 2</td></tr><tr><td>description</td><td>Type the second line of the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line2</td></tr></table>

### <a href=#address1Line3 name="address1Line3">address1Line3</a>

Type the third line of the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 3</td></tr><tr><td>description</td><td>Type the third line of the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line3</td></tr></table>

### <a href=#address1Longitude name="address1Longitude">address1Longitude</a>

Type the longitude value for the primary address for use in mapping and other applications.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Longitude</td></tr><tr><td>description</td><td>Type the longitude value for the primary address for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_longitude</td></tr></table>

### <a href=#address1Name name="address1Name">address1Name</a>

Type a descriptive name for the primary address, such as Corporate Headquarters.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Name</td></tr><tr><td>description</td><td>Type a descriptive name for the primary address, such as Corporate Headquarters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_name</td></tr></table>

### <a href=#address1PostalCode name="address1PostalCode">address1PostalCode</a>

Type the ZIP Code or postal code for the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_postalcode</td></tr></table>

### <a href=#address1PostOfficeBox name="address1PostOfficeBox">address1PostOfficeBox</a>

Type the post office box number of the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Post Office Box</td></tr><tr><td>description</td><td>Type the post office box number of the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_postofficebox</td></tr></table>

### <a href=#address1ShippingMethodCode name="address1ShippingMethodCode">address1ShippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address1ShippingMethodCode_display name="address1ShippingMethodCode_display">address1ShippingMethodCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1StateOrProvince name="address1StateOrProvince">address1StateOrProvince</a>

Type the state or province of the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>Type the state or province of the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_stateorprovince</td></tr></table>

### <a href=#address1Telephone1 name="address1Telephone1">address1Telephone1</a>

Type the main phone number associated with the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Telephone 1</td></tr><tr><td>description</td><td>Type the main phone number associated with the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone1</td></tr></table>

### <a href=#address1Telephone2 name="address1Telephone2">address1Telephone2</a>

Type a second phone number associated with the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Telephone 2</td></tr><tr><td>description</td><td>Type a second phone number associated with the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone2</td></tr></table>

### <a href=#address1Telephone3 name="address1Telephone3">address1Telephone3</a>

Type a third phone number associated with the primary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number associated with the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone3</td></tr></table>

### <a href=#address1UPSZone name="address1UPSZone">address1UPSZone</a>

Type the UPS zone of the primary address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: UPS Zone</td></tr><tr><td>description</td><td>Type the UPS zone of the primary address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_upszone</td></tr></table>

### <a href=#address1UTCOffset name="address1UTCOffset">address1UTCOffset</a>

Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: UTC Offset</td></tr><tr><td>description</td><td>Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_utcoffset</td></tr></table>

### <a href=#address2AddressId name="address2AddressId">address2AddressId</a>

Unique identifier for address 2.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: ID</td></tr><tr><td>description</td><td>Unique identifier for address 2.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_addressid</td></tr></table>

### <a href=#address2AddressTypeCode name="address2AddressTypeCode">address2AddressTypeCode</a>

Select the secondary address type.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Address Type</td></tr><tr><td>description</td><td>Select the secondary address type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address2AddressTypeCode_display name="address2AddressTypeCode_display">address2AddressTypeCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2City name="address2City">address2City</a>

Type the city for the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: City</td></tr><tr><td>description</td><td>Type the city for the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_city</td></tr></table>

### <a href=#address2Composite name="address2Composite">address2Composite</a>

Shows the complete secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2</td></tr><tr><td>description</td><td>Shows the complete secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_composite</td></tr></table>

### <a href=#address2Country name="address2Country">address2Country</a>

Type the country or region for the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_country</td></tr></table>

### <a href=#address2County name="address2County">address2County</a>

Type the county for the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: County</td></tr><tr><td>description</td><td>Type the county for the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_county</td></tr></table>

### <a href=#address2Fax name="address2Fax">address2Fax</a>

Type the fax number associated with the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Fax</td></tr><tr><td>description</td><td>Type the fax number associated with the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_fax</td></tr></table>

### <a href=#address2Latitude name="address2Latitude">address2Latitude</a>

Type the latitude value for the secondary address for use in mapping and other applications.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Latitude</td></tr><tr><td>description</td><td>Type the latitude value for the secondary address for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_latitude</td></tr></table>

### <a href=#address2Line1 name="address2Line1">address2Line1</a>

Type the first line of the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Street 1</td></tr><tr><td>description</td><td>Type the first line of the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line1</td></tr></table>

### <a href=#address2Line2 name="address2Line2">address2Line2</a>

Type the second line of the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Street 2</td></tr><tr><td>description</td><td>Type the second line of the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line2</td></tr></table>

### <a href=#address2Line3 name="address2Line3">address2Line3</a>

Type the third line of the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Street 3</td></tr><tr><td>description</td><td>Type the third line of the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line3</td></tr></table>

### <a href=#address2Longitude name="address2Longitude">address2Longitude</a>

Type the longitude value for the secondary address for use in mapping and other applications.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Longitude</td></tr><tr><td>description</td><td>Type the longitude value for the secondary address for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_longitude</td></tr></table>

### <a href=#address2Name name="address2Name">address2Name</a>

Type a descriptive name for the secondary address, such as Corporate Headquarters.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Name</td></tr><tr><td>description</td><td>Type a descriptive name for the secondary address, such as Corporate Headquarters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_name</td></tr></table>

### <a href=#address2PostalCode name="address2PostalCode">address2PostalCode</a>

Type the ZIP Code or postal code for the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_postalcode</td></tr></table>

### <a href=#address2PostOfficeBox name="address2PostOfficeBox">address2PostOfficeBox</a>

Type the post office box number of the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Post Office Box</td></tr><tr><td>description</td><td>Type the post office box number of the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_postofficebox</td></tr></table>

### <a href=#address2ShippingMethodCode name="address2ShippingMethodCode">address2ShippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address2ShippingMethodCode_display name="address2ShippingMethodCode_display">address2ShippingMethodCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2StateOrProvince name="address2StateOrProvince">address2StateOrProvince</a>

Type the state or province of the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: State/Province</td></tr><tr><td>description</td><td>Type the state or province of the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_stateorprovince</td></tr></table>

### <a href=#address2Telephone1 name="address2Telephone1">address2Telephone1</a>

Type the main phone number associated with the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 1</td></tr><tr><td>description</td><td>Type the main phone number associated with the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone1</td></tr></table>

### <a href=#address2Telephone2 name="address2Telephone2">address2Telephone2</a>

Type a second phone number associated with the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 2</td></tr><tr><td>description</td><td>Type a second phone number associated with the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone2</td></tr></table>

### <a href=#address2Telephone3 name="address2Telephone3">address2Telephone3</a>

Type a third phone number associated with the secondary address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number associated with the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone3</td></tr></table>

### <a href=#address2UPSZone name="address2UPSZone">address2UPSZone</a>

Type the UPS zone of the secondary address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: UPS Zone</td></tr><tr><td>description</td><td>Type the UPS zone of the secondary address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_upszone</td></tr></table>

### <a href=#address2UTCOffset name="address2UTCOffset">address2UTCOffset</a>

Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: UTC Offset</td></tr><tr><td>description</td><td>Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_utcoffset</td></tr></table>

### <a href=#budgetAmount name="budgetAmount">budgetAmount</a>

Information about the budget amount of the lead's company or organization.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Amount</td></tr><tr><td>description</td><td>Information about the budget amount of the lead's company or organization.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>budgetamount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#budgetAmountBase name="budgetAmountBase">budgetAmountBase</a>

Value of the Budget Amount in base currency.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Amount (Base)</td></tr><tr><td>description</td><td>Value of the Budget Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>budgetamount_base</td></tr></table>

### <a href=#budgetStatus name="budgetStatus">budgetStatus</a>

Information about the budget status of the lead's company or organization.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget</td></tr><tr><td>description</td><td>Information about the budget status of the lead's company or organization.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>budgetstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No Committed Budget</td><td>0</td></tr><tr><td>en</td><td>May Buy</td><td>1</td></tr><tr><td>en</td><td>Can Buy</td><td>2</td></tr><tr><td>en</td><td>Will Buy</td><td>3</td></tr></table></td></tr></table>

### <a href=#budgetStatus_display name="budgetStatus_display">budgetStatus_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#companyName name="companyName">companyName</a>

Type the name of the company associated with the lead. This becomes the account name when the lead is qualified and converted to a customer account.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company Name</td></tr><tr><td>description</td><td>Type the name of the company associated with the lead. This becomes the account name when the lead is qualified and converted to a customer account.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>companyname</td></tr></table>

### <a href=#confirmInterest name="confirmInterest">confirmInterest</a>

Select whether the lead confirmed interest in your offerings. This helps in determining the lead quality.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confirm Interest</td></tr><tr><td>description</td><td>Select whether the lead confirmed interest in your offerings. This helps in determining the lead quality.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>confirminterest</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#decisionMaker name="decisionMaker">decisionMaker</a>

Select whether your notes include information about who makes the purchase decisions at the lead's company.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Decision Maker?</td></tr><tr><td>description</td><td>Select whether your notes include information about who makes the purchase decisions at the lead's company.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>decisionmaker</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the lead, such as an excerpt from the company's website.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the lead, such as an excerpt from the company's website.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#doNotBulkEMail name="doNotBulkEMail">doNotBulkEMail</a>

Select whether the lead accepts bulk email sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the lead can be added to marketing lists, but will be excluded from the email.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Bulk Emails</td></tr><tr><td>description</td><td>Select whether the lead accepts bulk email sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the lead can be added to marketing lists, but will be excluded from the email.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotbulkemail</td></tr></table>

### <a href=#doNotEMail name="doNotEMail">doNotEMail</a>

Select whether the lead allows direct email sent from Microsoft Dynamics 365.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Emails</td></tr><tr><td>description</td><td>Select whether the lead allows direct email sent from Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotemail</td></tr></table>

### <a href=#doNotFax name="doNotFax">doNotFax</a>

Select whether the lead allows faxes.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Faxes</td></tr><tr><td>description</td><td>Select whether the lead allows faxes.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotfax</td></tr></table>

### <a href=#doNotPhone name="doNotPhone">doNotPhone</a>

Select whether the lead allows phone calls.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Phone Calls</td></tr><tr><td>description</td><td>Select whether the lead allows phone calls.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotphone</td></tr></table>

### <a href=#doNotPostalMail name="doNotPostalMail">doNotPostalMail</a>

Select whether the lead allows direct mail.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Mails</td></tr><tr><td>description</td><td>Select whether the lead allows direct mail.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotpostalmail</td></tr></table>

### <a href=#doNotSendMM name="doNotSendMM">doNotSendMM</a>

Select whether the lead accepts marketing materials, such as brochures or catalogs. Leads that opt out can be excluded from marketing initiatives.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing Material</td></tr><tr><td>description</td><td>Select whether the lead accepts marketing materials, such as brochures or catalogs. Leads that opt out can be excluded from marketing initiatives.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotsendmm</td></tr></table>

### <a href=#EMailAddress1 name="EMailAddress1">EMailAddress1</a>

Type the primary email address for the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email</td></tr><tr><td>description</td><td>Type the primary email address for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress1</td></tr></table>

### <a href=#EMailAddress2 name="EMailAddress2">EMailAddress2</a>

Type the secondary email address for the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address 2</td></tr><tr><td>description</td><td>Type the secondary email address for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress2</td></tr></table>

### <a href=#EMailAddress3 name="EMailAddress3">EMailAddress3</a>

Type a third email address for the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address 3</td></tr><tr><td>description</td><td>Type a third email address for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress3</td></tr></table>

### <a href=#estimatedAmount name="estimatedAmount">estimatedAmount</a>

Type the estimated revenue value that this lead will generate to assist in sales forecasting and planning.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Est. Value</td></tr><tr><td>description</td><td>Type the estimated revenue value that this lead will generate to assist in sales forecasting and planning.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>estimatedamount</td></tr></table>

### <a href=#estimatedAmountBase name="estimatedAmountBase">estimatedAmountBase</a>

Value of the Est. Value in base currency.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Est. Value (Base)</td></tr><tr><td>description</td><td>Value of the Est. Value in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>estimatedamount_base</td></tr></table>

### <a href=#estimatedCloseDate name="estimatedCloseDate">estimatedCloseDate</a>

Enter the expected close date for the lead, so that the sales team can schedule timely follow-up meetings to move the prospect to the next sales stage.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Est. Close Date</td></tr><tr><td>description</td><td>Enter the expected close date for the lead, so that the sales team can schedule timely follow-up meetings to move the prospect to the next sales stage.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>estimatedclosedate</td></tr></table>

### <a href=#estimatedValue name="estimatedValue">estimatedValue</a>

Type a numeric value of the lead's estimated value, such as a product quantity, if no revenue amount can be specified in the Est. Value field. This can be used for sales forecasting and planning.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Est. Value (deprecated)</td></tr><tr><td>description</td><td>Type a numeric value of the lead's estimated value, such as a product quantity, if no revenue amount can be specified in the Est. Value field. This can be used for sales forecasting and planning.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>estimatedvalue</td></tr></table>

### <a href=#evaluateFit name="evaluateFit">evaluateFit</a>

Select whether the fit between the lead's requirements and your offerings was evaluated.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Evaluate Fit</td></tr><tr><td>description</td><td>Select whether the fit between the lead's requirements and your offerings was evaluated.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>evaluatefit</td></tr></table>

### <a href=#fax name="fax">fax</a>

Type the fax number for the primary contact for the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Type the fax number for the primary contact for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fax</td></tr></table>

### <a href=#firstName name="firstName">firstName</a>

Type the first name of the primary contact for the lead to make sure the prospect is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Name</td></tr><tr><td>description</td><td>Type the first name of the primary contact for the lead to make sure the prospect is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>firstname</td></tr></table>

### <a href=#industryCode name="industryCode">industryCode</a>

Select the primary industry in which the lead's business is focused, for use in marketing segmentation and demographic analysis.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Industry</td></tr><tr><td>description</td><td>Select the primary industry in which the lead's business is focused, for use in marketing segmentation and demographic analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>industrycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Accounting</td><td>1</td></tr><tr><td>en</td><td>Agriculture and Non-petrol Natural Resource Extraction</td><td>2</td></tr><tr><td>en</td><td>Broadcasting Printing and Publishing</td><td>3</td></tr><tr><td>en</td><td>Brokers</td><td>4</td></tr><tr><td>en</td><td>Building Supply Retail</td><td>5</td></tr><tr><td>en</td><td>Business Services</td><td>6</td></tr><tr><td>en</td><td>Consulting</td><td>7</td></tr><tr><td>en</td><td>Consumer Services</td><td>8</td></tr><tr><td>en</td><td>Design, Direction and Creative Management</td><td>9</td></tr><tr><td>en</td><td>Distributors, Dispatchers and Processors</td><td>10</td></tr><tr><td>en</td><td>Doctor's Offices and Clinics</td><td>11</td></tr><tr><td>en</td><td>Durable Manufacturing</td><td>12</td></tr><tr><td>en</td><td>Eating and Drinking Places</td><td>13</td></tr><tr><td>en</td><td>Entertainment Retail</td><td>14</td></tr><tr><td>en</td><td>Equipment Rental and Leasing</td><td>15</td></tr><tr><td>en</td><td>Financial</td><td>16</td></tr><tr><td>en</td><td>Food and Tobacco Processing</td><td>17</td></tr><tr><td>en</td><td>Inbound Capital Intensive Processing</td><td>18</td></tr><tr><td>en</td><td>Inbound Repair and Services</td><td>19</td></tr><tr><td>en</td><td>Insurance</td><td>20</td></tr><tr><td>en</td><td>Legal Services</td><td>21</td></tr><tr><td>en</td><td>Non-Durable Merchandise Retail</td><td>22</td></tr><tr><td>en</td><td>Outbound Consumer Service</td><td>23</td></tr><tr><td>en</td><td>Petrochemical Extraction and Distribution</td><td>24</td></tr><tr><td>en</td><td>Service Retail</td><td>25</td></tr><tr><td>en</td><td>SIG Affiliations</td><td>26</td></tr><tr><td>en</td><td>Social Services</td><td>27</td></tr><tr><td>en</td><td>Special Outbound Trade Contractors</td><td>28</td></tr><tr><td>en</td><td>Specialty Realty</td><td>29</td></tr><tr><td>en</td><td>Transportation</td><td>30</td></tr><tr><td>en</td><td>Utility Creation and Distribution</td><td>31</td></tr><tr><td>en</td><td>Vehicle Retail</td><td>32</td></tr><tr><td>en</td><td>Wholesale</td><td>33</td></tr></table></td></tr></table>

### <a href=#industryCode_display name="industryCode_display">industryCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#initialCommunication name="initialCommunication">initialCommunication</a>

Choose whether someone from the sales team contacted this lead earlier.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Initial Communication</td></tr><tr><td>description</td><td>Choose whether someone from the sales team contacted this lead earlier.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>initialcommunication</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Contacted</td><td>0</td></tr><tr><td>en</td><td>Not Contacted</td><td>1</td></tr></table></td></tr></table>

### <a href=#initialCommunication_display name="initialCommunication_display">initialCommunication_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#jobTitle name="jobTitle">jobTitle</a>

Type the job title of the primary contact for this lead to make sure the prospect is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Job Title</td></tr><tr><td>description</td><td>Type the job title of the primary contact for this lead to make sure the prospect is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>jobtitle</td></tr></table>

### <a href=#lastName name="lastName">lastName</a>

Type the last name of the primary contact for the lead to make sure the prospect is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Name</td></tr><tr><td>description</td><td>Type the last name of the primary contact for the lead to make sure the prospect is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastname</td></tr></table>

### <a href=#lastUsedInCampaign name="lastUsedInCampaign">lastUsedInCampaign</a>

Shows the date when the lead was last included in a marketing campaign or quick campaign.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Campaign Date</td></tr><tr><td>description</td><td>Shows the date when the lead was last included in a marketing campaign or quick campaign.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastusedincampaign</td></tr></table>

### <a href=#leadQualityCode name="leadQualityCode">leadQualityCode</a>

Select a rating value to indicate the lead's potential to become a customer.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating</td></tr><tr><td>description</td><td>Select a rating value to indicate the lead's potential to become a customer.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>leadqualitycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Hot</td><td>1</td></tr><tr><td>en</td><td>Warm</td><td>2</td></tr><tr><td>en</td><td>Cold</td><td>3</td></tr></table></td></tr></table>

### <a href=#leadQualityCode_display name="leadQualityCode_display">leadQualityCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#leadSourceCode name="leadSourceCode">leadSourceCode</a>

Select the primary marketing source that prompted the lead to contact you.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead Source</td></tr><tr><td>description</td><td>Select the primary marketing source that prompted the lead to contact you.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>leadsourcecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Advertisement</td><td>1</td></tr><tr><td>en</td><td>Employee Referral</td><td>2</td></tr><tr><td>en</td><td>External Referral</td><td>3</td></tr><tr><td>en</td><td>Partner</td><td>4</td></tr><tr><td>en</td><td>Public Relations</td><td>5</td></tr><tr><td>en</td><td>Seminar</td><td>6</td></tr><tr><td>en</td><td>Trade Show</td><td>7</td></tr><tr><td>en</td><td>Web</td><td>8</td></tr><tr><td>en</td><td>Word of Mouth</td><td>9</td></tr><tr><td>en</td><td>Other</td><td>10</td></tr></table></td></tr></table>

### <a href=#leadSourceCode_display name="leadSourceCode_display">leadSourceCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#masterId name="masterId">masterId</a>

Unique identifier of the master lead for merge.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Master ID</td></tr><tr><td>description</td><td>Unique identifier of the master lead for merge.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>masterid</td></tr></table>

### <a href=#merged name="merged">merged</a>

Tells whether the lead has been merged with another lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Merged</td></tr><tr><td>description</td><td>Tells whether the lead has been merged with another lead.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>merged</td></tr></table>

### <a href=#middleName name="middleName">middleName</a>

Type the middle name or initial of the primary contact for the lead to make sure the prospect is addressed correctly.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Middle Name</td></tr><tr><td>description</td><td>Type the middle name or initial of the primary contact for the lead to make sure the prospect is addressed correctly.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>middlename</td></tr></table>

### <a href=#mobilePhone name="mobilePhone">mobilePhone</a>

Type the mobile phone number for the primary contact for the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mobile Phone</td></tr><tr><td>description</td><td>Type the mobile phone number for the primary contact for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mobilephone</td></tr></table>

### <a href=#need name="need">need</a>

Choose how high the level of need is for the lead's company.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Need</td></tr><tr><td>description</td><td>Choose how high the level of need is for the lead's company.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>need</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Must have</td><td>0</td></tr><tr><td>en</td><td>Should have</td><td>1</td></tr><tr><td>en</td><td>Good to have</td><td>2</td></tr><tr><td>en</td><td>No need</td><td>3</td></tr></table></td></tr></table>

### <a href=#need_display name="need_display">need_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#numberOfEmployees name="numberOfEmployees">numberOfEmployees</a>

Type the number of employees that work at the company associated with the lead, for use in marketing segmentation and demographic analysis.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>No. of Employees</td></tr><tr><td>description</td><td>Type the number of employees that work at the company associated with the lead, for use in marketing segmentation and demographic analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>numberofemployees</td></tr></table>

### <a href=#pager name="pager">pager</a>

Type the pager number for the primary contact for the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pager</td></tr><tr><td>description</td><td>Type the pager number for the primary contact for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pager</td></tr></table>

### <a href=#participatesInWorkflow name="participatesInWorkflow">participatesInWorkflow</a>

Shows whether the lead participates in workflow rules.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Participates in Workflow</td></tr><tr><td>description</td><td>Shows whether the lead participates in workflow rules.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>participatesinworkflow</td></tr></table>

### <a href=#preferredContactMethodCode name="preferredContactMethodCode">preferredContactMethodCode</a>

Select the preferred method of contact.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Method of Contact</td></tr><tr><td>description</td><td>Select the preferred method of contact.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredcontactmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Any</td><td>1</td></tr><tr><td>en</td><td>Email</td><td>2</td></tr><tr><td>en</td><td>Phone</td><td>3</td></tr><tr><td>en</td><td>Fax</td><td>4</td></tr><tr><td>en</td><td>Mail</td><td>5</td></tr></table></td></tr></table>

### <a href=#preferredContactMethodCode_display name="preferredContactMethodCode_display">preferredContactMethodCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Select the priority so that preferred customers or critical issues are handled quickly.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Select the priority so that preferred customers or critical issues are handled quickly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#purchaseProcess name="purchaseProcess">purchaseProcess</a>

Choose whether an individual or a committee will be involved in the  purchase process for the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase Process</td></tr><tr><td>description</td><td>Choose whether an individual or a committee will be involved in the  purchase process for the lead.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>purchaseprocess</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Individual</td><td>0</td></tr><tr><td>en</td><td>Committee</td><td>1</td></tr><tr><td>en</td><td>Unknown</td><td>2</td></tr></table></td></tr></table>

### <a href=#purchaseProcess_display name="purchaseProcess_display">purchaseProcess_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#qualificationComments name="qualificationComments">qualificationComments</a>

Type comments about the qualification or scoring of the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Qualification Comments</td></tr><tr><td>description</td><td>Type comments about the qualification or scoring of the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>qualificationcomments</td></tr></table>

### <a href=#revenue name="revenue">revenue</a>

Type the annual revenue of the company associated with the lead to provide an understanding of the prospect's business.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Revenue</td></tr><tr><td>description</td><td>Type the annual revenue of the company associated with the lead to provide an understanding of the prospect's business.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>revenue</td></tr></table>

### <a href=#revenueBase name="revenueBase">revenueBase</a>

Value of the Annual Revenue in base currency.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Revenue (Base)</td></tr><tr><td>description</td><td>Value of the Annual Revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>revenue_base</td></tr></table>

### <a href=#salesStage name="salesStage">salesStage</a>

Select the sales stage of this lead to aid the sales team in their efforts to convert this lead to an opportunity.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Stage</td></tr><tr><td>description</td><td>Select the sales stage of this lead to aid the sales team in their efforts to convert this lead to an opportunity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>salesstage</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Qualify</td><td>0</td></tr></table></td></tr></table>

### <a href=#salesStage_display name="salesStage_display">salesStage_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#salesStageCode name="salesStageCode">salesStageCode</a>

Select the sales process stage for the lead to help determine the probability of the lead converting to an opportunity.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Stage Code</td></tr><tr><td>description</td><td>Select the sales process stage for the lead to help determine the probability of the lead converting to an opportunity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>salesstagecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#salesStageCode_display name="salesStageCode_display">salesStageCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#salutation name="salutation">salutation</a>

Type the salutation of the primary contact for this lead to make sure the prospect is addressed correctly in sales calls, email messages, and marketing campaigns.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Salutation</td></tr><tr><td>description</td><td>Type the salutation of the primary contact for this lead to make sure the prospect is addressed correctly in sales calls, email messages, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>salutation</td></tr></table>

### <a href=#scheduleFollowupProspect name="scheduleFollowupProspect">scheduleFollowupProspect</a>

Enter the date and time of the prospecting follow-up meeting with the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Schedule Follow Up (Prospect)</td></tr><tr><td>description</td><td>Enter the date and time of the prospecting follow-up meeting with the lead.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>schedulefollowup_prospect</td></tr></table>

### <a href=#scheduleFollowUpQualify name="scheduleFollowUpQualify">scheduleFollowUpQualify</a>

Enter the date and time of the qualifying follow-up meeting with the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Schedule Follow Up (Qualify)</td></tr><tr><td>description</td><td>Enter the date and time of the qualifying follow-up meeting with the lead.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>schedulefollowup_qualify</td></tr></table>

### <a href=#SIC name="SIC">SIC</a>

Type the Standard Industrial Classification (SIC) code that indicates the lead's primary industry of business for use in marketing segmentation and demographic analysis.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SIC Code</td></tr><tr><td>description</td><td>Type the Standard Industrial Classification (SIC) code that indicates the lead's primary industry of business for use in marketing segmentation and demographic analysis.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sic</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the lead is open, qualified, or disqualified. Qualified and disqualified leads are read-only and can't be edited unless they are reactivated.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the lead is open, qualified, or disqualified. Qualified and disqualified leads are read-only and can't be edited unless they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Qualified</td><td>1</td></tr><tr><td>en</td><td>Disqualified</td><td>2</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the lead's status.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the lead's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>New</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Contacted</td><td>2</td><td>0</td></tr><tr><td>en</td><td>Qualified</td><td>3</td><td>1</td></tr><tr><td>en</td><td>Lost</td><td>4</td><td>2</td></tr><tr><td>en</td><td>Cannot Contact</td><td>5</td><td>2</td></tr><tr><td>en</td><td>No Longer Interested</td><td>6</td><td>2</td></tr><tr><td>en</td><td>Canceled</td><td>7</td><td>2</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subject name="subject">subject</a>

Type a subject or descriptive name, such as the expected order, company name, or marketing source list, to identify the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Topic</td></tr><tr><td>description</td><td>Type a subject or descriptive name, such as the expected order, company name, or marketing source list, to identify the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>300</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#telephone1 name="telephone1">telephone1</a>

Type the work phone number for the primary contact for the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Phone</td></tr><tr><td>description</td><td>Type the work phone number for the primary contact for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone1</td></tr></table>

### <a href=#telephone2 name="telephone2">telephone2</a>

Type the home phone number for the primary contact for the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Home Phone</td></tr><tr><td>description</td><td>Type the home phone number for the primary contact for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone2</td></tr></table>

### <a href=#telephone3 name="telephone3">telephone3</a>

Type an alternate phone number for the primary contact for the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other Phone</td></tr><tr><td>description</td><td>Type an alternate phone number for the primary contact for the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone3</td></tr></table>

### <a href=#purchaseTimeFrame name="purchaseTimeFrame">purchaseTimeFrame</a>

Choose how long the lead will likely take to make the purchase, so the sales team will be aware.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase Timeframe</td></tr><tr><td>description</td><td>Choose how long the lead will likely take to make the purchase, so the sales team will be aware.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>purchasetimeframe</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Immediate</td><td>0</td></tr><tr><td>en</td><td>This Quarter</td><td>1</td></tr><tr><td>en</td><td>Next Quarter</td><td>2</td></tr><tr><td>en</td><td>This Year</td><td>3</td></tr><tr><td>en</td><td>Unknown</td><td>4</td></tr></table></td></tr></table>

### <a href=#purchaseTimeFrame_display name="purchaseTimeFrame_display">purchaseTimeFrame_display</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#webSiteUrl name="webSiteUrl">webSiteUrl</a>

Type the website URL for the company associated with this lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Type the website URL for the company associated with this lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>websiteurl</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the Lead record.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the Lead record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this case. This field is for internal use only.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this case. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#followEmail name="followEmail">followEmail</a>

Information about whether to allow following email activity like opens, attachment views and link clicks for emails sent to the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Follow Email Activity</td></tr><tr><td>description</td><td>Information about whether to allow following email activity like opens, attachment views and link clicks for emails sent to the lead.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>followemail</td></tr></table>

### <a href=#timeSpentByMeOnEmailAndMeetings name="timeSpentByMeOnEmailAndMeetings">timeSpentByMeOnEmailAndMeetings</a>

Total time spent for emails (read and write) and meetings by me in relation to the lead record.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Spent by me</td></tr><tr><td>description</td><td>Total time spent for emails (read and write) and meetings by me in relation to the lead record.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timespentbymeonemailandmeetings</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Unique identifier of the account with which the lead is associated.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier of the account with which the lead is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountid</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Unique identifier of the contact with which the lead is associated.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Unique identifier of the contact with which the lead is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contactid</td></tr></table>

### <a href=#yomiCompanyName name="yomiCompanyName">yomiCompanyName</a>

Type the phonetic spelling of the lead's company name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Company Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the lead's company name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomicompanyname</td></tr></table>

### <a href=#yomiFirstName name="yomiFirstName">yomiFirstName</a>

Type the phonetic spelling of the lead's first name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi First Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the lead's first name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomifirstname</td></tr></table>

### <a href=#yomiFullName name="yomiFullName">yomiFullName</a>

Combines and shows the lead's Yomi first and last names so the full phonetic name can be displayed in views and reports.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Full Name</td></tr><tr><td>description</td><td>Combines and shows the lead's Yomi first and last names so the full phonetic name can be displayed in views and reports.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>450</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomifullname</td></tr></table>

### <a href=#yomiLastName name="yomiLastName">yomiLastName</a>

Type the phonetic spelling of the lead's last name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Last Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the lead's last name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomilastname</td></tr></table>

### <a href=#yomiMiddleName name="yomiMiddleName">yomiMiddleName</a>

Type the phonetic spelling of the lead's middle name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Middle Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the lead's middle name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the prospect.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomimiddlename</td></tr></table>

### <a href=#campaignId name="campaignId">campaignId</a>

Choose the campaign that the lead was generated from to track the effectiveness of marketing campaigns and identify  communications received by the lead.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source Campaign</td></tr><tr><td>description</td><td>Choose the campaign that the lead was generated from to track the effectiveness of marketing campaigns and identify  communications received by the lead.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>campaignid</td></tr></table>

### <a href=#relatedObjectId name="relatedObjectId">relatedObjectId</a>

Related Campaign Response.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related Campaign Response</td></tr><tr><td>description</td><td>Related Campaign Response.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>relatedobjectid</td></tr></table>

### <a href=#originatingCaseId name="originatingCaseId">originatingCaseId</a>

This attribute is used for Sample Service Business Processes.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating Case</td></tr><tr><td>description</td><td>This attribute is used for Sample Service Business Processes.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>originatingcaseid</td></tr></table>

### <a href=#qualifyingOpportunityId name="qualifyingOpportunityId">qualifyingOpportunityId</a>

Choose the opportunity that the lead was qualified on and then converted to.  
First included in: <a href="../../Lead.md" target="_blank">crmCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Qualifying Opportunity</td></tr><tr><td>description</td><td>Choose the opportunity that the lead was qualified on and then converted to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>qualifyingopportunityid</td></tr></table>

### <a href=#GDPROptOut name="GDPROptOut">GDPROptOut</a>

Describes whether lead is opted out or not  
First included in: <a href="../../projectCommon/Lead.md" target="_blank">projectCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GDPR Optout</td></tr><tr><td>description</td><td>Describes whether lead is opted out or not</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_gdproptout</td></tr></table>

### <a href=#orderType name="orderType">orderType</a>

Whether the Opportunity created when qualifying this Lead is for an Item- based or a Work-based sale  
First included in: <a href="../../projectCommon/Lead.md" target="_blank">projectCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Whether the Opportunity created when qualifying this Lead is for an Item- based or a Work-based sale</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_ordertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Item based</td><td>192350000</td></tr><tr><td>en</td><td>Work based</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#orderType_display name="orderType_display">orderType_display</a>

First included in: <a href="../../projectCommon/Lead.md" target="_blank">projectCommon/Lead</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#applicationDeadline name="applicationDeadline">applicationDeadline</a>

Deadline to submit application.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Application Deadline</td></tr><tr><td>description</td><td>Deadline to submit application.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_applicationdeadline</td></tr></table>

### <a href=#deliveryFrameworkId name="deliveryFrameworkId">deliveryFrameworkId</a>

First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Framework</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deliveryframeworkid</td></tr></table>

### <a href=#expectedAmountRequested name="expectedAmountRequested">expectedAmountRequested</a>

Amount requested by the Grant Seeker.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Amount Requested</td></tr><tr><td>description</td><td>Amount requested by the Grant Seeker.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_expectedamountrequested</td></tr></table>

### <a href=#expectedamountrequestedBase name="expectedamountrequestedBase">expectedamountrequestedBase</a>

Value of the Expected Amount Requested in base currency.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Amount Requested (Base)</td></tr><tr><td>description</td><td>Value of the Expected Amount Requested in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_expectedamountrequested_base</td></tr></table>

### <a href=#expectedDuration name="expectedDuration">expectedDuration</a>

Expected duration of the Grant in months.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Duration (Months)</td></tr><tr><td>description</td><td>Expected duration of the Grant in months.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_expectedduration</td></tr></table>

### <a href=#expectedStartDate name="expectedStartDate">expectedStartDate</a>

Expected start date of the Grant.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Start Date</td></tr><tr><td>description</td><td>Expected start date of the Grant.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_expectedstartdate</td></tr></table>

### <a href=#isRenewal name="isRenewal">isRenewal</a>

Indicates if this is a renewal Grant.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Renewal</td></tr><tr><td>description</td><td>Indicates if this is a renewal Grant.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_isrenewal</td></tr></table>

### <a href=#leadDocketId name="leadDocketId">leadDocketId</a>

Docket  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Docket</td></tr><tr><td>description</td><td>Docket</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_lead_docketid</td></tr></table>

### <a href=#letterofIntentDeadline name="letterofIntentDeadline">letterofIntentDeadline</a>

Deadline to submit notification to donor that organization will be competing for this grant.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Letter of Intent Deadline</td></tr><tr><td>description</td><td>Deadline to submit notification to donor that organization will be competing for this grant.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_letterofintentdeadline</td></tr></table>

### <a href=#organizationalBudget name="organizationalBudget">organizationalBudget</a>

Total budget of the Organization.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Budget</td></tr><tr><td>description</td><td>Total budget of the Organization.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_organizationalbudget</td></tr></table>

### <a href=#organizationalBudgetBase name="organizationalBudgetBase">organizationalBudgetBase</a>

Value of the Organization Budget in base currency.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Budget (Base)</td></tr><tr><td>description</td><td>Value of the Organization Budget in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_organizationalbudget_base</td></tr></table>

### <a href=#organizationType name="organizationType">organizationType</a>

Type of Account.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Type</td></tr><tr><td>description</td><td>Type of Account.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_organizationtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Oil & Gas</td><td>100000000</td></tr><tr><td>en</td><td>Petroleum</td><td>100000001</td></tr><tr><td>en</td><td>Fossil Fuels</td><td>100000002</td></tr><tr><td>en</td><td>Heavy Crude</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#organizationType_display name="organizationType_display">organizationType_display</a>

First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#requestType name="requestType">requestType</a>

Indicates the type of Inquiry/LOI/Lead.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Request Type</td></tr><tr><td>description</td><td>Indicates the type of Inquiry/LOI/Lead.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_requesttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>General Support</td><td>100000000</td></tr><tr><td>en</td><td>Project Support</td><td>100000001</td></tr></table></td></tr></table>

### <a href=#requestType_display name="requestType_display">requestType_display</a>

First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#totalProjectBudget name="totalProjectBudget">totalProjectBudget</a>

Budget defined by the Grant Seeker.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Project Budget</td></tr><tr><td>description</td><td>Budget defined by the Grant Seeker.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalprojectbudget</td></tr></table>

### <a href=#totalProjectBudgetBase name="totalProjectBudgetBase">totalProjectBudgetBase</a>

Value of the Total Project Budget in base currency.  
First included in: nonProfit/Lead (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Project Budget (Base)</td></tr><tr><td>description</td><td>Value of the Total Project Budget in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalprojectbudget_base</td></tr></table>

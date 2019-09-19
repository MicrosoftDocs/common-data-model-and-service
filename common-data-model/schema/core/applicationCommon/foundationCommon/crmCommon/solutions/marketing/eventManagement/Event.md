---
title: Event - Common Data Model | Microsoft Docs
description: Container to manage and plan marketing activities that take place at a specific venue or location.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Event

Container to manage and plan marketing activities that take place at a specific venue or location.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/Event.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/Event  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventId](#eventId)|Unique identifier for entity instances|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[stateCode](#stateCode)|Status of the Event|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[stateCode_display](#stateCode_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[statusCode](#statusCode)|Reason for the status of the Event|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[statusCode_display](#statusCode_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[name](#name)|The name of the custom entity.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[entityImageId](#entityImageId)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[baseRecurrentEventID](#baseRecurrentEventID)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[bookedFlightReservations](#bookedFlightReservations)|Flight reservations booking status|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[bookedFlightReservations_display](#bookedFlightReservations_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[bookRooms](#bookRooms)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[bookRooms_display](#bookRooms_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[budgetAllocated](#budgetAllocated)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[budgetAllocatedBase](#budgetAllocatedBase)|Value of the Budget Allocated in base currency.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[cateringRequired](#cateringRequired)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[cateringRequired_display](#cateringRequired_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[checkInCount](#checkInCount)|Check-in count|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[confirmedHotelChoices](#confirmedHotelChoices)|Hotel choices confirmation status|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[confirmedHotelChoices_display](#confirmedHotelChoices_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[countdownInDays](#countdownInDays)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[createMarketingCollateral](#createMarketingCollateral)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[createMarketingCollateral_display](#createMarketingCollateral_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[definePackagesandPricing](#definePackagesandPricing)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[definePackagesandPricing_display](#definePackagesandPricing_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[defineSessions](#defineSessions)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[defineSessions_display](#defineSessions_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[defineTeam](#defineTeam)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[defineTeam_display](#defineTeam_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[description](#description)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[developMarketingPlan](#developMarketingPlan)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[developMarketingPlan_display](#developMarketingPlan_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[earlyBirdCutOffDate](#earlyBirdCutOffDate)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventDebriefing](#eventDebriefing)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventDebriefing_display](#eventDebriefing_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventEndDate](#eventEndDate)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventFormat](#eventFormat)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventFormat_display](#eventFormat_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventStartDate](#eventStartDate)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventTimeZone](#eventTimeZone)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventTimeZoneName](#eventTimeZoneName)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventType](#eventType)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventType_display](#eventType_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventVenueCost](#eventVenueCost)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventVenueCostBase](#eventVenueCostBase)|Value of the Event Venue Cost in base currency.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[expectedOutcome](#expectedOutcome)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[followUpOnLeads](#followUpOnLeads)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[followUpOnLeads_display](#followUpOnLeads_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[guestLogistics](#guestLogistics)|Whether guest logistics are required or not.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[guestLogistics_display](#guestLogistics_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[identifySpeakers](#identifySpeakers)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[identifySpeakers_display](#identifySpeakers_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[identifySponsors](#identifySponsors)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[identifySponsors_display](#identifySponsors_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[isRecurringEvent](#isRecurringEvent)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[isTemplate](#isTemplate)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[isTemplate_display](#isTemplate_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[language](#language)|The language of the webinar|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[language_display](#language_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[makePaymentsDue](#makePaymentsDue)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[makePaymentsDue_display](#makePaymentsDue_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[manageRegistrationCount](#manageRegistrationCount)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[manageRegistrationCount_display](#manageRegistrationCount_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[maximumEventCapacity](#maximumEventCapacity)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[maxNumberOfRegistrations](#maxNumberOfRegistrations)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[miscellaneousCosts](#miscellaneousCosts)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[miscellaneousCostsBase](#miscellaneousCostsBase)|Value of the Miscellaneous Costs in base currency.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[notifyAuthoritiesOfEvent](#notifyAuthoritiesOfEvent)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[notifyAuthoritiesOfEvent_display](#notifyAuthoritiesOfEvent_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[planRegistration](#planRegistration)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[planRegistration_display](#planRegistration_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[presentationManagerUrl](#presentationManagerUrl)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[primaryGoal](#primaryGoal)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[primaryGoal_display](#primaryGoal_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[primaryVenue](#primaryVenue)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[producer](#producer)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[publicEventURL](#publicEventURL)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[publishStatus](#publishStatus)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[publishStatus_display](#publishStatus_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[readableEventID](#readableEventID)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[recurrencePattern](#recurrencePattern)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[recurrentEventStatus](#recurrentEventStatus)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[registrationCount](#registrationCount)|Registration count of the Event.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[registrationsTarget](#registrationsTarget)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[requestSponsorship](#requestSponsorship)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[requestSponsorship_display](#requestSponsorship_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[revenueFromSponsorship](#revenueFromSponsorship)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[revenueFromSponsorshipBase](#revenueFromSponsorshipBase)|Value of the Revenue from Sponsorship in base currency.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[scheduleAirportPickups](#scheduleAirportPickups)|Airport pickups scheduling status|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[scheduleAirportPickups_display](#scheduleAirportPickups_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[scheduleSessions](#scheduleSessions)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[scheduleSessions_display](#scheduleSessions_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[selectSpeakers](#selectSpeakers)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[selectSpeakers_display](#selectSpeakers_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[selectVendors](#selectVendors)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[selectVendors_display](#selectVendors_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sendEventInvitation](#sendEventInvitation)|Event invitation sending status|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sendEventInvitation_display](#sendEventInvitation_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sendMarketingMaterial](#sendMarketingMaterial)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sendMarketingMaterial_display](#sendMarketingMaterial_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sendPreEventReminders](#sendPreEventReminders)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sendPreEventReminders_display](#sendPreEventReminders_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sendThankYouEmails](#sendThankYouEmails)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sendThankYouEmails_display](#sendThankYouEmails_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[showWaitlist](#showWaitlist)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[targetRevenue](#targetRevenue)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[targetRevenueBase](#targetRevenueBase)|Value of the Target Revenue in base currency.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[teamDebriefing](#teamDebriefing)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[teamDebriefing_display](#teamDebriefing_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[totalCostOfEventsActivities](#totalCostOfEventsActivities)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[totalCostOfEventsActivitiesBase](#totalCostOfEventsActivitiesBase)|Value of the Total Cost of Events Activities in base currency.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[totalCostOfExternalMembers](#totalCostOfExternalMembers)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[totalCostOfExternalMembersBase](#totalCostOfExternalMembersBase)|Value of the Total cost of External Members in base currency.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[totalRegistrationFee](#totalRegistrationFee)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[totalRegistrationFeeBase](#totalRegistrationFeeBase)|Value of the Total Registration Fee in base currency.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[totalRevenueFromTheEvent](#totalRevenueFromTheEvent)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[totalRevenueFromTheEventBase](#totalRevenueFromTheEventBase)|Value of the Total Revenue from the event in base currency.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[waitlistStartingPoint](#waitlistStartingPoint)|Waitlist Starting Point|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[waitlistthisEvent](#waitlistthisEvent)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[waitlistthisEvent_display](#waitlistthisEvent_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[webinarConfigurationId](#webinarConfigurationId)|Webinar Configuration|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[webinarID](#webinarID)|Webinar ID of the Event.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[webinarNotificationSeen](#webinarNotificationSeen)|Whether the webinar creation notification has been seen or not|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[webinarOperation](#webinarOperation)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[webinarStatus](#webinarStatus)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[webinarStatusReason](#webinarStatusReason)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[webinarType](#webinarType)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[webinarURL](#webinarURL)|URL of the webinar. This might be URL of external webinar provider.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sendSurveys](#sendSurveys)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sendSurveys_display](#sendSurveys_display)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventURLspecified](#eventURLspecified)|Determines whether an event URL is specified.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sessionsCount](#sessionsCount)|The number of sessions in this event|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sessionsCountDate](#sessionsCountDate)|Last Updated time of rollup field Session count.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[sessionsCountState](#sessionsCountState)|State of rollup field Session count.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[allowAnonymousRegistrations](#allowAnonymousRegistrations)||<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[portalBannerImage](#portalBannerImage)|The portal banner image.|<a href="Event.md" target="_blank">eventManagement/Event</a>|
|[eventURL](#eventURL)||<a href="Event.md" target="_blank">eventManagement/Event</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#eventId name="eventId">eventId</a>

Unique identifier for entity instances  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_eventid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Event  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Event</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Event  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Event</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#baseRecurrentEventID name="baseRecurrentEventID">baseRecurrentEventID</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base Recurrent Event ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>40</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_baserecurrenteventid</td></tr></table>

### <a href=#bookedFlightReservations name="bookedFlightReservations">bookedFlightReservations</a>

Flight reservations booking status  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booked Flight reservations?</td></tr><tr><td>description</td><td>Flight reservations booking status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_bookedflightreservations</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#bookedFlightReservations_display name="bookedFlightReservations_display">bookedFlightReservations_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#bookRooms name="bookRooms">bookRooms</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Book Rooms</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_bookrooms</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#bookRooms_display name="bookRooms_display">bookRooms_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#budgetAllocated name="budgetAllocated">budgetAllocated</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Allocated</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_budgetallocated</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#budgetAllocatedBase name="budgetAllocatedBase">budgetAllocatedBase</a>

Value of the Budget Allocated in base currency.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Allocated (Base)</td></tr><tr><td>description</td><td>Value of the Budget Allocated in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_budgetallocated_base</td></tr></table>

### <a href=#cateringRequired name="cateringRequired">cateringRequired</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Catering required?</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_cateringrequired</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No</td><td>100000001</td></tr><tr><td>en</td><td>Yes</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#cateringRequired_display name="cateringRequired_display">cateringRequired_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#checkInCount name="checkInCount">checkInCount</a>

Check-in count  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check-in count</td></tr><tr><td>description</td><td>Check-in count</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_checkincount</td></tr></table>

### <a href=#confirmedHotelChoices name="confirmedHotelChoices">confirmedHotelChoices</a>

Hotel choices confirmation status  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confirmed Hotel choices?</td></tr><tr><td>description</td><td>Hotel choices confirmation status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_confirmedhotelchoices</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#confirmedHotelChoices_display name="confirmedHotelChoices_display">confirmedHotelChoices_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#countdownInDays name="countdownInDays">countdownInDays</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Countdown in Days</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_countdownindays</td></tr></table>

### <a href=#createMarketingCollateral name="createMarketingCollateral">createMarketingCollateral</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Create Marketing Collateral</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_createmarketingcollateral</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#createMarketingCollateral_display name="createMarketingCollateral_display">createMarketingCollateral_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#definePackagesandPricing name="definePackagesandPricing">definePackagesandPricing</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Define Packages and Pricing</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_definepackagesandpricing</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#definePackagesandPricing_display name="definePackagesandPricing_display">definePackagesandPricing_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#defineSessions name="defineSessions">defineSessions</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Define Sessions</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_definesessions</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#defineSessions_display name="defineSessions_display">defineSessions_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#defineTeam name="defineTeam">defineTeam</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Define Team</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_defineteam</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#defineTeam_display name="defineTeam_display">defineTeam_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_description</td></tr></table>

### <a href=#developMarketingPlan name="developMarketingPlan">developMarketingPlan</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Develop Marketing Plan</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_developmarketingplan</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#developMarketingPlan_display name="developMarketingPlan_display">developMarketingPlan_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#earlyBirdCutOffDate name="earlyBirdCutOffDate">earlyBirdCutOffDate</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Early Bird Cut-off Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_earlybirdcutoffdate</td></tr></table>

### <a href=#eventDebriefing name="eventDebriefing">eventDebriefing</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Debriefing</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventdebriefing</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#eventDebriefing_display name="eventDebriefing_display">eventDebriefing_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#eventEndDate name="eventEndDate">eventEndDate</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event End Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventenddate</td></tr></table>

### <a href=#eventFormat name="eventFormat">eventFormat</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Format</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventformat</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>On Site</td><td>100000001</td></tr><tr><td>en</td><td>Webinar</td><td>100000002</td></tr><tr><td>en</td><td>Hybrid</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#eventFormat_display name="eventFormat_display">eventFormat_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#eventStartDate name="eventStartDate">eventStartDate</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Start Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventstartdate</td></tr></table>

### <a href=#eventTimeZone name="eventTimeZone">eventTimeZone</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Time Zone</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventtimezone</td></tr></table>

### <a href=#eventTimeZoneName name="eventTimeZoneName">eventTimeZoneName</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Time Zone Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventtimezonename</td></tr></table>

### <a href=#eventType name="eventType">eventType</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Executive Briefing</td><td>100000001</td></tr><tr><td>en</td><td>Conference</td><td>100000002</td></tr><tr><td>en</td><td>Demonstration</td><td>100000003</td></tr><tr><td>en</td><td>Training</td><td>100000004</td></tr><tr><td>en</td><td>Webcast</td><td>100000005</td></tr></table></td></tr></table>

### <a href=#eventType_display name="eventType_display">eventType_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#eventVenueCost name="eventVenueCost">eventVenueCost</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Venue Cost</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventvenuecost</td></tr></table>

### <a href=#eventVenueCostBase name="eventVenueCostBase">eventVenueCostBase</a>

Value of the Event Venue Cost in base currency.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Venue Cost (Base)</td></tr><tr><td>description</td><td>Value of the Event Venue Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventvenuecost_base</td></tr></table>

### <a href=#expectedOutcome name="expectedOutcome">expectedOutcome</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Outcome</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_expectedoutcome</td></tr></table>

### <a href=#followUpOnLeads name="followUpOnLeads">followUpOnLeads</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Follow up on Leads</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_followuponleads</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#followUpOnLeads_display name="followUpOnLeads_display">followUpOnLeads_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#guestLogistics name="guestLogistics">guestLogistics</a>

Whether guest logistics are required or not.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Guest Logistics?</td></tr><tr><td>description</td><td>Whether guest logistics are required or not.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_guestlogistics</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No</td><td>100000001</td></tr><tr><td>en</td><td>Yes</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#guestLogistics_display name="guestLogistics_display">guestLogistics_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#identifySpeakers name="identifySpeakers">identifySpeakers</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identify Speakers</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_identifyspeakers</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#identifySpeakers_display name="identifySpeakers_display">identifySpeakers_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#identifySponsors name="identifySponsors">identifySponsors</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identify Sponsors</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_identifysponsors</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not applicable</td><td>100000001</td></tr><tr><td>en</td><td>Incomplete</td><td>100000002</td></tr><tr><td>en</td><td>Complete</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#identifySponsors_display name="identifySponsors_display">identifySponsors_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isRecurringEvent name="isRecurringEvent">isRecurringEvent</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Recurring Event</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_isrecurringevent</td></tr></table>

### <a href=#isTemplate name="isTemplate">isTemplate</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Template</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_istemplate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#isTemplate_display name="isTemplate_display">isTemplate_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#language name="language">language</a>

The language of the webinar  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language</td></tr><tr><td>description</td><td>The language of the webinar</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_language</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>English</td><td>100000000</td></tr><tr><td>en</td><td>French</td><td>100000001</td></tr><tr><td>en</td><td>German</td><td>100000002</td></tr><tr><td>en</td><td>Spanish</td><td>100000003</td></tr><tr><td>en</td><td>Italian</td><td>100000004</td></tr><tr><td>en</td><td>Russian</td><td>100000005</td></tr><tr><td>en</td><td>Dutch</td><td>100000006</td></tr><tr><td>en</td><td>Turkish</td><td>100000007</td></tr><tr><td>en</td><td>Portuguese</td><td>100000008</td></tr><tr><td>en</td><td>Chinese (Simplified)</td><td>100000009</td></tr><tr><td>en</td><td>Chinese (Traditional)</td><td>100000013</td></tr><tr><td>en</td><td>Japanese</td><td>100000010</td></tr><tr><td>en</td><td>Korean</td><td>100000011</td></tr><tr><td>en</td><td>Hebrew</td><td>100000012</td></tr></table></td></tr></table>

### <a href=#language_display name="language_display">language_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#makePaymentsDue name="makePaymentsDue">makePaymentsDue</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Make Payments Due</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_makepaymentsdue</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#makePaymentsDue_display name="makePaymentsDue_display">makePaymentsDue_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#manageRegistrationCount name="manageRegistrationCount">manageRegistrationCount</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manage Registration Count?</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_manageregistrationcount</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#manageRegistrationCount_display name="manageRegistrationCount_display">manageRegistrationCount_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#maximumEventCapacity name="maximumEventCapacity">maximumEventCapacity</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum Event Capacity</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_maximumeventcapacity</td></tr></table>

### <a href=#maxNumberOfRegistrations name="maxNumberOfRegistrations">maxNumberOfRegistrations</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max number of registrations</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_maxnumberofregistrations</td></tr></table>

### <a href=#miscellaneousCosts name="miscellaneousCosts">miscellaneousCosts</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Miscellaneous Costs</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_miscellaneouscosts</td></tr></table>

### <a href=#miscellaneousCostsBase name="miscellaneousCostsBase">miscellaneousCostsBase</a>

Value of the Miscellaneous Costs in base currency.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Miscellaneous Costs (Base)</td></tr><tr><td>description</td><td>Value of the Miscellaneous Costs in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_miscellaneouscosts_base</td></tr></table>

### <a href=#notifyAuthoritiesOfEvent name="notifyAuthoritiesOfEvent">notifyAuthoritiesOfEvent</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Notify Authorities of Event</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_notifyauthoritiesofevent</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#notifyAuthoritiesOfEvent_display name="notifyAuthoritiesOfEvent_display">notifyAuthoritiesOfEvent_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#planRegistration name="planRegistration">planRegistration</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Plan Registration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_planregistration</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#planRegistration_display name="planRegistration_display">planRegistration_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#presentationManagerUrl name="presentationManagerUrl">presentationManagerUrl</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Presentation Manager URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_presentationmanagerurl</td></tr></table>

### <a href=#primaryGoal name="primaryGoal">primaryGoal</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Goal</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_primarygoal</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Marketing</td><td>100000001</td></tr><tr><td>en</td><td>Sales</td><td>100000002</td></tr><tr><td>en</td><td>Education</td><td>100000003</td></tr><tr><td>en</td><td>Morale</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#primaryGoal_display name="primaryGoal_display">primaryGoal_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#primaryVenue name="primaryVenue">primaryVenue</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Venue</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_primaryvenue</td></tr></table>

### <a href=#producer name="producer">producer</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Producer</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_producer</td></tr></table>

### <a href=#publicEventURL name="publicEventURL">publicEventURL</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_publiceventurl</td></tr></table>

### <a href=#publishStatus name="publishStatus">publishStatus</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Publish Status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_publishstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>100000000</td></tr><tr><td>en</td><td>Ready to publish</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Published</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#publishStatus_display name="publishStatus_display">publishStatus_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#readableEventID name="readableEventID">readableEventID</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Readable Event ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_readableeventid</td></tr></table>

### <a href=#recurrencePattern name="recurrencePattern">recurrencePattern</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrence pattern</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>512</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_recurrencepattern</td></tr></table>

### <a href=#recurrentEventStatus name="recurrentEventStatus">recurrentEventStatus</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrent Event Status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>4</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_recurrenteventstatus</td></tr></table>

### <a href=#registrationCount name="registrationCount">registrationCount</a>

Registration count of the Event.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration Count</td></tr><tr><td>description</td><td>Registration count of the Event.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registrationcount</td></tr></table>

### <a href=#registrationsTarget name="registrationsTarget">registrationsTarget</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registrations target</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registrationstarget</td></tr></table>

### <a href=#requestSponsorship name="requestSponsorship">requestSponsorship</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Request Sponsorship</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_requestsponsorship</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#requestSponsorship_display name="requestSponsorship_display">requestSponsorship_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#revenueFromSponsorship name="revenueFromSponsorship">revenueFromSponsorship</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Revenue from Sponsorship</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_revenuefromsponsorship</td></tr></table>

### <a href=#revenueFromSponsorshipBase name="revenueFromSponsorshipBase">revenueFromSponsorshipBase</a>

Value of the Revenue from Sponsorship in base currency.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Revenue from Sponsorship (Base)</td></tr><tr><td>description</td><td>Value of the Revenue from Sponsorship in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_revenuefromsponsorship_base</td></tr></table>

### <a href=#scheduleAirportPickups name="scheduleAirportPickups">scheduleAirportPickups</a>

Airport pickups scheduling status  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Schedule airport pickups?</td></tr><tr><td>description</td><td>Airport pickups scheduling status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_scheduleairportpickups</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#scheduleAirportPickups_display name="scheduleAirportPickups_display">scheduleAirportPickups_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#scheduleSessions name="scheduleSessions">scheduleSessions</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Schedule Sessions</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_schedulesessions</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#scheduleSessions_display name="scheduleSessions_display">scheduleSessions_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#selectSpeakers name="selectSpeakers">selectSpeakers</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Select Speakers</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_selectspeakers</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#selectSpeakers_display name="selectSpeakers_display">selectSpeakers_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#selectVendors name="selectVendors">selectVendors</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Select Vendors</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_selectvendors</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#selectVendors_display name="selectVendors_display">selectVendors_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#sendEventInvitation name="sendEventInvitation">sendEventInvitation</a>

Event invitation sending status  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Send Event invitation</td></tr><tr><td>description</td><td>Event invitation sending status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sendeventinvitation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#sendEventInvitation_display name="sendEventInvitation_display">sendEventInvitation_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#sendMarketingMaterial name="sendMarketingMaterial">sendMarketingMaterial</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Send Marketing Material</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sendmarketingmaterial</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#sendMarketingMaterial_display name="sendMarketingMaterial_display">sendMarketingMaterial_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#sendPreEventReminders name="sendPreEventReminders">sendPreEventReminders</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Send Pre Event Reminders</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sendpreeventreminders</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#sendPreEventReminders_display name="sendPreEventReminders_display">sendPreEventReminders_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#sendThankYouEmails name="sendThankYouEmails">sendThankYouEmails</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Send Thank You Emails</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sendthankyouemails</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#sendThankYouEmails_display name="sendThankYouEmails_display">sendThankYouEmails_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#showWaitlist name="showWaitlist">showWaitlist</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Show Waitlist</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_showwaitlist</td></tr></table>

### <a href=#targetRevenue name="targetRevenue">targetRevenue</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target Revenue</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_targetrevenue</td></tr></table>

### <a href=#targetRevenueBase name="targetRevenueBase">targetRevenueBase</a>

Value of the Target Revenue in base currency.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target Revenue (Base)</td></tr><tr><td>description</td><td>Value of the Target Revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_targetrevenue_base</td></tr></table>

### <a href=#teamDebriefing name="teamDebriefing">teamDebriefing</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Team Debriefing</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_teamdebriefing</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#teamDebriefing_display name="teamDebriefing_display">teamDebriefing_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#totalCostOfEventsActivities name="totalCostOfEventsActivities">totalCostOfEventsActivities</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Cost of Events Activities</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalcostofeventsactivities</td></tr></table>

### <a href=#totalCostOfEventsActivitiesBase name="totalCostOfEventsActivitiesBase">totalCostOfEventsActivitiesBase</a>

Value of the Total Cost of Events Activities in base currency.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Cost of Events Activities (Base)</td></tr><tr><td>description</td><td>Value of the Total Cost of Events Activities in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalcostofeventsactivities_base</td></tr></table>

### <a href=#totalCostOfExternalMembers name="totalCostOfExternalMembers">totalCostOfExternalMembers</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total cost of External Members</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalcostofexternalmembers</td></tr></table>

### <a href=#totalCostOfExternalMembersBase name="totalCostOfExternalMembersBase">totalCostOfExternalMembersBase</a>

Value of the Total cost of External Members in base currency.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total cost of External Members (Base)</td></tr><tr><td>description</td><td>Value of the Total cost of External Members in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalcostofexternalmembers_base</td></tr></table>

### <a href=#totalRegistrationFee name="totalRegistrationFee">totalRegistrationFee</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Registration Fee (package cost)</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalregistrationfee</td></tr></table>

### <a href=#totalRegistrationFeeBase name="totalRegistrationFeeBase">totalRegistrationFeeBase</a>

Value of the Total Registration Fee in base currency.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Registration Fee (package cost) (Base)</td></tr><tr><td>description</td><td>Value of the Total Registration Fee in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalregistrationfee_base</td></tr></table>

### <a href=#totalRevenueFromTheEvent name="totalRevenueFromTheEvent">totalRevenueFromTheEvent</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Revenue from the event</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalrevenuefromtheevent</td></tr></table>

### <a href=#totalRevenueFromTheEventBase name="totalRevenueFromTheEventBase">totalRevenueFromTheEventBase</a>

Value of the Total Revenue from the event in base currency.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Revenue from the event (Base)</td></tr><tr><td>description</td><td>Value of the Total Revenue from the event in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalrevenuefromtheevent_base</td></tr></table>

### <a href=#waitlistStartingPoint name="waitlistStartingPoint">waitlistStartingPoint</a>

Waitlist Starting Point  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Waitlist Starting Point</td></tr><tr><td>description</td><td>Waitlist Starting Point</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_waitliststartingpoint</td></tr></table>

### <a href=#waitlistthisEvent name="waitlistthisEvent">waitlistthisEvent</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Waitlist this Event</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_waitlistthisevent</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No</td><td>100000001</td></tr><tr><td>en</td><td>Yes</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#waitlistthisEvent_display name="waitlistthisEvent_display">waitlistthisEvent_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#webinarConfigurationId name="webinarConfigurationId">webinarConfigurationId</a>

Webinar Configuration  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Configuration</td></tr><tr><td>description</td><td>Webinar Configuration</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarconfigurationid</td></tr></table>

### <a href=#webinarID name="webinarID">webinarID</a>

Webinar ID of the Event.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar ID</td></tr><tr><td>description</td><td>Webinar ID of the Event.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarid</td></tr></table>

### <a href=#webinarNotificationSeen name="webinarNotificationSeen">webinarNotificationSeen</a>

Whether the webinar creation notification has been seen or not  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Notification Seen</td></tr><tr><td>description</td><td>Whether the webinar creation notification has been seen or not</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarnotificationseen</td></tr></table>

### <a href=#webinarOperation name="webinarOperation">webinarOperation</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Operation</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinaroperation</td></tr></table>

### <a href=#webinarStatus name="webinarStatus">webinarStatus</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarstatus</td></tr></table>

### <a href=#webinarStatusReason name="webinarStatusReason">webinarStatusReason</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Status Reason</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarstatusreason</td></tr></table>

### <a href=#webinarType name="webinarType">webinarType</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Type</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinartype</td></tr></table>

### <a href=#webinarURL name="webinarURL">webinarURL</a>

URL of the webinar. This might be URL of external webinar provider.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar URL</td></tr><tr><td>description</td><td>URL of the webinar. This might be URL of external webinar provider.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarurl</td></tr></table>

### <a href=#sendSurveys name="sendSurveys">sendSurveys</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Send Surveys</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sendsurveys</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not started</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Completed</td><td>100000003</td></tr><tr><td>en</td><td>Not applicable</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#sendSurveys_display name="sendSurveys_display">sendSurveys_display</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#eventURLspecified name="eventURLspecified">eventURLspecified</a>

Determines whether an event URL is specified.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event URL specified</td></tr><tr><td>description</td><td>Determines whether an event URL is specified.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_eventurlspecified</td></tr></table>

### <a href=#sessionsCount name="sessionsCount">sessionsCount</a>

The number of sessions in this event  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session count</td></tr><tr><td>description</td><td>The number of sessions in this event</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_sessionscount</td></tr></table>

### <a href=#sessionsCountDate name="sessionsCountDate">sessionsCountDate</a>

Last Updated time of rollup field Session count.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session count (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Session count.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_sessionscount_date</td></tr></table>

### <a href=#sessionsCountState name="sessionsCountState">sessionsCountState</a>

State of rollup field Session count.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session count (State)</td></tr><tr><td>description</td><td>State of rollup field Session count.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_sessionscount_state</td></tr></table>

### <a href=#allowAnonymousRegistrations name="allowAnonymousRegistrations">allowAnonymousRegistrations</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Anonymous Registrations</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_allowanonymousregistrations</td></tr></table>

### <a href=#portalBannerImage name="portalBannerImage">portalBannerImage</a>

The portal banner image.  
First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Portal Banner Image</td></tr><tr><td>description</td><td>The portal banner image.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_headerimage</td></tr></table>

### <a href=#eventURL name="eventURL">eventURL</a>

First included in: eventManagement/Event (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Portal Event URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventurl</td></tr></table>

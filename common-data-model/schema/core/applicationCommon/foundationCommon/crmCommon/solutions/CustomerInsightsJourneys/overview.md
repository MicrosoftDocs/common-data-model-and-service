---
title: overview of CustomerInsightsJourneys - Common Data Model | Microsoft Docs
description: CustomerInsightsJourneys is a folder that contains standard entities related to the Common Data Model.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 3/12/2025
ms.author: cdmditeam
---

# Overview of CustomerInsightsJourneys


## Entities

|Name|Description|
|---|---|
|[ActionEventDropoff](ActionEventDropoff.md)|Logged when a customer drops out of a journey step|
|[ActionEventInflow](ActionEventInflow.md)|Logged when a customer enters a journey step|
|[ActionEventPostponed](ActionEventPostponed.md)|Logged when an journey step is postponed \(paused\) for a customer, usually for quiet hours|
|[ActionEventProcessed](ActionEventProcessed.md)|Logged when a customer goes through a journey step successfully|
|[ActionEventResumed](ActionEventResumed.md)|Logged when a journey step is resumed for a customer|
|[ActionEventSystemFailure](ActionEventSystemFailure.md)|Logged when an journey step fails for a customer|
|[ActivityContactBlocked](ActivityContactBlocked.md)||
|[ActivityContactBlockedBusinessUnit](ActivityContactBlockedBusinessUnit.md)||
|[ActivityContactBlockedConsent](ActivityContactBlockedConsent.md)||
|[ActivityContactBlockedExternalConsent](ActivityContactBlockedExternalConsent.md)||
|[ActivityContactBlockedSuppression](ActivityContactBlockedSuppression.md)||
|[ActivityContactDispatched](ActivityContactDispatched.md)||
|[ActivityContactExpired](ActivityContactExpired.md)||
|[ActivityContactProcessingFailed](ActivityContactProcessingFailed.md)||
|[BotCustomLinkClicked](BotCustomLinkClicked.md)|Logged when a bot clicks a custom message link\.|
|[BotEmailLinkClicked](BotEmailLinkClicked.md)|Triggered when a bot clicks a link in an email\.|
|[BotPushNotificationLinkClicked](BotPushNotificationLinkClicked.md)|Logged when a bot clicks a push notification link\.|
|[BotSmsLinkClicked](BotSmsLinkClicked.md)|Triggered when a bot clicks an SMS link\.|
|[ConfirmableFormSubmitted](ConfirmableFormSubmitted.md)||
|[ConfirmationRequest](ConfirmationRequest.md)||
|[ConfirmationResponse](ConfirmationResponse.md)||
|[ContactDeleted](ContactDeleted.md)|Indicates that a contact has been deleted\. This interaction applies to Outbound marketing only\.|
|[ConversionEventTouchPoint](ConversionEventTouchPoint.md)||
|[CreateCrmActivityContactProcessed](CreateCrmActivityContactProcessed.md)||
|[CreateCustomChannelActivityContactProcessed](CreateCustomChannelActivityContactProcessed.md)||
|[CreateLeadActivityContactProcessed](CreateLeadActivityContactProcessed.md)||
|[CreateRecord](CreateRecord.md)||
|[CustomBounced](CustomBounced.md)|Occurs when a custom channel message fails to deliver\.|
|[CustomChannelResponse](CustomChannelResponse.md)||
|[CustomDelivered](CustomDelivered.md)|Logged when a custom channel message is delivered\.|
|[CustomerJourneyContactRecordUpdated](CustomerJourneyContactRecordUpdated.md)||
|[CustomerJourneyIterationStarted](CustomerJourneyIterationStarted.md)||
|[CustomerVoiceQuestionResponseSubmitted](CustomerVoiceQuestionResponseSubmitted.md)|Generated per each answered question in the Customer Voice survey|
|[CustomerVoiceSuveyResponseSubmitted](CustomerVoiceSuveyResponseSubmitted.md)|Generated when Customer Voice response is submitted|
|[CustomLinkClicked](CustomLinkClicked.md)|Triggered when a custom channel message link is clicked\.|
|[CustomNotSent](CustomNotSent.md)|Logged when a custom channel message fails to send\.|
|[CustomReceived](CustomReceived.md)|Indicates a custom channel message reply was received\.|
|[CustomSent](CustomSent.md)|Generated when a custom channel message is successfully sent\.|
|[DomainNotOwnedByAnyone](DomainNotOwnedByAnyone.md)|Triggered when during sending an email, the domain used isn’t authenticated anywhere|
|[DomainOwnedByDifferentOrganization](DomainOwnedByDifferentOrganization.md)|Triggered when using non authenticated domain that is owned by another organization|
|[EmailAddressOptedOut](EmailAddressOptedOut.md)|Triggered when a contact, lead, or CI profile opts out via the preference center form\.|
|[EmailBlockBounced](EmailBlockBounced.md)|Triggered when an email is blocked due to bounce|
|[EmailBlocked](EmailBlocked.md)|Triggered when an email is blocked due to various reasons\.|
|[EmailBlockedByActivityExpiration](EmailBlockedByActivityExpiration.md)|Triggered when an email is blocked due to reaching the expiration date|
|[EmailBlockedByUnsubscription](EmailBlockedByUnsubscription.md)|Triggered when an email gets blocked due to no consent|
|[EmailBlockedByUser](EmailBlockedByUser.md)|Triggered when a contact had marked you email as Do Not Email|
|[EmailBlockedConsentNotGiven](EmailBlockedConsentNotGiven.md)||
|[EmailBlockedContactabilityDoNotEmail](EmailBlockedContactabilityDoNotEmail.md)||
|[EmailBlockedDomainDeliverability](EmailBlockedDomainDeliverability.md)||
|[EmailBlockedDuplicateAddress](EmailBlockedDuplicateAddress.md)|Logged when an email is blocked due to duplicate addresses\.|
|[EmailBlockedExternalConsentFailure](EmailBlockedExternalConsentFailure.md)|Logged when an email is blocked due to missing consent\.|
|[EmailBlockedFrequencyCapReached](EmailBlockedFrequencyCapReached.md)||
|[EmailBlockedInactiveContact](EmailBlockedInactiveContact.md)|Logged when an email is blocked due to an inactive contact\.|
|[EmailBlockedInvalidRecipientAddress](EmailBlockedInvalidRecipientAddress.md)||
|[EmailBlockedInvalidReplyToAddress](EmailBlockedInvalidReplyToAddress.md)||
|[EmailBlockedInvalidSenderAddress](EmailBlockedInvalidSenderAddress.md)||
|[EmailBlockedMissingContactData](EmailBlockedMissingContactData.md)|Triggered when a contact was deleted or there is a missing security access|
|[EmailBlockedMissingRelatedData](EmailBlockedMissingRelatedData.md)|Triggered when we can’t fetch related record used in personalization query|
|[EmailBlockedOtherReason](EmailBlockedOtherReason.md)|Logged when an email is blocked due to other reasons\.|
|[EmailBlockedSuspension](EmailBlockedSuspension.md)||
|[EmailBlockedTrialQuotaExceeded](EmailBlockedTrialQuotaExceeded.md)||
|[EmailBounceCacheBlocked](EmailBounceCacheBlocked.md)|Triggered when an email is blocked by suppression list|
|[EmailBounced](EmailBounced.md)|Logged when an email fails to deliver due to a bounce\.|
|[EmailCcSent](EmailCcSent.md)|Generated when an email is successfully sent to a cc recipient\.|
|[EmailClicked](EmailClicked.md)|Triggered when an email link is clicked\.|
|[EmailContainsBlacklistedLinks](EmailContainsBlacklistedLinks.md)|Triggered when an email contains flagged blacklisted links\.|
|[EmailDelivered](EmailDelivered.md)|Indicates that an email was successfully delivered\.|
|[EmailFeedbackLoop](EmailFeedbackLoop.md)|Generated when an email is marked as spam\.|
|[EmailForwarded](EmailForwarded.md)|Indicates that an email was forwarded\. This interaction applies to Outbound marketing only\.|
|[EmailHardBounced](EmailHardBounced.md)||
|[EmailHardRemoteBounced](EmailHardRemoteBounced.md)||
|[EmailOpened](EmailOpened.md)|Logged when a contact, lead, or CI profile opens an email\.|
|[EmailSendingFailed](EmailSendingFailed.md)||
|[EmailSent](EmailSent.md)|Generated when an email is successfully sent\.|
|[EmailSoftBounced](EmailSoftBounced.md)||
|[EmailSoftRemoteBounced](EmailSoftRemoteBounced.md)||
|[EmailSubscriptionSubmit](EmailSubscriptionSubmit.md)||
|[EntityDeleted](EntityDeleted.md)|Indicates that an entiry has been deleted\. This interaction applies to Outbound marketing only\.|
|[EventCheckIn](EventCheckIn.md)|Logged when registered attendee is checked in for an event\.|
|[EventRegistration](EventRegistration.md)|Logged when event registration is created\.|
|[EventRegistrationCanceled](EventRegistrationCanceled.md)|Logged when an event registration is canceled\.|
|[EventRegistrationCreatedFromWaitlist](EventRegistrationCreatedFromWaitlist.md)||
|[EventRegistrationWaitlisted](EventRegistrationWaitlisted.md)||
|[ExperimentationDistribution](ExperimentationDistribution.md)||
|[ExperimentationGoal](ExperimentationGoal.md)||
|[FormsProSurveyOpened](FormsProSurveyOpened.md)||
|[FormsProSurveyQuestionAnswered](FormsProSurveyQuestionAnswered.md)||
|[FormsProSurveySubmitted](FormsProSurveySubmitted.md)||
|[FormSubmissionConfirmed](FormSubmissionConfirmed.md)|Generated when the double opt\x2din is confirmed\.|
|[FormSubmissionExpired](FormSubmissionExpired.md)|Generated when the double opt\x2din expires after 28 days since the form submission\.|
|[FormSubmitted](FormSubmitted.md)|Generated when a marketing or event registration form is submitted\.|
|[FormVisited](FormVisited.md)|Generated when a contact or lead visits a tracked form page\.|
|[GoalEvent](GoalEvent.md)|Logged when a customer meets the goal for the journey|
|[InvalidRecipientAddress](InvalidRecipientAddress.md)|Logged when an email is blocked due to invalid recipient address\.|
|[InvalidReplyToAddress](InvalidReplyToAddress.md)|Logged when an email is blocked due to invalid Reply\x2dTo address\.|
|[InvalidSenderAddress](InvalidSenderAddress.md)|Logged when an email is blocked due to invalid sender address\.|
|[JourneyEventCancelledByActionFailure](JourneyEventCancelledByActionFailure.md)|Logged when a journey instance is terminated by a failure in a journey step|
|[JourneyEventCancelledByExitEvent](JourneyEventCancelledByExitEvent.md)|Logged when a journey instance is terminated when a customer qualifies for an exit criteria|
|[JourneyEventCancelledByJourneyStopped](JourneyEventCancelledByJourneyStopped.md)|Logged when a journey instance is terminated because the user has stopped the journey|
|[JourneyEventCancelledBySupressionSegment](JourneyEventCancelledBySupressionSegment.md)|Logged when a customer does not go to the next journey step because they belong to a suppression segment which excludes them from the journey|
|[JourneyEventCompleted](JourneyEventCompleted.md)|Logged when a customer completes a journey run|
|[JourneyEventEntryProcessed](JourneyEventEntryProcessed.md)|Logged when a customer enters the journey \(emitted by the flow\)|
|[JourneyEventEntrySystemFailure](JourneyEventEntrySystemFailure.md)|Logged when a customer fails to enter the journey due to a system error|
|[JourneyEventExited](JourneyEventExited.md)||
|[JourneyEventInflow](JourneyEventInflow.md)|Logged when a customer enters a journey \(emitted by the service before calling the flow\)|
|[JourneyEventInprogress](JourneyEventInprogress.md)||
|[JourneyEventPreEntryDropoff](JourneyEventPreEntryDropoff.md)|Logged when a customer drops off before attempting to enter a journey|
|[JourneyEventProfileResolvedWithRetry](JourneyEventProfileResolvedWithRetry.md)|Logged when the system finds the customer matching the event after trying again|
|[JourneyEventProfileUnresolved](JourneyEventProfileUnresolved.md)|Logged when the system can't find a matching customer for the event|
|[JourneyEventUndefined](JourneyEventUndefined.md)||
|[LeadScoreBoost](LeadScoreBoost.md)|Triggered when a lead score is increased\. This interaction applies to Outbound marketing only\.|
|[LinkedInFormSubmission](LinkedInFormSubmission.md)|Occurs when a LinkedIn lead form is submitted\. This interaction applies to Outbound marketing only\.|
|[MissingDataAccessPrivileges](MissingDataAccessPrivileges.md)||
|[OptimizationFeedback](OptimizationFeedback.md)||
|[OutOfEmailCredits](OutOfEmailCredits.md)|Triggered when a trial organization reaches the quota of number of sent emails\.|
|[PassThroughActivityContactProcessed](PassThroughActivityContactProcessed.md)||
|[PushNotificationLinkClicked](PushNotificationLinkClicked.md)|Logged when a push notification link is clicked\.|
|[PushNotificationNotSent](PushNotificationNotSent.md)|Indicates a push notification failed to send\.|
|[PushNotificationOpened](PushNotificationOpened.md)|Logged when a push notification is opened\.|
|[PushNotificationSent](PushNotificationSent.md)|Triggered when a push notification is sent\.|
|[RedirectLinkClicked](RedirectLinkClicked.md)|Triggered when a redirect link is clicked\. This interaction applies to Outbound marketing only\.|
|[SchedulerActivityContactProcessed](SchedulerActivityContactProcessed.md)||
|[SegmentMembersCountChanged](SegmentMembersCountChanged.md)||
|[SegmentRelationshipEdited](SegmentRelationshipEdited.md)||
|[SegmentSubscribed](SegmentSubscribed.md)||
|[SegmentUnsubscribed](SegmentUnsubscribed.md)||
|[SessionRegistrationCanceled](SessionRegistrationCanceled.md)|Logged when a session registration is canceled\.|
|[SessionRegistrationCreatedFromWaitlist](SessionRegistrationCreatedFromWaitlist.md)||
|[SessionRegistrationWaitlisted](SessionRegistrationWaitlisted.md)||
|[SmsBounced](SmsBounced.md)|Occurs when an SMS fails to deliver\.|
|[SmsDelivered](SmsDelivered.md)|Logged when an SMS is delivered\.|
|[SmsLinkClicked](SmsLinkClicked.md)|Triggered when an SMS link is clicked\.|
|[SmsNotSent](SmsNotSent.md)|Logged when an SMS fails to send\.|
|[SmsReceived](SmsReceived.md)|Indicates an SMS reply was received\.|
|[SmsSent](SmsSent.md)|Generated when an SMS is successfully sent\.|
|[SplitterActivityContactProcessed](SplitterActivityContactProcessed.md)||
|[SurveyResponse](SurveyResponse.md)||
|[TriggerActivityContactProcessed](TriggerActivityContactProcessed.md)||
|[TriggerCrmWorkflowActivityContactProcessed](TriggerCrmWorkflowActivityContactProcessed.md)||
|[VoiceCallAttempted](VoiceCallAttempted.md)|Triggered when Contact Center had attempted to make a voice call|
|[VoiceCallBlocked](VoiceCallBlocked.md)|Triggered when CIJ blocks sending a request to Contact Center to make a phone call|
|[VoiceCallNotAttempted](VoiceCallNotAttempted.md)|Triggered when Contact Center does not attemp to make a phone call\.|
|[VoiceCallSent](VoiceCallSent.md)|Triggered when CIJ send a request to Contact Center to make a phone call|
|[WebsiteClicked](WebsiteClicked.md)|Logged when a known contact, lead, or CI profile clicks a tracked website link\.|
|[WebsiteVisited](WebsiteVisited.md)|Logged when a known contact, lead, or CI profile visits a tracked website\.|
